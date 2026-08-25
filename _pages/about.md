---
layout: about
title: About
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: myphoto.JPG
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>1140 Amsterdam Ave</p>
    <p>NYC, NY 10027</p>

# selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

# announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

# latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi, welcome to my personal website. My name is Yuting Gong and I am a first-year Ph.D. student in East Asian Languages and Cultures (EALAC) at Columbia University. I am a first-generation college student born at the eastern edge of the Tibetan Plateau. I primarily conduct research in topics such as state-building, gender, mobility and how these aspects intersecting with each other in borderland regions, such as Sino-Tibetan borderlands. I was trained with social science mostly and my previous research mainly focused on contemporary era and I am incorporating historical perspective in my future research and hopefully will be able to self-label as a historian someday. Methodologically, I am navigating a method integrating historical archival research with contemporary ethnographic fieldwork. 

Growing up as first-generation college student, I am fully aware of the maldistribution of educational resources, especially towards women, ethnic minorities and kids from less-developed area. That is to say, if you do have any questions, please feel free to reach out! 


<style>
/* 1. 强制纯黑主题色（经典、醒目） */
:root {
  --global-theme-color: #000000 !important; 
}

/* 2. 学术感拉满：全局强行替换为 Serif 衬线字体 */
body, h1, h2, h3, h4, h5, h6, p, a, div, span, li {
  font-family: "Georgia", "Times New Roman", Times, serif !important;
}

/* 3. 横幅样式（高度加长，包住全部内容） */
.hero-banner {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 900px; /* 【拉长了背景图】：从 700 变 900，确保你的照片全部在背景里 */
  background-image: url('/assets/img/IMG_2568.JPG');
  background-size: cover;
  background-position: center;
  z-index: 0;
  pointer-events: none;
}

/* 4. 保护排版 */
header, nav {
  position: relative !important;
  z-index: 10 !important;
}
.container {
  position: relative !important;
  z-index: 5 !important;
}

/* 5. 头像和文字的位置微调 */
.post {
  /* 头像稍微往下挪了一点，不至于顶着天花板 */
  margin-top: 150px !important; 
}
</style>
