# actions-test-yml

How to run the project

    npx playwright test --project=chromium

components of GitHub actions
1. Events: They trigger the actions.

    -> more than 35 events and continuously being added.
    
    -> workflow_dispatch, sheduled, pull_request, repository_dispatch (REST_API), issues 

    -> defined by "on"

    -> each event can have several types

   -> each event can have different branches
![img_1.png](images/img_1.png)
![img.png](images/img.png)
![img.png](images/img3.png)


2. Jobs: are a set of steps that run in sequence to accomplish a task.
   
    -> Each job runs on its own runner.


![img.png](images/img4.png)

3. Steps: Are either a shell script, or an actions that will be run on the runner.

![img.png](images/img5.png)

4. Actions: They are individual tasks that we can combine to empower our jobs.
    
    -> available from community - GitHub Marketplace

    -> GitHub (prefix "actions/")

    -> own actions 

![img.png](images/img6.png)

5. Runners 

    -> machines where workflow gets executed

![img.png](images/img7.png)


===========================
workflow
=============================

![img.png](images/img8.png)
![img.png](images/img9.png)
![img.png](images/img10.png)
![img.png](images/img11.png)
![img.png](images/img12.png)
![img.png](images/img13.png)