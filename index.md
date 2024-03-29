---
layout: cv
title: Jay Mellor
---
# Jay Mellor | Software Engineer

Morpeth, Northumberland  
07910 740908  
jaymellor25@gmail.com  
[https://www.linkedin.com/in/jay-mellor-496533101/](https://www.linkedin.com/in/jay-mellor-496533101/)  
[https://github.com/JayMellor](https://github.com/JayMellor)


## Profile
A dedicated and driven developer, who strives for the best solution in terms of readability, reusability and security.  
Also a keen researcher and trainer - eager to learn new skills and practices and share the knowledge in the team.  
Known for a quality-focused mindset be it at component or architectural level.

## Technical Skills

| **Frontend**    |                       | **Backend**           | **Other**              |
|:----------------|:----------------------|:----------------------|:-----------------------|
| TypeScript      | Jest                  | Python                | Git                    |
| React           | React Testing Library | Django                | Docker                 |
| React Query     | MSW                   | Django REST Framework | GitLab CI              |
| React Hook Form | Redux                 | PostgreSQL            | REST                   |
| Material UI     | SCSS                  | pandas                | Functional Programming |
| Angular         | HTML                  | Celery                | Scrum                  |
| NgRx            |                       | Django Signals        | AWS EC2                |
| RxJS            |                       | Asyncio               | AWS S3                 |
| Karma           |                       | Pytest                |                        |
|                 |                       | Selenium              |                        |

## Professional Experience

`2023-present`
**Hofy Ltd** Senior Software Engineer

_Technologies used: TypeScript, React, Go, PostgreSQL_

Hofy Ltd provides a rental and purchasing services to companies to equip remote workers. Also handles transfer of company assets, repairs and warranties.

- Implemented functionality to enable Store & Reuse in the platform (https://www.hofy.com/blog/store-reuse-hofy-devices).

- Spearheaded updating existing tests to use the Builder pattern. This allowed more extensible test packages and more reliable tests as database manipulation is abstracted away

- Challenged existing practice around paginated responses, ushering adoption of using a generic paginated response. This ensures conformity of HTTP responses and reduces risk of errors caused by manual duplication of code

`2021-2023`
**EY** Senior Full Stack Developer

_Technologies used: All specified technologies in Technical Skills_

Maintainer and Subject Matter Expert of the Business Influencer Platform (BIP), the name of the HR culture transformation platform following Tao Leadership's acquisition by EY.

- Optimised survey analytics pipeline using pandas and queryset aggregation bringing a 2 hour run down to 2 minutes while also making the code easier to manage and test. This allowed greater confidence in the system to produce data-driven insights at scale

- Optimised the key network graph visualisation on the platform by using hash maps and adjacency lists, allowing a 50,000 node graph to be rendered and re-rendered in under a second, where it timed out previously. This allowed for the connections of a large company to be displayed in granular detail on a web browser

- Implemented timezone support for the survey scheduling system, allowing 'sprints' of surveys to be sent out in consistent dates and times for a recipient time zone

- Trained and supported consultants using the platform to support clients, covering the lifecycle of scheduling surveys, checking invite output and engagement, and finally accessing aggregated results

- Shared knowledge in the team about our code and data architecture, allowing developers to understand the flow of the application and data scientists to know what data schemata we expose

`2019-2021`
**Tao Leadership Ltd** Full Stack Developer

_Technologies used: All specified technologies in Technical Skills_

Tao Leadership Ltd was a small (7-8 people)  HR consultancy that used Data Science insights from survey results to drive culture change. It was acquired by EY in 2021. 

- Part of a small development team (2-3 people), meaning the role covered entire development cycle, including:
	- Collecting requirements from the stakeholder
	- Designing UI mockups
	- Implementing
	- Testing
	- Deployment to demo and production environments
	- Training the client on functionality
	- Managing client queries and bug reports
	
- Able to quickly pivot implementations and projects according to quickly changing requirements from the stakeholder. We worked in a cadence of 1-week sprints to handle the everchanging workload

- Developed a sophisticated role-based permissions system ensuring users could only view and manage data they were authorised to. This allowed greater autonomy in user management, clearer boundaries for different user roles and ensuring the system could remain multi-tenanted.

- Implemented a data uploader, allowing user and demographic data, and later survey answers from 3rd party systems, to be uploaded en masse into the system in a reliable way, flagging errors or warnings when they occured. This allowed scalable support of clients engagements and insurance of their data's validity on the system.
	
- Rearchitected existing survey system by removing redundant Django models and Celery tasks and consolidating functionality into a smaller core. This allows for simpler operational maintainance of daily surveys (a key product) while increasing code readability and test coverage

- Built communication data analysis tool with Django (in part using TDD) to query a Microsoft Graph endpoint and store its consolidated results on a client's cloud instance. This allowed for consensual retrieval of client metadata to provide a more accurate picture of their interactions as used in culture change

- Developed a D&I dashboard in Angular for a client to learn their company's segregations and prejudices resulting from anonymously and consensually collected data. This makes use of data manipulation on both the frontend and backend to display data in an intuitive manner having been produced by an AWS Lambda pipeline

- Trained clients on culture transformation platform for their role in guiding their leaders in culture change. This allows for increased product knowledge by the client, in turn reducing misunderstanding and data errors

- Led the effort to increase test coverage and move to behaviour-driven unit testing, making the application more reliable and understandable

`2016-2019`
**Kerridge Commercial Systems** Software Engineer

_Technologies used: KCML, CVS, Oracle, SSH_

Maintained a desktop ERP application written in proprietary KCML (simlar to C++) which queries an Oracle database. The application is hosted on client or third-party servers.

- Optimised client ERP operations by systematically allocating relevant products to a picker in a warehouse through use of precise SQL queries and providing simple design and UX. This increased the client's visibility and efficiency of warehouse throughput

- Enabled client visibility and insight on project expenses by allowing Purchase Orders to be allocated to a project, adding restrictions on the Purchase Orders relating to the budget of the project and providing a dashboard for the management of projects

- Mentored and trained the development team through sharing product and programming knowledge, pair-programming and hosting confidential one-to-one meetings. This allowed for greater knowledge transfer and increased psychological safety in the team

## Personal Projects / Technical Interests 
- A filter dropdown with extensive state management in React: [https://github.com/JayMellor/react-erp](https://github.com/JayMellor/react-erp)
- A simple Blog Engine written in Elm: [https://github.com/JayMellor/BlogEngineElm](https://github.com/JayMellor/BlogEngineElm)
- Exercises from learning Clojure through [Clojure for the Brave and True](https://www.braveclojure.com/clojure-for-the-brave-and-true/): [https://github.com/JayMellor/cftbat-main](https://github.com/JayMellor/cftbat-main)
- Recipes and code from learning Common Lisp with [Practical Common Lisp](https://gigamonkeys.com/book/) and [CLOG](https://github.com/rabbibotton/clog): [https://github.com/JayMellor/common-lisp-recipes](https://github.com/JayMellor/common-lisp-recipes)
- I enjoy using Emacs when I can. This CV was written using Markdown on Emacs and pushed to my GitHub repository!

## Academic Achievements

`2014-2015`
**Durham University** Master of Science in Particles, Strings and Cosmology **Merit**  
- Authored paper on Spinor Helicity Formalism, Amplitudes and Polytopes
- Presented a technical Particle Physics lecture on the Standard Model to a lay audience

`2010-2014`
**University of York** Master of Mathematics **2:1**  
- Achieved 80-90% in C++ courses
- Completed two basic Russian Language courses

`2008-2010` **A-Levels** A in Maths and Physics and B in Further Maths  
`2008-2009` **AS-Levels** A in Chemistry and B in Computing  
`2003-2008` **GCSEs** 10 A\*-Cs including A\* in Maths and Chemistry and A in Physics

## Personal Interests
- Reading Maths and Lambda Calculus/Logic books
- Reading science-fiction and fantasy books (Asimov at present)
- Gaming (souls-likes and metroidvanias are my faviourite)
- Cooking and eating curry 😋


