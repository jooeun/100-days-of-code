# 100 Days Of Code - Log

## Legend

### Day CX : regular day of code
### Day TX: Some form of training (algorithm practice, tutorials, etc.)

## I'm not following the original version, just read https://github.com/shuroukami/100-days-of-code/blob/master/rules.md before you yell at me.

### Day 0: August 20, 2018
##### *(Prior to starting all this)*

**Starting point**: Did a couple of leetcode exercises, started dabbling with jest and babel by using the addition/subtraction fact "project" as an excuse. Moved some github repos to bitbucket because... Because, I guess.

**Thoughts:** Heeeerrree we go.

### Day 1 (T1): August 29, 2018

**Today's Progress**: Tried to solve https://leetcode.com/problems/rotate-array/description/. I did both brute force and extra array (did that first) solutions without help. I had the big idea correct for what was listed as solution 3, but I was not able to come up with a final solution.

**Thoughts**: Reading the solution, I don't actually understand why the author states that Solution 3 is an O(n), one-pass solution when there is a do-while loop (which, admittedly, wouldn't iterate through the entire array)? Oh well, maybe I'll go back to this again later. Spent waaaay too much time fishing for a way to do without the inner do-while loop (which prevented me from arriving at it in the first place)...

### Day 2 (C1): August 30, 2018

**Today's Progress**: Progress? I'm not sure if I should even really count this, but just worked on an internal tool for my personal use. Tried messing with using .NET Core, .NET Framwork, and .NET Standard all in the same solution, seems like the tooling in VS is a bit wonky, so I'll try that again some other time.

...and now that I'm done going down that rabbit hole that is my tool, I learned some more about regex and messing with ID3 tags in .NET. This was more educational than I thought it would be!

**Thoughts**: Hilarious that this has nothing to do with any real learning that I wanted to do, yet this is the one thing that actually follows the #100DaysOfCode definition the closest.

### Day 3 (C2): August 31, 2018

**Today's Progress**: Finished that personal tool of mine. Did a bit of refactoring/clean-up so that I don't let it drop off my mind completely like last time.

### Day 4 (T2): September 1, 2018

**Today's Progress**: Eased into algorithm practice again on leetcode, will dive into the interview question pile after I'm a bit more comfortable with more concepts presented there.

**Thoughts**: Really wanna get back on that react tutorial, too...

### Day 5 (T3): September 2, 2018

**Today's Progress**: Started 2-D array portion in leetcode. Stopping midway without finishing diagonal traverse question, too late in the night.

**Thoughts**: At least it's a "medium" question...

### Day 6 (T4): September 5, 2018

**Today's Progres**: Quick session to finish up diagonal traverse question. Algorithm was right, performance didn't measure up all that well against the other solutions. Noted some low hanging fruits plus a major optimization I should have identified the first time. Oh well, I'll get better.

**Thoughts**: Picked back up after a holiday and a missed day, commitment/consistency is hard.

### Day 7 (T5): September 6, 2018

**Today's Progress**: Went back to see what I can do to improve my algorithm from yesterday, turns out all I needed to do was change one data type that I was using in one of my functions... and I didn't even pick the type myself, I just let my IDE do it! That was a painful lesson in consciously picking my data types... 

**Thoughts**: I wonder whether I should resist or indulge in the temptation of veering off into the data/ML world..

### Day 8 (T6): September 8, 2018

**Today's Progress**: Solved another algorithm challenge. Ran into out of memory exception with first brute-force "algorithm", quickly went to tuple-based solution. Ran into overflow issues because of big counters. First solved with bigger data type (i.e. long), then updated to solve without using longs.

**Thoughts**: That was clooooose, almost failed the challengeeeee.

### Day 9 (T7): September 10, 2018

**Today's Progress**: Having learned from the previous challenge, was able to come up with a memory and runtime efficient algorithm on more or less the first go. Might not have arrived so fast on a whiteboard, though (TDD ftw :p)..

**Thoughts**: Another close call on failing the challenge, but I did a much more meaningful/impactful thing yesterday so I don't feel bad about that. Feels somewhat good that I'm finding the algorithm chellenges fairly easy, but that's probably also due to the nature of the lesson content. Aah, this imposter syndrome is painting a negative light on everything I do.

### Day 10 (T8): September 11, 2018

**Today's Progress**: Got through a couple of problems fairly easily. First attempt at binary addition got me 16th percentile among the C# submissions. Was able to get up to 100% after getting rid of unnecessary reversing operations and realizing I should use multiple and decreasing indices.

**Thoughts**: Things are starting to come a bit easier, even after an initial fail. Understanding strangers' code is also getting easier, too.

### Day 11 (T9): September 13, 2018

**Today's Progress**: First shot at implementing "IndexOf", got it right the first time but the performance didn't rank all that high (~77%, but that might also have been due to a bunch of cop-out solutions, too). Got kind of close to a performant solution but couldn't get all the way through. Looked at a fast solution and see the end optimization I should have arrived at.

**Thoughts**: Yet another day after rest day... more like 100DaysOfCodeIn200Days at this rate :p

### Day 12 (C3): September 16, 2018

**Today's Progress**: Re-started with React tutorial I hadn't touched in a long time. Yeah, yeah, I know it doesn't count technically, but this is my thing. Plus, I'm counting two day's worth of this as one day of code. I also started planning how to use React for next personal project.

### Day 13 (C4): September 18, 2018
**Today's Progress**: More React tutorials, counting yesterday and today as one day again. I also finally looked into using Typescript with React, saw that I could use all of CSS without the whole webpack ejecting thing, nice! 

**Thoughts**: React+Typescript was much better than a lot of the (earlier, admittedly) blogs out there made it out to be (https://github.com/Microsoft/TypeScript-React-Starter), thanks Microsoft. Being able to use Typescript with React is a two-birds-with-one-stone situation for me, so hopefully that adds to the motivation.

### Day 14 (C5): September 19, 2018

**Today's Progress**: Officially started personal project using React + Typescript. Began creating a simple functional component. Most importantly, made sure to incorporate testing straight away. This means I'll be hitting the following throughout this project: 

- React (for which I'll go back to the tutorial after initial phase of project is done)
- Typescript (I mean, why not? maybe I'll go back and do vanilla JS at some point?)
- Jest/Enzyme

**Thoughts**: The above are the bare minimum that I'll force myself to hit. Excited to see what else comes up.