---
layout: page
title: DALI @ MICCAI 2021
subtitle: The MICCAI workshop on Data Augmentation, Labeling, and Imperfections
description: The homepage of the MICCAI workshop on Data Augmentation, Labeling, and Imperfections
hero_image: /hero.png
image: /logo.png
show_sidebar: true
---

# DALI: The MICCAI Workshop on Data Augmentation, Labeling, and Imperfections

With the proliferation of data-intensive methods for supervised learning, the demand for large quantities of annotated data has never been higher. Unfortunately, large-scale collections of medical images are exceptionally challenging to collect and require rare and expensive expertise to annotate. Moreover, medical data are often noisy and imperfect due to missing entries and sensing heterogeneity. A forum for discussing contemporary and practical approaches for dealing with these challenges is urgently needed.

The MICCAI Workshop on **D**ata **A**ugmentation, **L**abeling, and **I**mperfections (**DALI**) aims to provide a venue for researchers to present and discuss their experiences working on these important topics.

## Important Dates

- **[Paper Submission](https://cmt3.research.microsoft.com/DALI2021) Opens**: April 30, 2021
- **Paper Submission Deadline**: ~~June 25~~ **July 2**, 2021
- **Notification to Authors**: ~~July 30~~ **August 2**, 2021
- **Camera Ready Deadline**: ~~August 6~~ **August 7**, 2021
- **Workshop Day**: Oct. 1, 2021

## Call For Papers

Training machine learning systems for image recognition, object detection and image segmentation often requires a huge amount of expert annotated data to reach a high level of accuracy. Having a large number of labeled images helps to increase the performance of machine learning models by generalizing better and thereby reducing overfitting. Most popular benchmark datasets for general image recognition tasks have a few thousand to millions of images.

Obtaining such huge amounts of labeled data is very challenging in the medical imaging domain, however, due to costly annotation by domain experts and lack of high-quality anonymized data out of privacy concerns. Furthermore, there are unique challenges to collecting annotated medical datasets. For instance, examples of rare pathological conditions, although hard to obtain, are extremely important for accurate representation of the data distribution; there are often variations among experts who provide labels, especially for conditions that human experts are most confused about and need help the most.

The goal of this workshop is to bring together and create a discussion forum for researchers in the MICCAI community who are interested in the rigorous study of medical data as it relates to machine learning systems, who are developing and promoting novel techniques in data augmentation, labeing, and learning from small or imperfect data, who would like to contribute benchmark datasets, open challenges and tasks that enable fair comparisons among existing and new techniques, and who are applying such techniques to improving the performance of medical image computing systems. The workshop will have invited speakers who will speak about popular and emerging approaches for data augmentation or imputation, and learning from small or noisy medical data. The workshop welcomes submissions that present new ideas, new results, new datasets, as well as discussion and evaluation of existing approaches. The topics of interest include but are not limited to:

- Training and evaluation with noisy or uncertain labels
- Data annotation tools and practices
- Synthetic data for medical image analysis
- One-shot/few-shot learning
- Active learning
- Semi-, weakly-, self-supervised learning
- Deep learning for small, noisy and imperfect data
- Domain adaptation/generalization
- Erroneous label detection
- Data augmentation
- Data imputation
- Principles and/or case studies of annotated datasets and benchmarks
- Anonymization, PHI detection

Submissions to our workshop will be managed using the same platform as the main MICCAI conference, using the Microsoft CMT. Tentative conference submission website is at: [https://cmt3.research.microsoft.com/DALI2021](https://cmt3.research.microsoft.com/DALI2021)

Papers submitted to this workshop are limited to 8 pages including references. Papers should be formatted in Lecture Notes in Computer Science style, and should be anonymized in order to allow for double blind review. Authors should consult Springer’s authors’ guidelines and use their proceedings templates, either for LaTeX or for Word, for the preparation of their papers. Supplemental material submission is optional, which may include:

- Videos of results that cannot be included in the main paper
- Anonymized related submissions to other conferences and journals
- Appendices or technical reports containing extended proofs and mathematical derivations that are not essential for the understanding of the paper

Contents of the supplemental material should be referred to appropriately in the paper and that reviewers are not obliged to look at it.

## Program

### Invited Speakers

- [Margrit Betke](https://www.bu.edu/cs/profiles/betke/), Boston University; 11:30 - 12:10 UTC, Talk Info()
- [Stephen Wong](https://www.houstonmethodist.org/faculty/stephen_wong/), Houston Methodist; 12:20 - 13:00 UTC, Talk Info()
- [Ekin Dogus Cubuk](https://scholar.google.com/citations?user=Mu_8iOEAAAAJ&hl=en), Google Brain; 14:00 - 14:40 UTC, Talk Info()
- [Jerry Prince](https://engineering.jhu.edu/ece/faculty/prince-jerry-l/), Johns Hopkins University; 15:00 - 15:40 UTC, Talk Info()
- [Adrian Dalca](http://www.mit.edu/~adalca/), Massachusetts Institute of Technology; 16:00 - 16:40 UTC, Talk Info()
- [Steve Jiang](https://profiles.utsouthwestern.edu/profile/150563/steve-jiang.html), UT Southwestern; 17:00 - 17:40 UTC, Talk Info()

### Full Oral Presentations

- **An efficient data strategy for the detection of brain aneurysms from MRA with deep learning**, 9:20 - 9:40 UTC, *Youssef Assis (University of Lorraine); Liang Liao (CHRU Nancy); Fabien Pierre (University of Lorraine); René Anxionnat (CHRU Nancy); Erwan Kerrien (Inria)*
- **DeepMCAT: Large-Scale Deep Clustering for Medical Image Categorization**, 9:40 - 10:00 UTC, *Turkay Kart (Imperial College London); Wenjia Bai (Imperial College London); Ben Glocker (Imperial College London); Daniel Rueckert (Imperial College London)*
- **Zero-Shot Domain Adaptation in CT Segmentation by Filtered Back Projection Augmentation**, 11:10 - 11:30 UTC, *Talgat Saparov (MIPT); Anvar Kurmukov (Artificial Intelligence Research Institute, Russia, Moscow); Boris Shirokikh (Skoltech); Mikhail Belyaev (Skoltech)*
- **Medical image segmentation with imperfect 3D bounding boxes**, 14:40 - 15:00 UTC, *Ekaterina Redekop (Philips); Alexey Chernyavskiy (Philips Innovation Lab RUS)*
- **Scalable Semi-supervised Landmark Localization for X-ray Images using Few-shot Deep Adaptive Graph**, 15:40 - 16:00 UTC, *Xiao-Yun Zhou (PAII INC.); Bolin Lai (Ping An Technology (Shanghai) Co.,Ltd.); Weijian Li (University of Rochester); Yirui Wang (PAII Inc.); Kang Zheng (PAII Inc.); Fakai Wang (University of Maryland, College Park); Chihung Lin (CGMH); Le Lu (PAII Inc.); Lingyun Huang (PingAn Technology); Mei Han (PAII Labs); Guotong Xie (Ping An Technology (Shenzhen) Co. Ltd.); Jing Xiao (Ping An Insurance (Group) Company of China); Kuo Chang-Fu (Chang Gung Memorial Hospital); Adam P Harrison (PAII Inc.); Shun Miao (PAII)*
- **One-shot Learning for Landmarks Detection**, 16:40 - 17:00 UTC, *Zihao Wang (Inria); Clair Vandersteen (Université Côte d’Azur, Centre Hospitalier Universitaire de Nice); RAFFAELLI CHARLES (Centre Hospitalier Universitaire de Nice); Nicolas Guevara (Université Côte d’Azur, Centre Hospitalier Universitaire de Nice); François Patou (Oticon Medical, Research & Technology group); Herve Delingette (Inria)*


### Short Oral Presentations

- **FS-Net: a new paradigm of data expansion for medical image segmentation**, 10:00 - 10:10 UTC, *Xutao Guo (Harbin Institute of Technology, Shenzhen); Yanwu Yang (HIT at shenzhen); Ting Ma (Harbin Institute of Technology,Shenzhen)*
- **Data Augmentation with Variational Autoencoders and Manifold Sampling**, 10:10 - 10:20 UTC, *Clément Chadebec (Université de Paris); Stéphanie Allassonnière (Université de Paris)*
- **MetaHistoSeg: A Python Framework for Meta Learning in Histopathology Image Segmentation**, 10:20 - 10:30 UTC, *Zheng Yuan (Salesforce Research); Andre Esteva (Salesforce Research); Ran Xu (Salesforce Research)*
- **Label noise in segmentation networks : mitigation must deal with bias**, 10:30 - 10:40 UTC, *Eugene Vorontsov (Polytechnique Montreal); Samuel Kadoury (Polytechnique Montréal)*
- **How few annotations are needed for segmentation using a multi-planar U-Net?**, 10:40 - 10:50 UTC, *William M Laprade (University of Copenhagen); Mathias Perslev (University of Copenhagen); Jon Sporring (University of Copenhagen)*
- **Evaluation of Active Learning Techniques on Medical Image Classification with Unbalanced Data Distributions**, 10:50 - 11:00 UTC, *Quok Zong Chong (Imperial College London; Metalynx); William J Knottenbelt (Imperial College London); Kanwal K Bhatia (Metalynx)*
- **Semi-supervised Surgical Tool Detection Based on Highly Confident Pseudo Labeling and Strong Augmentation Driven Consistency**, 11:00 - 11:10 UTC, *Wenjing Jiang (Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences); Tong Xia (Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences); Zhiqiong Wang (Northeastern University); Fucang Jia (Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences)*
- **Compound Figure Separation of Biomedical Images with Side Loss**, 12:10 - 12:20 UTC, *Tianyuan Yao (Vanderbilt University); Chang Qu (Vanderbilt University); Quan Liu (Vanderbilt University); Ruining Deng (Vanderbilt University); Yuanhan Tian (Vanderbilt University); Jiachen Xu (Vanderbilt University); Aadarsh Jha (Vanderbilt University); Shunxing Bao (Vanderbilt University); Mengyang Zhao (Dartmouth College); Agnes fogo (VUMC); Bennett A Landman (Vanderbilt University); Catie Chang (Vanderbilt University); Haichun Yang (Vanderbilt University Medical Center); Yuankai Huo (Vanderbilt University)*
- **Automated Iterative Label Transfer Improves Segmentation of Noisy Cells in Adaptive Optics Retinal Images**, 17:40 - 17:50 UTC, *Jianfei Liu (National Eye Institute); Nancy aguilera (National Institutes of Health); Tao Liu (National Institutes of Health); Johnny Tam (National Institutes of Health)*

## People

### Co-Chairs

- Nicholas Heller, University of Minnesota, USA
- Sharon Xiaolei Huang, The Pennsylvania State University, USA
- Hien V. Nguyen, University of Houston, USA

### Editorial Chairs

- Raphael Sznitman, University of Bern, Switzerland
- Yuan Xue, Johns Hopkins University, USA

### Award Committee

- Dimitris N. Metaxas, Rutgers University, New Brunswick, NJ, USA
- Diana Mateus, Centrale Nantes, France

### Advisory Board

- Stephen Wong, Houston Methodist Hospital, Houston, TX, USA
- Jens Rittscher, University of Oxford, Oxford, UK
- Margrit Betke, Boston University, Boston, MA, USA
- Emanuele Trucco, University of Dundee, Scotland

### Program Committee

- Alison C Leslie, University of Minnesota
- Amelia Jiménez-Sánchez, Pompeu Fabra University
- Anjali Balagopal, UT Southwestern
- Brett Norling, University of Minnesota
- Chandra Kambhamettu, University of Delaware
- Chao Chen, Stony Brook University
- Christoph M. Friedrich, University of Applied Sciences and Arts Dortmund
- Devante F Delbrune, University of Minnesota
- Edward Kim Drexel, University
- Emanuele Trucco, University of Dundee
- Filipe Condessa, Instituto Superior Tecnico, Portugal / Carnegie Mellon University
- Haomiao Ni, Penn State University
- Hui Qu, Adobe Inc.
- Jiarong Ye, Penn State University
- Jue Jiang, Memorial Sloan Kettering Cancer Center
- Kelvin Wong, Houston Methodist Hospital Research Institute
- Li Xiao, Chinese Academy of Science
- Michael Goetz, German Cancer Research Center DFKZ
- Nicha Dvornek, Yale University
- Niklas E.P. Damberg, University of Minnesota
- Pengyu Yuan, University of Houston
- Pietro Antonio, Cicalese University of Houston
- Rafat Solaiman, University of Minnesota Medical School
- Samira Zare, University of Houston
- Ti Bai, UT Southwestern Medical Center
- Weidong Cai, University of Sydney
- Wen Hui Lei, University of Electronic Science and Technology of China
- Xiao Liang, UT Southwestern
- Xiaoxiao Li, Princeton University
- Xiaoyang Li, Adobe

## Sponsor

Prizes for **best paper** and **people's choice** are sponsored by [Histosonics](https://histosonics.com/).

![Histosonics graphic](https://histosonics.com/wp-content/uploads/2020/03/histosonics_ogimage.jpg)

## Previous Editions

DALI is the result of a merger between three proposals submitted to the 2021 MICCAI Conference:

- [MIL3D](https://www.hvnguyen.com/lesslabelsimperfectdataml2020) -- **Medical Image Learning with Less Labels** -- *(proposed 2nd edition)*
- [LABELS](https://www.miccailabels.org/) -- **Large-scale Annotation of Biomedical Data and Expert Label Synthesis** -- *(proposed 6th edition)*
- DAIMIA -- **Data Augmentation and Imputation in Medical Image Analysis** -- *(proposed 1st edition)*
