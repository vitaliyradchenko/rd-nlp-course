# NLP. Deep Dive

Чтобы установить виртуальную среду, вы должны остаться в корневой папке и выполнить следующую команду: `python3.6 -m venv venv`.  
После этого активируйте среду `source venv/bin/activate`.  
Посе активации установите необходимые пакеты `requirements.txt`. Для этого нужно запустить данную команду `pip install -r requirements.txt`  
Для комфортной работы с jupyter ноутбуками вам следует установить kernel для своей среды:
```bash
ipython kernel install --user --name=nlp-course
```

## Lectures

1. [Знакомство с NLP](https://docs.google.com/presentation/d/11wX8F8SJtPjIbSSIS5hGBmQTqQlrLJMxNH61lLyNPVM/edit?usp=sharing), 
[настройка окружения](https://docs.google.com/presentation/d/1ApvRH8wBGq1DvkCiUm1cqWn21lDHZf-LpNEdJo3WLPM/edit?usp=sharing),
[использование NLTK и SpaCy](https://github.com/vitaliyradchenko/nlp-course/blob/master/workshops/NLTK_Spacy.ipynb)
2. [Базовые подходы к обработке текста](https://docs.google.com/presentation/d/1xFc0h9nrc1lrAHKsRC3WHWrA9RxVW6J5BqdWvM-16Lk/edit?usp=sharing)
3. [Word embeddings](https://docs.google.com/presentation/d/1vDb9-NIKWMAlLYiQdigDDbWd_-RWIH8q7MFE0HE8r7o/edit?usp=sharing)
4. [Знакомство с pytorch](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Into%20to%20pytorch.ipynb),
[тренировка простых нейронных сетей](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Intro%20to%20NN.ipynb)
5. [Recurrent neural networks](https://docs.google.com/presentation/d/13ar7A9MWugvGeD-07FhRR8UVPs7JZrQhM4xuKsU0oW8/edit?usp=sharing)
6. [Использование предобученных векторов слов](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Simple%20NN.ipynb)
7. [Использование рекуррентных нейронных сетей](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/RNN.ipynb)
8. [Языковая модель и архитектура transformer](https://docs.google.com/presentation/d/1ac0slzDyzmtZxm1W4jB-GZpYYZ2h08XeSoFaPMYmnVQ/edit)
9. [Токенизация и ознакомление с библиотекой transformers](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Tokenization%20and%20into%20to%20transformers%20by%20HuggingFace.ipynb)
10. [Генерация речи](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Text%generation.ipynb)
11. [Разбор SOTA архитектур основанных на трансформерах](https://docs.google.com/presentation/d/1iUKFlUung6VdGpsa1eFtPv3H5Got3CXOK-_TIQr4WSU/edit?usp=sharing)
12. [Подходы к файнтюнингу](https://docs.google.com/presentation/d/1VyVplkTasPpD-w3l-p2Ont6f2IVouOZa64V-8yEogqs/edit?usp=sharing)
13. [Технические модификации тренировки и инференса](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Training%tricks.ipynb)
14. [Ner воркшоп](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Ner_workshop.ipynb)
15. [Conversation Ai. Чатботы](https://docs.google.com/presentation/d/1WFJTAKLAucoM0RCFxJnZ6CCY6mBCAWugHFu18FtNfx8/edit?usp=sharing)
16. [Анализ и интерпертация результатов](https://docs.google.com/presentation/d/1GdOkbKyhUuZJ8MuQBsNaU4SF8jn8l4JxEdkKAl80yqA/edit?usp=sharing)
17. [Оптимизация моделей. Дистилляция](https://docs.google.com/presentation/d/1rsHITht30cyDwceVEKanKS8pRFProa8ex-EYPgH20Ds/edit?usp=sharing). [Подготовка модели ученика для дистилляции](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Initialize_student_model.ipynb)