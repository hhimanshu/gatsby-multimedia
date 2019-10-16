---
date: "2019-09-05"
---
<iframe width="800" height="450" src="https://www.youtube.com/embed/7rVPidhSI-s?controls=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Filter Arrays in JavaScript  
This video covers how to filter elements from a
JavaScript Array using a higher order function called filter()  

![cta](https://i.imgur.com/syji68u.jpg)

## Code  
`gist:hhimanshu/dfe2669b70a1f6234c792a818fc4338a#1.Iterations.md`

## Transcript  
**00:00**          Hi there , it's Harit from bonsaiilabs. Welcome to the series on JavaScript. Today in this video, we are going to learn three most common ways of using for loops in JavaScript. So let's dive in there. Not three common ways of writing. Four loops using four, four,N and four of let's look at each one of them one by one. The fourth statement creates a loop that consists of three optional expressions and closed in parents' disease and separated by semi-colons. And it is followed by statement. It starts with the initialization. It is followed by the condition and the final expression within the body of the four loops. We execute one or more statements. So let's start with an example. Let's say we create a variable called I with the initial value of zero. Before any code could be executed in the loop, a condition is checked. So in our example, we check that the value of I should be less than 10 and after every loop execution, the final expression is evaluated. So we increment the value of [inaudible] after every loop. Right now in the statements, we are printing the current value of I in the loop. Let's see that inaction. So let's create our four loop now.

**01:19**          So as you see, we have created a four loop the variables, identify or called i. We check in the condition that the value of I should be less than 10 we're incrementing the value of I buy one after every loop and in the body we are printing out the current value fi. Let's go ahead and run that. So as you see, when we run the for loop, we get the values from zero to nine it did not print out the value of 10 why? Because our condition said that the value of I should be less than 10 when we initialize the identifier I we use the keyword called [inaudible]. The challenge with VAT is when you initialize a variable using a VAD keyword, the variable [inaudible] is created in the global scope. Let me tell you what I mean. So as you see, I'm trying to print the value of [inaudible] after the for-loop has executed and when we run it.

**02:14**          Yeah,

**02:14**          you see a value of 10 which means even though we wanted the value of it to be used only inside the folder, the variable was created in the global scope and that's the reason we were able to get the value fight even outside of the fall loop. Now this may not be desirable, so what should you do? So instead of using a VAT cuber to initialize the variables, you should use let keyword. So let initializes the variables in the block scope, which means once the fall loop complete execution, the variable, I will no longer be accessible. Let me show you what I mean.

**02:49**          So when it run the sample, it printed up all the values from zero to nine. But when we try to print the value of I outside of four loop, the variable I did not exist. So it is better and safer to introduce your new variables using the led keyword. Now the other type of four loop is a four in loop affordance statement. It relates over all enumerable properties of an object consists of two parts followed by the statements. It starts with the object over which you want to iterate. It assigns every property of an object to a variable and it is separated by the end keyword. And within the body you can have one or more statements. So let's say we have a weekdays object which consists of seven properties with the associated numerical values. So we want to iterate over the weekdays object and for every object we want to assign it a property called property. Now this property, when the loop start would contain only the property keys and not devalues. And within the body we are pointing out what the property key is. Let's see that in action. So we have a weekdays object here with seven properties. Now we will use for in loop to iterate over the properties

**04:04**          [inaudible]

**04:06**          so as you see it rating over weekdays and within every loop we are getting the property insight, the P variable and we are printing that variable on the console. Let's run it. So when you run you see all the properties printed on the console and not their associated values. The four in loop, it weights only over the property, keys off an object. It does not equate over the values. The third kind of for loop is a form of loop, a form of loop. It read over it rebels it Tribbles or nothing. But the objects that can be iterated upon such as address string map set. And for every part of the loop the variable gets the value from these Iterable. And within the body of the fourth statement you can have one or more statements doing something with these values. So for example, we can have a my retrievable object which has it, are able properties and put every Iterable we take the values and we put that in a variable called value. And within the statements we are printing out the value on the console. Let's see that in action. So string is a treble in Java script. So we have created a variable called Iterable and assigned it the value of the string called bonsai labs. So let's enter it over the Iterable using the four of lube.

**05:27**          So as you see, we are using a four off loop and we are iterating over the Iterable object for every loop. We are putting the value inside the variable called V and all we're doing is printing out the value on the console. Let's run it. So as you see at the output, since a string is an Iterable, the four of loop pig, every character of the string and printed that out on the console. Now we know that even the areas are retrievable. So how about we iterate over the areas using the four off loop serve, change the value of Iterable from string to an array. And it contains four elements. As we see here, we're using the same form of Lu to read over the array now. So let's run it and see the output.

**06:12**          Hmm.

**06:13**          So as you see at this point in time, the four of Luke, it rated over every element of the array and every element became one element when printed on the console. We know that even set isn't a treble. So can we iterate over a set using a photo flu? Let's try that. So I've changed the code so that our it Tribble is no longer an airy but a set and it contains three elements and say the set, and we're using the same form of blue to print the values and save the set on the console. Let's run them.

**06:48**          Hmm.

**06:49**          So as you see, as expected, Defore of blueprinted every element of the set on the console one by one. So the question is, what's the difference between for off and for N? So the far off it rates over all the values of your etrailer's and foreign only. It treats all the keys of the properties and not on the values. So when you have a use case of iterating over to Iterable, ask yourself whether you are only interested in the keys or the properties or you're interested in all the values and that will help you decide whether foreign or far off is a good choice. And that's it. If you do like the video, please hit the subscribe button and stay tuned for more awesome content. Thank you.

![cta](https://i.imgur.com/Uhmcvxx.png)