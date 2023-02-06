Hi, welcome to the Trivia Moms club! This document is here to serve as a guide for the newcomers.
 
How do you make questions? Pretty easily!

First, create either a GitHub or Pastebin account. Once you do so, create a Repository and set it to Public.
 
Look at this example:
 
q "**What is the first book in A Song of Ice and Fire?**"
a "A Game of Thrones"
 
For questions with multiple potential answers:
q "**S01E01: Who is the first Targaryen to appear on screen in House of the Dragon?**"
a "King Jaehaerys I Targaryen", "Jaehaerys I Targaryen", "Jaehaerys Targaryen", "Jaehaerys I", "Jaehaerys 1", "J1", "Jaehaerys"
 
Want to include an image in your question?
 
q "**Name the character in the picture.**"
a "Lyanna Stark", "Lyanna"
i "https://i.imgur.com/EGsEa8W.jpg"
 
VERY IMPORTANT: You may have to manually add the "i." and ".jpg" once you copy/paste the file. That's fine, its still functional that way.

Once done with creating your questions, use the RAW copy option, and copy the link.
 
Now that we have questions covered, let's show you how to use Maester Bot.

Master command: /trivia
The criteria below will achieve most of the commands needed for being a Trivia Mom.

Want to create a trivia set?
/trivia create name
 
Want to edit the questions inside a trivia?
/trivia edit config: name options: questions link
 
Want to have the questions shuffle inside your set?
/trivia edit name shuffle TRUE; FALSE for no shuffle.
(Make sure true/false is in all caps)
 
Want to start a trivia?
/trivia start config: name, limit: number of questions, shuffle: TRUE/FALSE, scoring: REDUCTIVE/FIRST
 
Want to stop a trivia?
/trivia stop
 
Want to see a list full list of all the trivias?
/trivia list
 
Scoring options for trivia:
/trivia edit name scoring FIRST
(First makes it so only one person can get the answer correct. Also make sure FIRST is in all caps)
 
/trivia edit name scoring REDUCTIVE
(Reductive makes it so 5 people are allowed to get the answer correct. Make sure reductive is also in caps)
 
This should get you started. If you have any questions please contact us we will be glad to help! :)
