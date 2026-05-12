# MIGA: Enhancing Train-Free Infinite-Frame Generation for Consistent Long Videos

Project page for the paper **"Enhancing Train-Free Infinite-Frame Generation for Consistent Long Videos"**, accepted by **ICML 2026**.

This page showcases generated long video samples, the abstract, and an overview of the two core mechanisms (TTA & DCE) of MIGA.

## File Structure

| File | Description |
|------|-------------|
| `index.html` | Project page with title, ICML 2026 badge, author list, video demos, abstract (with Figure A1) and method overview (with Figure 1 / Figure A2). |
| `prompts.txt` | Text prompts used to generate the three demo videos. |
| `1_iron_man.mp4` | Generated video: Iron Man soaring through a cloud-filled sky. |
| `2_sea_turtle.mp4` | Generated video: A sea turtle gliding through a colorful coral reef. |
| `3_corge_dog.mp4` | Generated video: A fluffy Corgi dog trotting across a green lawn. |
| `1_corge_dog.mp4`, `3_iron_man.mp4` | Additional generation samples. |
| `figure_a1.jpg` | Figure A1: 1k+ frame qualitative results overview shown under the abstract. |
| `method_tta.png` | Figure 1: Two-Stage Training-Inference Alignment (TTA) framework. |
| `method_dce.png` | Figure A2: Dual Consistency Enhancement (DCE) framework. |
| `.gitignore` | Git ignore rules. |

## Authors

Xiaokun Feng¹·²·³, Jiashu Zhu³, Meiqi Wu³, Chubin Chen³, Fangyuan Mao³, Haiyang Guo³, Jiahong Wu³, Xiangxiang Chu³, Kaiqi Huang¹·² (✉)

1. School of Artificial Intelligence, University of Chinese Academy of Sciences, Beijing, China
2. The Key Laboratory of Cognition and Decision Intelligence for Complex Systems, Institute of Automation, Chinese Academy of Sciences, Beijing, China
3. AMAP, Alibaba Group, Beijing, China

Corresponding author: Kaiqi Huang &lt;kaiqi.huang@nlpr.ia.ac.cn&gt;

## Local Preview

Just open `index.html` directly in a browser, or serve the directory:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy to GitHub Pages

This folder is fully self-contained — uploading it to a GitHub repository (e.g. `miga-project-page`) and enabling GitHub Pages on the default branch will publish the site at `https://<user>.github.io/<repo>/`.
