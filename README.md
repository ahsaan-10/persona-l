# Data Storytelling Dashboard

**A single-page site that presents business data the way an analyst would explain it: dashboard layouts, key numbers, and short narrative case studies.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/deployed%20on-Vercel-000000?logo=vercel&logoColor=white)

**[View the live site →](https://ahsaanlab.vercel.app)**

---

## Overview

The site explores how to communicate data clearly to a non-technical audience. Instead of a wall of charts, each section pairs a dashboard-style visual with the story behind it: the question, what the numbers show, and the decision it supports.

## Features

- **Dashboard layouts:** KPI cards, chart panels, and summary tables designed to be read at a glance.
- **Narrative case studies:** problem → analysis → outcome sections that explain the "so what" of the data.
- **Animated metrics:** counters and scroll-triggered reveals that draw attention to key numbers.
- **Process timeline:** a step-by-step view of an analysis workflow, from raw data to recommendation.
- **Zero build step:** plain HTML, CSS, and vanilla JavaScript in one file.

> The charts and figures are illustrative examples designed to demonstrate presentation, not results from a real dataset.

## Run locally

```bash
git clone https://github.com/ahsaan-10/data-storytelling-dashboard.git
cd data-storytelling-dashboard
python -m http.server 8080
```

Then open http://localhost:8080.

## Project structure

```text
data-storytelling-dashboard/
└── index.html   # Content, styles, and interactions
```

## License

Released under the [MIT License](LICENSE).
