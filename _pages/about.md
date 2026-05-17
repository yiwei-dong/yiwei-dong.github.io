---
layout: archive
classes: wide
permalink: /
title: "About me"
excerpt: "Yiwei Dong"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .lang-switcher {
    display: inline-flex;
    align-items: center;
    background: #f3f4f6;
    border-radius: 8px;
    padding: 3px;
    margin-bottom: 28px;
    gap: 2px;
  }
  .lang-btn {
    font-size: 0.85em;
    font-weight: 500;
    padding: 5px 18px;
    border-radius: 6px;
    border: none;
    cursor: pointer;
    background: transparent;
    color: #6b7280;
    transition: all 0.18s ease;
    letter-spacing: 0.02em;
  }
  .lang-btn.active {
    background: #ffffff;
    color: #1f2937;
    box-shadow: 0 1px 3px rgba(0,0,0,0.10);
  }
  .bio-block {
    display: none;
    text-align: justify;
    line-height: 1.8;
    font-size: 1.02em;
    color: #374151;
    margin-bottom: 32px;
  }
  .bio-block.visible { display: block; }
  .bio-block a {
    color: #4b5563;
    text-decoration: none;
    border-bottom: 1px solid #d1d5db;
    transition: color 0.15s, border-color 0.15s;
  }
  .bio-block a:hover { color: #111827; border-bottom-color: #9ca3af; }
  .bio-block strong { color: #111827; font-weight: 600; }
  .logo-row {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 52px;
    padding: 20px 0 36px;
  }
  .logo-row img {
    height: 50px;
    width: auto;
    object-fit: contain;
    opacity: 0.75;
    filter: grayscale(20%);
    transition: opacity 0.2s, filter 0.2s;
  }
  .logo-row img:hover { opacity: 1; filter: grayscale(0%); }
  .section-divider { border: none; border-top: 1px solid #e5e7eb; margin: 4px 0 28px; }
  .news-shell {
    border: 1px solid #e5e7eb;
    border-radius: 10px;
    padding: 26px 28px;
    background: #ffffff;
    margin-top: 4px;
  }
  .tl-track {
    border-left: 2px solid #e5e7eb;
    margin-left: 6px;
    padding-left: 24px;
    position: relative;
  }
  .news-item { position: relative; margin-bottom: 22px; }
  .news-item:last-child { margin-bottom: 0; }
  .news-dot {
    position: absolute;
    left: -30px;
    top: 7px;
    width: 9px;
    height: 9px;
    border-radius: 50%;
    background: #9ca3af;
    border: 2px solid #ffffff;
  }
  .news-date {
    display: inline-block;
    font-size: 0.76em;
    font-weight: 600;
    letter-spacing: 0.05em;
    color: #6b7280;
    background: #f3f4f6;
    border-radius: 4px;
    padding: 1px 8px;
    margin-bottom: 5px;
  }
  .news-en, .news-zh {
    display: none;
    font-size: 0.96em;
    color: #1f2937;
    line-height: 1.65;
    margin: 0;
  }
  body.lang-en .news-en { display: block; }
  body.lang-zh .news-zh { display: block; }
</style>

<!-- ══ Language Toggle ══ -->

<div class="lang-switcher">
  <button class="lang-btn active" id="btn-en" onclick="setLang('en')">English</button>
  <button class="lang-btn"        id="btn-zh" onclick="setLang('zh')">中文</button>
</div>

<!-- ══ Bio ══ -->

<div class="bio-block visible" id="bio-en">
  <strong>Short Bio.</strong> Hi! I am Yiwei Dong, and you can also call me <strong>Ives</strong>. I recently obtained my Master's degree in <strong>Computer Control &amp; Automation</strong> from the <a href="https://www.ntu.edu.sg/eee">School of Electrical and Electronic Engineering (EEE)</a>, <a href="https://www.ntu.edu.sg/">Nanyang Technological University (NTU), Singapore</a>, under the supervision of <a href="https://soujanyaporia.github.io/"><strong>Prof. Soujanya Poria</strong></a>. Previously, I completed my undergraduate studies at the <a href="https://math.szu.edu.cn">School of Mathematical Sciences</a>, <a href="https://www.szu.edu.cn">Shenzhen University (SZU), China</a>, majoring in <strong>Information and Computing Science</strong>. Currently, I am embarking on my professional journey in the robotics industry as a <strong>Product Manager</strong>, dedicated to bridging cutting-edge automation and AI technologies with impactful product solutions.
</div>

<div class="bio-block" id="bio-zh">
  <strong>简介：</strong>大家好，我是<strong>董奕崴</strong>，你也可以叫我 Ives。我毕业于新加坡<a href="https://www.ntu.edu.sg/">南洋理工大学 (NTU)</a> <a href="https://www.ntu.edu.sg/eee">电气与电子工程学院</a>，获得了<strong>计算机控制与自动化</strong>专业的硕士学位，师从 <a href="https://soujanyaporia.github.io/"><strong>Soujanya Poria 教授</strong></a>。在此之前，我本科就读于中国<a href="https://www.szu.edu.cn">深圳大学 (SZU)</a> <a href="https://math.szu.edu.cn">数学科学学院</a>，主修<strong>信息与计算科学</strong>专业。目前，我正投身于机器人行业，担任<strong>产品经理</strong>岗位，致力于将先进的自动化与人工智能技术转化为真正改变生活的优秀产品。
</div>

<!-- ══ School Logos ══ -->

<div class="logo-row">
  <img src="images/ntu-logo.png" alt="Nanyang Technological University">
  <img src="images/szu-logo.png" alt="Shenzhen University">
</div>

<hr class="section-divider">

## <i class="fas fa-newspaper"></i> Recent News

<div class="news-shell">
  <div class="tl-track">

    <div class="news-item">
      <div class="news-dot"></div>
      <div class="news-date">05 / 2026</div>
      <p class="news-en">I successfully completed my postgraduate studies at NTU and am currently awaiting degree conferment.</p>
      <p class="news-zh">我已顺利完成在南洋理工大学 (NTU) 的硕士学业，目前正在等待官方学位授予。</p>
    </div>

    <div class="news-item">
      <div class="news-dot"></div>
      <div class="news-date">03 / 2026</div>
      <p class="news-en">Submitted my Master's dissertation for examination, detailing a reasoning guidance framework based on PRM and Beam Search.</p>
      <p class="news-zh">提交了我的硕士毕业论文以供审查，其中详细介绍了一个基于 PRM 和 Beam Search 的推理引导框架。</p>
    </div>

  </div>
</div>

<script>
function setLang(lang) {
  document.getElementById('bio-en').className = 'bio-block' + (lang === 'en' ? ' visible' : '');
  document.getElementById('bio-zh').className = 'bio-block' + (lang === 'zh' ? ' visible' : '');
  document.getElementById('btn-en').className = 'lang-btn' + (lang === 'en' ? ' active' : '');
  document.getElementById('btn-zh').className = 'lang-btn' + (lang === 'zh' ? ' active' : '');
  document.body.className = (document.body.className || '').replace(/\blang-\w+/g, '').trim() + ' lang-' + lang;
}
setLang('en');
</script>
