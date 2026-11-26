## Hi, I'm Lyydi. Welcome to my page!👋

I'm a software development student at Oulu University of Applied Sciences. I have a background in IT recruitment consulting where I realized I wanted to actually take part in building something. I took the leap and found my passion!

At the moment I'm most interested in AI in software development, Cyber Security and Data. 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-LyydiLiinamaa-0A66C2)](https://www.linkedin.com/in/lyydi-liinamaa)

---

## 🔧 My skills

### Coding
- **Most used technologies:** React, JavaScript and TypeScript
- **Languages I have basic working knowledge in:**  Python, C++, C, Java, Kotlin, CSS and HTML
- **AI-assisted coding:** Generally my school work is manually coded and my own projects are AI-assisted. I use AI as a tool to work faster, while understanding and reviewing every line I ship.
- **Other:** GitHub, Docker, API basics

### AI
- **AI-assisted development:** AI as a daily tool in my own projects, with every line understood and reviewed
- **AI workflow automation:** Scheduled AI agent tasks (more below)
- **AI in projects:** LLM-based tagging and descriptions in the Name generator's data pipeline (more below) and an AI answering bot for short-term rental guest messages (in progress)

### Data
- **Tableau Desktop Foundations - Salesforce Certified:** Done in my free time out of interest in data visualization
- **Power BI:** Used daily as a recruitment consultant tracking sales and performance targets
- **SQL:** MySQL and PostgreSQL on projects

### Cyber Security
- **Security fundamentals:** Core concepts, common attack types and best practices 
- **Capture The Flag exercises:** TryHackMe
- **Linux command line:** Navigating and searching file systems, file permissions, processes, piping and text processing (grep, find, awk), SSH

---

## 💾 My favorite projects

Here are a couple of picks from what I have done during studies and in my free time. 

### [Movie App](https://github.com/oamk-group-14/movie-web-app)

Full-stack web application developed as a group for a Web Programming course. The application uses The Movie Database (TMDB) API to retrieve movie and TV show information. It is built with React, Node.js, Express, and PostgreSQL, with Docker used to run the application services. In addition to the required features, the project includes an AI-powered recommendation system that provides personalized movie and TV show suggestions based on each user's favorites and reviews.

My contributions included frontend authentication state management, account deletion, the "Now Showing in Theatres" feature, and the full group functionality: creating and deleting groups, join requests, member management, as well as adding movies and TV shows to group pages. I also built the home page and the favorite list sharing feature, and served as the team's Scrum Master.

### [Budgeting App (in progress)](https://github.com/Lylled/Expense-App)

Mobile application built in my own time to track personal and household expenses from receipts. It uses Google's ML Kit for on-device text recognition, combined with a native document scanner (Jetpack Compose via Expo's @expo/ui) that detects, crops, and deskews the receipt before reading it. The app is built with React Native, Expo Router, and TypeScript, with Supabase (PostgreSQL + Row Level Security) handling authentication and data storage, currently targeting Android. It differs from banks' own budget trackers by being more flexible and customizable.

### [Name Generator](https://github.com/Lylled/nimigeneraattori) ➡️ [Live Demo](https://lylled.github.io/nimigeneraattori/)

Web application built in my own time that generates period-appropriate Finnish names for characters in creative projects. The name lists are built with a Python data pipeline, and the front end uses React, TypeScript and Vite. It is deployed as a static site on GitHub Pages through GitHub Actions, with automated tests in Vitest. Beyond basic name generation, the app adds surnames that match the era and region, so a western Finnish character born in the early 1800s gets a patronymic and a farm name instead of a modern surname. It also supports Finland-Swedish and Orthodox naming traditions, style filters, and name cards showing each name's origin and a popularity chart. AI was used to help tag and describe the names before the site was published, so the site itself makes no AI calls, which keeps it fast and free to host.

### AI Agents

#### Job Market Technology Tracker
Scheduled AI agent that analyzes new junior IT job postings on Duunitori every week. A Python scraper (requests, BeautifulSoup) collects new postings and pre-classifies them, after which the agent reviews each one, filters out unsuitable roles and extracts required and nice-to-have technologies by category, such as Data, AI and Cyber Security. The results are added to two cumulative reports, one for roles requiring no experience and one for roles requiring less than two years, so the data grows week by week. Totals are verified with a script after each update.

#### Weekly IT News Digest
Scheduled AI agent that compiles the previous week's IT news every Monday into a structured digest covering cyber security, AI tools for developers, the Finnish IT job market and selected companies and public sector organizations. The instructions require the agent to verify publication dates, cite a source for every item and clearly separate confirmed news from rumors. Each item includes a note on why it matters to someone early in their IT career.

---

## 🤖 Next 

After completing the projects I'm working on at the moment, I want to focus on Capture The Flag exercises and developing more advanced AI functionalities in applications.  

**Projects I'm working on**
- Budgeting App (see above)
- [AI automated answering bot for short-term rental management](https://github.com/Lylled/automaticanswer)

**Projects I'm planning**
- Personal AI assistant
- Electricity price tracker
