```yml
#Workflow
#should have name
name: hello 
#on tells when the workflow should run 
on:
  workflow_dispatch:

#jobs
#should be inside the workflow
jobs:

  say-hello:
    runs-on: ubunu-latest
#steps
#should be inside the job 

    steps:
      - name: say hello to everyone
        run: echo "hello dosto"

#steps
#should be inside the job 
---
