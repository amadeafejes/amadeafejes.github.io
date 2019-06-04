---
layout: post
title: "Data Engineering A-Z: Apache Airflow"
---

I shall begin my Data Engineering encyclopedia with an article about a classic Data Engineer tool, Apache Airflow. If you are an aspiring Data Engineer like me who has made some research about Data Engineering tools I'm sure you have met with the name Apache Airflow. The more I get involved in data pipelines the more I find this program unavoidable, so I decided to start my blog with an article about Airflow. I'm going to show you what is the reason that it is part of every second data engineer job description.

I assume you have a basic understanding of Python data pipelines. If not, no worries it is not rocket science: it is just some steps that process data defining these steps as Python code. I could write a long post about why Python is used in this field, but I think you can imagine it: Python is easy to learn, expressive and has a lot of useful libraries to use.

When you would like to create a data pipeline you just write the python code using any tools you like Jupyter or a simple text editor and then run it. Sounds easy, right? But what if you need to run your pipeline every day or five times a day or in every 10 miniutes? What if you need to schedule these steps and make them run in the future? Good news: you don't need to sit there start your python script every time you need nor wait for the right time, bacause you can use Apache Airflow that makes it much easier.


