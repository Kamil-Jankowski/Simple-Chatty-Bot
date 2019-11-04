# Simple Chatty Bot


**Stage 2: (ongoing)**

_At this stage, you will introduce yourself to the bot. He will greet you by your name and then try to guess your age using arithmetic operations._

_Your program must print the following lines:_

```
Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
What a great name you have, {yourName}!
Let me guess your age.
Enter remainders of dividing your age by 3, 5 and 7.
Your age is 22; that's a good time to start programming!
You may change the name and the creation year of your bot if you want.
```

_Instead of `{yourName}`, the bot must print your name entered from the standard input. Instead of `{yourAge}`, the bot must determine your age according to the following formula:_

```
age = (remainder3 * 70 + remainder5 * 21 + remainder7 * 15) % 105
```
Where `remainder3`, `remainder5` and `remainder7` is three numbers you input to the program.

Here is an example of a dialogue with the bot. Input lines are started with ">" symbol. You do not need to read this symbol.

```
Hello! My name is Aid.
I was created in 2018.
Please, remind me your name.
> Max
What a great name you have, Max!
Let me guess your age.
Say me remainders of dividing your age by 3, 5 and 7.
> 1 2 1
Your age is 22; that's a good time to start programming!
```

Use the provided template to simplify your work. You can change the text, but not the number of printed lines.
***

**Stage 1:**

_Digital personal assistants help people to drive cars, plan their day, buy something online. In a sense, they are simplified versions of artificial intelligence with whom you can talk._

_In this project, you will develop step by step a simple bot which will help you to study programming._

_For the first stage, you will write a bot who displays a greeting, its name and the date of its creation._

_Your program must print the following lines:_

```
Hello! My name is {botName}.
I was created in {birthYear}.
```
_Instead of `{botName}` print any name you choose and replace `{birthYear}` with the current year (four digits), ex:_

```
Hello! My name is Aid.
I was created in 2018.
```
_You can change the text if you need but print exactly two lines._
