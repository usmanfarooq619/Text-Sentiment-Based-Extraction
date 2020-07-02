# Text-Sentiment-Based-Extraction
Using BERT Question Answering Model
    
   Even though huge strides have been made in the field
of NLP, the domain of Text summarizing still remain relatively
unexplored. In this code we give an end-to-end ’Text Extraction’
against sentiments using Question Answering model through
BERT (Bidirectional Encoder Representations from Transformers).
Most of the model usually uses this model for simple text
summarizing, but in contrast to these models we do our text
extraction on the basis of Sentiments (Positive, Negative, Neutral)
and evaluate our model on the basis of Jaccard score. For our
model we will use data that is mostly comprised of Tweets and
we will try to do Text Extraction/Summarizing on the basis of the
sentiments of these Tweets. Even though research has been done
on the application of BERT algorithm, very few literature could
be found on the application of the BERTForQuestionAnswering
Models. We will make use of this novel approach and through
this effort we were able to achieve very promising result.

Now a days, Text Extraction and summarization is a
common problem in natural language processing (NLP) and
information retrieval (IR). Summerization a technique in
which is a condensed version of a text or paragraph that
covers main points. Similarly text extraction is a processes
which is used to normalize text and get the desire part or
sentiment of a sentence or passage, it plays an important role
in reducing the reading time of audience and searching time
of the researcher.Also both of these techniques is used for the
sentiment analysis to get the emotion of the given passage.
In this paper extraction technique is used which helps to get
key phrases or sentence form the given passage and tells the
sentiment of it.
For this purpose Bidirectional Encoder Representations
from Transformers (BERT) powerful algorithm of NLP and
IR is used, which is a pre-trained deep learning model
developed by google (2018)[1]. It is a state of the art
algorithm which gives incredible results in number of NLP
tasks like question answering and inference. We explore the
BertForQuestionAnswering in our project, this model take
questions and return answer from the given text summary.
Will ask our model about negative sentiment and the answer
will tells the nature of the given sentence ”my boss is bullying
me” .
We next probe to Bert Tokenizer which converts input data
in to the shape which is accepted by the mode, by converting
each token with token ids existing in the embedding table
and manages masks. For the sake of evaluation General
Language Understanding Evaluation (GLUE)[2]is used which
contains multiple tools for the evaluation of the model and
for optimization of model Adam [3] algorithm is used, an
algorithm which is gradient based and use stochastic objective
functions, depends on adaptive estimation.
Data set is originally available onhttps://
appen.com/resources/datasets/ ”Figure Eight’s Data for
Everyone platform” titled by Sentiment Analysis it’s also
publically available on Kaggle named as tweet sentiment
extraction which is investigated in our project.Data set
contains 4 columns naming (textID, Text, Sentiment and
selected text) and 27481 unique values.
The following paper is organized as: Section II covers the
literature which is reviewed for this study. Section III explain
the details of approach which is used. Section IV describe the
results that is achieved during this study. Section V define the
conclusion and the scope of future work. Section VI contains
the references of this study.


References:

https://www.kaggle.com/rinnqd/is-this-a-leak-or-magic
https://www.kaggle.com/futureboykid/2nd-place-post-processing
https://www.kaggle.com/jonathanbesomi/private-test-not-that-private-afterall
https://github.com/sarnthil/unify-emotion-datasets/tree/master/datasets
https://www.kaggle.com/rohitsingh9990/preprocessing-that-worked
https://www.kaggle.com/c/tweet-sentiment-extraction/discussion/159499
https://app.wandb.ai/cayush/bert-finetuning/reports/Sentence-classification-with-Huggingface-BERT-and-W%26B--Vmlldzo4MDMwNA
https://keras.io/examples/nlp/text_extraction_with_bert/

Major Code help have been taken from these authors i dont have any rights of there  work.
