*[JĘZYK POLSKI](README.md)*

[PDF](./out/EE-dyplom.pdf)

## Comparative analysis of neural vision algorithms for depth perception
In this engineering thesis, a comparative analysis of leading depth perception algorithms based on neural network architecture was conducted in a unified testing environment. Six algorithms were tested as part of the research: AdelaiDepth, DepthAnythingV2, GCNDepth, MetaPrompt-SD, Metric3D, and SQLdepth. The research was carried out on datasets encompassing various scenarios, allowing for comprehensive results. Additionally, a proprietary dataset was developed and used to verify the effectiveness of the algorithms. The analysis aimed to evaluate their performance in different application contexts, considering accuracy, time efficiency, and system requirements. Based on the results, a summary was prepared to systematize and consolidate the findings. The thesis concludes with a detailed interpretation of the results obtained during the analysis and recommendations for use cases for each algorithm, taking into account their strengths and specific application requirements. The final conclusions indicate the absence of a universal algorithm for all applications, highlighting the necessity to tailor the algorithm choice to the specific needs of a project. The results presented in this thesis can provide valuable guidance for engineers and scientists involved in the development and implementation of depth perception systems, aiding in the optimal selection of tools for specific applications.

## Compile instruction (debian based os)
```
sudo apt install latexmk texlive-xetex texlive-lang-polish biber
latexmk -xelatex -outdir=out EE-dyplom.tex
```
