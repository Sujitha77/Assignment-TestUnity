# **Assignment-TestUnity**

## **Assigment**
**Scope:** To automation End-To-End automation using ``Cypress``, ``Javascript/TypeScript`` with ``BDD- cucumber``


**Assumptions:**
The following assumptions form the basis of the test automation strategy.

- An integrated tool suite must be the primary test management, planning, development, and implementation.

- The tool suite must be used to direct and control test execution, to store and retrieve test artifacts, and to capture/analyze/report test results.

- The tool suite must include a tool of choice for defect tracking and resolution.

- The tool suite must include a component for test requirements management.

- The tool suite must include a configuration management tool of choice.

- The configuration management tool of choice must be used to put manual and automated test artifacts under configuration management.

- The proper automated testing workspaces must be created on test servers that are separate from development servers.

- Testing standards must be documented and followed.

**Tools&Language:**
- JavaScript/TypeScript
- Cypress
- Node

**Scenario:**
- To validate the ``Quotation to a registered Insurance customer`` in demo.guru99 application:
   - Login failure
   - Login success
   - Request Quotation
   - Retrieve Quotation
   - Profile
   - Edit Profile
   - Logout

**Execution Steps:**

- Clone this project to local using ``git``

    ``
      git clone https://github.com/Sujitha77/Assignment-TestUnity.git
    ``
- Install dependencies using package.json

    ``
    npm install package.json
    ``

-  Once installed all dependencies, you should get ``node_modules`` folder in your local

- Final step to open cypress
  
  ``
  npx cypress open 
  ``
- After once it's open, click on ``Guru99_login.feature`` file


