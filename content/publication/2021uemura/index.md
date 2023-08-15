---
title: "Automated segmentation of an intensity calibration phantom in clinical CT images using a convolutional neural network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Keisuke Uemura
- Yoshito Otake
- Masaki Takao
- admin
- Akihiro Kawasaki
- Nobuhiko Sugano
- Yoshinobu Sato

# Author notes (optional)
# author_notes: []

date: "2021/3/17"
doi: "10.1007/s11548-021-02345-w"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-17"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: International Journal of Computer Assisted Radiology and Surgery

publication_short: Int J CARS

abstract: Purpose In quantitative computed tomography (CT), manual selection of the intensity calibration phantom’s region of interest is necessary for calculating density (mg/cm3) from the radiodensity values (Hounsfield units  HU). However, as this manual process requires effort and time, the purposes of this study were to develop a system that applies a convolutional neural network (CNN) to automatically segment intensity calibration phantom regions in CT images and to test the system in a large cohort to evaluate its robustness. Methods This cross-sectional, retrospective study included 1040 cases (520 each from two institutions) in which an intensity calibration phantom (B-MAS200, Kyoto Kagaku, Kyoto, Japan) was used. A training dataset was created by manually segmenting the phantom regions for 40 cases (20 cases for each institution). The CNN model’s segmentation accuracy was assessed with the Dice coefficient, and the average symmetric surface distance was assessed through fourfold cross-validation. Further, absolute difference of HU was compared between manually and automatically segmented regions. The system was tested on the remaining 1000 cases. For each institution, linear regression was applied to calculate the correlation coefficients between HU and phantom density. Results The source code and the model used for phantom segmentation can be accessed at https://github.com/keisuke-uemura/CT-Intensity-Calibration-Phantom-Segmentation. The median Dice coefficient was 0.977, and the median average symmetric surface distance was 0.116 mm. The median absolute difference of the segmented regions between manual and automated segmentation was 0.114 HU. For the test cases, the median correlation coefficients were 0.9998 and 0.999 for the two institutions, with a minimum value of 0.9863. Conclusion The proposed CNN model successfully segmented the calibration phantom regions in CT images with excellent accuracy.

# Summary. An optional shortened abstract.
summary: []
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overall scheme for modelling the shape variations associated with liver fibrosis stage and predicting it fromMR images by using PLSR-based shape features (scores)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
