![Alt text](https://miro.medium.com/max/1024/1*-FWtm_SGM0Fx2xMHw_lGmw.jpeg?raw=true "Deploy Angular on Netlify")

# Deploy Angular project on Netlify.

Netlify is a platform where you can build, deploy and host your fron-end.
In this article you will lear how deploy your Angular project in a few steps.

## 1.- Create an Angular project

Run `ng new angular-netlify` for create angular project.

## 2.- In your Github account create a new repository.

![Alt text](https://miro.medium.com/max/714/1*6NL6pJh518EHuILzi6th2w.png?raw=true "Create new repository on GitHub")

## 3.- Connect and send your local project with your remote repository.

Connect
`git remote add origin https://github.com/lemmusm/angular-deploynetlify.git`

Send
`git push -u origin master`

![Alt text](https://miro.medium.com/max/1329/1*R4_uWUTIJtenJRIR35y06g.png?raw=true "GitHub repository")

## 4.- In Netlify login with your Github account, create new site and connect to repository created.

![Alt text](https://miro.medium.com/max/827/1*1RSRzW0H09zejRDYajWUlQ.png?raw=true "Login with GitHub")

![Alt text](https://miro.medium.com/max/1230/1*o34oR1tcu4hS8584dHyMcQ.png?raw=true "Create new site on Netlify")

![Alt text](https://miro.medium.com/max/885/1*n6qRfsp_C-IKSEvTWxiQGA.png?raw=true "Pick a repository")

## 5.- Build options and deploy.

![Alt text](https://miro.medium.com/max/761/1*RdezvCj2JhlTJaGHN0sYUg.png?raw=true "Build settings")

![Alt text](https://miro.medium.com/max/1220/1*Zc9bBPX86v6L7XEDufRHSQ.png?raw=true "Deploy in progress")

![Alt text](https://miro.medium.com/max/1230/1*Lk_Ppb-RLsY-zrOLSk355A.png?raw=true "Site deployed")

[TEST RESULT!](https://suspicious-neumann-81fba2.netlify.com/)

Now, when you do push to Github repository, Netlify automatically deployment your project.

That is it, easy and simple.
