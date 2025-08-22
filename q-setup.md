# Getting started with Amazon Q CLI

I originally thought the term “vibe coding” was so silly until I tried it out for the first time last month. Having a startup background and a knack for thinking up hackathon project ideas is a killer skill for this line of prototyping.

I’ll show you how to sign up for Amazon Q and vibe code for free: 

1. [Create a free AWS builder profile](https://docs.aws.amazon.com/signin/latest/userguide/create-aws_builder_id.html) 
	1. I’d recommend creating one for home with your personal email
	2. and another for work signing up with your work email
2. [Install Amazon Q for Developer on your command line](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/command-line-installing.html) 
	1. Go into the Mac app that was installed and authenticate with that Builder profile you made
	2. [Instructions for Windows users](https://dev.to/aws/the-essential-guide-to-installing-amazon-q-developer-cli-on-windows-lmh)
3. You’ll know everything works once you type `q` in your command line and Amazon Q opens up and you can just start asking it questions. 
4. Amazon Q will stop every step of the way and explain the changes it wants to make. It will ask `y / n / t` which is short for yes / no / or “trust” — which I love `trust` cause it’s true vibe coding and so fun
5. [Some advice on Reddit](https://www.reddit.com/r/ClaudeAI/comments/1kivv0w/the_ultimate_vibe_coding_guide/) and a few sample prompts to try are below
6. This 9 minute podcast episode is great: [Y-Combinator Startup School: How to get the most out of vibe coding](https://open.spotify.com/episode/5RShVmFo5G3IUFjgNaxxqg?si=b583f327b6c04b71)


**VIBE A:** **Building a Sudoku game**

```
You’re my game designer teammate. I’m bored and want to play Sudoku.`  
  
`Create a mini game for me that’s based on modern game app design principles.`  
  
`I want to play it as a single webpage that I host on my computer. It should be able to accept mouse and keynote inputs.`  
`Make sure you can save my score using local storage.`
```

**VIBE B: Now build a knockoff game of tetris**

`Now do that same prompt again but replace “Sudoku” with “Tetris”`


**VIBE C:** **Building a to-do app**
```

Context:  

I’m creating a minimal todo app with a lo-fi, calm aesthetic that helps users focus without distraction.

  
Objective:  
Generate code for a todo list component that supports adding, completing, and filtering tasks.  
  
Vibe Direction:  
The app should feel warm, slightly imperfect, and intentionally simple—like a physical notebook or paper list. Interactions should be gentle and predictable, creating a sense of calm productivity.  
  
Technical Parameters:  
- Use vanilla JavaScript, HTML and CSS (no frameworks)  
- Support local storage for persistence  
- Ensure it works well on both desktop and mobile  
- Keep performance lightweight and fast  
  
Visual Reference:  
Use a paper-like background texture, muted earthy colors, and a handwriting-inspired font. Elements should have slight asymmetry or imperfection to feel human-made rather than digital.  
  
Additional Notes:  
Avoid bright colors, sharp transitions, or notification sounds that might disrupt the calm feeling. Animation should be minimal and subtle.
```

**EXTRA CREDIT:** Send me some screenshots once you get these working :)