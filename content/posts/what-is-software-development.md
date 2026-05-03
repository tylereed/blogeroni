+++
date = '2026-05-02T20:19:40-06:00'
draft = false
title = 'What Is Software Development'
+++

# What is Software Development

Do you remember those word problems from elementary school?  Perhaps with a little dread.  Or maybe a lot of dread.  Don't worry; me too.

"Sally has 10 apples.  She gives Tommy 3 of them.  How many apples does Sally have left?"  How would you solve that?  Well,  "gives" is a hint that it's a subtraction problem.  You see that Sally starts with 10, so that's the minuend. The other number listed is 3, so that must be the subtrahend.  You can easily turn that into a formula of "10 – 3 = ?".  You can easily perform subtraction in your head, and you get the difference of 3.

I'm sorry if I scared you with the terms "minuend," "subtrahend," and "difference.".  You might not have ever even learned them at all.  But that's okay, because even without knowing all the technical jargon for the mathematical operations, you are still able to get the answer.

At its core, software development is about turning word problems into something a computer can execute.  A computer is stupid.  It can only do exactly what it's been told to do.  But computers don't work in human languages, such as English.

What a good software developer does is take an explanation meant for human understanding and translate it into a mathematical function a computer can understand.  And the difficulty of this? Languages meant for human to human communication are inherently ambiguous.

Let's expand on the earlier example of apples.  The original problem (10 – 3 = ?) could be turned into a computer program very easily.  It really shouldn't be.  It's something an average adult can do in their head.  To be more useful, the program should be able to take in any arbitrary numbers and subtract them. (Even then, this contrived exampled shouldn't be its own dedicated program; just get a calculator.)

"Take in 2 numbers.  Subtract them.  Output the answer."  This description is ambiguous.  A naive approach would be to just take it as written.

1. Make the first number the minuend.
2. Make the second number the subtrahend.
3. Perform the subtraction
4. Output the difference.

A bug report comes back.  "The system is outputting negative numbers."  This description is also ambiguous.  What's wrong with negative numbers?  Well, in our apple problem, you can't give away more apples than you have. Now we're getting somewhere.

A computer is stupid.  It executes a program exactly as written. Here, It needs to be told that negative numbers aren't an acceptable answer.  To use technical jargon, these are "business rules."  Business rules are definitions that define what the computer should do in different situations.  "Name is required." "You must make a selection." "Negative apples aren't allowed."

In our trite little example, Sally can't give away more apples than she has.  So we need to define a business rule that specifies what the computer should do in that case.  As a developer, I don't know all the business rules.  I can take a guess what the person wants the program to do, but I need clarity for that.  I don't know what the user wants.  And a lot of times, the user doesn't know what they want until they see it. By asking questions and gathering information, I can then give some thoughts or ideas on how the system should behave.

Interpretation 1: Output negative numbers.
Interpretation 2: Output 0.
Interpretation 3: Output an error message.
Interpretation 4: Switch the numbers and perform the subtraction that way.

Before the bug report, any of these interpretations is valid and reasonable based on the initial requirements. The bug report tells us that interpretation 1 is wrong, and that the naive approach is not correct.  So how do you choose the correct interpretation?  By going back and asking questions for clarification. Which really is what should have been done in the first place.

1. Make the larger number the minuend
2. Make the smaller number the subtrahend
3. Perform the subtraction
4. Output the difference

This is where jargon can come in handy.  Minuend and subtrahend and difference have very specific meanings in this context. These precise definitions provide a "mindless" computer with the information it needs to return a reasonable answer.  Jargon is helpful in that it is precise and specific.  But with an unfamiliar audience, it can also present problems because it is precise and specific.  There is a learning curve caused by the jargon, but once learned, it makes communication easier.

Oftentimes, if someone is having difficulty finding a word or a phrase, they get the general idea across by saying, "You know what I mean." And another person, sharing the experience of being human and having a human brain, usually does. But if they don't, they can ask clarifying questions, or come back with a specific problem and ask for more information.

A computer doesn't do that. It can't. So how do we handle this?  A human needs to tell the computer what to do, in a precise language (i.e. a programming language). Think through the problem forward and backward and anticipate where any misunderstanding might arise. We translate human language into computer code.

Software development is taking an ambiguous description meant for human understanding and turning it into a mathematical function that a computer can execute.

 You know what I mean?