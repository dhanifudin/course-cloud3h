CI/CD

   CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development.
The "CI" in CI/CD always refers to continuous integration, ehich is an automation process for developers. 
The "CD" in CI/CD refers to continuous delivery and/or continuous deployment, which are related concepts that sometimes 
get used interchangeably. 
  In software development, multiple team members develop code and contribute to creating the software's functionality.
when multiple people contribute to a code base, it is important to maintain its integrity and ensure that any team member
can retrieve that latest version and build and run it locally. 
  Github actions are a set of actions in a github repository workflow. 
action: the smallest building block of a workflow is an action, which can be dentified as an individual task. 
artifacts : the files generated when you build your software project or test your software project are artifacts. 
event : an even triggers a workflow in github action.
github-hosted runners: hosted runners are machine similar to hosted agents in azure develops pipelines. 
job : a job is a set of steps set up o run in a single runner. 
self-hoseted runner: self-hosted runner are useful when you have special hardware configurations / software requirements for
                     buildiing your application or running your jobs. 
step : a task is an action or a command is identified as a step. 
workflow: in a github repo, the process set up in a YAMLfile defining the build, test, package, or deployment jobs is called a
          workflow. 
workflow file: the YAML file stored in github/workflow/folder in your github repository. 
workflow run: a workflow exceutes based on the preconfigured triggers/events. 
  Secret are important in any CI/CD pipeline implementation tool. they protect sensitive information, such as connecting strings
and passwords, and keep passwords or other secrets applied in application configuration settings. 
