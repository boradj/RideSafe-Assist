Cyclist safety remains a critical concern in both urban and rural settings, where dense traffic and unpredictable
road conditions heighten the risk of accidents. This research introduces a compact, costeffective
real-time alert system that integrates computer vision and deep learning technologies to enhance
cyclist situational awareness. Central to the system is a raspberry pi, which processes visual
data from a camera module and proximity distance measurements from ultrasonic sensors. The you
only look once - fastest version 2 (YOLOFastestV2) object detection model is fine-tuned for detecting
potential hazards, including approaching vehicles, while estimating their speed and measuring safe distances.
Alerts are transmitted to cyclists via a mobile web application, ensuring prompt and actionable
feedback to improve safety.
The system harnesses edge computing to perform data processing locally on the Raspberry pi, significantly
reducing latency and removing reliance on cloud services. Rigorous real-world testing validated
the system’s performance, achieving high object detection accuracy, precise speed estimation, and realtime
alert generation within 66 milliseconds. These capabilities make it an effective advanced driver
assistance system (ADAS) tailored for cyclists.
The system demonstrated high responsiveness, with ultrasonic sensors delivering real-time proximity
data three times faster than the camera-based detection. This seamless integration allowed for realtime
updates, timely alerts, and continuous tracking of vehicles, ensuring robust performance even in
complex and dynamic traffic scenarios. This work advances the intersection of smart internet of things
(IoT), ADAS, and cyclist safety by presenting a scalable solution for diverse environments. By fostering
safer cycling conditions, the system promotes sustainable urban mobility and encourages the wider
adoption of cycling as a viable transport alternative.
