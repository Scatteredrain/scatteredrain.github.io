---
permalink: /phd/
title: "PhD Plans / Fall 2028"
excerpt: "Zhenyu Yi is seeking fully funded PhD positions starting Fall 2028: medical image computing, endoscopic vision-language pre-training, structured weak supervision from clinical reports, and efficient multimodal LLMs for 3D imaging and video."
author_profile: true
---

<span class='anchor' id='phd-plan'></span>

<div class="phd-card">
  <div class="phd-head">
    <h1 class="phd-title"><span class="phd-dot"></span> Prospective PhD Student &mdash; Fall 2028</h1>
    <span class="phd-tag">Application cycle 2027 / 2028</span>
  </div>
  <p class="phd-lead">
    I am a second-year M.S. student at <strong>Shanghai Jiao Tong University</strong> (advised by
    <a href="https://scholar.google.com/citations?user=YEYK0MoAAAAJ&hl=zh-CN&oi=ao">Lichi Zhang</a> and
    <a href="https://scholar.google.com/citations?hl=zh-CN&user=m6ZNDewAAAAJ">Qian Wang</a>, graduating 2028),
    and I am looking for <strong>fully funded PhD positions starting in Fall 2028</strong>.
    My work sits at the intersection of <strong>medical image computing</strong> and
    <strong>efficient multimodal foundation models</strong>, always anchored to a real clinical question:
    how to learn reliable diagnostic models when annotations are scarce, noisy, or only available at the
    patient / report level, and how to keep 3D and video models cheap enough to run in a clinic.
  </p>
  <div class="phd-chips">
    <span class="phd-chip">Endoscopic image &amp; video analysis</span>
    <span class="phd-chip">Vision-language pre-training for endoscopy</span>
    <span class="phd-chip">3D CT vision-language MIL</span>
    <span class="phd-chip">Weak / noisy / semi-supervision</span>
    <span class="phd-chip">Efficient MLLM &amp; visual-token sparsity</span>
  </div>
</div>

<h2 class="phd-block-title">🧭 What I would like to work on in a PhD</h2>
<p class="phd-sub">Three directions, in decreasing order of how much I have already built toward them.</p>
<ol class="phd-list">
  <li><strong>Clinical vision-language pre-training beyond natural images.</strong> Reports, anatomy taxonomies and procedure videos are paired data that nobody pays to label. <em>EndoVLM</em> (MICCAI 2026, co-first) turns 348K endoscopic examinations into anatomy-conditioned visual memory via sparse pooling over redundant frames; I want to push this to longitudinal, multi-center and multi-modal settings.</li>
  <li><strong>Learning from the supervision that actually exists.</strong> Clinicians label findings, not pixels. <em>PhenoMIL</em> (MedIA 2026, co-first) learns from phenotype-level supervision, and <em>SALI</em> (MICCAI 2024 Oral, co-first) from temporal cues in unlabeled video. The interesting next step is weak supervision that is <em>structured</em> &mdash; report-derived, guideline-derived, or outcome-derived.</li>
  <li><strong>Efficient multimodal LLMs for 3D and video.</strong> A CT volume is a thousand slices and a colonoscopy is an hour. <em>CARVE</em> (arXiv 2026, first author) reallocates visual evidence across slices instead of compressing every slice equally; <em>Brain-Adapter</em> (MICCAI 2026, first author) routes a dual-stream VLM inside a MIL framework. Token budgeting under a fixed clinical latency is the problem I would most like to keep working on.</li>
</ol>

<h2 class="phd-block-title">🗓 Timeline I am planning around</h2>
<table class="phd-table">
  <thead>
    <tr><th>When</th><th>What happens</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Now &rarr; mid 2027</strong></td>
      <td>Finish the 3D/efficiency papers, keep one strong first-author work in flight, and build relationships through visiting stays or co-supervision. Emails to PIs are most effective <em>before</em> the cycle, not in December.</td>
    </tr>
    <tr>
      <td><strong>Summer 2027</strong></td>
      <td>Shortlist programs; ask referees; draft SOP; refresh CV and one-page research statement; take/refresh English test scores if a program needs them.</td>
    </tr>
    <tr>
      <td><strong>Sept &ndash; Dec 2027</strong></td>
      <td>US / Canada PhD applications (most CS &amp; BME deadlines are <code>Dec 1 &ndash; Dec 15, 2027</code> for Fall 2028 entry); UK CDT/studentship rounds and Singapore rounds also open here.</td>
    </tr>
    <tr>
      <td><strong>Dec 2027 &ndash; Jan 2028</strong></td>
      <td>European structured PhD schools (ETH, EPFL, TU Delft) and most funded studentships close; German/Dutch vacancy-based posts are advertised continuously and usually appear from early 2028.</td>
    </tr>
    <tr>
      <td><strong>Jan &ndash; Apr 2028</strong></td>
      <td>Interviews, offers, visits / open days, funding decisions; visa paperwork for admitted students.</td>
    </tr>
    <tr>
      <td><strong>Autumn 2028</strong></td>
      <td>Start.</td>
    </tr>
  </tbody>
