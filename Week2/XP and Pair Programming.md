Now that we've discussed what Agile is, lets discover one of many Agile frameworks i.e., Extreme programming. 

# Extreme Programming (XP)
- Developed by Kent Beck
 - It is a lightweight process that focuses on customer satisfaction and team collaboration.
 - It follows a set of values (Agile Manifesto)
 - Mostly used for small teams, with risky projects, and high customer participation.


## XP Core Values
1. Communication
2. Simplicity
3. Feedback
4. Respect
5. Courage

## XP Practices

![9 Practices of XP](https://user-images.githubusercontent.com/128154979/226687902-8d0b5d58-9397-439c-b8e1-07300a2b89d3.jpg)

1.  **Planning Game:** This involves both the development team and the customer. The customer prioritizes the requirements(stories), and the team estimates the effort required to implement them(tasks). This approach enables the team to focus on delivering the highest value features first.

2.  **Small Releases:** XP emphasizes the delivery of small, working increments of software. This practice allows the customer to see progress and provide feedback early in the development process.
 
3. **Metaphor:** This means a simple layman explanation of how the code works, i.e., the ability to explain the system to the new people without flooding them with technical terms.

4. **Simple Design:** Encouraging the team to keep the system design as simple as possible. The goal is to minimize complexity and ensure that the system is easy to understand, maintain, and modify.

5. **Test-first:** First write the test code and then write the program. 

6. **Refactoring:** Its primary focus is to remove the duplication of various processes.

7. **Pair Programming:** Two developers working together on the same code at the same time. The driver writes the code and the obsever identifies/ reviews mistakes simultaneously.

8. **Collective Ownership:** The entire team takes ownership of the code. It promotes collaboration and teamwork, as every team member can work on any part of the code.

9. **Continuous Integration:** Integrating the code into the main codebase frequently. The primary goal of CI is to identify issues and conflicts in the codebase as early as possible, allowing developers to resolve them quickly.
 
10. **40-Hour Week:** All team members must complete 40 Hours/week. This practice is used to ensure that the team members have a good work-life balance. 
 
11. **On-Site Customer:** This practice involves having a customer representative on the development team who provides regular feedback. 

12. **Coding Standards:** Coding standards are guidelines that the team follows when writing code. These guidelines ensure that the code is consistent and maintainable, regardless of who wrote it.


## The XP Process
- **Planning:** The first stage, is when the customer meets the development team and presents the requirements in the form of user stories to describe the desired result. The value of each user story is then estimated, which helps the team to understand how long it will take to implement it. If one or more of the stories can’t be estimated, so-called **spikes**  can be introduced which means that further research is needed.

  XP practices used here are:
  
  Planning Game, On-Site Customer 

- **Designing:** It is a part of the planning process, but can be set apart to emphasize its importance. It’s related to one of the main XP values i.e., simplicity. A good design brings logic and structure to the system and allows to avoid unnecessary complexities and redundancies.

  XP practices used here are:
  
  Simple Design, Refactoring
 
- **Coding:** It is the phase during which the actual code is created by implementing the following XP practices:

   Coding standards, Pair programming, Collective code ownership

- **Testing:** This is the **core** of extreme programming. It is the regular activity that involves both **unit tests** (automated testing to determine if the developed feature works properly) and **acceptance tests** (customer testing to verify that the overall system is created according to the initial requirements).

  XP practices used here are:
  
  Iterative development, Continuous Integration, Test first

- **Listening:** Constant communication and feedback. The customers and project managers are involved to describe the business logic and value that is expected.

## Advantages of XP

- Simpicity
- Stability (Continuous testing)
- Clear, comprehensive code
- Little overtime
- Reduced Documentation (User stories)


Now that we clearly understand Extreme programming practices, let us dive in one specific practice i.e., Pair programming.

# Pair programming
Pair programming as discussed is an Agile development techinque originatingg from XP. As the term is self explanatory, two developers sit on one computer and work together on the same task. The one writing the code is referred as **pilot/ driver** and the one monitoring the code is called the **navigator**.
Both Developers are equally invested in the task, the pilot can change to the navigator and vice versa. 

## Pair programming styles
- **Driver-Navigator:** One acts as driver (writes the code) and the other acts as navigator (guides the driver/ monitors the code)
- **Unstructured Pair:** Both developers can trade off who takes the lead.
- **Ping-Pong Pairing:** Both developers switch back and forth. It creates a dynamic where neither developer can take control over another's work. 

## Benefits of Pair Programming
- Improved code quality
- Better communication between developers
- Collective code ownership
- Error identification is made easier
- Efficient work
- Knowledge is spread among pairs
