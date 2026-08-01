Real Time AI Voice Assistant Project Description and Deep Code Walkthrough

This project is a detailed voice assistant simulation created inside Google Colab using Python programming. The main goal of this project is to build a complete speech pipeline that handles voice communication. The program prints the conversation text on the screen and plays a clear audio answer between two different characters named Emily and Alex.

The project is implemented using pure Python libraries within the Google Colab environment. It utilizes the gTTS library which is Google Text to Speech to synthesize human like voices and the IPython display module to handle audio playback. The flow of the entire conversation is managed sequentially through controlled time delays which makes the script fully autonomous and lightweight without needing external cloud APIs.

The python code is written in a very simple and direct sequence. First I imported the speech recognition library to prepare the text sentences. I also imported the gTTS library to convert the prepared text dialogues into digital audio files. Finally I used the IPython display function to create the actual sound players on the laptop screen and imported time library to manage the dialogue speed.

The core of the project is a single python function named voice to voice assistant which manages the whole interaction. Inside the function the program prints a scenario message to explain the background of the two characters. Emily acts as a software engineer asking for technical career advice. Alex acts as an AI tech expert who gives her a professional technical roadmap.

For the programming implementation I created five continuous conversational steps inside the function. In each step Emily asks a question and the program calls the gTTS function to convert her text into an audio file. I selected the com top level domain for Emily so she speaks with a standard American accent. The code saves her sound as an mp3 file and uses the display Audio function with autoplay enabled to play it instantly.

Right after Emily speaks I added a specific time sleep function set to four or six seconds. This delay timer is a very important part of the code because it stops the voices from overlapping inside the web browser. It gives enough time for Emily to finish her question before Alex starts his response.

When the timer finishes Alex answers her question. The code creates a new gTTS object for Alex but this time I changed the top level domain parameter to co uk so he answers with a professional British accent. His sound is saved as a separate mp3 file and played automatically on the screen. Another six seconds delay timer is added after Alex finishes to let the conversation sound natural before Emily asks her next question.

The discussion between Emily and Alex covers five steps. First Emily asks where to start learning artificial intelligence and Alex tells her to learn Python and basic mathematics. Second she asks about libraries and he recommends NumPy and Pandas for data and Scikit Learn for machine learning. Third they talk about building real projects for GitHub repositories to show skills. Fourth they discuss deep learning neural networks for advanced computer vision tools. Finally Emily thanks Alex for the amazing roadmap and Alex wishes her good luck with her AI assignment project.

The final output demo video is uploaded in this repository under the name output video mp4. You can click directly on the video file in the files list at the top of this page to watch and hear the full voice conversation performance.

How to Open and Run this Project

To open the project repository and run the notebook you must follow these exact execution steps. First click on the python notebook file inside this repository which is named Voice Assistant Project ipynb. When the file opens look at the very top of the script preview window and you will see a prominent button that says Open in Colab. Click on this button and the web browser will automatically redirect you to the live Google Colab environment.

Once you are inside the Google Colab interface you will see the code blocks displayed on your screen. Go to the top horizontal menu bar of the page and click on the option named Runtime. A vertical dropdown menu will open containing multiple commands. Look through this menu and click on the option that says Run all. 

When you click Run all the environment will automatically connect to a remote server and begin executing the entire program from top to bottom. It will first install the required packages and then it will run the core voice function. Scroll down to the very last output section at the bottom of the page and you will see the text printing dynamically line by line. At the same time you will hear the voices of Emily and Alex speaking back to you from your computer speakers with their proper accents and perfectly timed pauses.
