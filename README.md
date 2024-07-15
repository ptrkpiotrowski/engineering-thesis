*[ENGLISH LANGUAGE](README.en.md)*

[PDF](./out/EE-dyplom.pdf)

## Analiza porównawcza neuronowych wizyjnych algorytmów percepcji głębi
W niniejszej pracy inżynierskiej wykonano analizę porównawczą wiodących algorytmów percepcji głębi opartych o architekturę sieci neuronowych w ujednoliconym środowisku testowym. W ramach badań przetestowano sześć algorytmów: AdelaiDepth, DepthAnythingV2, GCNDepth, MetaPrompt-SD, Metric3D oraz SQLdepth. Badania przeprowadzono na zestawach danych obejmujących różnorodne scenariusze, co pozwoliło na uzyskanie wszechstronnych wyników. W ramach pracy opracowany został również autorski zbiór danych, na których zweryfikowano efektywność algorytmów. Wykonana analiza miała na celu ocenę ich wydajności w różnych kontekstach aplikacyjnych, z uwzględnieniem dokładności, wydajności czasowej oraz wymagań systemowych. Na podstawie wyników przygotowano zestawienie, które pozwoliło na ich usystematyzowanie i podsumowanie. Praca kończy się szczegółową interpretacją wyników uzyskanych podczas analizy oraz rekomendacjami przypadków użycia dla każdego algorytmu, uwzględniającymi ich mocne strony oraz specyficzne wymagania aplikacyjne. Wnioski końcowe wykazują brak uniwersalnego algorytmu do wszystkich zastosowań, wskazując na konieczność dostosowania wyboru algorytmu do specyficznych potrzeb projektu. Rezultaty przedstawione w niniejszej pracy mogą stanowić cenną wskazówkę dla inżynierów i naukowców zajmujących się rozwojem i implementacją systemów percepcji głębi, pomagając w optymalnym doborze narzędzi do specyficznych zastosowań.

## Instrukcja kompilacji (debian based os)
```
sudo apt install latexmk texlive-xetex texlive-lang-polish biber
latexmk -xelatex -outdir=out EE-dyplom.tex
```
