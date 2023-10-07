# wavemomentum

Python Version: 3.8.10
Pip Version: 21.1.1

Libraries:

mediapipe
opencv-contrib-python
streamlit
pyatuogui

## Inspiration
When viewing the Rythmhacks presentation, we noticed that sometimes there would be some human error in the timing of the slide changes. This inspired us to think of a solution. We instantly saw that some of the presenters were putting their thumbs up to signal the change, and so we thought, "Why can't a computer just detect the thumbs up", and thats exactly what we did. 

## What it does
WaveMomentum allows users to control their computers using simple hand gestures. We solve the issue of turning slides during a presentation, touching your screen with greasy or dirty hands, and not being fluent in using your keyboard due to disabilities. We fine-tuned the program to ensure that it could recognize hand movements accurately and quickly respond to user commands. The result is a program that can revolutionize the way we interact with computers, making it more intuitive and hands-free.

## How we built it
We used OpenCV to take a camera input from the computer, then we used Google's MediaPipe library to recognize the hand movements and gestures. We setup a Streamlit web app to customize the actions the user wants to be done. Once the hands were recognized, we interpreted the data and matched it with the user's customized actions. 

## Challenges we ran into
Installing packages was our biggest problem during this project. We had run into many compatibility issues when trying to install all our package and ended up only getting it to work on one device. Alongside the bad internet, this set us back 3 hours at the start of the hackathon.

One of the packages we ran into the most issues with was MediaPipe Model Maker, we were planning on training our own model of hand gestures. We tried extremely hard to download it, asking organizers, the internet, and AI. All of them were not able to solve our issue, this set us back additional time and required us to pivot greatly. 

## Accomplishments that we're proud of
Due to the many setbacks and frustration, we are very proud of the outcome of the **entire** project. 

Hand gesture recognition using MediaPipe. It is by far the most proud thing we accomplished, we stayed us an entire night researching, learning, and creating the entire system. 
Taking the coordinates from your hand using a hand tracking system to move the cursor.
Creating a Streamlit web app that allows you to control the functionality of the program.

## What we learned
How to use Google's MediaPipe to track and recognize hands and gestures.
How to use OpenCV to pair up with MediaPipe to supply a consistent video stream.
How to use Streamlit to create a web app and then take the data and apply it to the program.

## What's next for WaveMomentum

Creating custom keyboard shortcuts that can be used with the gestures.
Optimizing the hand tracking mouse cursor to perform better.
Training a model with more data to ensure fast and accurate detection with more gestures.
Hosting the website.
