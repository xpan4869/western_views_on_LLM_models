# Narratives of AI Innovation: A Textual Analysis of Western Social Media’s View on ChatGPT and DeepSeek
Author: _Xinyue 'Yolanda' Pan_  
Date: _March 9th, 2025_  
Presentation Video Link: _https://www.youtube.com/watch?v=eMbICh3nlS8_  

## Github Repo Overview  
**Data**: 
- reddit_text_data/:
    - Source: arctic-shift
    - Time Range: 2024/12/27 - 2025/03/03
    - too big to upload, save in local
  
    | subreddits | posts |  comments |
    | -------- | ------- | ------- |
    | r/aritificialingelligence | 10882 | 90705 |
    | r/machinelearning | 8450 | 27801 |
    | r/deepseek | 5686 | 32517 |
    | r/chatgpt | 44721 | 609444 |
    | r/perplexity_ai | 1633 | 13914 |
  
- emotional_narratives_data/
    - tagged using samlowe/roberta-base-go_emotions
  
- topic_modeling_data/  
    - tagged using BERTopic
  
**Jupyter Notebook**:
- data_preprocess.ipynb: data preprocessing  
- data_analysis_ml_application.ipynb: sentiment/emotion labeling, topic modeling, clustering, data analysis

## Project Overview

**Motivation**

The rise of DeepSeek and other large language models (LLMs) marks both a technological milestone and an opportunity to explore the geopolitical and cultural tensions in the global AI landscape. This study examines how predominantly English-speaking social media platforms, particularly Reddit, shape perceptions of AI models like ChatGPT (developed in the U.S.) and DeepSeek (developed in China). 

**Research Question**

What narratives emerge from Western Reddit communities’ discussions about ChatGPT and DeepSeek, and how do these narratives reflect user perceptions of AI innovation?

**Machine Learning Task Formulation**

(1) emotion/sentiment labeling with RoBERTa-base-go_emotions (supervised), (2) topic modeling with BERTopic (unsupervised) to identify narrative themes, and (3) clustering (unsupervised) of BERTopic probability outputs to group similar narratives and answer the research question.

**Theory of Orientalism**

Edward Said’s theory of Orientalism (1977) provides a critical framework for understanding how the West constructs the "Other," often framing Chinese AI technologies like DeepSeek as exotic, inferior, or threatening, while portraying Western models like ChatGPT as symbols of innovation and superiority. This study explores how Western social media users on Reddit (e.g., r/ChatGPT and r/DeepSeek) reinforce these Orientalist narratives, reflecting broader geopolitical tensions and cultural biases. While the Reddit community is predominantly tech-savvy and Western-centric, it offers valuable insights into how power dynamics shape global AI discourse, particularly in the context of rising competition between the West and China. 

**Hypothesis**

H1: Sentiment towards DeepSeek will be more negative and emotionally charged compared to ChatGPT, reflecting cultural stereotypes about Chinese LLMs. ‘

H2: Discussions about Chinese LLMs will frequently feature terms like "surveillance" or "authoritarianism," while Western LLMs will emphasize "freedom," "creativity," and "leadership." 

H3: Clustering of DeepSeek discussions will group granular topics into broader themes, with "geopolitical risks" exhibiting more negative sentiment than "technical capabilities."

