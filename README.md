# AI Fortune Teller Website

一个单文件的东方玄学风 AI 命理占卜网页，适合直接部署到 GitHub Pages。

## 特色

- 单文件 `index.html`，内嵌 CSS 与 JavaScript
- 深色神秘东方命理视觉风格
- 三步占卜动画流程：净心 / 问卦 / 呈象
- DeepSeek API 驱动的免费洞察 + 完整解读
- 模拟支付宝付款解锁完整内容
- 本月运势、吉祥物、分享运势卡生成
- LocalStorage 缓存用户信息与 24 小时内的解锁状态
- 移动端优先、响应式设计

## 部署

推送到 GitHub 仓库后，可通过 GitHub Pages 访问：

- Repo: `https://github.com/jswoo999-beep/ai-fortune-teller-website`
- Pages: `https://jswoo999-beep.github.io/ai-fortune-teller-website/`

## 注意

当前版本按需求直接在前端调用 DeepSeek API，因此 API Key 会暴露在浏览器端。若正式商用，建议改为后端代理调用。