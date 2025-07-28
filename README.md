# MongoShop_CI-CD
Streamlining My Node.js App Deployment with CI/CD 🚀📦

In this Project I have already made node.js application so with the help of youtube videos I made a CI/CD pipelines of my project. I used Jenkins to build entire pipelines

In this project I learn lot of things like :-
- Jenkins
- Master-slave concept
- Build a decalartive pipeline
- How to add eplugin with credentials like DockerHub
- Implement a ci/cd pipeline with groovy
  

📌 Different stages of pipelines ?
Code -----> Build -----> Test -----> Deploy

✍️ Code : Developers commit code to a shared repo like GitHub
🏗️ Build : Jenkins compiles,  resolve dependencies or assembles the code.
🧪 Test : Jenkins tests the code automatically to find bugs.
        - Unit tests (individual components).
        - Integration tests (combined modules).
        - Code quality checks (e.g., SonarQube).
🚀 Deploy: Jenkins sends the final, tested application to servers or the cloud for users to access.


----------------------------


🪄 In my project I Implement Jenkins (CI/CD) pipelines.
1️⃣ I have already made node.js app
2️⃣ Setup agent
3️⃣ Create a declarative pipeline
4️⃣ Write a entire pipeline (Groovy) 
5️⃣ Different stages : Greet, Code, Build, Test, Push to DockerHub, Deploy
6️⃣ Apply GitHub Webhooks (Whenever commit in repo , so automatically build pipeline)
