---
title: "Event 2"
date: 2026-06-13
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Summary Report: “FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture”

### Event Objectives

- Help students better understand career directions in information technology and cloud computing.
- Share practical insights into the real work of a DevOps Engineer in a business environment.
- Introduce how to design a scalable URL Shortening Service on AWS.
- Provide information about AWS community programs such as First Cloud AI Journey, AWS Student Builder Group, AWS Community Builder, and AWS Partner.
- Share real-world experience about the Data Analytics Engineer role, career development mindset, and working culture in multinational corporations.
- Help students prepare better in terms of technical skills, system thinking, communication, and adaptability for real working environments.

### Speakers

- **Trong H. Truong** – DevOps Engineer @ Endava Vietnam
- **Đinh Trung Kiên** – Lead Developer at Startup
- **Nguyễn Minh Thọ** – Student
- **Danh Hoàng Hiếu Nghị** – AI Engineer, AWS Community Builder, AWS Student Builder Group Leader
- **Đạt Phạm** – Data Analytics Engineer
- **Cường Nguyễn** – Process Engineer

### Key Highlights

#### Real-world perspective on the DevOps Engineer role

The DevOps sharing session helped me understand that DevOps is not simply about writing CI/CD pipelines, deploying Docker or Kubernetes, or fixing production issues at midnight. In reality, DevOps is closely related to systems, processes, automation, operations, and supporting development teams to work more efficiently.

Key points included:

- DevOps is not only a collection of tools such as CI/CD, Docker, Kubernetes, cloud, or monitoring.
- DevOps work requires understanding how applications are built, tested, deployed, logged, and configured across different environments.
- Fundamental knowledge such as Linux, networking, Git, CI/CD, Python or Golang, and containers is very important.
- DevOps engineers need to ask “why” before asking “how”.
- Communication is an important part of the job because DevOps often requires collaboration with different teams.
- A good DevOps engineer does not only know how to use tools, but also understands systems, automates repetitive work, and makes things clearer for the team.

#### Designing a URL Shortening Service on AWS

The presentation about the URL Shortening Service helped me understand how a URL shortener can be designed on AWS with scalability in mind. Starting from a simple flow between user, frontend, backend, and database, the session expanded into a more practical architecture using services such as CloudFront, AWS WAF, Amazon Amplify, Amazon ECS, Amazon ElastiCache, and DynamoDB.

Important points included:

- A URL Shortener converts a long URL into a shorter link that is easier to share.
- The basic flow includes users submitting a URL, the frontend sending the request to the backend, and the backend generating a short code and storing it in a database.
- A simple implementation is easy to build and has low cost, but it may face issues such as security limitations, latency, single point of failure, and poor scalability.
- The frontend can use Amazon CloudFront, AWS WAF, and Amazon Amplify to distribute content, protect the system, and simplify deployment.
- A Key Generation Service can pre-generate short codes and store them in Redis through Amazon ElastiCache to reduce load during high traffic.
- The Backend Service can use Amazon ECS, Spring Boot, Redis cache, and DynamoDB to handle link creation and redirection.
- The architecture can apply the cache-aside pattern to improve read performance and reduce direct database queries.

#### Journey from First Cloud AI Journey to AWS Partner

The sharing session by Danh Hoàng Hiếu Nghị gave me a clearer view of how students can join the AWS community and develop their career path in the cloud field. The session showed that getting the first job is only the beginning. After that, each person still needs to keep learning, gaining experience, and shaping their own direction.

Key highlights included:

- First Cloud AI Journey is a program that helps students approach cloud and AI in a more structured way.
- After starting a career, each person can grow in different directions such as Solutions Architect, DevOps Engineer, Platform Engineer, or Software Engineer.
- AWS Student Builder Group is an environment where students can learn, connect, and grow with the AWS community.
- AWS Community Builder Program helps technology enthusiasts share knowledge and contribute to the community.
- AWS Partner creates opportunities to work more deeply with the AWS ecosystem and businesses using cloud.
- Networking, continuous learning, and building a personal brand on LinkedIn are also important parts of career development.

