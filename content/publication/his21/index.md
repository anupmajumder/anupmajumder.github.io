---
title: 'Feature Ranking Based Carrot Disease Recognition Using MIFS Method'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Md. Sabab Zulfiker
  - Aditya Rajbongshi
  - Md. Jueal Mia  
  - Anup Majumder 
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-03-04T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-030-96305-7_6'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In proceedings of the 21st International Conference on Hybrid Intelligent Systems (HIS 2021), Springer, 2021
publication_short: In proceedings of the 21st International Conference on Hybrid Intelligent Systems (HIS 2021), Springer, 2021

abstract: Due to the rapid advancement of computer vision-based technology, automated disease recognition using vision-based technology has become more popular in recent times. In this paper, we have proposed an optimal solution to identify diseased carrots. Firstly, various image-preprocessing techniques have been performed on the collected images. Then, we have used the k-means clustering technique for segmenting the disease-affected region, and then 10 different Statistical and Gray-Level Co-occurrence Matrix (GLCM) features have been extracted from the segmented images. The Mutual information-based feature selection technique is applied. To handle the class imbalance problem, we have performed the synthetic minority oversampling technique (SMOTE) on the training dataset after selecting the top N (5 <  = N <  = 10) features. After that we have trained 5 different machine learning (ML) classifiers. Then, we have used four performance metrics and plotted Receiver Operating Characteristic (ROC) curve to evaluate the classifiers’ performance using the test dataset. From the result analysis, the Random Forest classifier with the top nine features has outperformed all the applied classifiers with the highest accuracy of 94.17%. Lastly, we have found that the features selection technique has helped to minimize the computational cost.

# Summary. An optional shortened abstract.
summary:  This paper proposed an optimal solution to identify diseased carrots. The Random Forest classifier with the top nine features has outperformed all the applied classifiers with the highest accuracy of 94.17%. Lastly, we have found that the features selection technique has helped to minimize the computational cost.

tags:
  - Machine Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-96305-7_6'
# url_code: 'https://figshare.com/articles/dataset/An_Empirical_Study_of_Deep_Learning_Models_for_Vulnerability_Detection/20791240'
# url_dataset: 'https://figshare.com/articles/dataset/An_Empirical_Study_of_Deep_Learning_Models_for_Vulnerability_Detection/20791240'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://link.springer.com/chapter/10.1007/978-3-031-27409-1_15'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Steps to identify diseased carrots'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
 - carrot_disease

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
