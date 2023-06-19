# Low-resource languages in neural machine translation
Low-resource languages pose challenges in Neural Machine Translation (NMT) due to the limited availability of parallel training data. Here are some key problems associated with low-resource languages in NMT:

1. Data Scarcity: Low-resource languages often lack sufficient parallel data, which is essential for training NMT models effectively. This scarcity of data makes it difficult for the models to learn accurate translations and can lead to poor performance.

2. Out-of-Vocabulary (OOV) Words: Low-resource languages may contain a higher number of out-of-vocabulary words, i.e., words that are not present in the training vocabulary. Translating these OOV words accurately becomes challenging as the models may struggle to find appropriate translations.

3. Translation Quality: With limited training data, NMT models for low-resource languages may produce translations that suffer from inaccuracies, inconsistencies, or grammatical errors. The models might struggle to capture the nuances and specific characteristics of the target language.

4. Domain Adaptation: NMT models trained on high-resource languages may not perform well when applied to low-resource languages, especially if the domains or language styles differ significantly. Adapting the models to the specific domain or style of the low-resource language becomes crucial for improved translation quality.

5. Lack of Resources and Evaluation Metrics: Low-resource languages often lack comprehensive linguistic resources, such as dictionaries, corpora, or evaluation metrics. This scarcity hinders the development and evaluation of NMT models for these languages.


Addressing these challenges requires innovative approaches and techniques specifically tailored to low-resource languages. Researchers and practitioners explore methods like transfer learning, unsupervised or semi-supervised learning, data augmentation, and domain adaptation techniques to enhance the performance of NMT models for low-resource languages.


In this project used data augmentation techniques for solving low-resource languages problem in NMT. 

Language:
Here, this project took Bengali to Chinese, Chinese to Bengali, Hindi to Chinese, Chinese to Hindi, Urdu to Chinese, Chinese to Urdu, Turkish to Chinese, Chinese to Turkish, Uzbek to Chinese, Chinese to Uzbek. 

Datasets:
The datasets took a from Tanzil Corpora open subtitle. 
