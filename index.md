---
---

# 欢迎来到我们的实验室

我们专注于 **AI for Science、计算生物学、数据驱动研究**。
这个网站用于展示研究成果、开源项目、团队成员和最新动态。

如果你希望合作、加入团队或交流想法，欢迎随时联系。

{%
  include button.html
  link="research"
  text="查看研究方向"
  icon="fa-solid fa-flask"
%}
{%
  include button.html
  type="github"
  text="GitHub 项目"
  link="https://github.com/Xgogu/my-lab-website"
%}
{%
  include button.html
  link="contact"
  text="联系我"
  icon="fa-regular fa-paper-plane"
%}

{% include section.html %}

## Highlights

{% capture text %}

我们聚焦可复现科研与跨学科问题，结合机器学习与生物医学数据，
探索更高效、可解释、可落地的研究方法。

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/share.jpg"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

这里整理了进行中的课题、可复用工具和数据资源，
方便快速了解我们正在解决的关键问题与进展。

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/background.jpg"
  link="projects"
  title="Projects"
  flip=true
  text=text
%}

{% capture text %}

我们是一支开放、互助、重视成长的团队。
欢迎学生、开发者和研究者参与合作与交流。

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Team"
  text=text
%}
