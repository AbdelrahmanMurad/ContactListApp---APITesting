# API Testing Project

## Project Week Overview

This is a 5-day collaborative project where QAs will work in groups of 4 to simulate a real-world software development environment. Teams will follow **Scrum methodology**, adopting its key ceremonies to reflect agile workflows.

### Scrum Meetings

- **Sprint Planning**  
  Duration: 2 hours (Day 1)  
  Objective: Understand project requirements, analyze scope, and assign tasks.

- **Daily Scrum**  
  Duration: 10 minutes daily  
  Objective: Share progress, upcoming tasks, and blockers.

- **Sprint Review**  
  Duration: 1 hour (Day 5)  
  Objective: Present work, discuss challenges, and gather peer feedback.

---

## Weekly Timeline

| **Day** | **Stage** | **Goals & Deliverables** |
|--------|-----------|---------------------------|
| **Day 1** | Learn about Requirements → Analysis | - Document explaining how each API is triggered from the UI  
- Trello board setup with tasks  
- Postman workspace created and shared  
- List of questions or ambiguities |
| **Day 2** | Design | - Design **positive** and **negative** test cases for each API using Excel |
| **Day 3** | Implementation (Create API requests and environment variables) | - Postman Collection with organized folders and requests covering all test cases |
| **Day 4** | Implementation (Create assertions for each request) | - Add assertions (tests) for each API request  
- Run collection and ensure zero failures/errors |
| **Day 5** | Presentation | - 20-minute team presentation covering all deliverables |

---

## Application Under Test

- **App:** [Contact List App](https://thinking-tester-contact-list.herokuapp.com/)  
- **API Documentation:** [Contact List Documentation](https://documenter.getpostman.com/view/4012288/TzK2bEa8)

### Team Assignments

- **Team 1:** Focus on **Contacts APIs**
- **Team 2:** Focus on **Users APIs**

---

## Tools Used

- Trello
- Postman
- Microsoft Excel

---

## Guidelines

- Create a **new Postman workspace** and invite all team members.
- Set up a **new Trello board**:
  - Create a card for each API
  - Assign tasks clearly
- Ensure Postman Collection:
  - Is well-structured and organized
  - Includes requests for all relevant API endpoints
  - Contains **tests in the "Tests" tab** (JavaScript assertions)
- Use **environment variables** throughout the collection (e.g., base URLs, tokens)

---

## Tips

- **Positive Test Case:**  
  Example: Send a POST request with all required fields in the JSON body.

- **Negative Test Case:**  
  Example: Send a POST request with missing required fields and verify the proper error response.

- Explore the UI of the app to identify and cover more relevant test scenarios.

---

 ## Contributors

- [Ahmad]()
- [Majd]()
- [Saif]()
