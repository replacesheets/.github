## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

intro:
this is a project, aimed to get me rich and married incha allah, what it does is help ecommerce store owners in many ways starting with order confirmation and saisie, trying to automate them to get faster, cheaper and better confirmation and delivery rates.

---------------
## deployment:
-production: frontend: https://cod-manager.com/
             backend : https://api.cod-manager.com/
             database: mongodb atlas /production
-staging:    frontend: https://ecomircili.onrender.com
             backend : https://staging.api.cod-manager.com/
             database: mongodb atlas /staging
-dev:        database: mongodb /dev

--------------
## git branches:
-production: main
-staging: staging
-dev: dev
approach: code in a seperate branch - merge to dev - test locally - merge to staging - push to origin/staging (frontend and backend) - test staging - PR to main in frontend and backend - check the changes - accept PR - and that's it

