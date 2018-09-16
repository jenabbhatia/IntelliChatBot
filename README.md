# IntelliChatBot
A conversational Chatbot with tensorflow

    Dependencies
       -numpy
       -scipy
       -six
       -tensorflow 0.12.1
    Use pip to install any missing dependencies

    Usage
    1.) To train the bot, edit seq2qeq.ini file so that mode is set like
        mode = train
    2.) Then run the code like
        python chat.py
    3.) To test the bot after training, edit seq2seq.ini file so that mode is set like
        mode = test
    4.) then run the code like
        python chat.py
   
    This cornell movie corpus contains a large metadata-rich collection of fictional conversations extracted from raw movie scripts:
           1.) Download the processed data by running pull_data.sh
                ./pull_data.sh
           2.) After runninh pulldata script following files will be generated:
                    train.enc
                    train.dec
                    test.enc
                    test.dec
           3.) Put the above generated files in /data folder
           
    

