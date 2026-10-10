# 财富自由计算器 · Compound Interest Calculator

一个**单文件、纯前端**的复利计算小工具：整个工具就是一个 `index.html`，双击就能用，不联网、不上传、不装任何东西。

## 🚀 在线使用

👉 **[agnes-calculator.netlify.app](https://agnes-calculator.netlify.app)** — 点开即用，无需下载

## 📥 下载

👉 [点我直接下载（ZIP，解压后双击 index.html 即可使用）](https://github.com/Agnes-studio/compound-interest-calculator/archive/refs/heads/main.zip)

只要单个 HTML 文件？打开 [index.html](https://github.com/Agnes-studio/compound-interest-calculator/blob/main/index.html)，点页面**右上角的下载按钮**（⬇ Download raw file）即可。

## ✨ 特点

- **完全离线**：所有计算都在浏览器本地完成，数据不会离开你的电脑
- **单文件**：只有一个 `index.html`，拷走就能用，无需安装、无需依赖
- **五参数可调**：初始金额、每年追加投入、年利率、年数、复利频率（年/季/月/日）
- **四层堆叠柱状图**：本金 / 累计追加 / 往年利息 / **当年利息（金色高亮）**，每年新长的利息一目了然
- **关键指标卡片**：最终金额、总投入本金、利息收益、增长倍数、末年每年利息
- **按年查询利息**：输入任意年份，直接显示当年利息金额
- **里程碑提示**：自动算出"利息超过累计本金"和"当年利息超过年投入（钱替你工作）"两个节点
- **多币种**：支持 ¥ CNY / $ USD / € EUR，中文金额自动以"万/亿"显示

## 🔀 计算逻辑

| 项目 | 说明 |
|---|---|
| 复利公式 | A = P(1+r/n)^(nt) + C×[(1+r/n)^(nt)−1]/[(1+r/n)^n−1] |
| 年投入计入 | 每年末计入 Annual contributions at year-end |
| 当年利息 | 当年本息和 − 上年本息和 − 当年追加投入 |

## 💖 支持作者

如果这个工具对你有帮助，可以请作者喝杯咖啡：

- ⚡ [爱发电](https://afdian.com/a/Agnesxie)（微信 / 支付宝）
- ☕ [Ko-fi](https://ko-fi.com/agnesxie)（信用卡 / PayPal）

## 📄 License

MIT
