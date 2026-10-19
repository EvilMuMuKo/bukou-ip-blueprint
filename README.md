# 不逃跑木口 · 抖音个人 IP 经营蓝图

一个无依赖、单页、可离线运行的 HTML 静态站点。包含账号定位、观点边界、内容架构、选题库、十二周首轮安排、制作流程及变现检验框架。

## 一键部署（有 GitHub CLI 时）

解压完整文件夹后，使用终端进入该文件夹，执行 `bash publish-with-gh.sh`。脚本会先核对当前 GitHub 身份是否为 `EvilMuMuKo`，然后新建公开仓库、推送三个站点文件，并尝试自动启用 GitHub Pages。要求本机已安装 `git` 和 `gh`，并用 `gh auth login` 登录。脚本不处理现有仓库，避免覆盖已有内容。

## GitHub Pages 手动部署

1. 在 GitHub 的 **EvilMuMuKo** 个人账户下新建公开仓库 `bukou-ip-blueprint`，初始化 `README.md` 可选。
2. 将本目录的 `index.html`、`.nojekyll` 和 `README.md` 放到仓库 **`main`** 分支根目录。文件本身包含全部 HTML/CSS/JavaScript，不需要 npm、Jekyll 或构建流程。
3. 在仓库 **Settings → Pages → Build and deployment** 中选择 **Deploy from a branch**，Branch 选择 **`main`**，Folder 选择 **`/(root)`**，然后 Save。
4. 等 Pages 显示发布成功后，使用 GitHub **Settings → Pages → Visit site** 提供的网址验证打开。

默认项目页网址通常为 `https://evilmumuko.github.io/bukou-ip-blueprint/`，**须以 GitHub 实际显示为准**。

## 公开与隐私

此仓库按公开发布设计。任何人均能查看、下载、复制网页和 Git 历史；`noindex` 只是搜索引擎建议，不是访问保护。
站点为创作策划文档，不能等同于已执行或已获得认可的商业承诺。内容审慎区分真实经验、条件推理、个人选择与待检验假设。
网页仅在当前浏览器保存部分用户勾选与收藏状态，不会上传到网络或自动执行商业操作。

## 维护

- 直接编辑 `index.html` 即可；建议每次改动记录来源与修正原因。
- 不要上传私人日记原文、身份证件、银行或证券账户资料、公司内部文件、登录凭据或不可公开的项目源码。
- 允许浏览与讨论；本仓库未提供开放转载或再许可授权。商业转载请征得权利人同意。

© 2026 MuKo. 除依法允许或另行授权外，保留相关权利。
