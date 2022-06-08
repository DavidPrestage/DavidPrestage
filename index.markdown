---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash

excerpt: "Project portfolio"
header:
  overlay_image: assets/images/laptop.jpeg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption:

feature_row1:
  - url: /cooking-conversion
    image_path: /assets/images/cooking.png
    alt: "Cooking conversion tool"
    title: "Cooking Conversion Web Application"
    excerpt: "Built using: Flask, Python, Postgres, HTML, CSS (Flexbox)"
    btn_label: More info / view webapp
  - url: /university
    image_path: /assets/images/birmingham.jpg
    alt: "Birmingham University"
    title: "Birmingham University Taught Coding Assignments"
    excerpt: "Languages covered: Java, SQL"
    btn_label: More info
  - url: /cs50
    image_path: /assets/images/cs50.png
    alt: "cs50"
    title: "CS50 Introduction To Computer Science: HarvardX"
    excerpt: "Completed coding problem sets and labs in: C, Python, SQL."
    btn_label: More info

feature_row2:
  - image_path: /assets/images/website.jpg
    url: /portfolio
    alt: "davidprestage.com"
    title: "Portfolio website davidprestage.com"
    excerpt: "Built using: Jekyll"
    btn_label: More info


---
<body>
{% include feature_row id="feature_row1" %}
{% include feature_row id="feature_row2" %}
</body>