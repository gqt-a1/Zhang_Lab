# Zhang_Lab 每周汇报

纯静态网站，起始日期为 2026-11-21，每周六按成员顺序循环。首次打开请添加真实成员。

## GitHub Pages 部署

将本目录文件上传至 GitHub 仓库根目录。在仓库 Settings → Pages → Build and deployment 选择 Deploy from a branch，分支 main、目录 / (root)，保存后等待 GitHub 提供网站链接。

## 使用

- 添加、改名、上移、删除成员后会重排全部轮次，包括历史；修改前可导出备份。
- 修改日期只允许推迟到周六，当前及后续场次整体顺延，人员顺序保留。
- 浏览器修改保存在 localStorage；跨设备共享需导出 schedule.json 并提交到仓库。其他设备已有本地排期时点击“使用仓库排期”。无实时多人同步。
- 导出的 ICS 为从起始日期开始104场的全天日历快照，修改后需重新导出导入，不是自动订阅。
- 月历显示公历、星期和主要中国节日提示。农历日期使用浏览器 Intl 中国历法；清明日期使用近似公式。节日不是官方放假调休安排。
- 可直接打开 index.html 并手动导入 JSON；通过静态服务器访问可自动读取仓库排期。

节假日通知参考：https://www.gov.cn/gongbao/2025/issue_12406/material/gwygb202532.pdf