#### The real work of a Data Analytics Engineer

The Data Analytics Engineer session helped me understand that data analytics work is not only about creating reports or dashboards. Depending on the domain, business model, and supported department, a Data Analytics Engineer can be involved in many different real-world problems.

Main points included:

- In an operations-focused business, a Data Analytics Engineer may build daily, weekly, monthly, and quarterly reports to track performance.
- Dashboards help businesses monitor data trends, detect anomalies, and support decision-making.
- Data analysis is not only about presenting numbers, but also about finding root causes and proposing solutions.
- In factory or manufacturing environments, data from machines, operations, and IoT devices can be analyzed to optimize costs and improve performance.
- A Data Analytics Engineer needs to collaborate with multiple departments to solve practical business problems.

#### Skills and mindset for third-year and fourth-year students

This part emphasized that students who are preparing to enter the job market need more than technical knowledge. Skills such as critical thinking, communication, data storytelling, and problem solving are very important in a business environment.

Important ideas included:

- Critical thinking helps students analyze information objectively and make reasonable judgments.
- Communication skills help present ideas and analysis results clearly to different audiences.
- Data storytelling helps turn dry numbers into meaningful insights that can drive actions.
- Problem solving requires identifying challenges, analyzing root causes, and proposing suitable solutions.
- When preparing reports, students should not only present numbers but also understand why changes happen and what can be improved.

#### Culture in multinational corporations

The MNC culture sharing session helped me understand how multinational corporations operate, recruit, and build their working environment. Corporate culture is not just a slogan. It reflects how people in an organization think, work, and solve problems.

Key points included:

- A standard recruitment process in MNCs usually includes CV screening, initial interviews, ability tests, technical interviews, and culture-fit evaluation.
- No-Blame Post-Mortem culture in technology environments focuses on finding the root cause of incidents instead of blaming individuals.
- Caring and Inclusive culture puts people at the center, respects diversity, and encourages continuous improvement.
- Students need to prepare English ability, logical thinking, presentation skills, and the ability to work with international standards.
- To work well in a global environment, each person should learn international standards while still keeping their own identity and suitable personal mindset.

### Key Takeaways

#### Career mindset

- There are many career directions in the technology industry, such as DevOps Engineer, Software Engineer, Platform Engineer, Solutions Architect, and Data Analytics Engineer.
- Getting the first job is only the beginning. What matters more is continuous learning and developing capabilities through each stage.
- Students should actively build practical experience, a portfolio, and the ability to explain what they have done.
- Career development should focus on improving real capabilities instead of only chasing job titles.
- A career path can start from being an executor, then grow into an active learner, a problem solver, a system thinker, and eventually a leader.

#### DevOps and system thinking

- DevOps is not only about knowing many tools, but also about understanding how systems operate.
- Fundamentals remain important because tools can change over time.
- System thinking helps developers look at problems from a broader perspective instead of only handling small tasks.
- Automating repetitive work helps reduce errors and improve team efficiency.
- AI can support work, but it should not replace personal thinking and understanding.

#### Cloud architecture on AWS

- A simple system can face difficulties when scaling if the architecture is not designed properly.
- CloudFront, WAF, Amplify, ECS, ElastiCache, and DynamoDB can be combined to build a system with better performance and scalability.
- Caching helps reduce latency and lower database load.
- Pre-generating short codes with a Key Generation Service helps the backend handle requests faster.
- When designing a system, it is necessary to consider security, performance, cost, availability, and scalability.

#### Data Analytics and corporate culture

- Data Analytics is not only about visualizing data, but also about finding insights and proposing actions.
- Data storytelling makes analysis results easier for decision-makers to understand.
- MNC environments require professionalism, clear communication, critical thinking, and adaptability.
- A good corporate culture focuses on improving systems instead of blaming individuals.
- Working in a global environment requires continuous learning and the ability to follow high standards.

### Development Workflow

