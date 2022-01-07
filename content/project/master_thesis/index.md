---
title: Master Thesis
summary: "Circular Codes, Reading Frames and Error Correction in Translation."
tags:
- master-thesis
- circular-codes
- dna-translation
- computational-genomics
- dna
date: "2021-10-10"

# Optional external URL for project (replaces project detail page).
external_link: ""

links:
- icon: arrow-alt-circle-down
  icon_pack: fas
  name: Download the pdf file
  url: "https://paolodalena.netlify.app/uploads/mscth.pdf"
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This work is the result of a collaboration with the [Institute of Mathematical Biology](https://www.cammbio.hs-mannheim.de/institute.html) (Department of Computer Science, [Mannheim University of Applied Sciences](https://www.english.hs-mannheim.de/the-university.html)) and [Professor Simone Giannerini](https://www.unibo.it/sitoweb/simone.giannerini/en) from the University of Bologna.

This research has been going on for several years, is constantly evolving and covers many different fields. So, the results in my thesis are just one step.
If you are curious, you can read the [article](https://www.nature.com/articles/s41598-021-87534-y) presenting the results immediately preceding my work that guided us in our analysis. For further information, please refer to the bibliography of the dissertation.


Click {{% staticref "uploads/mscth.pdf" "newtab" %}}here{{% /staticref %}} to download the pdf file. If you're interested in further material related to this topic, don't hesitate to contact me!




## ABSTRACT:

The presence of error correction mechanisms involved in translation has been ascertained but
their elucidation requires a mathematical framework which is still missing. Comma-free codes are
synchronizable error correcting codes that were introduced by Sir Francis Crick in 1957 to tackle
the difficult problem of frame retrieval during translation. Despite its appeal the proposal was
discarded but in 1996, thanks to a large scale exploratory analysis of coding sequences, a weaker
form of comma-free codes, called circular codes, were hypothesized to be involved in the translation
machinery. Recent works established a connection between circular codes and group theory and
identified a set of 216 circular codes possessing desirable mathematical properties. These, in turn,
can be partitioned into 27 equivalence classes according to the 8 nucleotide transformations linked
to the dihedral group of symmetry. The coverage of a circular code is a measure of its compliance
with a specific sequence or organism. It has universal properties, is strongly correlated with
translation accuracy and behaves differently in the initial and final parts of the sequences. This
agrees with the molecular biology of the translation process and raises interesting questions. This
thesis moves from these results and studies both the codon usage and the code coverage in 24
different organisms. The analyses are carried out in the R environment and part of the work has
been devoted to collaborating at the development of the R package mathDNA, which implements
some of the functions used in the analysis. The results confirm the different behavior in terms of
code coverage and codon usage at the beginning and at the end of the sequences and proves that
there is a universal and complex relationship between the coverage of two sets of codes linked by
Keto-Amino transformation. The existence of a correlation between the length of a sequence and
the code coverage is also found.
