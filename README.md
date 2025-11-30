# Dorm-manage-system
The first project for student

注意点一：🔔

千万不要再把 node_modules 提交进 Git 仓库：

体积巨大

会带各种奇怪的测试文件 / 证书 / 私钥模版

正确做法是：代码 + package.json + package-lock.json，node_modules 由 npm install 还原

这次被 GitHub 拦下来其实是好事，它帮你挡了一枪。以后看到 GH013 之类错误，都要当作“⚠ 安全预警”，认真处理。