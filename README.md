# Chatbot
A simple rule based chat bot using python. It can also be switched to human support if the bot is not able to answer the queries.
## Dependencies
  - This program can be run on Windows and Linux.
  - Programming language used is Python 3.8
## Steps to install python3.8 on Linux
  - sudo apt-get install build-essential checkinstall
  - sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev \
    libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev
  - cd /opt
  - sudo wget https://www.python.org/ftp/python/3.8.0/Python-3.8.0.tgz
  - sudo tar xzf Python-3.8.0.tgz
  - cd Python-3.8.0
  - sudo ./configure --enable-optimizations
  - sudo make altinstall
  - _As you have not overwritten the default Python version on the system, So you have to use Python 3.8 as follows:_
  - python3.8 -V
## Instructions
  - Kindly make sure you have the latest python version i.e. 3.8 as the format in which the split function is used will throw                   an error in previous verisons.
  - To execute run the following command 
    - **python3.8 chatbot.py**
  - Here is the list of the queries you can ask the chatbot
    - hi
    - how are you
    - who are you
    - what do you like
    - suggest me some movies
    - I have already watched it
    - ok I will watch it
    - how is the weather today
    - who is your creator
    - bye
   - Here are some responses which you can give if the bot asks you something
      - yes
      - no
      - why
   - The bot is designed to answer differently for different sequences in which the questions will be asked
   - For example if you query I have watched it without asking suggest me some movies, it will have a different answer.
   - If some query is asked outside from these queries the bot will first confirm then it will shift the control to a human support who        will then interact with the customer.
   - As soon as the customer asks something from within the queries the controls will be shifted autromatically to the bot.

