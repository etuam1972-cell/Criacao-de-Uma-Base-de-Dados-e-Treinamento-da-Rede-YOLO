Treinamento da Rede YOLO com Transfer Learning e Dataset COCO
Desafio de Projeto da DIO (Digital Innovation One)

Trilha / Bootcamp: BairesDev - Machine Learning Practitioner

📌 Descrição do Desafio
Este projeto tem como objetivo realizar a preparação de dados e a aplicação de Transfer Learning na rede de detecção de objetos YOLO.

Conforme as especificações do desafio:

Utilizou-se a base de dados pública COCO Dataset para extrair imagens anotadas sem a necessidade de rotulagem manual exaustiva no LabelMe.

Foi realizado o fine-tuning da rede YOLO mantendo pesos pré-treinados no backbone e ajustando as camadas finais para ao menos duas classes específicas: dog (cachorro) e bicycle (bicicleta).

O projeto foi estruturado para ser executado diretamente em um ambiente de GPU em nuvem, como o Google Colab.

📸 Exemplo de Resultado Esperado
O resultado final do modelo retreinado/ajustado gera caixas delimitadoras (bounding boxes) e rótulos sobre as classes detectadas:

+-------------------------------------------------------+
|  [bicycle]                                            |
|  +-------------------------------------------------+  |
|  |                                                 |  |
|  |   [dog]                                         |  |
|  |   +-------------------+                         |  |
|  |   |                   |                         |  |
|  |   |   🐕              |        🚲               |  |
|  |   +-------------------+                         |  |
|  |                                                 |  |
|  +-------------------------------------------------+  |
+-------------------------------------------------------+
