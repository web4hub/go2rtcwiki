| Name              | Gen | Year | Core                         | Xeon       | Pentium                | Celeron                    |
|-------------------|-----|------|------------------------------|------------|------------------------|----------------------------|
| Westmere/Ironlake | 5.5 | 2010 | i3/5/7-xxx                   |            | (G/P)6000, U5000       | P4000, U3000               |
| Sandy Bridge      | 6   | 2011 | i3/5/7-2000                  | E3-1200    | (B)900, (G)800, (G)600 | (B)800, (B)700, G500, G400 |
| Ivy Bridge        | 7   | 2012 | i3/5/7-3000                  | E3-1200 v2 | (G)2000, A1018         | G1600, 1000, 900           |
| Bay Trail         | 7   | 2013 |                              |            | J2000, N3500, A1020    | J1000, N2000               |
| Haswell           | 7.5 | 2013 | i3/5/7-4000                  | E3-1200 v3 | (G)3000                | G1800, 2000                |
| Broadwell         | 8   | 2014 | i3/5/7-5000                  | E3-1200 v4 | 3800                   | 3700, 3200                 |
| Braswell          | 8   | 2013 |                              |            | (J/N)37x0              | (J/N)30x0, N31x0           |
| Skylake           | 9   | 2015 | i3/5/7-6000                  |            | (G)4000                | 3900, 3800                 |
| Apollo Lake       | 9   | 2016 |                              | E3-1x00 v5 | (J/N)4xxx              | (J/N)3xxx                  |
| Kaby Lake         | 9.5 | 2016 | m3/i3/5/7-7000               |            | (G)4000                | (G)3900, 3800              |
| Coffee Lake       | 9.5 | 2017 | i3/5/7/9-8000, i3/5/7/9-9000 | E-2x00     | (G)5xxx                | (G)49xx                    |
| Gemini Lake       | 9.5 | 2017 |                              | E3-1x00 v6 | (J/N)5xxx              | (J/N)4xxx                  |
| Whiskey Lake      | 9.5 | 2018 | i3/5/7-8000U                 |            |                        |                            |
| Ice Lake          | 11  | 2019 | i3/5/7-10xx(N)Gx             |            |                        |                            |
| Tiger Lake        | 12  | 2020 | i3/5/7-11xx(N)Gx             | W-11xxxM   | (G)7xxx                | (G)6xxx                    |

- **Sandy Bridge** (2011): decoding/encoding for AVC/H.264
- **Sandy Bridge** (2011): OpenVINO Detector for Frigate 12+
- **Braswell** (2013): decoding/encoding for MJPEG
- **Skylake** (2015): decoding/encoding for HEVC/H.265
- [i965-va-driver](https://packages.debian.org/ru/sid/i965-va-driver) from **Westmere** to **Coffee Lake**
- [intel-media-va-driver](https://packages.debian.org/sid/intel-media-va-driver) from **Broadwell**

## Useful links

- https://en.wikipedia.org/wiki/Intel_Graphics_Technology#Capabilities_(GPU_hardware)
- https://en.wikipedia.org/wiki/Intel_Quick_Sync_Video#Hardware_decoding_and_encoding
- https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/system-requirements.html