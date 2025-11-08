# News-feed-application
    

---

markdown
📰 News Feed Application

A simple web-based application that fetches and displays real-time news headlines using *Java Servlets* and the *NewsAPI*.

---

📌 Features

- Fetch top headlines using NewsAPI
- Display live news titles and descriptions
- Simple HTML user interface
- Built using Java Servlets (J2EE)
- Easy to expand with categories and personalization

---

🛠 Technologies Used

- Java Servlet (J2EE)
- HTML & CSS (Basic UI)
- NewsAPI (RESTful API)
- Apache Tomcat (Web server)
- Eclipse / IntelliJ (IDE)

---

📁 Project Structure


NewsFeedApp/
├── WebContent/
│   ├── index.html
│   └── WEB-INF/
│       └── web.xml
├── src/
│   └── NewsServlet.java


---

🚀 How to Run the Project

1. *Get API Key*  
   Register at [https://newsapi.org](https://newsapi.org) to get a free API key.

2. *Replace API Key*  
   In `NewsServlet.java`, replace:
   java
   String apiKey = "YOUR_API_KEY";
   

3. *Deploy on Tomcat*  
   - Build the project in Eclipse/IntelliJ
   - Deploy the WAR or folder on Apache Tomcat

4. *Open in Browser*  
   Visit: `http://localhost:8080/NewsFeedApp/index.html`  
   Click on *"Show News"* to view latest headlines

---

🧪 Sample Output

