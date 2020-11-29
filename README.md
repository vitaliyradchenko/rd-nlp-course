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
3. [Word embedings](https://docs.google.com/presentation/d/1vDb9-NIKWMAlLYiQdigDDbWd_-RWIH8q7MFE0HE8r7o/edit?usp=sharing)
4. [Знакомство с pytorch](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Into%20to%20pytorch.ipynb),
[тренировка простых нейронных сетей](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/Simple%20NN.ipynb)
5. [Recurrent neural networks](https://docs.google.com/presentation/d/13ar7A9MWugvGeD-07FhRR8UVPs7JZrQhM4xuKsU0oW8/edit?usp=sharing)
6. Использование предобученных векторов слов
7. [Использование реккурентных нейронных сетей](https://github.com/vitaliyradchenko/rd-nlp-course/blob/main/workshops/RNN.ipynb)