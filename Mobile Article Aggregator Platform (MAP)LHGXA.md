<h1> Mobile Article Aggregator Platform (MAP)</h1><br><br><hr><br>

Mobile Article Aggregator Platform 是一个面向移动端内容聚合与分发场景的开源技术资源导航站。该项目定位于为开发者、技术研究人员以及内容运营团队提供结构化的移动端文章链接索引与快速检索能力，解决移动端技术文章分散、检索效率低下、域名迁移频繁导致链接失效等实际问题。

项目本身不存储任何文章内容，仅作为外链元数据的索引层与展示层，通过静态化的资源列表与分类标签体系，帮助用户在海量移动端技术文档中快速定位目标资源。目标用户包括移动端开发工程师、全栈技术学习者、技术博客维护者以及企业内部知识库管理人员。

<h2>功能概览</h2><br>

<p><h3>海量链接索引管理</h3>：支持对超过 250 条移动端技术文章链接进行集中存储与分类展示，覆盖多种技术子领域。</p>

<p><h3>静态化资源列表呈现</h3>：所有链接以纯 Markdown 形式维护于项目仓库中，无需数据库依赖，便于版本控制与协作编辑。</p>

<p><h3>分类标签体系</h3>：根据文章主题、技术栈或访问热度对链接进行逻辑分组，降低用户筛选成本。</p>

<p><h3>快速检索入口</h3>：提供基于文章 ID 或路径关键字的本地搜索功能，提升链接定位速度。</p>

<p><h3>链接状态检测工具</h3>：集成可选的定时检测脚本，自动标记可能失效或响应异常的链接，保障资源列表的有效性。</p>

<p><h3>移动端适配展示</h3>：前端模板针对手机和平板设备进行优化，确保在移动浏览器上获得良好的阅读与导航体验。</p>

<p><h3>开源协作扩展机制</h3>：支持社区用户通过提交 Issue 或 Pull Request 的方式新增、更新或删除链接条目，保持资源列表的时效性。</p>

<p><h3>轻量化部署能力</h3>：项目整体基于静态文件生成，可托管于任何支持 HTTP 服务的平台，包括 GitHub Pages、Cloudflare Pages 或自建 Nginx 服务器。</p>

<h2>应用场景</h2><br>

技术团队内部知识库建设：企业内部的技术团队可将本项目作为基础框架，整理团队内部积累的移动端技术文章链接，形成统一的知识索引入口，减少重复的文档查找工作。

个人技术博客的友情链接扩展：独立技术博客作者可利用本项目的资源列表作为博客侧边栏的补充，为读者提供更多外部阅读资源，同时降低博客维护外链的复杂度。

技术社区的内容聚合展示：技术社区运营方可基于本项目快速搭建文章推荐专区，将社区内的高质量技术帖按分类进行外链汇总，提升社区内容的曝光率与复用率。

技术培训课程的参考资料索引：培训机构或技术讲师可将本项目作为课程参考资料库，将课程中涉及的外部延伸阅读链接统一整理到项目列表中，方便学员课后查阅。

开源项目文档的关联资源导航：开源项目维护者可在项目文档中引用本项目的资源列表，为使用者提供相关的技术背景阅读材料，丰富项目的辅助信息生态。

<h2>快速开始</h2><br>

以下步骤将帮助您在本地环境快速部署并运行本项目的静态站点。

# 1. 克隆项目仓库到本地
git clone https://github.com/example/mobile-article-aggregator.git
cd mobile-article-aggregator

# 2. 安装项目依赖（基于 Node.js 环境）
npm install

# 3. 运行本地开发服务器，默认监听端口 3000
npm run dev

执行上述命令后，在浏览器中访问 `http://localhost:3000` 即可查看资源列表页面。如需构建生产环境静态文件，请执行 `npm run build`，生成的静态资源位于 `dist` 目录下。

<h2>安装要求</h2><br>

| 依赖项 | 必需版本 | 说明 |
|--------|----------|------|
| Node.js | 18.0 及以上 | 项目构建工具与开发服务器运行环境 |
| npm | 8.0 及以上 | Node.js 包管理器，用于安装项目依赖 |
| Git | 2.30 及以上 | 用于克隆仓库与版本管理 |
| 现代浏览器 | Chrome 90+ / Firefox 88+ | 前端页面访问与调试支持 |
| HTTP 服务器 | 任意静态文件服务 | 生产环境托管构建后的静态文件，如 Nginx、Caddy 或 Apache |
| 可选：Shell 环境 | Bash 4.0+ | 运行链接状态检测脚本（位于 scripts/ 目录） |

