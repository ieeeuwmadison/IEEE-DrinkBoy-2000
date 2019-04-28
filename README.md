# IEEE-DrinkBoy-2000
*Here for further instructions? See IEEE Breathalyzer.docx.*

## Overview
IEEE Breathalyzer project for Spring 2019. It detects alcohol and interacts with users.

## Component
1. Arduino Nano Clone
2. MQ3 Sensor
3. Piezo Buzzer
4. OLED Screen
5. Custom PCB

## Code Explanation
The provided code will warm up the MQ3 Sensor for some time with a loading bar showing a progress. After it is warm up, you can start blowing into the sensor. If the value is not higher than the THRESHOLD value, nothing will happen (the screen will not display anything). However, if the value exceeds, measuring message will appear and now you can keep blowing into it. It will take roughly 250 milliseconds for each sample (can be changed). The default number of samples is 10 samples per measuring. If the average value is high enough, the drunk message will be printed. Otherwise, drink more!

### Parameters
Here are some examples of parameters you can play with
1. WARMUP_PERIOD
2. SAMPLES
3. THRESHOLD
4. DRUNK
5. FREQ
6. DURATION
7. value in delay function--> delay(*this_value*);
8. more ... check the code!

We encourage you to study the code and play around with it!
