属性|说明
:-|:-
codec     |   Codec: h264 hevc
preset    |   Preset: p1 p2 p3 p4 p5 p6 p7
profile   |    H264: baseline main high high444; HEVC: main main10 frext
tuninginfo | TuningInfo: hq lowlatency ultralowlatency lossless
multipass  | Multipass: disabled qres fullres
fps     |   Frame rate
bf      |   Number of consecutive B-frames
rc      |   Rate control mode: constqp vbr cbr
gop     |   Length of GOP (Group of Pictures)
bitrate |   Average bit rate, can be in unit of 1, K, M
vbvbufsize | VBV buffer size in bits, can be in unit of 1, K, M
aq     |     Enable spatial AQ and set its stength (range 1-15, 0-auto)
temporalaq  |(No value) Enable temporal AQ
cq      |    Target constant quality level for VBR mode (range 1-51, 0-auto)
lookahead  | Maximum depth of lookahead (range 0-(31 - number of B frames))
qmin      |  Min QP value
qmax     |   Max QP value
initqp   |   Initial QP value
constqp   |  QP value for constqp rate control mode

结果：
|codec|preset|profile|tuninginfo|fps|rc|bitrate|vbv buffer|aq|imgs|
|----:|:-----|:------|---------:|--:|--|------:|---------:|-:|-|
|h264|p3|baseline|lowlatency|15|cbr|1000000|100000|0|<img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=50%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=50%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=50%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=50%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=20%><br><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=20%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=20%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=20%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=20%><img src="http://ugame-public.cn-bj.ufileos.com/p3-baseline-lowlatency-1000.h264-001.jpg" width=20%>|


