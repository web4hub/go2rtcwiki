## Apple HLS

```yaml
streams:
  # script will print:
  # ffmpeg:https://devstreaming-cdn.apple.com/videos/streaming/examples/bipbop_16x9/gear1/prog_index.m3u8#video=copy
  apple_hls: echo:python3 hls.py https://developer.apple.com/streaming/examples/basic-stream-osx-ios5.html
```

**hls.py**

```python
import re
import sys
from urllib.parse import urljoin

import requests

r = requests.get(sys.argv[1])
url = re.search(r"https.+?m3u8", r.text)[0]

r = requests.get(url)
m = re.search(r"^[a-z0-1/_]+\.m3u8$", r.text, flags=re.MULTILINE)
url = urljoin(url, m[0])

print("ffmpeg:" + url + "#video=copy")
```