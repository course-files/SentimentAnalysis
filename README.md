# Sentiment Analysis

| Key              | Value                                                                                                                                                                                                                                                                                              |
|:-----------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Course Codes** | BBT 4206, BFS 4102                                                                                                                                                                                                                                                                                 |
| **Course Names** | BBT 4206: Business Intelligence II (Week 10-12 of 13) and <br/>BFS 4102: Advanced Business Data Analytics (Week 10-12 of 13)                                                                                                                                                                       |
| **Semester**     | January to April 2026                                                                                                                                                                                                                                                                            |
| **Lecturer**     | Allan Omondi                                                                                                                                                                                                                                                                                       |
| **Contact**      | aomondi@strathmore.edu                                                                                                                                                                                                                                                                             |
| **Note**         | The lecture contains both theory and practice.<br/>This notebook forms part of the practice.<br/>It is intended for educational purpose only.<br/>Recommended citation: [BibTex](https://raw.githubusercontent.com/course-files/NaturalLanguageProcessing/refs/heads/main/RecommendedCitation.bib) |

## Repository Structure

```text
.
├── 1_topic_modeling_using_LDA.ipynb
├── 2_sentiment_analysis.ipynb
├── LICENSE
├── README.md
├── RecommendedCitation.bib
├── admin_instructions
│   ├── instructions_for_postlab_cleanup.md
│   ├── instructions_for_project_setup.md
│   └── instructions_for_python_installation.md
├── assets
│   └── images
│       ├── activate_venv_pycharm.png
│       └── activate_venv_vscode.png
├── data
│   ├── 202511-ft_bi1_bi2_course_evaluation.csv
│   ├── processed_scaled_down_reviews.csv
│   ├── processed_scaled_down_reviews_with_topics.csv
│   └── processed_scaled_down_reviews_with_topics_and_sentiments.csv
├── lab_submission_instructions.md
├── model
│   ├── sentiment_classifier.pkl
│   ├── topic_labels.json
│   ├── topic_model_lda.pkl
│   ├── topic_vectorizer.pkl
│   └── topic_vectorizer_using_tfidf.pkl
├── requirements
│   ├── base.txt
│   ├── colab.txt
│   ├── constraints.txt
│   ├── dev.inferred.txt
│   ├── dev.lock.txt
│   ├── dev.txt
│   └── prod.txt
└── requirements.txt

7 directories, 28 files
```

## Setup Instructions

- [Setup Instructions](/admin_instructions/instructions_for_project_setup.md)

## Lab Manual

Refer to the files below for more details:

1. [1_topic_modeling_using_LDA.ipynb](1_topic_modeling_using_LDA.ipynb)
2. [2_sentiment_analysis.ipynb](2_sentiment_analysis.ipynb)

## Lab Submission Instructions

- [Lab Submission Instructions](lab_submission_instructions.md)

## Cleanup Instructions (to be done after submitting the lab)

- [Cleanup Instructions](/admin_instructions/instructions_for_postlab_cleanup.md)