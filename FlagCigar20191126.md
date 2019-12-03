刘垚 104753191172
BAM FLAG:
143=128+8+4+2+1
R1端序列和参考序列完全匹配，没有错配、插入和缺失，R1和R2都没有mapping到参考序列上，R1采用的是PE双端测序。
99=64+32+2+1
R2端序列比对到参考序列的负链上，R1端序列和参考序列完全匹配，没有错配、插入和缺失，R1采用的是PE双端测序。
516=512+4
该序列未通过QC，且没有mapp到参考序列上，不通过，舍弃。
2064=2048+16
辅助比对结果显示该序列比对到参考序列的负链上。
147=128+16+2+1
R2端序列比对到参考序列的负链上，完全匹配，没有错配、插入和缺失，R2采用的是PE双端测序。

BAM CIGAR:
14M2D31M
1~14bp match，15~16bp deletion，17~47bp match。
3S6M1D5M
1~3bp 被剪切但仍在read中表示，4~9bp match，10bp deletion，11-15bp match。
6M14N5M
1~6bp match，7~20bp 跳过，21~25bp match。
7M5D8M2I14M
1~7bp match，8~12bp deletion，13~20bp match，21~22bp 为插入碱基，23~36bp match。
How long is the read with alignment CIGAR of 7M5D8M2I14M?
34bp