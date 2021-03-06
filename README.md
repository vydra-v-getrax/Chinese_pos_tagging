# Chinese_pos_tagging

This is a repository for code used in paper [**"Automatic POS-tagging for Chinese Using Parallel Data"**](https://www.hse.ru/en/edu/vkr/472522644).
The work consists of two parts: first, 'pos_tagging' presents a comparison of different approaches to Chinese part-of-speech tagging (for description, follow the link). Second, 'bi_lstm', provides a parallel-corpus based solution for specific data of the [**Russian-Chinese Parallel Corpus of RNC**](http://ruzhcorp.ruscorpora.ru/). 

 **Path** | **Description**|**Link**
:---|:---|:---
**pos_tagging.ipynb**|Colab notebook with code for preprocessing datasets, aligning tags and POS tagging tools comparison.|[_Access_](https://github.com/vydra-v-getrax/Chinese_pos_tagging/blob/main/pos_tagging.ipynb)
**Bi_lstm_for_tagging.ipynb**|Colab notebook with BiLSTM two-inputs model for POS tagging on parallel data|[_Access_](https://github.com/vydra-v-getrax/Chinese_pos_tagging/blob/main/Bi_lstm_for_tagging.ipynb)



<h3>
  
[Human-annotated](https://docs.google.com/spreadsheets/d/1ZG3xwqC7z857qjFdm3Z02yz968ArbGv7MJ-EDdw3yew/edit?usp=sharing) evaluation dataset is available here.
  
  
  

[Comparative table](https://docs.google.com/spreadsheets/d/1w7qRF3H2GmFOW5HvMIGrgIBC8RfK17UmkMJpzcOwAaQ/edit?usp=sharing) of Russian-Chinese tagsets is here.
</h3>

Run the code as described in the notebooks. 

Import necessary data from the **pos** folder.
