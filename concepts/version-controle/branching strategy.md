# Branching Strategy in git and github
  first once you start a project 
  1. create github repo
  2. structure your project branches for example
    main     -> production (ممنوع الشغل المباشر عليه)
    develop  -> integration branch (تجميع كل الشغل)
    feature/* -> لكل feature جديدة
    bugfix/* -> fixes على develop
    hotfix/* -> fixes عاجلة على main
    
  3. after finishing the edits in develop I start PullRequest
    very clean descriptoin  for what have been done 

code

git checkout develop
git checkout -b feature/contact-page