<h2>文档导航</h2><br>

| 层面 | 目录 | 回答的问题 |
|------|------|------------|
| 用户入门 | docs/getting-started.md | 如何使用本项目的资源列表？如何通过分类标签快速找到所需文章？ |
| 维护者指南 | docs/maintenance.md | 如何新增、修改或删除链接条目？链接格式校验规则是什么？ |
| 开发贡献 | docs/contributing.md | 如何搭建开发环境？代码风格规范与提交信息格式要求有哪些？ |
| 部署运维 | docs/deployment.md | 如何将站点部署到生产服务器？如何配置自定义域名与 HTTPS？ |

<h2>资源列表</h2><br>

<h3>移动端技术文章链接汇总</h3><br>

以下列表收录了本批次（第 8/24 批，共300 个资源链接）的全部移动端文章外链。所有链接均按照用户提供的原始格式原样呈现，未做任何协议、域名或路径的改动。

gitlab.com/JDJTY/txiqmhb/-/commit/0388520081bfbda3b810354eaaad3163749f24ad
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0388520081bfbda3b810354eaaad3163749f24ad?/WX=4fM
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/0388520081bfbda3b810354eaaad3163749f24ad?/sMq
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7f8139b7377e04c6f940f597a4668a3bf93a8e95
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7f8139b7377e04c6f940f597a4668a3bf93a8e95?/f5=w9a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/7f8139b7377e04c6f940f597a4668a3bf93a8e95?/9d7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d59f9f0d46e9cd3a8c8043b3799c3faa51ad9c32
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d59f9f0d46e9cd3a8c8043b3799c3faa51ad9c32?/9n=48I
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d59f9f0d46e9cd3a8c8043b3799c3faa51ad9c32?/Osq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8978a161a171f6f5e0f14082f528f0005662309e
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8978a161a171f6f5e0f14082f528f0005662309e?/dx=7yC
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8978a161a171f6f5e0f14082f528f0005662309e?/Bf9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/11847be194c9dc258387d3039704a2964064b0c9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/11847be194c9dc258387d3039704a2964064b0c9?/0Q=HUv
<br>
gitlab.com/EHWGW/fxleljy/-/commit/11847be194c9dc258387d3039704a2964064b0c9?/UyS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c1558cd41299631404dc7d923486d0ca766fa34f
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c1558cd41299631404dc7d923486d0ca766fa34f?/cP=zga
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c1558cd41299631404dc7d923486d0ca766fa34f?/jDh
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6deb5ceaec81da3406dc721bd416376e15fe0d8a
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6deb5ceaec81da3406dc721bd416376e15fe0d8a?/AH=VSt
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/6deb5ceaec81da3406dc721bd416376e15fe0d8a?/RvP
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1cf179ea4d6095750fba2368b749ce8df8e14d50
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1cf179ea4d6095750fba2368b749ce8df8e14d50?/2j=dxe
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1cf179ea4d6095750fba2368b749ce8df8e14d50?/CgA
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/01bf1ef94ab9122ea9d30f7f5e67979326930d8f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/01bf1ef94ab9122ea9d30f7f5e67979326930d8f?/4V=M6a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/01bf1ef94ab9122ea9d30f7f5e67979326930d8f?/VzT
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fcc5ddaef4e06494345c93e02e69929d9a372648
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fcc5ddaef4e06494345c93e02e69929d9a372648?/4i=zZk
<br>
gitlab.com/EHWGW/fxleljy/-/commit/fcc5ddaef4e06494345c93e02e69929d9a372648?/ImG
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5729ec4821bd95dbc472e54d58a4748fc5c9ec55
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5729ec4821bd95dbc472e54d58a4748fc5c9ec55?/8Y=Pd7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5729ec4821bd95dbc472e54d58a4748fc5c9ec55?/5Z3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ed1ca3b83e34ed475a3c433f4ec9ffe7dc75bab0
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ed1ca3b83e34ed475a3c433f4ec9ffe7dc75bab0?/3A=OLm
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/ed1ca3b83e34ed475a3c433f4ec9ffe7dc75bab0?/KoI
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a15679b7397252aa789ca5efbf046af91e453254
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a15679b7397252aa789ca5efbf046af91e453254?/VI=Pda
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a15679b7397252aa789ca5efbf046af91e453254?/5Z3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6b7379fd11067088c256e9cf2ef614600aa1ce3b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6b7379fd11067088c256e9cf2ef614600aa1ce3b?/oc=GX7
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6b7379fd11067088c256e9cf2ef614600aa1ce3b?/MqK
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6155bc61df7c1c99bc1335006f46684bc521e6cc
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6155bc61df7c1c99bc1335006f46684bc521e6cc?/B5=P3q
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6155bc61df7c1c99bc1335006f46684bc521e6cc?/f9d
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8e7016b0ef67db9b28ef193db31ccdfb132bfb38
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8e7016b0ef67db9b28ef193db31ccdfb132bfb38?/bB=sFW
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/8e7016b0ef67db9b28ef193db31ccdfb132bfb38?/OsM
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/82f497ab9d4de55701290466a6eddeeb0a4959c1
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/82f497ab9d4de55701290466a6eddeeb0a4959c1?/YI=ptX
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/82f497ab9d4de55701290466a6eddeeb0a4959c1?/f9d
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d4510f19ca791041b090de2d1211d4f5be29ee31
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d4510f19ca791041b090de2d1211d4f5be29ee31?/An=48m
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d4510f19ca791041b090de2d1211d4f5be29ee31?/uOs
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b4358a7f37096e6536a9fd472801c379d1510a2f
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b4358a7f37096e6536a9fd472801c379d1510a2f?/18=Pw3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/b4358a7f37096e6536a9fd472801c379d1510a2f?/FjD
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7ab02303da3d99f78cef301e7e1b47bc79ddc2c0
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7ab02303da3d99f78cef301e7e1b47bc79ddc2c0?/Vq=3Ur
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7ab02303da3d99f78cef301e7e1b47bc79ddc2c0?/W0U
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/93ec5d4177696fb8ef26d4a9c801f2162f6fa349
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/93ec5d4177696fb8ef26d4a9c801f2162f6fa349?/qo=i2C
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/93ec5d4177696fb8ef26d4a9c801f2162f6fa349?/HlF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6e6716ae2b91e786466aa78f512efe6669b50536
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6e6716ae2b91e786466aa78f512efe6669b50536?/Ab=2wG
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/6e6716ae2b91e786466aa78f512efe6669b50536?/Y2W
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aad8913f94935e8de129a08aa2c4df9f535cbdbd
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aad8913f94935e8de129a08aa2c4df9f535cbdbd?/of=PtN
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/aad8913f94935e8de129a08aa2c4df9f535cbdbd?/JnH
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6bb09df17c00de9a6c9f9a1662961e76b8a45cc6
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6bb09df17c00de9a6c9f9a1662961e76b8a45cc6?/C6=u1I
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6bb09df17c00de9a6c9f9a1662961e76b8a45cc6?/e8c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a1e43b0804edfe6db0614177a663c7e1ac27531c
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a1e43b0804edfe6db0614177a663c7e1ac27531c?/Gx=rfm
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/a1e43b0804edfe6db0614177a663c7e1ac27531c?/RvP
<br>
gitlab.com/EHWGW/fxleljy/-/commit/49fb170161009465c9b45384d669f2337447128c
<br>
gitlab.com/EHWGW/fxleljy/-/commit/49fb170161009465c9b45384d669f2337447128c?/vz=9TA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/49fb170161009465c9b45384d669f2337447128c?/igA
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/335840707db30ff168ac3ea926e4fef1ac0bb18f
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/335840707db30ff168ac3ea926e4fef1ac0bb18f?/mx=K44
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/335840707db30ff168ac3ea926e4fef1ac0bb18f?/TxR
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1acbc8c6cc948dc177ff537dfe0711ee7f9c56de
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1acbc8c6cc948dc177ff537dfe0711ee7f9c56de?/w0=eRY
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/1acbc8c6cc948dc177ff537dfe0711ee7f9c56de?/kiC
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/43fff51b0ec5151ea304e112bdb590915240e389
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/43fff51b0ec5151ea304e112bdb590915240e389?/96=XRl
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/43fff51b0ec5151ea304e112bdb590915240e389?/3X1
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c0ae08fb4245e24594eb59904ecd5b216133db9c
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c0ae08fb4245e24594eb59904ecd5b216133db9c?/ne=spF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/c0ae08fb4245e24594eb59904ecd5b216133db9c?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/bcdab0447619fac216cc288a13905b64794396e4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/bcdab0447619fac216cc288a13905b64794396e4?/EF=mN4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/bcdab0447619fac216cc288a13905b64794396e4?/Z3X
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d09f5319691f40c65a7cd30299f6a2fe066947d5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d09f5319691f40c65a7cd30299f6a2fe066947d5?/yw=tn7
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/d09f5319691f40c65a7cd30299f6a2fe066947d5?/MqK
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/bc5c81e2c6aec05bacaa51ee48b02cea58ed4163
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/bc5c81e2c6aec05bacaa51ee48b02cea58ed4163?/P2=JNU
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/bc5c81e2c6aec05bacaa51ee48b02cea58ed4163?/9d7
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d80b9f509693a9f36e153acad47db2fd8e29ab5a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d80b9f509693a9f36e153acad47db2fd8e29ab5a?/sg=Jae
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d80b9f509693a9f36e153acad47db2fd8e29ab5a?/wQu
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0c3a37e8925c1bd41584a0c3a0e9dee2789573e0
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0c3a37e8925c1bd41584a0c3a0e9dee2789573e0?/D7=vZq
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/0c3a37e8925c1bd41584a0c3a0e9dee2789573e0?/Bf9
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1ebb057c77abb1110838a5d0f14916558dc21f22
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1ebb057c77abb1110838a5d0f14916558dc21f22?/uh=Hys
<br>
gitlab.com/EHWGW/fxleljy/-/commit/1ebb057c77abb1110838a5d0f14916558dc21f22?/0Uy
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0fce4da2ebc960ec5d2cbab9076c78341a2cee2e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0fce4da2ebc960ec5d2cbab9076c78341a2cee2e?/qK=KLs
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0fce4da2ebc960ec5d2cbab9076c78341a2cee2e?/DhB
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/93aa3ccc8b36398ab7f1c55482108280d37e9759
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/93aa3ccc8b36398ab7f1c55482108280d37e9759?/nx=o2W
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/93aa3ccc8b36398ab7f1c55482108280d37e9759?/UyS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6fab25b62bbb5bb0695885d48ff85edde940a421
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6fab25b62bbb5bb0695885d48ff85edde940a421?/DU=4E5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6fab25b62bbb5bb0695885d48ff85edde940a421?/HlF
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/be87c71ce466ebee70fda0faa05af90a50bc3836
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/be87c71ce466ebee70fda0faa05af90a50bc3836?/3u=85W
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/be87c71ce466ebee70fda0faa05af90a50bc3836?/4Y2
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/920b290b91c9c9b615fe6e6dd1a48e824846b929
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/920b290b91c9c9b615fe6e6dd1a48e824846b929?/zw=rl5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/920b290b91c9c9b615fe6e6dd1a48e824846b929?/NrL
<br>
gitlab.com/EHWGW/fxleljy/-/commit/b766f868d403c4752d2dd9c06820ff4822c9c350
<br>
gitlab.com/EHWGW/fxleljy/-/commit/b766f868d403c4752d2dd9c06820ff4822c9c350?/bS=gAe
<br>
gitlab.com/EHWGW/fxleljy/-/commit/b766f868d403c4752d2dd9c06820ff4822c9c350?/c6a
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5b70e1c1e0cdb9506e0d7c9e25ee50f725dd426b
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5b70e1c1e0cdb9506e0d7c9e25ee50f725dd426b?/NB=paA
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5b70e1c1e0cdb9506e0d7c9e25ee50f725dd426b?/PtN
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8085920bb7677a2d2b9be1e9e09e422732cad2f5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8085920bb7677a2d2b9be1e9e09e422732cad2f5?/1B=2mG
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/8085920bb7677a2d2b9be1e9e09e422732cad2f5?/CgA
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fbe0f5bd4e5f614905d9678841cdd04eb91c22b2
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fbe0f5bd4e5f614905d9678841cdd04eb91c22b2?/9D=Kb8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/fbe0f5bd4e5f614905d9678841cdd04eb91c22b2?/xRv
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e8279f35caa42a66fc77741a24ccec239b8f7176
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e8279f35caa42a66fc77741a24ccec239b8f7176?/CT=3D4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/e8279f35caa42a66fc77741a24ccec239b8f7176?/GkE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a6245eee12bc5653993d678949c79146f3bf71cd
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a6245eee12bc5653993d678949c79146f3bf71cd?/Jw=DHO
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/a6245eee12bc5653993d678949c79146f3bf71cd?/31V
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8ed75fbf488b1ded2314846dc73b4dab206998ae
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8ed75fbf488b1ded2314846dc73b4dab206998ae?/m3=dne
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8ed75fbf488b1ded2314846dc73b4dab206998ae?/qKo
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a85bc00733db9a02f081012806aa3194d983a41a
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a85bc00733db9a02f081012806aa3194d983a41a?/S9=3ry
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a85bc00733db9a02f081012806aa3194d983a41a?/d7b
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9bdbb96a3fbdb5105efa3c7d84e2664aa489d075
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9bdbb96a3fbdb5105efa3c7d84e2664aa489d075?/ES=Ppg
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/9bdbb96a3fbdb5105efa3c7d84e2664aa489d075?/sMq
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6e973ab388f4052e05d63f9b64b10113a7d09d92
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6e973ab388f4052e05d63f9b64b10113a7d09d92?/nk=B5P
<br>
gitlab.com/EHWGW/fxleljy/-/commit/6e973ab388f4052e05d63f9b64b10113a7d09d92?/hBf
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9a619c830fca30b84e8efa5ff793916bfadb7b83
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9a619c830fca30b84e8efa5ff793916bfadb7b83?/vF=wKb
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9a619c830fca30b84e8efa5ff793916bfadb7b83?/wQu
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8412088aed939b5845593f2754aee41389e55fc6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8412088aed939b5845593f2754aee41389e55fc6?/Os=stQ
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/8412088aed939b5845593f2754aee41389e55fc6?/lFj
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ca4d3ee43fe4ccb7ac8029e94745383f88fcece3
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ca4d3ee43fe4ccb7ac8029e94745383f88fcece3?/zq=3Ur
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/ca4d3ee43fe4ccb7ac8029e94745383f88fcece3?/W0U
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/bea6e71f76811958cc489722d2618610e1ab9919
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/bea6e71f76811958cc489722d2618610e1ab9919?/G7=LIj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/bea6e71f76811958cc489722d2618610e1ab9919?/HlF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9b3f94294f0ae3ee65185fcae7c7654380602865
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9b3f94294f0ae3ee65185fcae7c7654380602865?/d3=u8c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/9b3f94294f0ae3ee65185fcae7c7654380602865?/a4Y
<br>
gitlab.com/EHWGW/fxleljy/-/commit/658a352634395e22494c7f82d16f0eaba58096c4
<br>
gitlab.com/EHWGW/fxleljy/-/commit/658a352634395e22494c7f82d16f0eaba58096c4?/H5=iz3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/658a352634395e22494c7f82d16f0eaba58096c4?/LpJ
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b75eef003b5b331d219ab5519fe3f66cbd4c9a66
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b75eef003b5b331d219ab5519fe3f66cbd4c9a66?/Vf=WkE
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/b75eef003b5b331d219ab5519fe3f66cbd4c9a66?/Ae8
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/737d261a5724d449cdacfdc5835aea278932e841
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/737d261a5724d449cdacfdc5835aea278932e841?/RL=fJ6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/737d261a5724d449cdacfdc5835aea278932e841?/vPt
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e4be80a88fd795f670d490502c8744e775d445cf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e4be80a88fd795f670d490502c8744e775d445cf?/C3=KrS
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/e4be80a88fd795f670d490502c8744e775d445cf?/Ae8
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/30f2d0aa7f9b1c91267bc4a0081b90b5d4b05574
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/30f2d0aa7f9b1c91267bc4a0081b90b5d4b05574?/K4=44c
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/30f2d0aa7f9b1c91267bc4a0081b90b5d4b05574?/xRv
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3a03beb41cf45c3fe29d22e128ce15c887192471
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3a03beb41cf45c3fe29d22e128ce15c887192471?/Zj=aoI
<br>
gitlab.com/EHWGW/fxleljy/-/commit/3a03beb41cf45c3fe29d22e128ce15c887192471?/kEi
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d2d6cf8a5eb477819d0e85baa20ed5e3e563f358
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d2d6cf8a5eb477819d0e85baa20ed5e3e563f358?/Dk=K1O
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/d2d6cf8a5eb477819d0e85baa20ed5e3e563f358?/3X1
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d783e3b0d8467d32dc4f58dbe568b25119e12909
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d783e3b0d8467d32dc4f58dbe568b25119e12909?/1b=lcq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d783e3b0d8467d32dc4f58dbe568b25119e12909?/ImG
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fd41e4503d88a67effe69ee32ddc5bbe779293de
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fd41e4503d88a67effe69ee32ddc5bbe779293de?/da=1vF
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/fd41e4503d88a67effe69ee32ddc5bbe779293de?/X1V
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/03eeb229c9c352e33ea2cf3def6105df5a5c20d8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/03eeb229c9c352e33ea2cf3def6105df5a5c20d8?/iV=cKo
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/03eeb229c9c352e33ea2cf3def6105df5a5c20d8?/mGk
<br>
gitlab.com/EHWGW/fxleljy/-/commit/064114a28188376cfbc9827390422d3147e009ff
<br>
gitlab.com/EHWGW/fxleljy/-/commit/064114a28188376cfbc9827390422d3147e009ff?/TE=iij
<br>
gitlab.com/EHWGW/fxleljy/-/commit/064114a28188376cfbc9827390422d3147e009ff?/b5Z
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/968b28485762a559849d58fead1aaaaab55b6899
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/968b28485762a559849d58fead1aaaaab55b6899?/gK=8Fz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/968b28485762a559849d58fead1aaaaab55b6899?/OMq
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5992a7af37de99c969086b511360a7911536b7a4
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5992a7af37de99c969086b511360a7911536b7a4?/tx=4Ls
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/5992a7af37de99c969086b511360a7911536b7a4?/hBf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/aa092f4bc72e96f82f51278e89545584eada1622
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/aa092f4bc72e96f82f51278e89545584eada1622?/HR=I2W
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/aa092f4bc72e96f82f51278e89545584eada1622?/SwQ
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/195d9c85686b284bfc1f0fc2ac0d154fa0b8f20e
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/195d9c85686b284bfc1f0fc2ac0d154fa0b8f20e?/T6=NR5
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/195d9c85686b284bfc1f0fc2ac0d154fa0b8f20e?/DhB
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7f8e91c1772be9fb3c5d50df80e4d2bf5a66337d
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7f8e91c1772be9fb3c5d50df80e4d2bf5a66337d?/ko=vCj
<br>
gitlab.com/EHWGW/fxleljy/-/commit/7f8e91c1772be9fb3c5d50df80e4d2bf5a66337d?/Y2W
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bcd8f3a17d260b5076b9874028adc4169f7a12d1
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bcd8f3a17d260b5076b9874028adc4169f7a12d1?/9u=uuS
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bcd8f3a17d260b5076b9874028adc4169f7a12d1?/nHl
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/953c7ba91f682c043679f8c27c6cc3535ad6f957
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/953c7ba91f682c043679f8c27c6cc3535ad6f957?/5P=ZQA
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/953c7ba91f682c043679f8c27c6cc3535ad6f957?/6a4
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4aecb6be1348a3ea5bd211fa3fb48013b085e16b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4aecb6be1348a3ea5bd211fa3fb48013b085e16b?/uo=8pj
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/4aecb6be1348a3ea5bd211fa3fb48013b085e16b?/rLp
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1048c0d3dffbd439cedc87de2879adf2c69495ad
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1048c0d3dffbd439cedc87de2879adf2c69495ad?/yf=5wg
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/1048c0d3dffbd439cedc87de2879adf2c69495ad?/c6a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5b70127d28fc4f2cf89b8b5e97d025a03f8e5260
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5b70127d28fc4f2cf89b8b5e97d025a03f8e5260?/n0=RL8
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/5b70127d28fc4f2cf89b8b5e97d025a03f8e5260?/xRv
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c71187f525ccd1589917f539f60ae92bf070a429
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c71187f525ccd1589917f539f60ae92bf070a429?/Ay=5Mt
<br>
gitlab.com/EHWGW/fxleljy/-/commit/c71187f525ccd1589917f539f60ae92bf070a429?/iCg
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fa252377048da0def237b035131d6d86fe3ccb4e
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fa252377048da0def237b035131d6d86fe3ccb4e?/N7=bZ3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/fa252377048da0def237b035131d6d86fe3ccb4e?/1Vz
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/bd8ca9fe9514742dbe4bcd5605a36d1459fa7553
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/bd8ca9fe9514742dbe4bcd5605a36d1459fa7553?/i3=D4l
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/bd8ca9fe9514742dbe4bcd5605a36d1459fa7553?/GkE
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/58563ef08ee5cf5fe6827c0a6c852675572a6e88
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/58563ef08ee5cf5fe6827c0a6c852675572a6e88?/aV=s8g
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/58563ef08ee5cf5fe6827c0a6c852675572a6e88?/1Vz
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bc5081fb2e5b4680cc5999a303480853077d041e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bc5081fb2e5b4680cc5999a303480853077d041e?/3A=uOs
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/bc5081fb2e5b4680cc5999a303480853077d041e?/oIm
<br>
gitlab.com/EHWGW/fxleljy/-/commit/697748f65201b3f1f031a81df79caddf85b8d649
<br>
gitlab.com/EHWGW/fxleljy/-/commit/697748f65201b3f1f031a81df79caddf85b8d649?/TE=iij
<br>
gitlab.com/EHWGW/fxleljy/-/commit/697748f65201b3f1f031a81df79caddf85b8d649?/5Z3
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6a51a539384c2d4f2cf072883657941cb6d3168b
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6a51a539384c2d4f2cf072883657941cb6d3168b?/mZ=9qk
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/6a51a539384c2d4f2cf072883657941cb6d3168b?/sMq
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/84e3f51fa0d1959e966c484ee0b6eb98270c6c10
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/84e3f51fa0d1959e966c484ee0b6eb98270c6c10?/NX=sWM
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/84e3f51fa0d1959e966c484ee0b6eb98270c6c10?/5Z3
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de561bcb06ec12580d172ed2c1e5867174bb600a
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de561bcb06ec12580d172ed2c1e5867174bb600a?/Qn=48m
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de561bcb06ec12580d172ed2c1e5867174bb600a?/uOs
<br>
gitlab.com/EHWGW/fxleljy/-/commit/806a3b3169563d1dd09b909bff939ec5ca798fab
<br>
gitlab.com/EHWGW/fxleljy/-/commit/806a3b3169563d1dd09b909bff939ec5ca798fab?/V9=Tey
<br>
gitlab.com/EHWGW/fxleljy/-/commit/806a3b3169563d1dd09b909bff939ec5ca798fab?/DBf
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/30e1267d7946b525c0079165853eef280a572a2e
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/30e1267d7946b525c0079165853eef280a572a2e?/63=UOi
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/30e1267d7946b525c0079165853eef280a572a2e?/0Uy
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ca14ff6c4a2ad7fa258c6fb498cf599ab05f04e4
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ca14ff6c4a2ad7fa258c6fb498cf599ab05f04e4?/R2=C3G
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/ca14ff6c4a2ad7fa258c6fb498cf599ab05f04e4?/Fjh
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6cc161dd3d274d2e5dfc9cf84ce728d1acc9f1f4
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6cc161dd3d274d2e5dfc9cf84ce728d1acc9f1f4?/xH=yLc
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/6cc161dd3d274d2e5dfc9cf84ce728d1acc9f1f4?/UyS
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d309ee1e30170fa91bbb58e91ed73698786cccc6
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d309ee1e30170fa91bbb58e91ed73698786cccc6?/m6=nhU
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/d309ee1e30170fa91bbb58e91ed73698786cccc6?/JnH
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d2e910bd3abe791f31f90757b7f8ce0d816f77a3
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d2e910bd3abe791f31f90757b7f8ce0d816f77a3?/sW=KxF
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d2e910bd3abe791f31f90757b7f8ce0d816f77a3?/a4Y
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a0d256ab7001e08949609ec01694e3cb85f1f158
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a0d256ab7001e08949609ec01694e3cb85f1f158?/TQ=rl5
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/a0d256ab7001e08949609ec01694e3cb85f1f158?/NrL
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0fd7128ec0cdc583457cafbe675c861e529704f1
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0fd7128ec0cdc583457cafbe675c861e529704f1?/os=zGn
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/0fd7128ec0cdc583457cafbe675c861e529704f1?/c6a
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0c37bcc7b1393732d0bf81113efff2e343973eb5
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0c37bcc7b1393732d0bf81113efff2e343973eb5?/6D=Rus
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/0c37bcc7b1393732d0bf81113efff2e343973eb5?/NrL
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de2f8e6657ed687131fd42a6525c5fee5379b4ee
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de2f8e6657ed687131fd42a6525c5fee5379b4ee?/Zq=t1l
<br>
gitlab.com/JDJTY/txiqmhb/-/commit/de2f8e6657ed687131fd42a6525c5fee5379b4ee?/Ae8
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d872eb599211a4d2f14a506feedb241419826b3e
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d872eb599211a4d2f14a506feedb241419826b3e?/RF=McA
<br>
gitlab.com/EHWGW/fxleljy/-/commit/d872eb599211a4d2f14a506feedb241419826b3e?/VzT
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/63e8f38331ef61063366eac2db3b1bfd02425522
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/63e8f38331ef61063366eac2db3b1bfd02425522?/pG=AU8
<br>
gitlab.com/JHEJHR/auhkgvk/-/commit/63e8f38331ef61063366eac2db3b1bfd02425522?/GkE
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c05d8b02fb7362c36c53704a17a888135221de8e
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c05d8b02fb7362c36c53704a17a888135221de8e?/3y=Izt
<br>
gitlab.com/qwAREGTH/lesqxqz/-/commit/c05d8b02fb7362c36c53704a17a888135221de8e?/1Vz
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/62c6f528bebf09e9169568b79612853824da4322
<br>
gitlab.com/GSEGERSGH/bbynuiq/-/commit/62c6f528bebf09e9169568b79612853824da4322?/Mq=nEb
<br>

