+++
date = '2026-04-12T15:49:53-05:00'
draft = false
title = 'Sporophyte Detection'
tags = ["deep learning", "ecology"]
+++

Working with biologists in the [Alberto lab](https://alberto-lab.blogspot.com/) at UW Milwaukee, I created a new dataset of over 1300 microscope images of *Giant Kelp* and *Nereocystis* sporophytes with hand labelled bounding boxes around around sporophytes and eggs. Using this data, I trained object detection machine learning models to identify sporophytes automatically. I contributed a [blog post](https://sinews.siam.org/Details-Page/estimating-giant-kelp-populations-with-deep-learning) about this project to SIAM news, and I gave a [contributed presentation](https://meetings.siam.org/sess/dsp_talk.cfm?p=121505) about the topic at the [SIAM MPE22 conference](https://www.siam.org/conferences/cm/conference/mpe22) in the summer of 2022. I have also created a [hugging face space](https://huggingface.co/spaces/liam-jemison/kelp) to demonstrate the network we trained.

I have made public some of [the code that I used to train yolov7 sporophyte detection models](https://github.com/dave-quesadilla/yolov7-kelp-traininghttps://github.com/dave-quesadilla/yolov7-kelp-training) as well as the [data I collected](https://github.com/dave-quesadilla/yolov7-kelp-training/releases/tag/v0.1.0) for this project. 
