## About me 👋

I am a passionate Software Engineer with a strong interest in backend development and data management. I love solving complex problems, learning new technologies, and collaborating with driven people to create meaningful solutions.

* 📍 Based in Lausanne, Switzerland 🇨🇭
* 🌍 Fluent in french (native language), English (C1+) and learning German (B2)
* 🧠 Always curious, constantly improving, and eager to take on technical challenges
* 💬 Reach me on [LinkedIn](https://www.linkedin.com/in/eva-ray-4540b5186/)

## Technical Focus

* **Languages**: Java, C++/C, Python, SQL, Javascript/HTML/CSS, Typescript, Haskell, Scala, Kotlin, Rust, Go.
* **Databases**: PostgreSQL, Couchbase, Neo4j, Elasticsearch, PostgreSQL JSONB, Hibernate ORM.
* **Frameworks**: Quarkus, React, Vue.js, Next.js.
* **Machine Learning**: Tensorflow, sickit-learn, CNN, classification, regression, SVM, ML on big data.
* **Cloud, Containerization  & Tools**: AWS, Azure, Google Cloud, Azure, Docker, Kubernetes, Terraform, Git, Maven, Gradle.

## Projects

### 📊 Bachelor Thesis: Semi-Structured Data Benchmark

For my Bachelor’s thesis (graded 6/6), I developed a platform to benchmark the performance of queries on semi-structured data across different storage models: classical PostgreSQL (relational), PostgreSQL with JSONB, and Couchbase. The platform automates workloads, collects metrics such as latency and cache efficiency, and analyzes how data modeling choices affect document search performance. I also performed an in-depth comparison of the performance across the three models.

* **Features**: Benchmark automation, workload configuration, performance metrics collection and presentation, Web interface, comparative analysis.
* **Dataset preparation**: Retrieved the Yelp Open Dataset, designed "schemas" for all three database models (PostgreSQL relational, PostgreSQL JSONB, Couchbase), and populated them with data.
* **Backend**: Implemented in Java with a focus on modular, maintainable, and extensible code.
* **Frontend**: Built in JavaScript using Vue.js for configuring and visualizing benchmarks.
* **Deployment**: All databases deployed on a VM in isolated environments, using Docker for consistency and reproducibility.
* **Detailed comparative analysis**: Studied the impact of query writing, read and interpreted execution plans, analyzed join algorithms, and assessed the effect of indexing on performance.

[**➡️ View Project Hub on GitHub**](https://github.com/evarayHEIG/tb-benchmark) **|** [**➡️ Read the Report**](https://github.com/evarayHEIG/tb-benchmark/blob/main/doc/report.pdf)

### 🌱 PlantKeeper: Plant Management Application using IoT

PlantKeeper is a system that monitors the state of home plants using IoT sensors and a centralized backend. It collects environmental data such as humidity and temperature, stores it in a PostgreSQL database, and provides users with a web interface to visualize measurements and manage their plants. This project has been realized for the summer group project of HEIG-VD. The code is organized accross 4 repositories: frontend, backend, Iot and servers.

**My job**: Frontend and backend developper.
**Technologies**: Typescript, React, Tailwind CSS, Axios, React Router, NestJS, TypeORM, JWT tokens, CI/CD.

[**➡️ View Project Hub on GitHub**](https://github.com/Plant-keeper) **|** [**➡️ Watch Presentation Video**](https://www.youtube.com/watch?v=sNf7IPKWoTk&t=1s)

### 🐜 Ant Colony Simulation Using Mesa

This project simulates an ant colony using the Mesa library, allowing users to visualize how ants behave and interact within a dynamic environment. This project demonstrates the agent-based paradigm, visualizing how individual agents (ants) interact with their environment and with each other to produce emergent collective behavior.

**Features**: Users can adjust parameters such as the number of ants, food sources, and their distribution from the home screen. The simulation illustrates ants moving, following pheromone trails, collecting food, and returning to the nest, while displaying the total food gathered and the number of simulation steps.

**Technologies**: Python, Mesa Library.

[**➡️ View Project on GitHub**](https://github.com/Sainane/PLM_Project)

