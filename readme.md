# Portfolio Deployment Plan
1. Working Branch
The **working branch** will be the **Dev** branch
     1. git **checkout Dev**

2. Check, commit changes, then push to **Staging** and **Production**
Upon changes, the **Dev** branch will be **merged** with the **master branch**
    1. git **status** to check for changes
    3. git **checkout** master
    4. git **merge** Dev
    5. git **add -A**
    6. git **commit -m** '*Specifics of commit*'
    7. git **push stageServer**
        1. push changes to staging server
    8. git **push prodServer**
        1. push changes to production server

3. Test Committed Changes
   1. Test last change and all site functionality to ensure nothing is malfunctioning as a result of changes

4. Communicate with class!
   1. In **mdd-0-1410** private group on slack, use #portfolioUpdate and mention changes to classmates 