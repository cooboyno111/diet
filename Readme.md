修改了一下这个web框架可以做到以下几点

1 node v0.12以上可用。

2 总打包体积（包括所有dependencies）非压缩情况下能到1.5M。(原始4.5M)

3 压缩后体积小于512KB，加上2-3M的nodejs，可以完整装入8M NAND的嵌入式openwrt/lede执行环境。

4 精简后体积仅为650KB，压缩后仅为150KB。
