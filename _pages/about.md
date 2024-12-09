---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!-- <!DOCTYPE html> -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
        }
    </style>
</head>
</html>

<!-- <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .entry {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .logo {
            width: 80px;
            height: 80px;
            margin-right: 20px;
        }
        .info {
            flex-grow: 1;
        }
    </style>
</head>
<body> -->


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
<div style="font-size: 18px;">
    I am a master's student in the Electrical & Computer Engineering department at Cornell University, where I have the privilege of being advised by 
    <a href="https://www.csl.cornell.edu/~zhiruz/">Prof. Zhiru Zhang</a>.
    <br><br>
    My research interests span <u>computer architecture</u>, <u>machine learning systems (MLSys)</u>, <u>machine learning</u>, <u>hardware compiler</u>. I am passionate about pushing the boundaries of hardware-software co-design for efficient AI and system architectures.
    <br><br>
    I am actively seeking a Ph.D. position for Fall 2025 to continue advancing these areas of research.
</div>


# 🔥 News
<div style="font-size: 18px;">
    - *2024.10*: &nbsp;🎉🎉 Our Paper SmoothE is accepted by ASPLOS 2025! 
</div>
<!-- - *2024.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASPLOS 2025</div><img src='images/smoothe.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SmoothE: Differentiable E-Graph Extraction](To Appear Soon)

<a href="https://www.csl.cornell.edu/~yc2632/">Yaohui Cai</a>, <strong style="font-size:1.0em;">Kaixin Yang</strong>, <a href="https://chenhui1016.github.io/">Chenhui Deng</a>, <a href="https://ycunxi.github.io/cunxiyu/">Cunxi Yu</a>, <a href="https://www.csl.cornell.edu/~zhiruz/">Zhiru Zhang</a>

International Conference on Architectural Support for Programming Languages and Operating Systems (**ASPLOS**), 2025. [Accept Rate: 12.7%]

[**Introduction**]
- The first differentiable approach to e-graph extraction by relaxing the discrete optimization problem of e-node selection into a continuous, probabilistic formulation which enables parallelizable global optimization that supports any differentiable objectives.
- Implement SmoothE in PyTorch and further introduce a set of performance optimization techniques to exploit vectorized processing, sparsity, seed batching to improve the efficiency of GPU execution.
<!-- [**Code**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
<!-- </div> -->

[**Code**] To be open-sourced soon.

[**Paper**] Coming up soon!
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 📖 Educations
<div class="entry">
    <img src="images/Cornell.png" alt="Cornell University" class="logo" style="width: 80px; height: 80px;">
    <div class="info">
        <strong>Cornell University</strong>, Ithaca, New York, United States <br>
        Aug 2023 - May 2024 <br>
        Master of Engineering in Computer Engineering <br>
        GPA: 3.96
    </div>
</div>

<div class="entry">
    <img src="images/BJTU.png" alt="Beijing Jiaotong University" class="logo" style="width: 80px; height: 80px;">
    <div class="info">
        <strong>Beijing Jiaotong University</strong>, Beijing, China <br>
        Sep 2019 - June 2023 <br>
        Bachelor of Engineering in Mechatronics <br>
        Major GPA: 92.4,  Outstanding Thesis Award <br>
    </div>
</div>

---

# 💼 Research Experience
<div class="entry">
    <img src="images/CSL.png" alt="Cornell Computer System Lab" class="logo" style="width: 80px; height: 80px;">
    <div class="info">
        <strong>Cornell Computer System Lab</strong>, Ithaca, New York, United States <br>
        May 2024 - Present, Full time, On-site <br>
        Aug 2023 - May 2024, Part time, On-site <br>
        Position: Research Intern <br>
        Advisor: Prof. Zhiru Zhang
    </div>
</div>
---

<!-- <html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .entry {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .logo {
            width: 80px;
            height: 80px;
            margin-right: 20px;
        }
        .info {
            flex-grow: 1;
        }
    </style>
</head>
<body> -->

# 💻 Internships
<style>
    .entry {
        display: flex;
        align-items: center;
        margin-bottom: 20px; /* Add some spacing between entries */
    }
    .logo {
        width: 80px;
        height: 50px;
        margin-right: 20px; /* Add space between the logo and text */
        object-fit: contain; /* Ensures the image fits well */
    }
    .info {
        flex-grow: 1; /* Makes the text take up remaining space */
    }
</style>

<div class="entry">
    <img src="images/Careverse.jpg" alt="Careverse Technology" class="logo" style="width: 80px; height: 50px;">
    <div class="info">
        <strong>Careverse Technology</strong>, Shanghai, China <br>
        June 2023 - August 2023 <br>
        Machine Learning Engineer
    </div>
</div>

<div class="entry">
    <img src="images/Nio.png" alt="NIO" class="logo" style="width: 80px; height: 50px;" >
    <div class="info">
        <strong>NIO</strong>, Shanghai, China <br>
        February 2023 - June 2023 <br>
        Embedded Software Engineer
    </div>
</div>

---

# 🎖 Honors and Awards
- *2020-2021 & 2021-2022* Second Class Scholarship for Academic Excellence.

- *2020-2021 & 2021-2022* Outstanding Student of the Acedamic Year 2020-2021.

---


