# Medical Emergency Real-time Monitoring System (WIP)

This project uses a B-L4S5I-IOT01A discovery kit as a wearable healthcare device, and the user is meant to recieve their health information through an app.

![Project Structure](시스템%20구성도%202.png?raw=true)

It is consisted of a STM32 project of the folder name "stm-aws_code", and an Android app project of the folder name "android-aws_app", and also a folder called "motion_detection" where the acceleration data was trained to deterimine the situation of the person.

The wearable device is used to detect medical emergencies, which could be fatal if not found early. It can read the acceleration info to detect if the user is falling down, and also can measure heart beat, and measure EMG.

##repository summary

motion detection: python(sklearn) code to train decision tree for motion detection
AWSlast: final integrated code

else: 가속도 센서, 아날로그 데이터 수집, aws 연결 등 세부 기능 구현
