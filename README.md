
# 自用Aurorae窗口装饰器主题
风格模仿deepin，用于kde  
建议搭配[KDE-Rounded-Corners](https://github.com/matinlotfali/KDE-Rounded-Corners)使用  
Fork from [Win11OS-kde](https://github.com/yeyushengfan258/Win11OS-kde)

## 预览:
![预览](/views/image.png)

<div align="center">
  <img src="views/1.png" width="30%">
  <img src="views/2.png" width="30%">
  <img src="views/3.png" width="30%">
</div>

## 快速安装
```bash
mkdir -p ~/.local/share/aurorae/themes/SkyShadow/
git clone https://github.com/SkyShadowHero/skyshadow-aurorae-theme.git
cd skyshadow-aurorae-theme
cp -r $(ls -A | grep -Ev '^(\.git|views|README\.md)$') ~/.local/share/aurorae/themes/SkyShadow/ 2>/dev/null && echo "Done"
```