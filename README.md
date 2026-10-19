# 稳步 · 下肢专项训练

一个无需账号的 4 周下肢运动训练与打卡网站。**公开页面只包含通用动作指导，不包含个人医疗记录、照片或训练日志。**

- [打开网站](https://chalme.github.io/leg-control-tracker/)
- 手机、电脑均可使用；无需安装。
- 5 个动作：Step-down、单腿 RDL、分腿蹲、慢速提踵、Wall Press。
- 支持左右分侧逐组打卡、动作说明、四周进阶、历史记录、评分趋势和 JSON 导入导出。
- 浏览器本地存储（LocalStorage）；不同设备之间**不会自动同步**，清理浏览器数据可能丢失记录，请定期导出 JSON。

## 公开部署

提交到 `main` 后，`.github/workflows/deploy.yml` 自动部署根目录 `index.html` 至 GitHub Pages。若自动启用 Pages 失败，请到 Settings → Pages → Build and deployment 设置为 **GitHub Actions**，再重新运行工作流。

## 数据与安全

数据只在当前浏览器保存；网站无账号、无后端、无埋点。不要把个人导出的训练记录上传到公开仓库。

## 训练边界

这是用于运动记录的一般训练参考，不构成病因诊断或个体医疗处方。出现疼痛、肿胀、卡锁、麻木或明显无力时应停止相应动作并寻求医学评估。

License: MIT
