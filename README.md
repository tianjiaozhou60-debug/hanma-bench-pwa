# hanma-bench-pwa

静态 PWA：广州汗马电子 - LED 外贸新人专业学习工作台 & 智能CRM系统

部署说明：

1. 我已将项目文件推送到仓库： https://github.com/tianjiaozhou60-debug/hanma-bench-pwa

2. 在 Vercel 上部署（网页）：
   - 登录 vercel.com → New Project → Import Git Repository → 选择 GitHub 并授权访问该仓库。
   - 选择仓库 `hanma-bench-pwa`。
   - Framework Preset 选择 "Other"。Build Command 留空，Output Directory 留空。
   - Deploy。部署完成后会得到一个 `*.vercel.app` 地址。

3. 在本地使用 Vercel CLI 部署（可选）：
   - 安装并登录：
     npm i -g vercel
     vercel login
   - 在项目目录运行：
     vercel --prod

文件列表已包含： index.html, vercel.json, manifest.json, service-worker.js, icons/

如需我继续在你的 Vercel 账号上创建项目并触发自动部署，请给我 Vercel 授权（在 Vercel 控制台将 GitHub 授权打开或分享 Vercel 项目访问权限），我可以帮你完成创建并返回部署地址。
