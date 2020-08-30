- [Interview-journey](#interview-journey)
- [Data Structures and Algorithms:](#data-structures-and-algorithms)
- [Time and Space Complexity:](#time-and-space-complexity)
- [Using your network for guidance:](#using-your-network-for-guidance)
- [My process so far](#my-process-so-far)
  - [Things I want to try](#things-i-want-to-try)
- [Tricks of the Trade](#tricks-of-the-trade)
    - [How to find the number of digits in an Int](#how-to-find-the-number-of-digits-in-an-int)
- [Other Learning Resources:](#other-learning-resources)

# Interview-journey
This is to pull together all of the resources and steps I used to prepare for my first FAANG Interview. The one thing I noticed however, is that everyone is so focused on the interview, and preparing for the interview, that we skip over learning just to become a better developer. Sure the end result is to be ready for an interview, but if you're just a regular dude like me, you just want to get gud. Make decent money, and chill. So that's how my guide is focused. If you don't like that, see the [Other Learning Resources](#other-learning-resources) Section for variances on this same knowledge and study path.

I really think the overall goal should be to gain a systematic process for approaching problems in CS or Software Engineering. You want to be able to come up with at least an idea of a generic solution on the spot, you can iterate over it if you're in an interview or at work, but the quick process you create should be able to get you what you need to get started right away. 

After that, move on to system design. I wouldn't try to mix the two, learn one first, then the other. Balanced based on how much time you have. As a regular dude, trying to bounce between Algorithms and System Design just was way too much. 

The behavioral portion of your evolution is important as well. You can be as smart as you want, smartest person in the room, yet, if when you try to speak, it sounds like alien, or you're so nervous you can't present ideas in a consumable fashion, or your developer ego is larger than the Sun, then there's goign to be problems there too. My thing is just be cool. There's always someone smarter than you, and its easier to work with anyone if you're relaxed and approachable vs anything else. 😎


# Data Structures and Algorithms: 
I'm a relatively new Swift Developer so not only do I need practice in basic Swift development, but also I'm a Business Graduate, not a CS Grad, so I've taught myself everything. This is great, however it also means I've missed a ton of things along the way, just trying to get the job done. 

Of course you know by now, in order to truly be a Master Developer, you have to have a decent understanding of Computer Science behind your experience. Here are the readings and repo's I've utilized to make the journey a little easier. Mine will be Swift focused, but normally its all transferrable.

This is by far the best resource in Swift that I've seen for DS and Algos: 
- [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club) - This helped me tremendously, because not too many people are using swift in these interviews.

You'll want to make sure you have a firm grasp on basic Data Types and Structures like:
- Strings, Integegers, Arrays and Dictionaries: I know you're like 'Strings and Integers?'. But believe me, you'll see how much you may not know was soon as you start doing some of the more difficult [LeetCode](leetcode.com) problems. I know at least I did. 
- Lists and Linked Lists
- Graphs and Trees - Basic understanding and traversal needed really only. 

# Time and Space Complexity: 
LOLOL. Yeah right. Idk jack shit about this!
Ok, so I found this, its a good explanation for understanding how to calculate basic space complexity of an algorithm: 
[Space Complexity of Algorithms](https://www.studytonight.com/data-structures/space-complexity-of-algorithms)

The swift algorithm club had a decent explanation of BigO Notation: 
[Swift Algorithm Club - Big O notation](https://github.com/insaineyesay/swift-algorithm-club/blob/master/Big-O%20Notation.markdown)

# Using your network for guidance:
I work at a fortune 30 medical insurance company. So, every now and then smart people get hired. Normally, they end up using this company as a springboard to something better. We've had guys go to Google, Microsoft, and Amazon. I think there's one guy in front of me that will make it to a large Silicon Valley organization, but after him, I'm on deck for take off, (Aug 2020 currently) so I need to get moving lol.

These guys that have moved onto other things are cool enough that they come back and help guide us through the path. This is incredibly vital. If you don't have such a group, create a slack channel or try to find one that you can get into. Normally, people love to help others and as long as you don't abuse the relationship, you should be able to ask general 'wtf' questions, to help you get over a hump. I wouldn't say problem specific questions, because that's exactly what you have to figure out on your own, but more like 'do you have a good resource for system design?' type of questions. 

# My process so far
Here's what I'm currently doing to go through each algorithm I write. One thing one of my coding buddies told me was to not spend hours and hours on a simple Alogrithm, this isn't Dark Souls. Yes, you feel great after solving, but the purpose isn't solving, its developing the mindset it takes to propeerly scope out a problem, break it down into chunks and solve it systematically. 

August 2020
* Hack the shit until it works in swift playgrounds (lol) 
* Just read the Hired in Tech site, well some of it anyway, and downloaded the Canvas that breaks each part down into sections, and by the end, if you've filled out everything, you should hit all the parts necessary to decently design an algorithmic solution. 
  * So for that I'm trying this process now moving forward: 
    * Define constraints
    * Idea Generation
    * Complexity
    * Talk it out so it makes sense in english
    * Write the code
    * Pass some test cases, including edge cases into the code and see if it still makes sense
    * Pass in some sample tests
    * Extensive Test
That seems like a lot, so we'll see where it gets me. I'll update the section as I get better at it. 

## Things I want to try
* Flashcards
* The systematic process above
* Writing notes 
* Reviewing solutions, not memorizing, then see if once I understand the solution, if I can implement something without looking back at it. 


# Tricks of the Trade
### How to find the number of digits in an Int
```
var n = 234
while(n > 0) {
  println(n % 10)
  n = n / 10
}
```

# Other Learning Resources:
- [Coding Interview Journey](https://github.com/jwasham/coding-interview-university)
- [Hired In Tech](https://www.hiredintech.com/classrooms/algorithm-design/lesson/31)
- 