</table>

<h2 class="phd-block-title">🤝 Groups I already have published with</h2>
<p class="phd-sub">These are the highest-odds routes, because the collaboration and the code already exist. For a 2028 start, the plan is a visiting / co-supervised stint during 2027 rather than a cold December email.</p>
<div class="phd-grid">
  <a class="phd-item" href="https://scholar.google.com/citations?user=LwQcmgYAAAAJ&hl=en" target="_blank" rel="noopener">
    <div class="phd-item-name">Zhiwei Wang &amp; Qiang Li</div>
    <div class="phd-item-org">HUST &middot; endoscopy + VLM</div>
    <div class="phd-item-note">SALI (MICCAI 2024 Oral, co-first), MonoBox (AAAI 2025), SAMIX (CVPR 2026). Colonoscopy video understanding and examination-assistance algorithms.</div>
  </a>
  <a class="phd-item" href="https://scholar.google.com/citations?user=_eqVp1AAAAAJ&hl=en" target="_blank" rel="noopener">
    <div class="phd-item-name">Yingda Xia</div>
    <div class="phd-item-org">DAMO Academy, Alibaba &middot; medical foundation models</div>
    <div class="phd-item-note">Senior author on EndoVLM and PhenoMIL. Confirm current affiliation; a joint / industrial-PhD route through Alibaba research is the realistic form.</div>
  </a>
  <a class="phd-item" href="https://damo.alibaba.com/research-areas?language=en" target="_blank" rel="noopener">
    <div class="phd-item-name">Zhongwei Qiu, Jianwei Xu, Sijing Li, Wenqiao Zhang</div>
    <div class="phd-item-org">DAMO Academy &amp; Zhejiang University</div>
    <div class="phd-item-note">The report-aligned, anatomy-conditioned pre-training line of EndoVLM and the evidence-driven multimodal RL of E-MRL (MICCAI 2026).</div>
  </a>
  <a class="phd-item" href="https://scholar.google.com/citations?user=YEYK0MoAAAAJ&hl=zh-CN&oi=ao" target="_blank" rel="noopener">
    <div class="phd-item-name">Lichi Zhang &amp; Qian Wang</div>
    <div class="phd-item-org">Shanghai Jiao Tong University &middot; current advisors</div>
    <div class="phd-item-note">Brain-Adapter, MUAD and the 3D CT work. Staying on is a real option, including through SJTU's medical-engineering cross-disciplinary platform, which already advertises a doctoral intake cycle.</div>
  </a>
  <a class="phd-item" href="https://yzb.sjtu.edu.cn/post/3766" target="_blank" rel="noopener">
    <div class="phd-item-name">SJTU Medical-Engineering Platform</div>
    <div class="phd-item-org">SJTU graduate admissions &middot; 申请-考核</div>
    <div class="phd-item-note">The 2027 intake notice is public and shows the shape of the cycle I would enter in 2028: platform-wide announcement, then per-school application-assessment rounds.</div>
  </a>
  <a class="phd-item" href="https://medai.lab.westlake.edu.cn/Join_us.htm" target="_blank" rel="noopener">
    <div class="phd-item-name">Westlake University &middot; Medical AI Lab</div>
    <div class="phd-item-org">Hangzhou &middot; posts PhD openings directly</div>
    <div class="phd-item-note">Recruits PhD students, postdocs and visiting students through a standing "Join us" page, so the 2028 posting can simply be watched rather than guessed at.</div>
  </a>
</div>

<!--PHD_TARGETS-->


<h2 class="phd-block-title">✉️ Contact &amp; materials</h2>
<ul class="phd-list">
  <li>Email: <a href="mailto:yezey7479@gmail.com">yezey7479@gmail.com</a> (fastest) &middot; <a href="https://scholar.google.com/citations?user=yoY2un8AAAAJ&hl=zh-CN" target="_blank" rel="noopener">Google Scholar</a> &middot; <a href="https://github.com/Scatteredrain" target="_blank" rel="noopener">GitHub</a></li>
  <li>Code for the works above is public: <a href="https://github.com/Scatteredrain/EndoVLM" target="_blank" rel="noopener">EndoVLM</a>, <a href="https://github.com/Scatteredrain/Brain-Adapter" target="_blank" rel="noopener">Brain-Adapter</a>, <a href="https://github.com/Scatteredrain/PhenoMIL" target="_blank" rel="noopener">PhenoMIL</a>, and a <a href="https://huggingface.co/Scatteredrain/EndoVLM" target="_blank" rel="noopener">Hugging Face release</a> of the endoscopy VLM.</li>
  <li>Back to <a href="/#publications">Publications</a> or <a href="/#about-me">About me</a>.</li>
</ul>

<p class="phd-footnote">
  Programme-level deadlines below are read from public pages and change year to year; I treat them as planning
  estimates and verify each one on the official admission page before relying on it. Anything I could not confirm
  is marked as such.
</p>
