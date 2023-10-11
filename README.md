# TCMNER_datasets
TCM NER dataset used in the paper "MC-TCMNER_A Multi-Modal Fusion Model Combining Contrast Learning Method for Traditional Chinese Medicine NER"
# Prescipts
Since there is currently a lack of publicly available large-scale TCMNER datasets, we collected and annotated a TCMNER dataset independently and used it to evaluate the model’s performance. We first used web scraping techniques to extract disease related information from [the website](https://www.zhzyw.com/jbdq.html), which includes brief descriptions of diseases, symptoms, causes, treatment methods, and others. For the extracted text content, we initially cleaned it by removing duplicate sentences and characters that are not Chinese. Four clinical experts from China (chief physicians) used the YEDDA annotation tool to individually annotate text for four types of information using BIO tagging. This dataset contains a total of 387,465 Chinese characters, with five types of entities: Symptoms, Causes, Herbs, Preparations(already prepared medicine), and Effects.
<p align="center">
    <img src="https://github.com/cshan-github/TCM_NER_datasets/blob/main/1.jpg" width="200" height="150">
