# Good-Bad-Chat
This project aims to classify text conversations into "good" and "bad" chats based on their content.

Model:
         +-------------------+
         | Input Text       | (variable length)
         +-------------------+
                |
                v
         +-------------------+
         | Embedding Layer   | (300 x 100)
         +-------------------+
                |
                v
         +-------------------+
         | Spatial Dropout   | (300 x 100)
         +-------------------+
                |
                v
         +-------------------+
         | LSTM Layer       | (100 units)
         +-------------------+
                |
                v
         +-------------------+
         | Dense Layer       | (1 unit)
         +-------------------+
                |
                v
         +-------------------+
         | Model Output      | (probability score)

Score:
![download](https://github.com/bibasrairockz/Good-Bad-Chat/assets/130794180/e7d72263-2b43-4d75-978d-573233678b81)

