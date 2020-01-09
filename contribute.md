# 贡献

##### 贡献者

?> ℹ️ 字典序排列，不分先后

- [DWCarrot](https://github.com/DWCarrot)
- [hycuihz](https://github.com/hycuihz)
- [KurisupiDango](https://github.com/KurisupiDango)
- [Ping-timeout](https://github.com/Ping-timeout)

##### 特别感谢

- [毛玉线圈物语](https://craft.moe)

------

### 参与贡献

IngWiki 由 Docsify 搭建，并托管于 Github Pages。

##### 参与要求

- 了解 Markdown、CommonMark 和 GitHub Flavored Markdown 语法
- 了解 Git 的基本用法，能够解决简单的文件冲突
- 有较好的文字表达能力和简单英译能力
- 是 Ingress 玩家并充分了解 Ingress 的内容

##### 参与方式

如您满足以上要求，并有兴趣参与本 Wiki 的编辑，欢迎点击页面右上角的   `Edit on GitHub` 来编辑。

完成后，访问本 repo 并提交 Pull Request，协作者将会协助审核，如无问题，即可合并至本 repo。

------

### 文件结构

- `_404.md` - 自定义 404 页面
- `_navbar.md` - 导航栏配置，一般情况下请勿更改
- `_sidebar.md` - 侧边目录配置
- `CNAME` - 域名 CNAME 信息，一般情况下请勿更改
- `contribute.md` - 贡献人员名单及贡献方式（本页面）
- `index.html` - Docsify 各项参数，一般情况下请勿更改
- `README.md` - 网站主页内容
- `sw.js` - 离线模式 "PWA" 配置脚本
- 二级目录说明
  - `assets` - 静态资源目录，包括图片，请上传至该目录使用
  - `starter` - "入坑" 子目录
  - `advanced` - "进阶" 子目录
  - `other` - "其他玩法" 子目录
  - `event` - "线下活动" 子目录
  - `resource` - "资源" 子目录

------

### 编写规范

1. **所有文本都必须使用 UTF-8 编码**，推荐使用 [VS Code](https://code.visualstudio.com/) 编辑器
2. Wiki 内的链接应使用相对路径，并注意检查引用路径是否正确
3. 文本排版保持简洁、美观。中文和西文、数字之间要有空格
4. 编辑或新建页面时，应保持文件结构正确、整洁
5. 由于托管在 Github Pages 的特殊性，请不要上传大文件。图片请 [压缩](https://squoosh.app/) 为 WEBP 后再上传，其他大文件请使用稳定可靠的文件托管外链服务
6. heading 风格方案

   - 页首标题使用一级 heading

   - 章节/section 使用三级 heading（如希望侧边栏自动展开 table of contents，则需要使用二级 heading）

   - 小节使用五级以下 heading

7. 颜色方案

   - 阵营颜色：`['#FF6600', '#00adef', '#00b056']; // none, res, enl `

   - 等级颜色：`['#000', '#FECE5A', '#FFA630', '#FF7315', '#E40000', '#FD2992', '#EB26CD', '#C124E0', '#9627F4']; // Level 0 - 8`
