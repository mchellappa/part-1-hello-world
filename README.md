# Hello World!

The following steps must be completed before proceeding:

```bash
git clone https://gitlab.manulife.com/jh-cloud-platform-workshop/part-1-hello-world
```
1. Open a file explorer window and navigate to the project folder (e.g.: C:\Training\PCF\part-1-hello-world).
2. Open the manifest.yml file, and change the name entry from ‘name: HelloDotnet-lab1’ to ‘name: HelloDotnet-<your first name>-lab1’.
    
    e.g. ‘name: HelloDotnet-Jane-lab1’
    
    This step is needed to help avoid naming conflicts during deployment to PCF.
3. Open the command prompt, and cd to the project folder. Run the command below and follow instructions to login.

    `cf login -o JHAS-CAC-DEV -s DE-PLAYAREA-CAC-DEV`

    This will log you in to the org/space for the training deployments.
4. Run the command below to deploy your application to PCF:

    `cf push`
