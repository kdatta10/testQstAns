# testQstAns
Please find the task below

 

How to submit the results: please use via Github/Gitlab/Bitbucket or any free Git repo services and share us the Git repo URL. Share this task in Git repo with tagging at each task

 

Duration: 3 days (If you are unable to complete in 3 days please submit the task completed in 3 days post review and interview you can submit the completed task)

 

1) write an http api with endpoints defined as below

    a) /counter:

        GET will return +1 of existing count

        POST will return +2 of existing count

        DELETE will return -1 of existing count

    b) /info:

         GET will return

            - git commit hash

            - branch name of the source code

            - environment name of the app

            - hostname

    * environment name to be determined based config or system variable during run time

2) Dockerize the app with minimal foot print

    preferably using multi stage building

3) Create a script which will allow

    a) install dependencies

    b) create Docker image - Docker tags either can be given as an argument or determine based on git hash

4) Create a README.MD file to describe how to run the app in local environment.

5) Design and document CI/CD work flow and code promotion

    ex: -  dev/qa/stress test/staging/prod etc.

6) Create helm chart for deploying the application.

7) Modify the script on task 3) to use the helm char to deploy the application to target environment.

8) Create helm chart and modify the script 3) to do blue green switch.

9) Add function in script 3) to increase or decrease the pods for the deployment on target enviroment.

10) Implement sticky session for the api so requests will always go to the same pod during blue green traffic shift

11) Update the read me files to explain how to use the script

 

Automation: (pick your favorite automation tool)

1) write automation scripts to install list of packages: haproxy

2) ensure haproxy starts automatically on reboot

3) update haproxy config from given repo on demand from given git repo
