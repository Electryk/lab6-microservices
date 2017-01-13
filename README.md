- Two microservices running:
  ![LogAndDashboardEvidence](img/LogAndDashboardEvidence.png)

- A third accounts microservice added at port 4444:
  ![2ndAccountServiceLogEvidence](img/2ndAccountServiceLogEvidence.png)

- Why the web microservice still running correctry when 1st accounts microservice is dead?

    Because microservices registers itselfs with a server name, and a second ACCOUNTS-SERVICE is alive.
    Then, is this microservice that receives requests from web microservice.