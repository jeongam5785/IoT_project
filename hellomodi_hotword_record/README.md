# "HELLO, MODI" Hotword Record

By using ***record_to_wave(filepath, duration)*** function in ***src/aiy/vision/audio.py***, we can record **"HELLO, MODI"** voice file as .wav     
#
## Reference  

1. Push the button and hold until the color of the button changes red.
-> When the color of the button is red, you can record 'a word' up to 10 seconds.
-> If you finished recording, release the button!
#
2. The form of the file name is **'yyyy-mm-dd_hh-mm-ss.wav'**. 
#
3. You can control the Voice Kit's sound volume.
```
~$ amixer set Master 20%
```
#

4. You can change the color of the button. 

```
RED = (0xFF, 0x00, 0x00)    
GREEN = (0x00, 0xFF, 0x00)  
YELLOW = (0xFF, 0xFF, 0x00) 
BLUE = (0x00, 0x00, 0xFF)   
PURPLE = (0xFF, 0x00, 0xFF) 
CYAN = (0x00, 0xFF, 0xFF)   
WHITE = (0xFF, 0xFF, 0xFF)  
```
#

For more information... check https://github.com/google/aiyprojects-raspbian.git
#




