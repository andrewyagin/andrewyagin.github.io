---
layout: essay
type: essay
published: false
title: There ARE Stupid Questions
date: 2019-01-24
labels:
  - Questions
  - Answers
  - Learning
---

I am sure many of us have heard it at some point or another that "There are no stupid questions". I have always taken issue with that statement. There are always stupid questions that can be asked. So it is of utmost important that we as individuals learn how to ask the right question, or rather, the **smart** question. Of all careers or fields of study, smart questions play a significant role in software engineering. Unlike most other specialties, those centered around computers most likely have the easiest to access resources, especially with the power of the internet at their fingertips. For that reason, such sites like StackOverflow or any other online forums. But while these services and groups of people may be useful in helping answer one another's question, smart questions are most likey to be answered as opposed to general and dumb questions. However this then begs the question: *What is a smart question?*

### So What **_IS_** a Smart Question?

First and foremost, it is imperative that you as an individual do some prior research before asking your question. After all, if your question is a trivial or simple one, you should be able to easily find the answers you're looking for. It's like the saying that some teachers employ: *"Ask Three Before Me"*, look for answers from several other sites before you resort to asking an online forum. Who knows, chances are there was someone else that asked the same if not similar question as you. If you have researched your question thouroughly, you can then finally inquire about it online. However, it should be noted that your question or post should meet certain requirements. Your question should be as succinct as possible while also as descriptive as possible. After all, if you ask a simple yes-or-no question, you will get a yes-or-no answer. Alternatively, if your post or question is too long and drones on and on, or if you include your entire 100+ lines of code, don't expect an answer! Who has time for that? You should be objective in your question, don't use anything similar to the following in your title: *"Can you please help me"* / *"URGENT* / *HELP!*, as they detract from the content of your question. Your title should instead demonstrate that you have done some searching on your own, or include what you have done on your part in the body of your post. Furthermore, a good question demonstrates to readers what your intentions are and and is clear what your issue is. Here is an example of a relatively *good* question:
```
What is the “-->” operator in C++?
----------------------------------------
After reading Hidden Features and Dark Corners of C++/STL on 
comp.lang.c++.moderated, I was completely surprised that the 
following snippet compiled and worked in both Visual Studio 
2008 and G++ 4.4.
Here's the code:

#include <stdio.h>
int main()
{
    int x = 10;
    while (x --> 0) // x goes to 0
    {
        printf("%d ", x);
    }
}
I'd assume this is C, since it works in GCC as well. Where is this defined in the standard, and where has it come from?
(Source: https://stackoverflow.com/questions/1642028/what-is-the-operator-in-c)
```
Notice the elements of the post: title is simple and straight to the point, in the first few sentences; they inform readers that they have done some research and even listed their sources; they include a brief, simple example in their attached code.


### Here is an example of a **_STUPID_** Question
```
Make this script work [closed]
----------------------------------------
For an assignment I need to write a piece of code which goes
through numbers 1 to 100, only prints even ones, and stops 
once they are printed. Yes, I know how to do it with a 
for loop but that's easy.

I want to know if it is possible to do it with a while loop. 
Here is my very clunky code 
(the result of me constantly changing things around):

import random
counter = 1
while (counter != 50):
    number = random.randrange(1, 100)
    if (int(number) % 2 == 0):
        print (number)
        counter = counter + 1
The problem with that is that it repeats numbers. It needs to only print each number once. 
And, yes, I have tried using random.sample, but that has a problem with ints.
(Source: https://stackoverflow.com/questions/32590751/make-this-script-work)
```
Conversely look at this question. Notice how the title is almost blatantly asking for readers to solve his problem for him and how it appears that he has not exhausted his resources in trying to find an answer. Although he goes into depth about some things that he has done on his end to solve his own problem, it doesn't seem to signal that he mostly fumbled around with possible solutions as opposed to taking the time to carefully think over his issue. Notice how he blatantly states that his code is clunky because of him "constantly changing things around".



