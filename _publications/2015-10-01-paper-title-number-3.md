---
title: "Semi-supervised learning with Noisy Students improves domain generalization in optic disc and cup segmentation in uncropped fundus images"
collection: publications
category: conferences
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about Domain generalization problem for OD/OC segmentation on fundus images.'
date: 2024-03-01
venue: 'Medical Imaging with Deep Learning'
slidesurl: '..'
paperurl: 'https://openreview.net/pdf?id=Wcb6Wynz3e'
citation: 'Moris, E., Larrabide, I., & Orlando, J. I. (2024). Semi-supervised learning with Noisy Students improves domain generalization in optic disc and cup segmentation in uncropped fundus images. In Medical Imaging with Deep Learning.'
---

Automated optic disc (OD) and cup (OC) segmentation in fundus images has been widely explored for computer-aided diagnosis of glaucoma. However, existing models usually suffer from drops in performance when applied on images significantly different than those used for training. Several domain generalization strategies have been introduced to mitigate this issue, although they are trained and evaluated using images manually cropped around the optic nerve head. This operation eliminates most sources of domain variation, therefore overestimating their actual ability to cope with new, unseen patterns. In this paper, we analyze the most recent and accurate methods for domain generalization in OD/OC segmentation by applying them on uncropped fundus pictures, observing notorious degradations in their performance when trained and evaluated under this setting. To overcome their drawbacks, we also introduce a simple semi-supervised learning approach for domain generalization based on the Noisy Student framework. Using a Teacher model trained on a combination of domains, we pseudo-labeled a dataset of 18.000 originally unlabeled images that are then used for training a Student model. This semi-supervised setting allowed the Student network to capture additional sources of variability while retaining the original cues and patterns used by the Teacher through the weak annotations.