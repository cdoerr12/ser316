Name - Christian Doerr
Class - SER316
Date - 10/20/26

Branch Structure

1) Dev
    Changes - Encouraging messages
2) feature1
    Changes - Quit Feature
            - User Feedback Messages
            - Play again loop
3) feature2
    Changes - Max Attempts
            - Game Over
4) feature3
    Changes - Added Hint Feature
5) hotfix
    Changes - RandomInt Fixes
6) main
    Changes - Initial Guessing Game

Summary

Merge - Leaves alot of messy room when dealing with multiple
        commits and consistantly has you doing more work then
        needed
Rebase - Like merge, but automatically commits the changes and 
        removes the extra steps that you do not need. Also cleans
        some of the history when looking at the final commits.
Squash - Allows you to handle everything at once rather than doing
        each individual commit for each fix. Worked really well and
        was a tad easier than the previous two.
Cherry-Pick - This one was super simple and just grabbed the commit
        and moved the change into the desired area. Not sure how 
        difficult this could have been if I had run into conflicts.
        Seemed rather easy.

TO NOTE - I have some messy gradlew conflicts added in everywhere
        because I did not inintially handle the gradlew in the
        ignore file. This is something I would not do in the future 
        as it made the history very messy in places it could have
        been clean.
TO NOTE 2 - DO NOT DO REBASE IN ONE-DRIVE WINDOWS. This blocks git 
        from removing the desired files while rebasing and will
        lock you in an infinite loot. Might be worth discussing with
        professor as this caused major issues during the assignment, 
        but is a rather one of case. I did major research into this and
        can explain further if needed.

History - Since we deleted feature 1 the history was not tagged on the dev
        history. Same with the cherry picking example from the very end.
        This does not mean that the history is not there, it is just not 
        tagged under another branch. Feature2 ended up rather messier than
        feature3 since we squashed feature3 for good readability. I liked 
        that everything was linear and that I was able to follow my process
        once everything was finished. It made me feel the project went well.

Real Life - I feel like going forward I would avoid the extra hastle from merge
        as much as possible. It was much easier to work with rebase since
        I am on a solo project. I may change my mind on this as the group
        projects may be different. I really think using Squash makes things 
        much neater and should be used whenever possible to make everything 
        much easier on the eyes without loosing detail.