# Newspaper

VPS 自动生成并同步的静态新闻站点，通过 GitHub Pages 发布。

- 网站：[newspaper.guzhengsvt.cn](https://newspaper.guzhengsvt.cn/)
- 往期新闻：[归档](https://newspaper.guzhengsvt.cn/archive/)
- 生成程序：[GuZhengSVT/Newspaper](https://github.com/GuZhengSVT/Newspaper)

## 阅读与订阅

站点按“科技”“政治”和“ACGN”三个一级板块展示新闻，首页默认通过按钮切换，也可在“首页布局”中选择分栏展示；布局选择在浏览器保存。政治细分中国、美国、欧洲、俄乌战争、中东地区、南美、非洲、其他八个子板块。子板块按各自的日报或周报周期更新。新闻包含正文、来源链接及可选配图，支持深浅配色、目录导航和归档搜索。

| RSS | 订阅地址 |
| --- | --- |
| 全部新闻 | [feed.xml](https://newspaper.guzhengsvt.cn/feed.xml) |
| 科技 | [feed-technology.xml](https://newspaper.guzhengsvt.cn/feed-technology.xml) |
| 政治 | [feed-politics.xml](https://newspaper.guzhengsvt.cn/feed-politics.xml) |
| ACGN | [feed-acgn.xml](https://newspaper.guzhengsvt.cn/feed-acgn.xml) |

网站仅展示最近 30 天的新闻。没有符合收录标准的内容时，当期可能为空；空刊不代表相关领域没有发生新闻。

## 发布方式

VPS 完成检索、编辑、核验和网页构建后，站点发布目录的变更会触发同步服务；服务等待当前新闻任务结束后，读取已完成的站点文件。有变化才提交到本仓库的 `main` 分支，再由 GitHub Pages 从根目录部署。过期内容清理后的网页构建也会触发同步，不再按分钟轮询检查。

自动同步提交统一使用标题 `deploy(site): sync generated site`，提交时间由 Git 记录。文档维护使用 `docs(site): ...`，便于区分站点发布与仓库说明的修改。

网页、样式和脚本由生成程序维护，直接修改本仓库中的生成文件会在下次同步时被覆盖。`README.md`、`robots.txt` 和 `LICENSE` 在同步时保留，可在本仓库中维护。服务端配置、账号凭据和原始采集记录不进入本仓库。

## 文件说明

| 路径 | 用途 |
| --- | --- |
| `index.html` | 首页 |
| `assets/` | 样式与浏览器脚本 |
| `daily/` | 已发布新闻页面，有新闻时生成 |
| `archive/` | 往期新闻索引 |
| `downloads/` | Markdown、JSON 下载文件，有新闻时生成 |
| `feed*.xml` | RSS 订阅 |
| `search.json` | 站内搜索索引 |
| `CNAME` | GitHub Pages 自定义域名 |
| `.nojekyll` | 直接发布静态文件，跳过 Jekyll 处理 |
| `robots.txt` | 搜索引擎抓取规则 |

## 抓取规则

允许抓取公开页面和 RSS，禁止抓取重复的下载文件及站内搜索数据。`robots.txt` 是爬虫访问约定，不承担访问控制作用。

## 许可证

仓库自有代码和文档采用 [MIT License](LICENSE)，与生成程序保持一致。第三方引文、图片等不在该授权范围内，其使用条件以原始来源为准。
