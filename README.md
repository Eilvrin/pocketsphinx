# Modified ROS wrapper for pocketsphinx  
Original repository: https://github.com/mikeferguson/pocketsphinx  
  
Also used repo: https://github.com/gorinars/ros_voice_control  

It uses up-to-date pocketsphinx features and is independent of most external dependencies.  
  
Current repository is a ROS wrapper which incorporates those features. 
  
## Installation 
1)   
    ```
    sudo apt-get install -y python python-dev python-pip build-essential swig libpulse-dev git
    sudo apt-get install python-pyaudio
    ```

2) pocketsphinx: You will need to have pip preinstalled for this to work
    ```
    sudo pip install pocketsphinx
    ```
3) Download and copy the hub4wsj_sc_8k language model  to /usr/share/pocketsphinx/model/hmm/en_US/. It can be found here: https://sourceforge.net/projects/cmusphinx/files/Acoustic and Language Models/Archive/US English HUB4WSJ Acoustic Model/

## Usage
``` 
roslaunch pocketsphinx pocketsphinx.launch
```

## Using your own keywords

You can run this with any set of words. To do that, you need lexicon and keyword list files (check voice_cmd.dic and voice_cmd.kwlist for details).

Word pronunciations for English can be found in CMUdict

You can also download pocketsphinx acoustic models for several other languages here

Read more about pocketsphinx on the official website: http://cmusphinx.sourceforge.net
