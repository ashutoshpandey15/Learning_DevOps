
***
## What is Devops ?

- Devops is combination of development and operations, it combines software development with IT operations.
- Where Development = developing the software 
- Operations = network + build + deploy + test + monitor 
- The whole process of Coding to Production is Devops.
- The goal is to deliver better software faster and more reliably.
---

- Benefits of Devops
    
    - Using CI/CD we make build and deploy application smoothly.
    - CI → Continuous Integration ⇒ Multiple commits and multiple changes which can be done by different developers can be integrated in the shared repository without affecting the Live Production.
    - Process Involved in CI
        - Commit
        - Build
        - Automation Build (building using automatic tools)
        - Reporting
    
	    ⇒CD → Continuous Deployment ⇒ In software development, continuous deployment means that whenever code changes are made and pass through all the stages of the pipeline (like coding, testing, and building), they are automatically deployed to the production environment without manual intervention. This allows for new features and updates to be released to users quickly and frequently.
    
    - CD is not just deployment we manage the application and monitor it to make sure that it is running fine.
    - Deploying the application with some manual Effort is called as Continuous Delivery.
    - Process ⇒
        - Deployment Pipeline
        - Automated Deploy
        - Testing
        - Release and Rollback
        - Monitoring
    - Before deploying in the production server we have several environments
        1. Dev - 1st deployment to check the working (Lowest env)
        2. QA - Testing or quality assurance
        3. PPD (Pre prod) - lower version of prod
        4. Prod -main environment where we deploy our application live
        5. DR - disaster recovery (if issue with prod environment we can rollback to DR)
    - Pipeline in DevOps →
        
        In DevOps, a pipeline is like an assembly line in a factory, but for software development. It's a set of automated steps that code goes through from the initial idea to being ready for use by customers.
        
        Imagine you're making a cake. The pipeline would be all the steps from gathering ingredients, mixing them, baking the cake, to finally decorating it. Each step is crucial, and if one goes wrong, it could affect the final product.
        
    
    ---
    
    ## How DevOps really helps ?
    
    - Less time to bring the application live in market (by using CICD).
    - Early Bug Detection (in pipeline).(sonarqube)
    - Increased Collaboration b/w operations and dev teams.
    - Improve Quality.
    - Agility and Flexibility (able to apply and deploy changes very easily).

	Let's say you're using a mobile banking app. In a DevOps environment:
	
	1. Developers write code for new features or bug fixes.
	2. This code is automatically tested and integrated with the existing app.
	3. If tests pass, the update is automatically prepared for deployment.
	4. Operations team works with developers to ensure smooth deployment.
	5. The app is updated frequently, maybe even daily, with minimal disruption.
	6. User behavior and app performance are monitored.
	7. Feedback from monitoring is used to plan future improvements.
	
	Without DevOps, this process might take weeks or months. With DevOps, it can happen much more quickly and frequently, leading to a better, more reliable app for users.

