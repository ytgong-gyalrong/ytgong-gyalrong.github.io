---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: myphoto.JPG
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>1140 Amsterdam Ave</p>
    <p>NYC, NY 10027</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.


<style>
/* 1. 强制替换主题色（常春藤绿） */
:root {
  --global-theme-color: #2e8b57 !important;
}

/* 2. 横幅样式 */
.hero-banner {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 350px;
  background-image: url('{{ "/assets/img/IMG_2568" | relative_url }}');
  background-size: cover;
  background-position: center;
  z-index: 0;
  pointer-events: none;
}

/* 3. 保护导航栏并把主页内容往下推 */
header, nav {
  position: relative !important;
  z-index: 10 !important;
}
.container {
  position: relative !important;
  z-index: 5 !important;
}
.post {
  margin-top: 200px !important;
}
</style>

<script>
  // 黑科技：强行在网页最底层插入横幅，彻底无视系统原有的背景限制
  document.addEventListener("DOMContentLoaded", function() {
    if (!document.querySelector('.hero-banner')) {
      var banner = document.createElement("div");
      banner.className = "hero-banner";
      document.body.insertBefore(banner, document.body.firstChild);
    }
  });
</script>
