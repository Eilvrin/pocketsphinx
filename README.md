# Modified ROS wrapper for pocketsphinx  
Original repository: https://github.com/mikeferguson/pocketsphinx  
  
Also used repo: https://github.com/gorinars/ros_voice_control  

It used up-to-date pocketsphinx features and is independent of most external dependencies.  
  
Current repository is a ROS wrapper which incorporates those features.  
  
## Dependencies  
1) pyaudio  
    ```
    sudo pip install pyaudio
    ```
or
    ```
    sudo apt-get install python-pyaudio
    ```
2) pocketsphinx: You will need to have pip preinstalled for this to work
    ```
    sudo pip install pocketsphinx
    ```

## Usage
``` 
roslaunch pocketsphinx pocketsphinx.launch
```
