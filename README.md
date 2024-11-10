# BioMedical_Extractive_Question_Answering

Designed and Developed a model that extracts the Biomedical Answer from given passage and questions and improves information retrieval from complex medical texts. By enhancing our Bio+ClinicalBERT model with NER, RE, and BiLSTM layers, it effectively addresses domain-specific terminology and biomedical relationships. Using ensemble learning, the model achieves notable results with an F1 score of 91.69, Exact Match of 88.35, and Lenient Accuracy of 0.84, showcasing its potential to aid clinical and research applications.

## Abstract:
In the realm of natural language processing, extractive question answering (EQA) from a given context paragraph is a fascinating task that has attracted the attention of researchers due to its practical applications and promising future across diverse fields. While EQA has flourished in general domains with abundant resources, the biomedical realm presents an exciting frontier for innovation. This emerging landscape offers a unique opportunity to contribute significantly and accelerate
progress. This study presents a novel approach to biomedical factoid-based extractive Question Answering, addressing the complexities of medical language. We leverage transformer-based pre-trained models, enhancing them with Named Entity Recognition, Relation Extraction, and BiLSTM layers. Our method, culminating in ensemble learning, achieves a 5.45\% performance boost. The resulting system not only improves answer accuracy but also uncovers intricate biomedical relationships, providing deeper insights for researchers and clinicians. By bridging the gap between complex medical texts and precise information retrieval, our work contributes significantly to advancing biomedical knowledge extraction. Our study progressed through a systematic evaluation of six transformer encoder models, ultimately selecting Bio+ClinicalBERT as the foundation for our approach. We developed three increasingly sophisticated BEQA models, culminating in Bio+ClinicalBERT_NER_RE_BiLSTM. This final model excelled in performance, achieving F1 91.69, Exact Match 88.35, and Lenient Accuracy 0.84. These results demonstrate our model's capability to navigate complex biomedical language, extract precise information, and significantly advance the field of biomedical question answering.