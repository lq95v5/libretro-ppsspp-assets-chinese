# libretro-ppsspp-assets-chinese
These are the asset files required for using libretro-ppsspp. They should be placed in the libretro system/PPSSPP directory.

这个是为retroarch得ppsspp核心建立的中文支持
我是根据libretro-ppsspp-assets 仓库修改了ppge_atlas.zim文件 
修改了README.md,添加了使用教程

# 如果你使用得是linux 
`mkdir -p  ~/.config/retroarch/system/PPSSPP `
` vim ~/.config/retroarch/retroarch.cfg`
找到 `system_directory` 行，修改为
`system_directory = "~/.config/retroarch/system/"`
然后 `git clone https://github.com/lq95v5/libretro-ppsspp-assets-chinese.git`
`cp libretro-ppsspp-assets-chinese/* ~/.config/retroarch/system/PPSSPP `
最后打开你的retroarch-settings-user-language-（左右方向键）选择chinese(traditinal)
# 如果你使用安卓
将 `ppge_atlas.zim` 放到`存储卡目录`下得 `Android/data/com.retroarch/files/system/PPSSPP`

## 存在的问题
存档菜单繁体还是会有一点乱码，不影响使用。




