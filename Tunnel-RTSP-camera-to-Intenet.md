As example, you have camera:
```yaml
rtsp://admin:password@192.168.1.123:554/cam/realmonitor?channel=1&subtype=0
````

Run [Ngrok](https://ngrok.com/) on any computer in you LAN (use [your token](https://dashboard.ngrok.com/get-started/eW91IHNoYWxsIG5vdCBwYXNzCnlvdSBzaGFsbCBub3QgcGFzcw)):
```yaml
ngrok tcp 192.168.1.123:554 --authtoken eW91IHNoYWxsIG5vdCBwYXNzCnlvdSBzaGFsbCBub3QgcGFzcw
```

You will get similar output:
```yaml
tcp://0.tcp.eu.ngrok.io:11465 -> 192.168.1.123:554
```

Now you have working stream:
```yaml
rtsp://admin:password@0.tcp.eu.ngrok.io:11465/cam/realmonitor?channel=1&subtype=0
```
