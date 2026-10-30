# McSafeNet.github.io

Edward（[@McSafeNet](https://github.com/McSafeNet)）的个人主页：<https://mcsafenet.github.io>

基于 [luost26/academic-homepage](https://github.com/luost26/academic-homepage) 模板（Jekyll + GitHub Pages）。

## 修改内容

| 内容 | 文件 |
| --- | --- |
| 姓名、简介、联系方式、教育/经历/奖项 | `_data/profile.yml` |
| 头像 | `assets/images/photos/portrait.jpg` |
| 项目（Projects 页 & 首页） | `_publications/<年份>/*.md`，封面图放 `assets/images/covers/` |
| 动态（News） | `_news/*.md` |
| 导航栏 | `_data/navigation.yml` |
| 首页显示开关 | `_data/display.yml` |

推送到 `main` 分支后，GitHub Pages 会自动构建发布。

## 本地预览

```bash
bundle install
bundle exec jekyll serve
```

然后访问 <http://localhost:4000>。
