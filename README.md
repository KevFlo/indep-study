# 4398 - Independent Study Project

## Create a app to count attendance of students from web-cam, and report the infromation on a website

---
## Approach:
    - [x] Create a script that will open up the webcame stream
    - [x] Find/Use model that detects humans in the stream
        + [ ] Store the cound of people on the stream after it ends
    - [ ] Connect the python script to a website
    - [ ] Configure the website for reporting attendance
---
To run this script you must run this command: ```python3 main.py -c True ```
>this will being the video stream from the web-cam and count the people in the frame
---
### Todo:
    -store the count of people in the video to a variable once the stream is cut off.
    -find a way to keep scrip running if web cam stream ends. (to store the count)
    -display the count on a website
    -website hosts the attendance and the script so it can run on x camera?