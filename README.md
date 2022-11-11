<H1>TamilEmo: Finegrained Emotion Detection Dataset for Tamil</H1>


Emotional Analysis from textual input has been considered both a challenging and interesting task in Natural Language Processing. However, due to the lack of datasets in low-resource languages (i.e. Tamil), it is difficult to conduct research of high standard in this area. Therefore we introduce this labelled dataset (a largest manually annotated dataset of more than 42k Tamil YouTube comments, labelled for 31 emotions including neutral) for emotion recognition. The goal of this dataset is to improve emotion detection in multiple downstream tasks in Tamil. We have also created three different groupings of our emotions (3-class, 7-class and 31-class) and evaluated the model's performance on each category of the grouping. Our MURIL-base model has achieved a 0.60 macro average F1-score across our 3-class group dataset. With 7-class and 31-class groups, the Random Forest model performed well with a macro average F1-scores of 0.42 and 0.29 respectively.

<H2>Dataset</H2>
The dataset is available on request by mailing the authors

<H2>Source Code</H2>
<ul>
<li>The ML_models.ipynb notebook consists of the source code for the ML models  </li>
<li>The source code for the transformers is used from the template <a href="https://github.com/seanbenhur/resusable_text_classification_template">here<> 
</ul>


