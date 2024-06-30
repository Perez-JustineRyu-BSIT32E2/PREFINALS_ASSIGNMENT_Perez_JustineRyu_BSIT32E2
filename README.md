# PREFINALS_ASSIGNMENT_Perez_JustineRyu_BSIT32E2
Self-Assessment: Onion Architecture, MVC, and Web API (.NET Core) with Bottlenecks (Encountered)
Conceptual Understanding:
 
Onion Architecture: (Yes/No) 
 
Have you heard of the Onion Architecture principle in software design? Yes
 
 
 
MVC Pattern: (Yes/No) 
 
Are you familiar with the Model-View-Controller (MVC) pattern for building web applications? Yes
 
 
 
Web API: (Yes/No) 
 
Do you understand the concept of building RESTful APIs using ASP.NET Core Web API? No

Application & Bottlenecks:
Onion Architecture:
 
 
Benefits: (1-3 keywords)
 
 
Briefly list some key benefits of using Onion Architecture in .NET Core projects. (e.g., separation of concerns, testability)

 Answer: 
   The code is organized in different layers, which explains what each part of the application does. When you need to make changes, a clear structure helps you find and edit the right part of the code without affecting everything else.
 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 
 
Have you encountered any challenges with Onion Architecture in your projects? If so, briefly describe the bottleneck(s). (e.g., Increased complexity for simple projects, difficulty finding developers familiar with the pattern)
 
 Answer:
  Yes, onion architecture is hard to understand. I always face many errors and have a hard time understanding how this programming works.
 

MVC:
 
 
Components: (1-3 keywords each)
 
 
Briefly describe the roles of the Model, View, and Controller in the MVC pattern.
 
Answer:
Model - Manages data and business logic. Data processing agreements and rules.
Show - Shows information to the user. Represents the user interface.
Controller - acts as a bridge between the model and the view. Processes user input and updates the model.
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 
 
Have you encountered any challenges with tight coupling between Model and Controller in MVC projects? If so, briefly describe the issue(s). (e.g., Difficulty in unit testing controllers, logic changes rippling through the application)
 
Answer
 Yes, sometimes it's complicated, but I understand the basics.
 

Web API:
 
 
Differences from MVC: (Yes/No and Briefly Explain)
 
 
Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
 
 
Answer:
 Traditional MVC applications are designed to build complete web applications using the Model-View-Controller pattern. These include templates to manage data and business logic, views to render HTML pages, and controls to manage user input and interactions. The main purpose of these applications is to create dynamic web pages that users can interact with directly through the browser.
In contrast, Web APIs focus on providing data services rather than full Web applications. They use templates to manage data and handlers to manage queries, but they don't use views. Instead of rendering HTML, Web APIs return data in JSON or XML format. These APIs are intended for use by other applications or services, allowing programmatic access to information and functionality without a user interface.
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 
 
Have you encountered any performance challenges with traditional MVC applications compared to Web APIs? If so, briefly describe the scenario(s). (e.g., Frequent page refreshes causing performance overhead, complex data exchange requiring a more lightweight approach)
 
 Answer:
   Yes, as far as I understand the two, I think the traditional ones are much more complicated than, for example, the Web API, because you have to make a lot of changes to make the traditional MVC work or to fix a bug.
