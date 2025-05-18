# Lab 7

1. I would fit the automated tests in my Recipe projetc development pipeline within a Github action that runs whenever a code is pushed. This is because when I make a pull request to merge the branch I made with the master/main branch, the Github action would run the automated tests before I am allowed to merge. Doing a Github action whenever a code is pushed and before a merge will ensure that my code is executing the right inputs and that I don't merge incorrect code into my main/master branch. If I can't merge, I know there is something wrong with the code I implemented. 
2. No, I wouldn't use an end to end test to check if a function is returning the correct output. This is because I can test a function's return output by using Github actions that implements automated testing. 
3. the difference between navigation and snapshot mode is that navigation mode analyzes a page after it loads while snapshot mode analyzes a page in its current state. Navigation mode is good for looking at overall performance while snapshot mode is good for finding accessibility issues.
4. Based on the Lighthouse results, three things that could improve the CSE 110 shop site are having properly size images, serving images in next-gen formats, and having a ` <meta name="viewport">` tag with `width` or `initial-scale`.