<h2>项目结构</h2><br>

项目目录采用模块化分层设计，便于维护与扩展。各子目录职责清晰，核心资源列表与前端展示逻辑分离。


mobile-article-aggregator/
├── public/                          # 静态资源目录，无需构建直接复制
│   ├── favicon.ico                  # 站点图标文件
│   └── robots.txt                   # 搜索引擎爬虫规则，屏蔽非生产环境路径
├── src/                             # 源代码主目录
│   ├── assets/                      # 前端资源文件（图片、字体、全局样式）
│   │   ├── images/                  # 项目用到的矢量图与位图素材
│   │   └── styles/                  # 全局基础样式与 CSS 变量定义
│   ├── components/                  # 可复用的 UI 组件
│   │   ├── LinkList.vue             # 链接列表核心渲染组件，支持分页与过滤
│   │   ├── SearchBar.vue            # 关键字搜索输入组件
│   │   └── CategoryFilter.vue       # 分类标签筛选组件
│   ├── data/                        # 数据层，存放静态链接资源列表
│   │   ├── links.json               # 主链接索引文件，包含全部 250 条记录
│   │   └── categories.json          # 分类映射表，定义标签与链接 ID 的对应关系
│   ├── layouts/                     # 页面布局模板
│   │   ├── default.vue              # 默认两栏布局（侧边栏 + 主内容区）
│   │   └── full-width.vue           # 全宽布局，用于搜索与统计页面
│   ├── pages/                       # 路由页面入口
│   │   ├── index.vue                # 首页，展示全部资源列表与分类概览
│   │   ├── about.vue                # 项目介绍与使用说明页面
│   │   └── stats.vue                # 链接统计信息页面（总数、分类分布）
│   ├── utils/                       # 工具函数库
│   │   ├── validator.js             # 链接格式校验与规范化工具
│   │   └── filter.js                # 数组过滤与排序辅助函数
│   └── main.js                      # 应用入口文件，初始化 Vue 实例与插件
├── scripts/                         # 运维与辅助脚本
│   ├── check-links.sh               # 批量检测链接可用性的 Bash 脚本
│   └── generate-sitemap.js          # 生成站点地图 XML 文件的 Node 脚本
├── tests/                           # 单元测试与集成测试
│   ├── unit/                        # 组件与函数的单元测试用例
│   └── e2e/                         # 端到端测试脚本（基于 Playwright）
├── .gitignore                       # Git 版本忽略规则文件
├── package.json                     # Node.js 项目依赖与脚本定义
├── README.md                        # 项目说明文档（本文件）
├── LICENSE                          # MIT 许可证全文
└── vite.config.js                   # Vite 构建工具配置文件


