部署到 Cloudflare Pages
再次无比感谢 Cloudflare 对技术的探索，让我可以实现这个项目。

Fork edgetunnel 本项目
https://github.com/zizifn/edgetunnel

fork

请一定要定期同步 fork，具体方式请参考 Github 文档。

注册 Cloudflare 账户
https://www.cloudflare.com/

访问 https://dash.cloudflare.com/
创建 Cloudflare Pages
cf-pagecf-page2

连接 GITHUB 账户 和 repo
连接 GITHUB 账户， 并且要选择你 fork 的 repo。

github-edgetunnel

填写 Pages build 信息
选项	值
Build Command	npm run cf-page-vless
Build Directory	dist/apps/cf-page-vless
环境变量	值
UUID	b7625108-80fb-4544-a1f2-aa40c931aa52
NODE_VERSION	18
请自己生成一个 UUID

build-config

部署成功访问 Pages URL
WARNING

页面的账户和密码，就是之前设置的 UUID

访问 Pages 项目地址，并且点击分享 Vless，扫码导入配置。

edgetunnel-overvide

修改 Cloudflare Pages 的设置 (可选但是推荐设置)
如果忘记 UUID 或者想修改配置，可以在 Pages 的设置里面修改。

自定义域名
custom_domain

使用 Cloudflare Pages 最新 build V2 系统
build-v

Cloudflare TOS
按照我对 Cloudflare TOS 理解。Cloudflare Pages 是可以运行代理软件的。

https://www.cloudflare.com/supplemental-terms/

Unlike most Cloudflare products, the Developer Platform can be used to host content. Content stored on the Developer Platform (whether in conjunction with a Cloudflare storage offering or not) that we determine in our sole judgment to be illegal, harmful, or in violation of Section 5 of the Cloudflare Developer Platforms Supplemental Terms may be blocked or removed, and use of the Developer Platform for storage of such illegal or harmful content may result in suspension or termination of Cloudflare Services. While we generally try to provide notice of such action, we reserve the right to take action without notice as appropriate. For these purposes, illegal or harmful content includes but is not limited to: (a) content containing, promoting, or facilitating child sexual abuse material or human trafficking; (b) content that infringes on another person’s intellectual property rights or is otherwise unlawful; (c) content that discloses sensitive personal information, incites or exploits violence, or is intended to defraud the public; and (d) content that seeks to distribute malware, facilitate phishing, or otherwise constitutes technical abuse.

按照我对协议理解，Cloudflare Worker 是可以运行代理软件的。

