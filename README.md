# CloseWRT-CI
云编译京东云百里CloseWRT固件

去除原git中的内网穿透和USB相关插件，添加adguardhome、lucky、openclash、openlist2

PADAVANONLY-24.10源码：
https://github.com/padavanonly/immortalwrt-mt798x-24.10.git

# 注意：

本项目仅支持编译带有defconfig目录的MTK SDK闭源项目。

# 固件简要说明：

固件每天早上4点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

MEDIATEK系列，配套的UBOOT：
https://github.com/VIKINGYFY/UBOOT-CI/releases

# 目录简要说明：

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置
