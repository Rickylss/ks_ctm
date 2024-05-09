# ks_ctm

ks_cm 全称 keyswap & copy to move，是一个 Windows 注册表文件，其包含两个功能：

1. keyswap，用于将 ctrl 键和 alt 键交换，方便在 Windows 上使用 Mac 键盘；
2. copy to move，用于将 Windows 上跨磁盘的文件拖动行为从默认的复制改为移动；

这两个功能是为了让用户在 Windows 上使用 Mac 的默认行为。

## 使用方法

右键 `ks_ctm.reg`，选择 `打开方式->注册表编辑器`，然后选择 `是`，完成导入后务必**重启系统**。

若要恢复原有设置，则右键 `revert.reg`，选择 `打开方式->注册表编辑器`，然后选择 `是`，完成导入后重启系统。

## 参考链接

- [修改键盘键位的布局](https://chengchaos.github.io/2019/06/18/windows-scancode-map.html)