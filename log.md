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

### Day 15 (C6): September 20, 2018

**Today's Progress**: Added one style and one test to same component from yesterday. Figured out parameterized unit testing without external dependencies in Jest (should have done so myself, really), slowly getting myself acquainted with testing React and using Jest and Enzyme. Will have to dig into Webpack at some point if I want to use CSS modules AND not mess up my project. Also started an internal debate on fetch vs axios in the ajax part of the React tutorial... 😂

**Thoughts**: On the big-picture side, came across a great set of blog posts that talk about all the pieces of a full-blown production environment, how to automate all the way from infrastructure to continuous delivery. Can't wait to sink my teeth into that stuff, too, but for now, focus on React project and algorithm practice? Maybe that should come last at this point...

### Day 16 (T10 + C7): September 22, 2018

**Today's Progress**: Tutorial: learned basics of making AJAX calls to dynamically feed data to React components through both axios and fetch API. I don't have a usage for my personal project yet, but it will definitely come into play eventually. Personal project: ended up learning more about Typescript than making progress on the project... this came about from noticing that my initial implementation from the previous day was going to fail spectacularly on an extremely simple case. But in reality, I actually did it that way on purpose so I could go through this exercise.

**Thoughts**: Maybe I should actually sit down and design the project a bit more further so I don't get distracted so easily? But that's not really a fair statement, I'm doing this precisely so I can learn these things (no room to do this regularly at work).

### Day 17 (T11 + C8): September 23, 2018

**Today's Progress**: 
- Tutorial: spent a looong time going through.. not much? small UI tweak and dealing with preventing infinite loop in updating state from response data in componentUpdate(), post-ing request to a URL (which is also a use of a class-based component not as a container). Finally a bit about interceptors for axios. 
- Personal project: realized the error of my ways with how I thought about (and consequently) named my first component. Started off the containing component as a container, but moved to another component for now. Started writing tests and got lost in the woods. I pushed way too far and now I feel physically sick.

### Day 18 (T12 + C9): September 25, 2018

**Today's Progress**:
- Tutorial: Pivoted to learn some sql. Wanted to get to window functions, but it was good to go over the basics. Hopefully I retain at least some of the ideas/patterns for using aggregations, joins, subqueries well...
- Personal project: Thought I was only going to get through the tutorial portion of the day, so really happy to have spent time on it. Wrapped up the components because I was getting too hung up on the testing (I'll make sure to come back to them, though), then went on to actually teasing out the domain models a bit, tried to make it idiomatic to Typescript, but who knows. Will probably put it up for code review to reddit or something later.

**Thoughts**: I can't tell if this is a good thing that I can't seem to stop once I get going. My sleep and health is not liking me doing this...

### Day 19 (C10): September 26, 2018

**Today's Progress**: Added a first draft of my domain models in, there's a ton of manual configuration at this point, not sure how I want to solve it going forward. Wrote a couple of tests for the container to get it started, ran into some infurating errors all because I didn't actually learn how to export and import interfaces from files. No more, I have conquered.

### Day 20 (T13): September 30, 2018

**Today's Progress**: Using axios to store and retrieve data from Firebase. Good practice on React, Firebase is rather delicious.

**Thoughts**: Came back from a health-enforced break. I get too excited when learning, need more self-control.

### Day 21 (C11): October 1, 2018

**Today's Progress**: Quick session today, added axios usage to personal project. Preceded by a research session of choosing between Realtime Database and Cloud Firestore (seems to be closer to "normal" NoSQL solutions) for way too long.

**Thoughts**: I suppose Cloud Firestore may be an option eventually, the idea of a hosted database that is also free is kind of growing on me... but alas, might mess me up with testability.

### Day 22: October 3, 2018

**Today's Progress**: Got hilariously side-tracked, practiced some JS and (bad (i.e. I'm bad at it) game programming with https://warriorjs.com/.

### Day 23 (C12): October 5, 2018

**Today's Progress**: Switched to pulling data from Firebase to initialize state to app. No longer using App component as container for navigator. Started writing unit tests, some outside forces made me stop midway.

**Thoughts**: Hanging on to this streak by a thread...

### Day 24 (T13): October 7, 2018

**Today's Progress**: More unit tests.

**Thoughts**: Still hanging on to this streak by a thread...
