This project is part of vibe coding workshop in SDAIA academy and DAICO at @ King Saud University

# Roaya-Career-Platform

Hello! Welcome to Roaya, a website our group built to help high school students in Saudi Arabia figure out which university major suits them best. Choosing a major can be stressful, so we designed this site to act as a virtual career advisor.
#SDAIA_ACADEMY #VIBE_CODING_WORKSHOP #DAICO #SDAIA 

## What Our Website Does

* **A Quick Quiz:** We created a 20-question assessment covering interests, personality, skills, work preferences, values, and goals.
* **Smart Matching:** The site uses the student's answers and their high school track to calculate a compatibility score for different majors.
* **Top Majors:** After the quiz, the dashboard shows a ranked list of the best 10 matches, including details like expected salaries, market demand, and Vision 2030 alignment.
* **University Suggestions:** We included specific Saudi universities tailored to the student's gender and city, plus the required Qudurat and Tahsili scores.
* **Visual Charts:** We used Chart.js to map out the user's personality traits on a radar chart and display progress bars for their skills.
* **Roadmap:** A step-by-step timeline guiding the student from high school to graduation.
* **Chat Advisor:** There is a built-in chat interface. It currently runs in a safe demo mode, but it is set up to connect to an AI backend to answer specific questions.

## How We Built It

We built this website using a "vibe coding" approach. Instead of getting bogged down in rigid planning or heavy frameworks, we focused on the flow of the project. We iterated quickly, using AI code assistants to help write the boilerplate and shape the logic on the fly, allowing us to just focus on making something that works well and looks good.

* **Core Tech:** HTML5, CSS3, and JavaScript.
* **Styling:** We used pure CSS with custom variables to keep things simple.
* **Typography and Icons:** We used the Cairo font from Google Fonts and custom inline SVG icons.
* **Charts:** We added Chart.js for the visual data.

## Live Demo

We have deployed the website so you can easily try it out! 

Check out the live version here: https://alanoud-alotaibi.github.io/Roaya-Career-Platform/

## A Note on Security and the AI Chat

If anyone wants to expand on our project and connect a real AI model to the chat, please be careful.

* Do not put your API keys directly into the HTML file.
* You will need to set up a secure backend to hold your keys, and then update the CHAT_ENDPOINT link in our index.html script.
* We also included a strict Content Security Policy (CSP) in the code to protect the site and keep data safe.

## Disclaimer

The acceptance rates, salaries, and university details we hardcoded into the site are estimates meant for general guidance. Students should always check official university websites and admission portals for accurate information.
