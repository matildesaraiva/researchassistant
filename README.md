# researchassistant

Data: AWS documentation
Goal of this project: Building a tool addressing the issue of large amounts of time spent by developers searching through documentation or asking other developers simple questions that are in the documentation of a company. This project will cover a subset of the data and will initially just be applied to one of the teams.
 1) Main goal is to have a system that can assist developers with parts of the documentation they aren’t familiar with
 2) Second goal is for the system to be able to point the user to further reading, by pointing them towards the source for the response and towards other documents that may be relevant to what they are currently working on.
 3) The final system will also handle internal documentation that contains sensitive information that can’t accessed externally and geographical restrictions (can’t leave the US).
 4) Example questions that the system needs to be able to respond to:
      • What is SageMaker?
      • What are all AWS regions where SageMaker is available?
      • How to check if an endpoint is KMS encrypted?
      • What are SageMaker Geospatial capabilities?

Presentation of the project should cover the following questions:
1. Does your solution solve the company’s pain points? What are they?
2. What is the name of the LLM Pattern you’ve used in this project? Since names are not yet standardized, feel free to elaborate on the pattern you used.
3. What tools did you use? Why did you select them?
4. What model would you use for this use case? Why? What did you use for your embeddings? How does that decision affect the performance of your system?
5. How does your system handle out-of-vocabulary (OOV) terms?
6. Would you need to self-host? Explain your decision.
7. How did you chunk the documents provided? Does this decision have any effect on the performance of the system?
8. What is missing for your solution to be production-ready?
9. Is your system able to handle changing information? What would happen if the documentation is updated?
10. How can you evaluate your system? How do you evaluate your information retrieval system? What would need to be different between evaluation during development and for production?
