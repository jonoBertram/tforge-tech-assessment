# Section 2: Back-end development

### Question 1

> Explain your familiarity with backend development technologies like Node.js and Next.js. Provide examples of projects where you've worked on the back-end.

My back-end development experience is much more limited than front-end although this is by choice. Throughout my career, I have decided to focus my efforts on honing my front-end skills to become an expert in this field.

That being said, I have still built and maintained a few back-end projects including the user database and API for [Yoco Reseller](https://reseller.yoco.com/) and their product database. These projects make use of Django with graphene, Python, and graphql endpoints to interface with the front-end. I also worked on a visual web interface for database management using Django's templating tools for displaying tables with simple and effective navigation between them.

I also built a basic API around an existing database of guitars for a luthier whose site a built that you can view [here](https://jgsguitars.com/). This involved queries and mutations for fetching and filtering lists of guitars based on their type, age, and other properties. This project involved basic MySQL queries to interface with the old existing database that was then accessed via PHP on the front-end.

### Question 2

> Discuss your experience with Docker and its role in backend development and deployment.

I have worked extensively with Docker to containerise both front and back-end projects for portability between machines and hosting services. Docker has also allowed my team to create complex CI pipelines that we use for pre-merge testing and deploying staging environments.

Docker is also a great tool for reducing build times as it can cache third-party package folders that remain unchanged between each build.
The Docker Desktop tool also makes starting, stopping, and analysing containers easy for simple debugging and maintenance.
