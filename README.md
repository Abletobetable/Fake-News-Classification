# Kontur-NLP-task
Задача детекции фейковых новостей.

Использованный стек:

- pytorch

- huggingface 

- pretrained navec embeddings

Подходы к решению (метрика f1_score):

  1. navec news average embedding + MLP = 0.82
  2. navec news как начальная инициализция, далее nn.Embeddings + LSTM = 0.86
  3. pretrained Distilbert из huggingface = 0.87
  
Это задание было вступительным испытанием на стажировку в Контур(весна 2022)
