# Deep Learning Chatbot

An intelligent chatbot trained on database made by Reddit comments.

:warning: This bot utilizes **Deep Learning** for training purposes. Be sure to have a powerful dedicated graphics card (a card with >= 3000 cuda cores) if you want to train the bot yourself. Training on CPU might take forever or might just straight up destroy the CPU, based on its capacity.


## The Build
This bot is built on data from all comments and conversations on Reddit made till May, 2009. Only the comments with upvotes **>= 5** are selected for training.

The training database as well as the conversations database are not uploaded on GitHub due to file size restrictions. If you want to train the bot on your own dataset, please modify **`bot_dbs.py`** accordingly. Be careful to change the path of downloaded data, as well as, take note of the directory structure of the storage.

Since this bot has been trained on old data, redefined training with current data is required in order to make it understand the current lingo.