# 易水成风 · 排盘

纯前端八字排盘，无需服务器。四柱、藏干十神、星运、纳音、空亡、神煞、大运、流年、流月、流日、真太阳时、晚子时口径、农历（含闰月）。

所有计算在浏览器本地完成；保存的命例只存在浏览器 localStorage，不上传。

## 在线使用

https://chengzaiqiang.github.io/paipan/

iPhone：Safari 打开 → 分享 → 添加到主屏幕。第一次加载后会缓存，之后离线可用。

## 技术

- 历法：lunar-javascript（MIT）https://github.com/6tail/lunar-javascript
- 神煞按通用排法计算；起运按「三天折一年」；具体体系约定以各自法本为准
- 本工具仅供学习研究，不构成任何建议

## 本地开发

源文件在私人项目 `易经/工具/学习工作台/paipan.html`，构建脚本生成此目录：

```
node build-static.js
```
