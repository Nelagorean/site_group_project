---
title: "Математическое моделирование теплопроводности и горения: Этап 2 — Алгоритмы"
authors:
- admin
- Irina
- Milena
- Evgenia
- Maria
date: "2025-04-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Численные алгоритмы решения задачи теплопроводности и химической реакции"
publication_short: ""

abstract: |
  Второй этап проекта посвящён разработке численных алгоритмов для системы уравнений, описывающей теплопроводность с экзотермической химической реакцией. Построены явная и неявная разностные схемы. Первая реализуется напрямую, но требует ограничений по шагу времени. Вторая (*неявная*) является безусловно устойчивой, но требует решения системы линейных уравнений. Алгоритмы подготовлены к реализации в Julia и OpenModelica.

# Summary. An optional shortened abstract.
summary: "Разработка явной и неявной разностных схем для численного решения модели теплопроводности и химической реакции."

tags:
tags:
- Математическое моделирование
- Алгоритмы
- Разностные схемы
- Теплопроводность
- Горение
featured: false

links:
- name: GitHub репозиторий
  url: https://github.com/Nelagorean/site_group_project
url_video: 'https://plvideo.ru/watch?v=q9HqKQO53cAr'
url_pdf: ""
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
# caption: 'Пример зимической реаеции горения. Бенгальский огонь'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- project_heat_conduction

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: presentation2
---

{{% callout note %}}
Следующий этап проекта будет посвящён описанию программной реализации проекта.
{{% /callout %}}


