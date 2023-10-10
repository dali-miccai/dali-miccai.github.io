---
layout: page
title: DALI @ MICCAI 2023, October 12, Vancouver, Canada
subtitle: The 3rd MICCAI workshop on Data Augmentation, Labeling, and Imperfections
description: The homepage of the MICCAI workshop on Data Augmentation, Labeling, and Imperfections
# carousels:
#   - images: 
#     - image: /hero.png
#     - image: /hero.png
#     - image: /hero.png
hero_image: /hero.png
image: /logo.png
show_sidebar: true
---
<!-- {% include carousel.html height="50" unit="%" duration="7" number="1" %} -->

# DALI: The 3rd MICCAI Workshop on Data Augmentation, Labeling, and Imperfections

The rapid expansion of data-intensive methods for supervised learning has led to an unprecedented demand for large quantities of annotated data. However, obtaining extensive collections of medical images is exceptionally challenging, as it necessitates rare and costly expertise for annotation. Furthermore, medical data are often noisy and imperfect due to missing entries and sensing heterogeneity. A forum for discussing contemporary and practical approaches for dealing with these challenges is urgently needed.

The MICCAI Workshop on **D**ata **A**ugmentation, **L**abeling, and **I**mperfections (**DALI**) aims to provide a venue for researchers to present and discuss their experiences related to these crucial topics, fostering a collaborative environment to tackle these challenges.

## Important Dates

