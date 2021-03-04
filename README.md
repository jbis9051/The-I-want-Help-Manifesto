# The "I Want Help" Manifesto

## Introduction

This document intends to aid those seeking help for programming related questions, on internet chat platforms, ask questions productively and efficiently. There is a lot of overlap in the following sections. That is intended. 

## Basic Rules

- Do not spam. This is a fairly simple rule, do not repost questions because you did not get an answer right away. It was likely people read it and just didn't care. Tough luck.
- Do not be a Help Vampire. Don't expect anyone to write your code for you unless you are willing to shell out a bit of dough ($$$). For more details see [How to ask](#how-to-ask).
- If you are going to post code, please learn how to properly format it. The chat formatting is pretty easy. 
- **DO NOT POST IMAGES OF CODE**. This is one of the most annoying things in the world. Helpers are likely going to want to test out some of your code or at a minimum reply with portions of your code that need to be changed. People don't want to spend 10 min retyping your code because you sent it in an image. Just copy and paste.
- Be respectful. This does not mean people cannot disagree or have a constructive argument, but name calling and offensive behavior will not be tolerated and is completely unproductive. Also, why would anyone want to help someone who calls them names?
- There is no need to ask permission to ask a question.  https://dontasktoask.com/

![](https://i.imgur.com/xNJLvFi.png)


## Don't Be a Help Vampire

10 simple steps to not being a Help Vampire.

1. **Show effort**: People really like to see that you are trying to achieve your goals on your own first.
2. **Be ready to be wrong**: Often people suggest you take a new approach.
3. **Don't ask for help before doing the research yourself**: If my google search returns your answer in the first three links, you are doing it wrong.
4. **When given resources to learn, use them**. We do not like repeating ourselves.
5. **Do not beg for help**: If you have asked once and we ignore you then move on.
6. **Contribute to the community**: People like to help people who also like to help people, it's pretty simple.
7. **Don't ask for code**: Pseudocode is more than helpful and will set you on your way.
8. **Ask for help finding the answer, do not ask for the answer**: nobody is here to do your work.
9. **Be polite**: People are trying to help you, no need to be rude.
10. **Crack a joke or two**: who doesn't like to laugh.

## How to ask?

### Template

If you are asking a question about a specific code related issue, follow the following format:


> Abstract summary of what you are trying to accomplish: "I am trying to check if an inputed number is even or odd."
>
> Expected Result: "The function should output "odd" for 5 and "even" for 6.
>
> Actual result: "The function outputs "odd" for all numbers."

> Your code: 

> ```js 
> function checkEvenOdd(num){
>  if(2 % num === 0){
>     console.log("even");
>  } else {
>     console.log("odd");
>  }
> }
> ```
>
> Troubleshooting steps and why they failed: "I've tried to search google. But didn't find anything useful.


### MCVE

When asking a question about code include a MCVE, or Minimal, Complete, and Verifiable Example. For more information, read this https://stackoverflow.com/help/minimal-reproducible-example. For questions related to Web, this is usually in the form of a [jsfiddle](https://jsfiddle.com) or something similar.

### Avoid the XY Problem

> The XY problem is asking about your attempted solution rather than your actual problem. This leads to enormous amounts of wasted time and energy, both on the part of people asking for help, and on the part of those providing help.
>
>    1. User wants to do X.
>    2. User doesn't know how to do X, but thinks they can fumble their way to a solution if they can just manage to do Y.
>    3. User doesn't know how to do Y either.
>    4. User asks for help with Y.
>    5. Others try to help user with Y, but are confused because Y seems like a strange problem to want to solve.
>    6. After much interaction and wasted time, it finally becomes clear that the user really wants help with X, and that Y wasn't even a suitable solution for X.
>
> The problem occurs when people get stuck on what they believe is the solution and are unable step back and explain the issue in full.

#### How to avoid it?

> 1. Always include information about a broader picture along with any attempted solution.
> 2. If someone asks for more information, do provide details.
> 3. If there are other solutions you've already ruled out, share why you've ruled them out. This gives more information about your requirements.
>
> Remember that if your diagnostic theories were accurate, you wouldn't be asking for help right?

For more information, please see [here](http://xyproblem.info/)


### Do Research Before Asking Your Question

#### Google Fu

Your program is likely not unique. Someone has probably asked about it before. Helpers are not your personal Googlers. Search your question up on Google before asking. Try a couple of things. Most of the time people are just going to search up your question on Google. 

The art of Google Fu is very powerful. Those who have mastered it can help even those most experienced with a language,  without having even heard of the langauge. 

#### Documentation

Read the damn docs. All languages and frameworks have documentation associated with it. Read them before asking a question. If you are asking about the `Array.prototype.map` function, look at the documentation related to that function.
