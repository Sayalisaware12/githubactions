so what isb Github Actions 

Github actions is feature to create custom auomated  workflow
it automates SDLC workflow like code , build , deploy, test and release
It also implements CICD DevOps 
Github Actions goes beyond just CICD and lets you run worflows when other events happened in the repo

What the term workflow means ??

Worflow is collection of jobs defined in a YAML file or it is automated process capable of executing one or more tasks.
name : is name of workflow
EVENTS : Any activity in the repo that can trigger the workflow
on: here it can be push or pull or issue creation in repository- push means whenever we push the code to repo it will trigger the workflow
JOBS: it consist of series of individual steps which are executed ion runner
Runners: is  a vm which is responsible for executing your workflows upon triggrring 
STEPS: Actions to be taken , commands , scripts 
steps:
Chain Jobs- needs

Advantages of GITHUB ACtions are 

It manages the infrastructure- like setting up servers . Scaling resources and managing execution environment.

It Handles the rest like - executing the tasks in VMS and caching necessary  dependencies  and providing reports on the outcomes .
automation in gihub - it streamlines the development work, reduces manual errors , and increases efficiency.

