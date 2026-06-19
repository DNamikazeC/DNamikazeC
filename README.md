<h1 align="center">Hi, I'm David Castillo <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
<img align="right" alt="GIF" height="160px" src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" />

Software Engineering student at Tecnológico de Antioquia (6th semester), based in Medellín <img src="https://flagcdn.com/16x12/co.png" alt="Colombia">.

Aspiring Data Engineer and Cloud Developer with a solid foundation in the software development lifecycle, databases (SQL Server, PostgreSQL), and Python. Experienced in optimizing and ensuring quality in data pipelines, combined with a C1 English level for effective global collaboration. Analytical, proactive, and focused on delivering results.

-  **Currently learning & mastering:**
  - AWS Cloud Architectures
  - Advanced Data Engineering pipelines with Python
  - ETL processes and Big Data fundamentals
- Outside of tech, I love watching movies, sketching tattoo designs, listening to music and visiting nearby towns.
-  Reach me at: <a href="mailto:davidcascua@gmail.com">davidcascua@gmail.com</a>

<a href="https://www.linkedin.com/in/davidcastilloc">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>

---

## My Skills Include

<h4> Data Stack & Programming Languages </h4>
<span>  
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
</span>

<h4> Databases </h4>
<span>
  <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white">
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white">
</span>

<h4> Frameworks & Libraries </h4>
<span>
  <img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB">
  <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white">
</span>

<h4> IDE & Data Tools </h4>
<span>
  <img src="https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
  <img src="https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white">
</span>

---

## Featured Projects

###  [RapidGo: Serverless Backend & Cloud Architecture](https://github.com/DNamikazeC/rapidgo-serverless)
*A cloud-native data and backend architecture migration project designed to transform a legacy monolithic system into a highly scalable, event-driven serverless infrastructure on Microsoft Azure.*

* **The Challenge:** RapidGo's legacy Node.js monolith was hitting critical performance bottlenecks during peak hours, causing >8-second API latencies and a 12% order cancellation rate, while incurring an inefficient fixed infrastructure cost ($4.2M COP/month).
* **The Solution & Optimization:** 
  * **Serverless Migration:** Re-architected the backend core using **Azure Functions** to achieve automatic event-driven scaling up to 500 req/sec, transitioning to a 100% pay-per-use model.
  * **NoSQL Database Engineering:** Authored architectural decisions (**ADR-02**) to migrate the persistence layer to **Azure Cosmos DB**. Engineered `/clienteId` as the logical partition key, physically grouping customer transactions to guarantee single-digit millisecond read/write latencies.
  * **API Management:** Centralized JWT authentication, throttling, and contract compatibility by routing traffic through **Azure API Management Gateway**.
* **Data & Tech Stack:** `Azure Functions` | `Azure Cosmos DB` | `API Management` | `Blob Storage` | `C4 Modeling` | `ADRs`

###  [FIFA World Cup Data Analysis & Predictive Modeling](https://github.com/DNamikazeC/world-cup-2026-analysis)
*A data-driven engineering and analytics project processing 50 years of historical World Cup data (832 matches) to model and predict front-runners for the 2026 tournament.*

* **The Challenge:** Aggregating, cleaning, and normalizing historical sports metrics spanning five decades of heterogeneous data, and designing a multi-variable scoring model to simulate future outcomes.
* **The Solution & Optimization:** Developed an end-to-end data pipeline using **Pandas** and **NumPy** for aggressive data cleansing, filtering, and structural transformation. Designed a custom scoring algorithm that aggregates historical win rates, stage progression, and goal differentials. Engineered interactive multi-dimensional data visualizations using **Plotly**.
* **Data & Tech Stack:** `Python` | `Pandas` | `NumPy` | `Plotly` | `Jupyter Notebook` | `Data Modeling`

###  [Eroa Orgánico ](https://github.com/DNamikazeC/eroa-organico)
*E-commerce web application inspired by a Colombian natural hair care brand, built with a focus on component-driven architecture and efficient state management.*

* **The Challenge:** Creating a seamless, highly responsive user experience for navigating product data and handling real-time cart state synchronization across components.
* **The Solution & Optimization:** Leveraged **React's Context API** to implement a centralized state management architecture for the global shopping cart, reducing redundant re-renders. Built a clean product data structure that allows instantaneous client-side category filtering.
* **Data & Tech Stack:** `React` | `Vite` | `Context API` | `TailwindCSS` | `React Router`

---

## Connect with Me

<a href="https://www.linkedin.com/in/davidcastilloc">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://www.instagram.com/david_castilloc/">
  <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" alt="Instagram">
</a>
<a href="mailto:davidcascua@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
</a>

###  GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=DNamikazeC&theme=radical&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://streak-stats.demolab.com/?user=DNamikazeC&theme=radical&hide_border=false)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=DNamikazeC&theme=radical&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

##  GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=DNamikazeC&theme=radical&no-frame=false&no-bg=true&margin-w=4)

<p align="center">
  <img src="https://raw.githubusercontent.com/DNamikazeC/DNamikazeC/output/github-contribution-grid-snake.svg" alt="snake">
</p>
