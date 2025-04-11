---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MASc. in Electrical and Computer Engineering, 2021
* BSc. in Electrical Engineering with Honors, 2019

Work experience
======
* 2022 – 2024: AI R&D Engineer @ Qatar Mobility Innovations Center (QMIC)
  * Developed real-time object tracking systems using YOLOv4-v7 for national and large-scale applications, including FIFA World Cup 2022, achieving 95% accuracy.
  * Optimized models for edge computing on Jetson Xavier and Nano using TensorRT, ONNX, and CUDA, enabling low-latency inference on live RTSP video streams in both server and edge environments.
  * Implemented logging and modular AI pipelines using Docker for effective deployment of AI applications.
  * Collaborated with cross-functional teams (software and field engineers) using Git and Jira to seamlessly visualize data into dashboards.

* 2019 — 2021: Deep Learning Graduate Researcher @ University of Waterloo
  * Researched and implemented deep learning models (CNN, LSTM, Transformers) for crop yield and price time series forecasting, improving accuracy by 70\% against baselines.
  * Curated and pre-processed time series datasets handling gaps, normalization, and feature engineering.
  * Built and deployed an application for data visualization to enhance stakeholder decision-making at Loblaw Companies Ltd.
  * Collaborated with team researchers and published four peer-reviewed papers at international AI conferences.
  
Skills
======
* Programming Languages: Python, SQL, C++, R, MATLAB
* AI Frameworks: TensorFlow, PyTorch, Keras, Scikit-learn, CUDA, ONNX
* Data Processing: NumPy, OpenCV, Pandas, GDAL
* Web App Frameworks: Flask, Django
* Developer Tools: Git, Docker, VS Code, MQTT, RabbitMQ, RGui

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
