---
show: true
width: 4
date: 2033-01-12 00:01:00 +0800
height: 295px
images:
- src: /photo/Munster.jpg
  title: Münster
  desc: 
- src: /photo/MontBlanc.jpg
  title: TMB
  desc: Life is beautiful.
- src: /photo/Paris.jpg
  title: La Seine
  desc: 
- src: /photo/LuShan.jpg
  title: 庐山
  desc:
- src: /photo/MathMunster.jpg
  title: Math Münster
  desc: Ugly but wonderful
- src: /photo/Strassbourg.jpg
  title: Strassbourg
  desc: 没有爱就看不见
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