- When building a software system, it is important to start by understanding requirements and user flow.
- A simple architecture should be evaluated in terms of advantages, disadvantages, and scalability before real implementation.
- Frontend, backend, cache, database, and security layers should have clear responsibilities.
- In DevOps, the workflow of build, test, deploy, logging, and monitoring should be clearly understood.
- In Data Analytics, the workflow should start from understanding the business problem, collecting data, analyzing it, visualizing results, and proposing solutions.
- In business environments, workflows should be transparent, communication should be clear, and continuous improvement should be encouraged.

### Applying to Work

- Strengthen fundamental knowledge such as Linux, networking, Git, CI/CD, containers, and cloud to prepare better for technical tasks.
- When working on frontend or API integration in the GreenLens Kids project, pay more attention to system flow, logging, error handling, and user experience.
- Apply a DevOps mindset by understanding how applications are built, run, configured, and deployed.
- Use the URL Shortening Service architecture as a reference to learn how to design a system with clear frontend, backend, cache, and database layers.
- When working with data or progress reports, do not only record results but also analyze causes and suggest improvements.
- Improve communication, teamwork, and project presentation skills to prepare for business environments.
- Take advantage of AWS community programs to continue learning, connecting, and expanding career directions.

### Event Experience

Attending the **“FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture”** was a very useful experience for me. The event did not only provide technical knowledge about DevOps, cloud architecture, and data analytics, but also helped me understand more about career paths, corporate culture, and the skills I need to prepare before entering the workplace.

#### Learning from experienced speakers

- The speakers shared many practical experiences from DevOps, AI, cloud, data analytics, and business environments.
- The sharing sessions helped me understand the difference between what is learned in school and what is required in real work.
- Examples about DevOps, the URL Shortener on AWS, and Data Analytics helped me visualize how technical knowledge is applied in companies.
- The sharing about the AWS community journey gave me more motivation to continue learning and participating in technology activities.

#### Hands-on technical exposure

- I understood more clearly that DevOps is not only about deploying code, but also about systems, automation, monitoring, and communication with the team.
- I learned how a URL Shortening Service can be designed on AWS using components such as CloudFront, WAF, Amplify, ECS, ElastiCache, and DynamoDB.
- I realized the role of caching, pre-computation, and separation of concerns in building scalable systems.
- The Data Analytics session helped me understand that data reports should include root-cause analysis and suggested solutions, not only numbers.

#### Leveraging modern tools and platforms

- The event helped me see more clearly the role of AWS services in building real-world systems.
- Cloud tools and platforms are not only used for deployment, but also support security, performance optimization, and scalability.
- Programs such as AWS Student Builder Group and AWS Community Builder can help students continue learning and connect with the community.
- Understanding different roles in the industry gave me more direction when choosing my future development path.

#### Networking and discussions

- The meetup created opportunities to listen to different perspectives from experienced people in the industry.
- The career and MNC culture sessions helped me understand how to prepare a CV, portfolio, interview skills, and communication skills.
- The event emphasized the importance of learning from the community and building professional connections.
- I realized that talking with experienced people can help students avoid common mistakes and choose a better direction.

#### Lessons learned

- Strong technical fundamentals are more important than only knowing many tools.
- DevOps requires system thinking, communication skills, and the habit of automating repetitive work.
- Cloud architecture design needs to consider security, performance, cost, and scalability.
- Data Analytics requires critical thinking, communication, and the ability to tell stories with data.
- Multinational business environments require professionalism, adaptability, and a continuous improvement mindset.
- Students should actively learn, join communities, and build practical experience early.

> Overall, the **FCAJ Meetup – Career, DevOps, AWS Architecture & MNC Culture** gave me many practical perspectives on the technology industry. After the event, I understood more clearly that to grow in this field, students need not only to learn new technologies but also to build strong fundamentals, develop system thinking, communicate effectively, and continuously improve themselves. The lessons from this event can be directly applied to my internship process, the GreenLens Kids project, and my long-term career direction.