<h2> 贡献指南</h2><br>

我们欢迎社区开发者以多种形式参与本项目的维护与改进。所有贡献需遵守项目行为准则，并按照以下流程操作。

第一步：查阅现有 Issue 与 Pull Request。在提交新贡献之前，请先浏览 GitHub 上的现有议题，确认无人正在处理相同问题或功能请求，避免重复劳动。

第二步：Fork 项目并创建功能分支。将本仓库 Fork 至个人账号下，然后基于 `main` 分支创建一个新的分支，分支命名建议采用 `feature/功能描述` 或 `fix/问题简述` 的格式。

第三步：完成代码或文档修改。请遵循项目既定的代码风格（ESLint 配置）与提交信息规范（使用 Conventional Commits 格式）。若涉及链接列表的增删，请同步更新 `src/data/links.json` 中的对应条目。

第四步：编写或更新测试用例。对于新增的功能或修复的缺陷，请在 `tests/` 目录下补充相应的单元测试或端到端测试，确保代码覆盖率不下降。

第五步：提交 Pull Request。推送本地分支到远程仓库后，向本项目的 `main` 分支发起 Pull Request，并在描述中清晰说明修改内容、动机以及相关 Issue 编号。项目维护者会在三个工作日内进行审阅。

<h2>常见问题</h2><br>

问：如何快速判断某条链接是否仍然有效？

答：项目根目录下的 `scripts/check

> 外链数量: 350 | 生成时间:2026年09月18日03时53分32秒
