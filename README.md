# CS 230 Module Eight Journal – The Gaming Room

## Overview
This repository contains the completed **Software Design Document** for *The Gaming Room* project, titled **“Draw It or Lose It.”** This submission fulfills the CS 230 Module Eight Journal requirements, showcasing my ability to design and document a software system that meets client specifications through a structured, object-oriented approach.

---

## 1. Client Summary
**Client:** The Gaming Room  
**Project:** Draw It or Lose It  

The Gaming Room wanted to expand their existing Android-based game, *Draw It or Lose It*, into a **multi-platform web application** accessible via browsers on desktop and mobile devices. The main software requirements included:
- A **single instance** of the game service existing in memory (singleton design pattern).
- Enforcing **unique names** for games, teams, and players.
- Ensuring **real-time synchronization** of gameplay across clients.
- Building a **scalable, secure, and maintainable architecture** that supports future growth.

The solution leverages **object-oriented programming** and **microservices architecture**, enabling cross-platform scalability and reliability while maintaining consistent game state management across distributed systems.

---

## 2. Strengths in Documentation
In developing this software design document, I believe I did particularly well in:
- **Structuring technical content** logically and comprehensively, ensuring clarity for both technical and non-technical readers.
- Clearly outlining the **system architecture view**, which details the logical, physical, and security layers of the distributed platform.
- Demonstrating strong understanding of **design patterns** such as Singleton and Iterator, and explaining how they meet the client’s unique requirements.

The use of visual and conceptual modeling (e.g., UML diagrams and architecture breakdowns) was also a strength, helping to communicate complex system relationships effectively.

---

## 3. Benefits of the Design Process
Working through the **software design document** before coding helped significantly in:
- Identifying **dependencies** and **integration points** early, which prevents implementation issues later.
- Clarifying how each **component interacts** within a distributed environment.
- Encouraging the use of **design patterns and modularity** that improve scalability and maintainability.

This documentation-driven approach reinforced the importance of planning before coding and made development far more efficient and organized.

---

## 4. Potential Revisions
If I could revise one part of my documentation, I would enhance the **Domain Model section** by including more detailed sequence diagrams to visualize interactions between objects during gameplay.  
This would provide clearer insight into **runtime behavior**, especially how the `GameService` interacts with teams and players during different game states. It would also strengthen communication between developers when implementing the real-time synchronization features.

---

## 5. Interpreting and Implementing User Needs
To interpret the user’s needs, I analyzed The Gaming Room’s business objectives and technical expectations:
- The users needed **a seamless and responsive experience**, so the design incorporated **WebSockets** for real-time interaction.
- They wanted **cross-platform availability**, so a **web-based microservices architecture** was chosen to support scalability and portability.
- They required **data consistency** and **security**, so features like **authentication (OAuth 2.0)**, **role-based access control**, and **TLS encryption** were integrated into the design.

Considering user needs ensures that the final product delivers **functionality, performance, and usability**, which are essential for user satisfaction and long-term product success.

---

## 6. Approach to Software Design
My approach to designing this software focused on **modularity**, **scalability**, and **security**. I followed a systematic process:
1. **Requirements Analysis:** Understanding both functional and non-functional requirements.
2. **Architectural Design:** Adopting a **three-tier microservices model** separating presentation, application, and data layers.
3. **Pattern Selection:** Using the **Singleton** pattern for centralized game state management and the **Iterator** pattern for enforcing unique names.
4. **Security Integration:** Embedding security throughout the architecture rather than treating it as a separate concern.
5. **Scalability Planning:** Designing for horizontal scalability using **Kubernetes** and **containerized microservices**.

In future projects, I plan to use similar strategies—especially emphasizing early architectural design, UML modeling, and security-first planning—to ensure efficient development and maintainability.

---

## 7. Reflection Summary
This project has been instrumental in reinforcing my understanding of **software design principles** and **distributed system architecture**. I learned how to communicate technical decisions effectively and how thoughtful design improves both the development process and the final product.  
By documenting design decisions thoroughly, I’ve created a reference that can guide future development and serve as a professional artifact in my computer science portfolio.

---

## Repository Contents
- `CS 230 completed software design document.docx` – Full software design document for *Draw It or Lose It*.
- `README.md` – Reflection journal following CS 230 Module Eight guidelines.

---

## Author
**Dale Davenport**  
Southern New Hampshire University – CS 230  
October 21, 2025
