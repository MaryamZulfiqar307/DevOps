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

1.  **Planning Game:** The customer and development team work together to prioritize requirements(stories) and estimate the effort needed to implement them(tasks), ensuring that the highest value features are delivered first.

2.  **Small Releases:** The team delivers working software in small increments, allowing the customer to provide feedback early in the development process.
 
3. **Metaphor:** The team uses simple explanations of how the code works to help everyone understand the system.

4. **Simple Design:** The team keeps the system design as simple as possible to minimize complexity and ensure it is easy to understand, maintain, and modify.

5. **Test-first:** The team writes tests before writing the program to ensure that the code meets the requirements.

6. **Refactoring:** Removing duplicate processes to improve code quality and maintainability.

7. **Pair Programming:** Two developers working together on the same code simultaneously.

8. **Collective Ownership:** The entire team takes ownership of the code. Any team member can work on any part of the code at any time.

9. **Continuous Integration:** Integrating code frequently to identify issues and conflicts in the codebase as early as possible.
 
10. **40-Hour Week:** This practice ensures that team members have a good work-life balance by limiting work-hours. 
 
11. **On-Site Customer:** A customer representative is part of the development team, providing regular feedback.

12. **Coding Standards:** The team follows coding standards to ensure that the code is consistent and maintainable.


## The XP Process
- **Planning:** The customer presents requirements in the form of user stories, and the team estimates their value and time to implement them. If one or more of the stories can’t be estimated, **spikes**  can be introduced which means that further research is needed. The XP practices used here include Planning Game and On-Site Customer. 

- **Designing:** It’s related to one of the main XP values i.e., simplicity. A good design brings logic and structure to the system and allows to avoid unnecessary complexities and redundancies. Simple Design and Refactoring practices are used.
 
- **Coding:** Coding standards, Pair programming, Collective code ownership are employed to create the actual code.

- **Testing:** This is the **core** of extreme programming. It is the regular activity that involves both **unit tests** (automated testing to determine if the developed feature works properly) and **acceptance tests** (customer testing to verify that the overall system is created according to the initial requirements). It uses the Iterative development, Continuous Integration, Test first practices.

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
