# ContentModeration

## Content Moderation for Online Chat Application

In today's world, it is a well known fact the internet and social media can be used to influence opinions and spread hate. Although the platform is not to blame, popular brands like facebook lose customers and their usage statistics go down because many people find some content offensive or inappropriate. In the recent past, people have been very vocal about their opinions, and have been posting offendable posts. This has caused social unrest and even riots between various sections of the society.

User generated contents contains different types of opinions and expressions through written texts, images or videos. And such contents may also contain objectionable visuals or which is not favorable for many people viewing such contents.

## Why Content Moderation is important
Moderating the content on social media websites is important, as now such platforms are used to promote the business, products and brands and such spam contents can disappoint other customers and discourage them to either stay away from such platforms or minimize the use of social media sites.

## Our Solution
Our idea is to develop a filter which can be embedded in any chat system or social media to prevent cyberbullying, hate spread, obscenity etc.

We have came up with a AI based Content Moderation model which is deployed as an API and it can be easily used in any Web or Mobile based platforms.

## Process Flow
For the image data, we are checking for any inappropriate text in the image or whether the image contains violence. The API checks the same for audio and video data aswell . Apart from images and videos of violence, It will also check for sexual or nudity related contents like, sexual activities, pornography, offensive signs, stripped images of people, especially females with revealing dresses and erotic gestures that are against the community of the chat platforms. In case of text data, along with checking for hatefull speech , the API will even check for any malicious links in the text in order to prevent cyberattacks such as phishing attacks. It will also check for spam messages/mails with circulates in online chat plaforms in the form of fake advertisements,self promotion etc.

## Architecture Diagram
![picture alt](https://github.com/Slainteee/Jatayu-ContentModeration/blob/master/documents/architecture.png)

## Tech Stack
1. Languages : Python. We will use Python basically for everything, from Modeling to ETL
2. AI/ML : Pytorch/Tensorflow(for most Deep Learning Tasks) and Scikit-Learn(Our go-to for most Non DL Tasks
3. NLP : NLTK/spaCy for extracting features from the text data.
4. OCR : For extracting Text from images, We rely on Tesseract OCR Engine.
5. Speech Recognition : Analysing Audio input can be achieved through Speech to text Conversion. We have used Sphinx/Google Speech Recognition for the same.
6. Version Control : Github is the best choice for any group project for code control and tracking.
7. Additional Libraries: Pandas, Numpy, MatplotLib
8. Google Colab for GPU support

### To Run
-> Clone the repo
```
git clone https://github.com/KKhushhalR2405/Content_Modearation_API.git
```
-> Navigate to the working directory
```
cd Content_Moderation_API
```
-> Create a virtual envirovnment (for windows)
```
python -m venv venv
```
-> Activate the Virtual Environment (for windows)
```
venv\scripts\activate
```
-> Install the required libraries using requirement.txt file
```
pip install -r requirements.txt
```
-> Run the API file using command prompt
```
python app.py
```
-> Open cmd again and change the directory
```
cd Web-Frontend
```
-> Run the server file
```
python server.py
```
-> Check the working of the API by using the webapp

-> Open chrome
```
localhost:1025
```
