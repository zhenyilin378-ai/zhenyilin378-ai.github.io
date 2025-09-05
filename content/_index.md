---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # ===== Bio / Hero =====
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: "Download CV"
        url: "/uploads/Youchen_CV.pdf?v=3"
    design:
      css_class: dark
      avatar:
        size: medium
        shape: circle
      background:
        color: "#f5f5f5"   # 淺灰背景
        image:
          filename: ""     # 移除原本 stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
