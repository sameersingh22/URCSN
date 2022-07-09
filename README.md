
# Introduction
URCSN (University of Regina Computer Science Navigator) is an **unofficial** upcoming chatbot that provides information about the University's Computer Science department.

## Purpose
While registering for courses and program-planning, sometimes picking the right course for the next term can get confusing. It might get complicated if those courses are not offered in a given term, or there are multiple instructors/sections for the same course, etc. Recently, I was in a similar situation and felt a need for a tool/service where I could get information about the courses at one place.
Although it is available online, the information is scattered throughout the website, making it confusing. With the knowledge and skills I gained in my NLP class, I am planning to create a chatbot that can resolve most of such problems for future/current students.  

# Description
The chatbot URCSN will be based on the different resources mentioned at the end of this document. It will involve the use of web scraping to generate lists of data depending on user input.


## Features
The chatbot will initially welcome the user and display a list of CS (Computer Science) programs offered at the University of Regina. The user can select any relevant program and the chatbot will reply with a menu asking the user what function to use for the selected program: 
  
1. **Course Description:** Generate a list of detailed descriptions of all the mandatory courses required to complete the selected program.
2. **Instructor Feedback:** Display the most recent feedback for instructors left by students on the instructor-ratings website RateMyProf. 
3. **Create a schedule:** Create multiple potential schedules with the given courses for a given program. 

## Constraints and Assumptions
The goal of this project is to apply my knowledge gained from my NLP class as well as the 
independent research I did for web scraping, chatbots, etc. The project is intended to be completed in a 2-month period. 
Since I am new to AI development, time and lack of in-depth experience are the most limiting factors.

## Intended Audience
Prospective future students can use this chatbot to browse through the current CS programs offered at the University of Regina and decide which program to apply for. Current students can use the chatbot to pick courses to register for the upcoming terms.


# References

Following is a list of tools and resources which I am planning to use as a reference for my project:

 - Paper: [A Neural Chatbot with Personality](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/reports/2761115.pdf)
 - Article: [Creating a Chatbot with Deep Learning, Python, and TensorFlow](https://pythonprogramming.net/chatbot-deep-learning-python-tensorflow/)
 - Tool: [Rasa: An open source machine learning framework for automated text and voice-based conversations](https://rasa.com/)
 - Article: [A Practical Introduction to Web Scraping in Python](https://realpython.com/python-web-scraping-practical-introduction/)