- **[Paper Submission](https://cmt3.research.microsoft.com/DALI2023) Opens**: **May 9**, 2023
- **Paper Submission Deadline**:  ~~June 25~~ **July 10**, 2023
- **Notification to Authors**:  ~~July 16~~ **July 31**, 2023
- **Camera Ready Deadline**:  ~~July 30~~ **August 17**, 2023
- **Workshop Day**: **October 12**, 2023, Vancouver, Canada

## Call For Papers

Training machine learning systems in the areas of image recognition, object detection, and image segmentation often demands an immense volume of expert-annotated data to achieve high accuracy. A larger number of labeled images enhances the performance of machine learning models by promoting better generalization and reducing overfitting. This necessity is even more critical for advanced learning architectures, such as vision transformers. Consequently, the most renowned benchmark datasets for general image recognition tasks comprise tens of thousands to millions of images.

Regrettably, acquiring such vast quantities of labeled data presents significant challenges in the medical imaging domain due to the high cost of annotation by domain experts and the scarcity of high-quality anonymized data stemming from privacy concerns. Additionally, there are distinct challenges associated with collecting annotated medical datasets. For example, while difficult to procure, instances of rare pathological conditions are crucial for accurately representing the data distribution. Furthermore, variations often exist among experts who provide labels, particularly for conditions that cause confusion among human experts and require the most assistance.

The goal of this workshop is to bring together and create a discussion forum for researchers in the MICCAI community, including those:

i. interested in the rigorous study of medical data as it relates to machine learning systems,
ii. developing and promoting novel directions of research in such techniques,
iii. contributing benchmark datasets, open challenges, and tasks that enable fair comparisons among existing and new techniques, and
iv. applying such techniques to improve the performance of medical image computing systems.

The workshop will feature invited speakers presenting popular and emerging data augmentation and contemporary approaches for learning from small and noisy medical data. The workshop welcomes submissions that present new ideas, new results, new datasets, as well as discussion and evaluation of existing approaches. The topics of interest include but are not limited to:

- Training and evaluation with noisy or uncertain labels
- Data annotation tools and practices
- Synthetic data for medical image analysis
- Data-related foundation models
- Multi-modal learning
- One-shot/few-shot learning
- Active learning
- Semi-, weakly-, self-supervised learning
- Deep learning for small, noisy and imperfect data
- Domain adaptation/generalization
- Erroneous label detection
- Data curation
- Principles and/or case studies of annotated datasets and benchmarks
- Anonymization, PHI detection
- Other related topics

Submissions to our workshop will be managed using the same platform as the main MICCAI conference, using Microsoft CMT. Workshop paper submission website is at: [https://cmt3.research.microsoft.com/DALI2023](https://cmt3.research.microsoft.com/DALI2023)

The DALI workshop will employ the same reviewing standards as the main conference. DALI workshop paper submissions should be anonymized to accommodate a double-blind review. Papers should be formatted using LaTeX or MS Word templates available at [Lecture Notes in Computer Science](https://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines). Manuscripts should be up to 8 pages (text, figures, and tables) plus up to 2 pages of references. In submitting a paper, authors implicitly acknowledge that no paper of substantially similar content has been or will be submitted to another conference or workshop until the decisions have been made by our workshop. Supplemental material submission is optional, which may include:

- Videos of results that cannot be included in the main paper
- Anonymized related submissions to other conferences and journals
- Appendices or technical reports containing extended proofs and mathematical derivations that are not essential for the understanding of the paper

Contents of the supplemental material should be referred to appropriately in the paper, and reviewers are not obliged to look at it.

## Camera Ready Submission Guidelines

Please carefully address the feedback provided by the reviewers. Submit the revised materials to the [DALI CMT site](https://cmt3.research.microsoft.com/DALI2023) as a single zip archive, named in the format `dali23_id-X.zip`, with "X" being replaced by your unique paper ID.

Your submission should include:

1. **Manuscript**: Maximum of 8.5 pages, inclusive of text, figures, and tables, with an additional allowance of up to 2 pages for references. The file should be named `manuscript.pdf`.
2. **Supplementary Material** (Optional): Name the file `supplementary_material.pdf`. Note that source files for supplementary materials aren't mandatory.
3. **Changes Document**: A detailed list of modifications made post-review. Name the file `changes_after_review.pdf`.
4. **Copyright Form**: Download and fill out the [copyright form](https://dali-miccai.github.io/DALI23_SNCS_ProceedingsPaper_LTP_ST_SN_Switzerland.docx). The form should be signed by the corresponding author. Digital signatures will not be accepted. Save this document as `copyright.pdf`.
5. **Source Files**: Include a folder named `src/`, which houses the source files for your manuscript (e.g., `.tex`, `.bib`, `.docx`).

To ensure your paper is presented at MICCAI DALI 2023, a minimum of one paper author **must** register to attend on the second workshop day, October 12. As a general rule, this registration should be an "in-person" registration. The camera-ready submission portal will prompt you to provide the registration number of the author who will be presenting your work.

## Program

### Location

- **Workshop: Meeting Room 14, Vancouver Convention Center East Building Level 1**
- **Coffee Break/Poster Session: The Poster Hall at Ground Level Exhibition B-C**
- **Virtual Attendance: ConFLUX platform** 

### Keynote Speakers

- [Dimitris N. Metaxas](https://people.cs.rutgers.edu/~dnm/), Rutgers University, USA [\[Keynote Info\]](talks/Dimitris_Metaxas.html)
- [Lena Maier-Hein](https://www.dkfz.de/en/imsy/team/people/Lena_Maier-Hein.html), German Cancer Research Center, Germany [\[Keynote Info\]](talks/Lena_Maier-Hein.html)
- [Paul M. Thompson](https://keck.usc.edu/faculty-search/paul-m-thompson/), University of Southern California, USA [\[Keynote Info\]](talks/Paul_Thompson.html)

### Schedule

- <ins>1:30 - 1:40 PM PDT</ins> Opening, welcome and introduction
- <ins>1:40 - 1:55 PM PDT</ins> **Oral: Masked Conditional Diffusion Models for Image Analysis with Application to Radiographic Diagnosis of Infant Abuse**,  *Andy Tsai (Boston Children's Hospital and Harvard Medical School)*
- <ins>1:55 - 2:10 PM PDT</ins> **Oral: Self-Supervised Single-Image Deconvolution with Siamese Neural Networks**,  *Mikhail Papkov (University of Tartu)*
- <ins>2:10 - 2:50 PM PDT</ins> **Keynote: The devil is in the details: On the importance of professionalizing the whole image analysis pipeline**, *[Lena Maier-Hein](https://www.dkfz.de/en/imsy/team/people/Lena_Maier-Hein.html) (German Cancer Research Center)*; [\[Details\]](talks/Lena_Maier-Hein.html)
- <ins>2:50 - 3:30 PM PDT</ins> **Keynote: Genetic Mutation and Biological Pathway Prediction from Whole Slide Images using Deep Learning for Cancer Detection and Diagnosis**, *[Dimitris N. Metaxas](https://people.cs.rutgers.edu/~dnm/) (Rutgers University)*; [\[Details\]](talks/Dimitris_Metaxas.html)
- <ins>3:30 - 4:00 PM PDT</ins> Coffee Break/Poster Session (Ground Level Exhibition B-C)
- <ins>4:00 - 4:30 PM PDT</ins> Poster Session (Ground Level Exhibition B)
- <ins>4:30 - 5:10 PM PDT</ins> **Keynote: AI and Data Efficient Deep Learning to Accelerate Large-Scale Studies of Brain Diseases**, *[Paul M. Thompson](https://keck.usc.edu/faculty-search/paul-m-thompson/) (University of Southern California)*; [\[Details\]](talks/Paul_Thompson.html)
- <ins>5:10 - 5:25 PM PDT</ins> **Oral: Knowledge Graph Embeddings for Multi-Lingual Structured Representations of Radiology Reports**,  *Tom J van Sonsbeek (University of Amsterdam)*
- <ins>5:25 - 5:40 PM PDT</ins> **Oral: Data Augmentation Based on DiscrimDiff for Histopathology Image Classification**,  *Xianchao Guan (Harbin Institute of Technology, Shenzhen)*
- <ins>5:40 - 5:55 PM PDT</ins> **Oral: URL: Combating Label Noise for Lung Nodule Malignancy Grading**,  *Xianze Ai (Northwestern Polytechnical University)*
- <ins>5:55 - 6:10 PM PDT</ins> **Oral: A Realistic Collimated X-Ray Image Simulation Pipeline**,  *Benjamin El-Zein (Friedrich-Alexander-University Erlangen-Nuremberg)*
- <ins>6:10 - 6:30 PM PDT</ins> Closing and award announcement

### Poster List (Ground Level Exhibition B)

- <ins>01</ins> URL: Combating Label Noise for Lung Nodule Malignancy Grading
- <ins>02</ins> Zero-shot Learning of Individualized Task Contrast Prediction from Resting-state Functional Connectomes
- <ins>03</ins> Microscopy Image Segmentation via Point and Shape Regularized Data Synthesis
- <ins>04</ins> A Unified Approach to Learning with Label Noise and Unsupervised Confidence Approximation
- <ins>05</ins> Transesophageal Echocardiography Generation using Anatomical Models
- <ins>06</ins> Data Augmentation Based on DiscrimDiff for Histopathology Image Classification
- <ins>07</ins> Clinically Focussed Evaluation of Anomaly Detection and Localisation Methods Using Inpatient CT Head Data
- <ins>08</ins> LesionMix: A Lesion-Level Data Augmentation Method for Medical Image Segmentation
- <ins>09</ins> Knowledge Graph Embeddings for Multi-Lingual Structured Representations of Radiology Reports
- <ins>10</ins> Modular, Label-Efficient Dataset Generation for Instrument Detection for Robotic Scrub Nurses
- <ins>11</ins> Adaptive Semi-Supervised Segmentation of Brain Vessels with Ambiguous Labels
- <ins>12</ins> Proportion Estimation by Masked Learning from Label Proportion
- <ins>13</ins> Active Learning Strategies on a Real-World Thyroid Ultrasound Dataset
- <ins>14</ins> A Realistic Collimated X-Ray Image Simulation Pipeline
- <ins>15</ins> Masked Conditional Diffusion Models for Image Analysis with Application to Radiographic Diagnosis of Infant Abuse
- <ins>16</ins> Self-Supervised Single-Image Deconvolution with Siamese Neural Networks

## Proceedings and CMIG Special Issue

Accepted DALI workshop papers will be published with MICCAI 2023 Proceedings in the Springer Lecture Notes in Computer Science (LNCS) series. A selection of the best papers will also be invited to submit revised and extended versions of their work to a Special Issue in CMIG ([Computerized Medical Imaging and Graphics](https://www.sciencedirect.com/journal/computerized-medical-imaging-and-graphics), IF: 5.7). The pre-selection of these papers will be based on editorial chair recommendations during the review process, with final decisions made by the program chairs. Extended papers should emphasize the application of DALI-related methods to address specific medical problems. Please note that even extended papers may be subject to rejection during the peer-review process of CMIG. The submission portal is open now. More details can be found [here](https://www.sciencedirect.com/journal/computerized-medical-imaging-and-graphics/about/call-for-papers#learning-with-imperfect-data-for-medical-image-analysis).

## Awards and Sponsors

We are pleased to announce that two prestigious awards will be presented at the upcoming DALI workshop, and we are grateful to our generous sponsors for making these prizes possible. The **Best Paper Award** and **People's Choice Award**, each with an amount of **$500**, are being sponsored by two leading companies in the industry: [SenseTime](https://www.sensetime.com/en) and [InferVision](https://global.infervision.com/).

We are thrilled to have SenseTime and InferVision as sponsors for the DALI workshop and are grateful for their support in recognizing outstanding contributions in medical AI research. We encourage all attendees to take the opportunity to learn more about these companies and their groundbreaking work.


<!-- ## Paper Presentation Guidelines

Each accepted paper will be given eleven minutes for presentation and Q&A. In-person presentations are highly recommended, but remote virtual presentations can be accommodated. Please complete the [survey form](https://docs.google.com/forms/d/112VBP1Zft_LDDIPivIcRXPJvsMF4POx31o10zRUQfkU) as soon as possible **by September 14th** to inform the workshop organizers about your presentation format (in-person or virtual) and the presenter of your paper.

Every accepted paper should upload the presentation slides in .pptx format. If your paper will be presented virtually, you are also required to upload a video of your presentation that is 8-9 minutes in length. Authors presenting in-person are strongly recommended to upload a video but they are not required to do so. Please name your files with a prefix that is your DALI22 paper id, e.g. dali22_id-X.pptx where X is replaced by your paper ID. The powerpoint slides and videos should be uploaded to the [Google Drive folder](https://drive.google.com/drive/folders/1vZE40Eq9XV2yr_SwZtP6UlzdA4BXgaIh), **no later than Monday, September 19th**. Please note that you may be asked to sign into one of your google accounts before accessing and uploading files to the folder above. If you encounter difficulty with login, please email Sharon Huang (suh972@psu.edu) and ask for an alternative way of uploading files.

The presenting author should be registered for the second workshop day (September 22) of the MICCAI conference. Via [pathable](https://miccai2022.pathable.eu/), the DALI workshop event can be added to your agenda. The physical event will be held in Room Aquarius 1, 8:00am-3:00pm SGT. Virtual attendees can join the event via a zoom link provided in pathable. The zoom link to join the event should become available in pathable, shortly before the start of the event (8:00am SGT on Sep. 22). -->

<!-- ## Program
 -->


<!-- ### Keynote Speakers
- [Yefeng Zheng](https://sites.google.com/site/yefengzheng/), Tencent Jarvis Lab, China; [talk info](talks/Yefeng_Zheng.html)
- [Daniel Rueckert](https://www.imperial.ac.uk/people/d.rueckert), Technical University of Munich, Germany and Imperial College London, UK; [talk info](talks/Daniel_Rueckert.html)
- [Ehsan Adeli](https://stanford.edu/~eadeli/), Stanford University, USA; [talk info](talks/Ehsan_Adeli.html)
- [Vishal M. Patel](https://engineering.jhu.edu/vpatel36/team/vishalpatel/), Johns Hopkins University, USA; [talk info](talks/Vishal_Patel.html)
- [Zhen Li](https://mypage.cuhk.edu.cn/academics/lizhen/), The Chinese University of Hong Kong, Shen Zhen, China; [talk info](talks/Zhen_Li.html)

### Panelists
- [Chen (Cherise) Chen](https://www.imperial.ac.uk/people/chen.chen15), Imperial College London, UK
- [Lequan Yu](https://yulequan.github.io/), University of Hong Kong, Hong Kong
- [Kelvin Wong](https://www.houstonmethodist.org/faculty/kelvin-wong/), Houston Methodist Hospital, USA; [Bio](talks/Kelvin_Wong.html)

### Click to see &rarr; [Full Program](DALI22_Program.pdf) -->

## People

### Program Chairs

- [Yuan Xue](mailto:Yuan.Xue@osumc.edu), Ohio State University, USA
- [Chen (Cherise) Chen](mailto:chen.chen15@imperial.ac.uk), University of Oxford, UK
- [Chao Chen](mailto:chao.chen.1@stonybrook.edu), Stony Brook University, USA

### Editorial Chairs

- Lianrui Zuo, Johns Hopkins University, USA
- Yihao Liu, Johns Hopkins University, USA

<!-- ### Award Committee -->
<!-- - Dimitris N. Metaxas, Rutgers University, USA -->

### Advisory Board

- Sharon Xiaolei Huang, The Pennsylvania State University, USA
- Hien V. Nguyen, University of Houston, USA
- Nicholas Heller, University of Minnesota, USA
- Stephen Wong, Houston Methodist Hospital, USA
- Daniel Rueckert, Technische Universität München, Germany
- Jerry Prince, Johns Hopkins University, USA
- Dimitris N. Metaxas, Rutgers University, USA
- Ehsan Adeli, Stanford University, USA

### Program Committee

- Amogh Subbakrishna Adishesha, The Pennsylvania State University
- Cheng Ouyang, Imperial College London
- Chenyu You, Yale University
- Christoph M. Friedrich, University of Applied Sciences and Arts Dortmund
- Edward Kim, Drexel University
- Fan Wang, Stony Brook University
- Gilbert Lim, SingHealth
- Haomiao Ni, The Pennsylvania State University
- Jiachen Liu, The Pennsylvania State University
- Kexin Ding, University of North Carolina at Charlotte
- Luyang Luo, The Chinese University of Hong Kong
- Michael Goetz, University Hospital Ulm
- Muchao Ye, The Pennsylvania State University
- Nicha Dvornek, Yale University
- Nicholas Heller, University of Minnesota
- Peiyu Duan, Yale University
- Peng Jin, The Pennsylvania State University
- Ruochen Wang, AbleTo, Inc.
- Samira Zare, University of Houston
- Samuel Remedios, Johns Hopkins University
- Saumya Gupta, Stony Brook University
- Sharon Xiaolei Huang, The Pennsylvania State University
- Weidong Cai, University of Sydney
- Weimin Lyu, Stony Brook University
- Yubo Fan, Vanderbilt University
- Yuli Wang, Johns Hopkins University
- Zeju Li, Imperial College London
- Zhangxing Bian, Johns Hopkins University
- Zuhui Wang, Stony Brook University

<img src="sensetime_logo.png" alt="SenseTime graphic" width="340" height="255"> &nbsp;&nbsp;&nbsp;&nbsp; <img src="infervision_logo.png" alt="InferVision graphic" width="400" height="300">


<!-- Prizes for **best paper and best paper honorable mention** awards are sponsored by [Rulai](https://rul.ai/), [Uzer](http://www.uzerhn.com/) and [United Imaging](https://www.uii-ai.com/en)

![Rulai graphic](rulai_logo.png)

![Uzer graphic](uzer_logo.jpg)

![United-Imaging_graphic](united_imaging_logo.png) -->

<!--[Histosonics graphic](https://histosonics.com/wp-content/uploads/2020/03/histosonics_ogimage.jpg) -->
