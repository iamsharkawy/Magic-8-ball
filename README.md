# Magic-8-ball

The Magic 8-Ball is a popular toy developed in the 1950s for fortune-telling or advice seeking.

Write a magic8.py Python program that can answer any “Yes” or “No” question with a different fortune each time it executes.

Magic 8-Ball, should I do this project?

We’ll be using the following 9 possible answers for our Magic 8-Ball:

* Yes - definitely
* It is decidedly so
* Without a doubt
* Reply hazy, try again
* Ask again later
* Better not tell you now
* My sources say no
* Outlook not so good
* Very doubtful

The output of the program will have the following format:

[Name] asks: [Question]
Magic 8-Ball’s answer: [Answer]

For example:

Joe asks: Is this real life?
Magic 8-Ball's answer: Better not tell you now


If you’re up for some more challenges, try implementing the following features to your program.

So far, the Magic 8-Ball provides 9 possible fortunes. Try to add a few more possible answers to the program.

To do this, you will need to increase the range of randomly generated numbers and add additional elif statements for each new answer.


* What if the asker does not provide a name, such that the value of name is an empty string? If the name string is empty, the output of the program looks like the following:

 asks: Will I win the lottery?
Magic 8 Ball's answer: Outlook not so good

As you can see, the formatting of the output can use some improvement when there is no name provided.

We can address this by printing out just the question, such that it looks like the following:

Question: Will I win the lottery?
Magic 8-Ball's answer: Outlook not so good

You can implement this by creating an if/else statement such that:

If the name is an empty string, it will only print the question.
Else, the player’s name and question are both printed.


* What if the question string is empty? If the user does not provide any question, then the Magic 8-Ball cannot provide a fortune, otherwise, the fabric of reality is at risk!

To ensure that the fabric of reality is safe, we can create an if/else statement where:

If the question is an empty string, print out a message to the user.
Else, print the name and question, with the Magic 8-Ball’s answer.
