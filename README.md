# [TOPIC 1.2] SERVERLESS CLOUD DEPLOYMENT WALKTHROUGHS

## [A] INFORMATION & DOCUMENTATION

**SERVERLESS / STATIC HOST:** Netlify - https://www.netlify.com/:

  - Netlify on deployment: https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/ 

  - Vite on Netlify deployment: https://vitejs.dev/guide/static-deploy.html#netlify

&nbsp;

## [B] BASIC STEPS

### UPLOADING NEW WEBSITE:
**1. Create new Local Repo & Publish to GitHub**

  - Using GitHub Desktop, Add or Create New **LOCAL** Repo from your existing portfolio project

  - One Git setup, publish the repo to GitHub

  - Set the GitHub repo to private, unless you are happy for code to be viewed by anyone!

&nbsp;

**2. Sign up to Netlify, Link your GitHub & Authorise Netlify**

&nbsp;

**3. Select your Repos**

  - Allow permissions to ALL your repositories
  
  - **NOTE:** You can just give it access to one, but you may choose to change in future, so access to ALL gives more flexibility

&nbsp;

**4. Configure your deploy settings**

  - Base directory: `/` (or `/client`)

  - Build comannd: `npm run build` (*OR `CI= npm run build`*)

  - Publish directory: `/dist`

&nbsp;

**5. Build your Site**

  - You can watch it build in the in-browser terminal

  - Go to Site Settings & change the site name to what you want your branch to be called

  - Review your dashboard & domain settings after setup as well - can use custom domains here!
  
&nbsp;

### CONTROLLING & UDPATING CONTENT:
1. Enable Continuous Deployment (turned on by default under "Build & Deploy")

2. When you push a new commit to GitHub, check that the new commit begins to build in "Deploys" tab

3. You can easily rollback to prior published versions in the event of a site-breaking bug!