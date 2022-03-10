# Pymaceuticals

## Background

What good is data without a good plot to tell the story?

So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

## Findings

1. There is a <b>positive correlation</b> between the weight of the mice and the size of the tumour. This linear correlation is indicated by the <b>P-Value of 0.84.</b> Therefore, it may be effective to limit the weight of the mice.

<p align="center">
  <img src="https://github.com/mnperic/pymaceuticals/raw/main/Images/linear_regression.png" alt="linear_regression"/>
</p>

2. Of the four drug regimens, <b>Capomulin seems to be the most effective drug to treat the cancer.</b> For example, the tumour size in Mouse I509 <b>decreased</b> over time.

<p align="center">
  <img src="https://github.com/mnperic/pymaceuticals/raw/main/Images/scatter_plot.png" alt="scatter_plot"/>
</p>

3. Of the four drug regimens analysed, <b>Capomulin and Ramicane were the most effective at decreasing tumour size.</b> Conversely, <b>Infubinol and Ceftamin were less effective in treating the cancers.</b> Consequently, I would recommend further studies or advancing the stages of both Capomulin and Ramicane in the treatment of tumours.

<p align="center">
  <img src="https://github.com/mnperic/pymaceuticals/raw/main/Images/box_plot.png" alt="box_plot"/>
</p>
