# CS-230-Operating-Platforms
Software Design portfolio featuring The Game Room's Draw It or Lose It application at Southern New Hampshire University.

## 1. Briefly summarize The Gaming Room client and their software requirements.

The Gaming Room is a client that wanted to expand its existing Android game, *Draw It or Lose It*, into a web-based application that could run across multiple platforms. In the game, teams compete to identify images, rendered from a library of stock drawings, within a limited time. The client needed software that could support multiple teams and players, maintain unique game and team names, allow only one instance of the game service in memory at a time, and provide a reliable and secure gaming experience across different operating systems.

## 2. What did you do particularly well in developing this documentation?

I believe I did particularly well in analyzing the technical requirements and comparing different operating systems. I focused on how Linux, macOS, Windows, and mobile platforms each handle performance, security, memory management, and scalability. I also connected design patterns directly to client requirements. The Singleton pattern ensures only one game service exists, and the Iterator pattern checks that game and team names are unique. This work helped me understand how operating system choices affect software design and how to communicate technical recommendations clearly.

## 3. What about the process of working through a design document did you find helpful when developing the code?

Working through the design document showed me the importance of planning before writing code. Breaking the application into smaller components made it easier to understand how the different parts interact. The UML class diagram was especially useful. It showed that Game, Team, and Player could all inherit from a shared Entity base class holding the ID and name, which gave me a clear structure to follow when coding. The process also helped me connect object-oriented concepts, such as inheritance and encapsulation, to real-world software development.

## 4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revisit my evaluation of the different operating platforms. Although I discussed their advantages and limitations, I could strengthen my analysis with more specific examples of performance, security, and resource management. Concrete references on each platform's costs and licensing would also help. These changes would give stronger justification for my recommendations and make the document more useful to the client.

## 5. How did you interpret the user's needs and implement them into your software design? Why is it important to consider the user's needs when designing?

I interpreted the client's needs by identifying the application's essential requirements: multiplayer support, unique game and team names, and cross-platform compatibility. I then turned each requirement into a specific design decision. The need for unique names led to the Iterator pattern, the need for a single game instance led to the Singleton pattern, and the fact that players would use many different devices shaped my platform evaluation and recommendation.

Understanding user needs is important because successful software has to solve the client's actual problems while remaining reliable, accessible, and easy to maintain. A technically sound design that misses a key requirement would fail the client, and fixing it later costs far more than getting it right during design.

## 6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach involved identifying the client's requirements, evaluating technical options, and selecting design strategies that supported scalability and maintainability. I modeled the domain with UML, chose design patterns that fit specific requirements, and considered operating system compatibility, networking, and security.

In future projects, I would continue using structured design documents, UML diagrams, and requirement analysis. I would also add these techniques:

- User stories and use-case diagrams, to capture requirements from the user's point of view.
- Sequence diagrams, to map how components interact during gameplay.
- More testing and user feedback throughout development, to find potential issues earlier.

## AI Usage Acknowledgment

I used generative AI to help organize and refine my portfolio reflections. I reviewed the content to make sure it accurately represents my understanding of the course concepts and project requirements.
