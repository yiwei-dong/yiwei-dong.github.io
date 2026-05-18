---
layout: archive
title: "Experiences"
permalink: /experiences/
author_profile: true
---

<style>
  /* ── Section Header ── */
  .sec-head {
    display: flex;
    align-items: center;
    gap: 10px;
    margin: 36px 0 16px;
    border-bottom: 1px solid #e2e2e2;
    padding-bottom: 10px;
  }
  .sec-head:first-child { margin-top: 0; }
  .sec-icon {
    width: 32px;
    height: 32px;
    border-radius: 6px;
    background: #f0f0f0;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
    font-size: 15px;
  }
  .sec-title-en { font-size: 15px; font-weight: 700; color: #111; }
  .sec-title-zh { font-size: 12px; color: #999; margin-left: 4px; }

  /* ── Timeline ── */
  .tl {
    border-left: 1.5px solid #d8d8d8;
    margin-left: 10px;
    padding-left: 22px;
  }
  .tl-item { position: relative; margin-bottom: 26px; }
  .tl-item:last-child { margin-bottom: 0; }
  .tl-dot {
    position: absolute;
    left: -28px;
    top: 8px;
    width: 9px;
    height: 9px;
    border-radius: 50%;
    background: #444;
    border: 2px solid #fff;
    box-shadow: 0 0 0 1.5px #ccc;
  }

  /* 新增：用于将文本内容与日期左右分离的 Flex 布局 */
  .tl-row {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 15px;
  }
  .tl-body { flex: 1; }

  .tl-org    { font-size: 14.5px; font-weight: 700; color: #111; margin: 0 0 1px; }
  .tl-org-zh { font-size: 12px;   color: #777;      margin: 0 0 4px; }
  .tl-role    { font-size: 13px;  color: #444;      margin: 0 0 1px; font-style: italic; }
  .tl-role-zh { font-size: 12px;  color: #888;      margin: 0 0 6px; font-style: italic; }
  
  /* 修改：移除了下边距，添加不换行和收缩属性以适应右侧布局 */
  .tl-period {
    display: inline-block;
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.04em;
    background: #f2f2f2;
    color: #666;
    border-radius: 3px;
    padding: 2px 7px;
    flex-shrink: 0;
    white-space: nowrap;
    margin-top: 1px;
  }

  .tl-meta    { font-size: 13px;  color: #333;  margin: 4px 0;  line-height: 1.6; }
  .tl-meta strong { color: #111; font-weight: 600; }
  .tl-meta-zh { font-size: 12px;  color: #888;  margin: 2px 0 4px; line-height: 1.6; }
  .tl-courses    { font-size: 12.5px; color: #555; line-height: 1.7; margin: 4px 0 0; }
  .tl-courses-zh { font-size: 12px;   color: #888; line-height: 1.7; margin: 3px 0 0; }

  /* ── Award / Competition List ── */
  .award-list { list-style: none; padding: 0; margin: 0; }
  .award-item {
    display: flex;
    align-items: baseline;
    gap: 10px;
    padding: 10px 0;
    border-bottom: 1px solid #f0f0f0;
  }
  .award-item:last-child { border-bottom: none; }
  .award-bullet {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: #aaa;
    flex-shrink: 0;
    margin-top: 3px;
  }
  .award-body { flex: 1; }
  .award-en   { font-size: 13.5px; color: #222; line-height: 1.5; }
  .award-zh   { font-size: 12px;   color: #888; margin-top: 2px; line-height: 1.5; }
  .award-tag {
    display: inline-block;
    font-size: 11px;
    color: #666;
    background: #f5f5f5;
    border-radius: 3px;
    padding: 0 6px;
    margin-left: 5px;
    vertical-align: middle;
  }
  .award-date { font-size: 11.5px; color: #aaa; flex-shrink: 0; white-space: nowrap; }
</style>

<!-- ══ Education ══ -->

<div class="sec-head">
  <div class="sec-icon"><i class="fas fa-graduation-cap" style="font-size:14px; color:#555;"></i></div>
  <span class="sec-title-en">Education</span>
</div>

<div class="tl">

  <div class="tl-item">
    <div class="tl-dot"></div>
    <div class="tl-row">
      <div class="tl-body">
        <p class="tl-org">Nanyang Technological University &nbsp;·&nbsp; Singapore</p>
        <p class="tl-org-zh">新加坡南洋理工大学 </p>
        <p class="tl-role">M.Sc. in Computer Control &amp; Automation</p>
        <p class="tl-role-zh">计算机控制与自动化 · 硕士研究生</p>
        <p class="tl-meta"><strong>GPA:</strong> 5.0 / 5.0 &nbsp;·&nbsp; Top 1%</p>
      </div>
      <div class="tl-period">Aug 2025 – Jul 2026</div>
    </div>
  </div>

  <div class="tl-item">
    <div class="tl-dot"></div>
    <div class="tl-row">
      <div class="tl-body">
        <p class="tl-org">Shenzhen University &nbsp;·&nbsp; Shenzhen, China</p>
        <p class="tl-org-zh">深圳大学</p>
        <p class="tl-role">B.Sc. in Information and Computing Science</p>
        <p class="tl-role-zh">信息与计算科学 · 理学学士</p>
        <p class="tl-meta"><strong>GPA:</strong> 3.68 / 4.5 &nbsp;·&nbsp; Top 15%</p>
      </div>
      <div class="tl-period">Sep 2020 – Jul 2024</div>
    </div>
  </div>

</div>

<!-- ══ Internship ══ -->

<div class="sec-head">
  <div class="sec-icon"><i class="fas fa-briefcase" style="font-size:13px; color:#555;"></i></div>
  <span class="sec-title-en">Internship</span>
</div>

<div class="tl">

  <div class="tl-item">
    <div class="tl-dot"></div>
    <div class="tl-row">
      <div class="tl-body">
        <p class="tl-org">Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences</p>
        <p class="tl-org-zh">中国科学院深圳先进技术研究院</p>
        <p class="tl-role">Algorithm Intern</p>
      </div>
      <div class="tl-period">Apr 2025 – Jul 2025</div>
    </div>
  </div>

</div>

<!-- ══ Extracurricular ══ -->

<div class="sec-head">
  <div class="sec-icon"><i class="fas fa-users" style="font-size:13px; color:#555;"></i></div>
  <span class="sec-title-en">Extracurricular Activities</span>
</div>

<div class="tl">

  <div class="tl-item">
    <div class="tl-dot"></div>
    <div class="tl-row">
      <div class="tl-body">
        <p class="tl-org">Huawei Intelligent Base Club, SZU</p>
        <p class="tl-org-zh">深圳大学华为智能基座社团</p>
        <p class="tl-role">President</p>
      </div>
      <div class="tl-period">Sep 2022 – Jun 2023</div>
    </div>
  </div>

</div>

<!-- ══ Honors & Scholarships ══ -->

<div class="sec-head">
  <div class="sec-icon"><i class="fas fa-award" style="font-size:14px; color:#555;"></i></div>
  <span class="sec-title-en">Honors &amp; Scholarships</span>
</div>

<ul class="award-list">

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">Outstanding Graduate of School of Mathematical Sciences, SZU</div>
      <div class="award-zh">深圳大学数学科学学院级优秀毕业生</div>
    </div>
    <div class="award-date">Jun 2024</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">Shenzhen University Third Class Scholarship</div>
      <div class="award-zh">深圳大学三等奖学金</div>
    </div>
    <div class="award-date">Dec 2023</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">Shenzhen University – Tencent Friend Scholarship</div>
      <div class="award-zh">深圳大学腾讯益友奖学金</div>
    </div>
    <div class="award-date">Jun 2023</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">Ministry of Education of China – Huawei Future Star Scholarship</div>
      <div class="award-zh">中国教育部 - 华为未来之星奖学金</div>
    </div>
    <div class="award-date">Dec 2022 &amp; 2023</div>
  </li>

</ul>

<!-- ══ Competitions ══ -->

<div class="sec-head">
  <div class="sec-icon"><i class="fas fa-trophy" style="font-size:13px; color:#555;"></i></div>
  <span class="sec-title-en">Competitions</span>
</div>

<ul class="award-list">

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">UG Innovation &amp; Entrepreneurship Training Program — Provincial Project</div>
      <div class="award-zh">大学生创新创业训练计划 · 广东省省级项目</div>
    </div>
    <div class="award-date">Jun 2024</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">China Artificial Intelligence Innovation Application Competition — Third Prize </div>
      <div class="award-zh">中国人工智能创新应用大赛 · 三等奖</div>
    </div>
    <div class="award-date">Feb 2023</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">China Undergraduate Mathematical Contest in Modeling — Provincial Second Prize </div>
      <div class="award-zh">全国大学生数学建模竞赛 · 省级二等奖</div>
    </div>
    <div class="award-date">Sep 2022</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">Shenzhen, HK &amp; Macau Undergraduate Maker Competition — Excellence Award </div>
      <div class="award-zh">深港澳大学生创客大赛 · 优秀奖</div>
    </div>
    <div class="award-date">Dec 2021</div>
  </li>

  <li class="award-item">
    <div class="award-bullet"></div>
    <div class="award-body">
      <div class="award-en">SZU Innovation &amp; Entrepreneurship Competition — Third Prize </div>
      <div class="award-zh">深圳大学创新创业大赛 · 三等奖</div>
    </div>
    <div class="award-date">Dec 2021</div>
  </li>

</ul>
