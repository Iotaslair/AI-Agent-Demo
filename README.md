# Overview
This repo is meant to serve as a gentle introduction into Agents.

# Getting Started
1. [Install Opencode's UI](https://opencode.ai/download)
    1. [Opencode could train on the prompts in this guide](https://opencode.ai/#:~:text=What%20about%20data%20and%20privacy%3F), but it's a guide so we don't have to worry about that
    2. If you have access to another AI Agent (OpenAI's Codex, Claude Code etc.) feel free to use that.
2. [Install Go](https://go.dev/dl/) or whatever programming language you want to use
3. Launch Opencode in the directory of this Git Repo

# FizzBuzz
FizzBuzz is a super common starting problem for programmers. Here's a prompt you can use

```
Create a go program that plays the children's game Fizz Buzz up to a hundred. Call the file fizzbuzz.go
```

Copy paste the problem into the text box in Opencode's UI
Once it's done run the code with `go run fizzbuzz.go`

## Iterate with it
Ask it to make the program output like two people are actually playing FizzBuzz. Something like:

- Alice: 1
- Bob: 2
- Alice: Fizz
- Bob: 4
- Alice: Buzz

## Iterate some more
Ask it to add unit tests to the code. AI agents are at their best when they can verify if their output is correct.

# Where to go from here
AI Agents can work with stuff much more complicated than a simple example like FizzBuzz. So start to experiment with it!

Here's an idea to get you started:
```
Create a terminal-based point-of-sale system written in go with order taking, tax calculation, receipt generation.
```

The fastest way you'll learn is to experiment with your actual work. Just for fun. Try to complete a small ticket from work only with an AI Agent. Don't actually write any code.

# Few words of advice before you go
- Don't expect it to complete a task with one prompt, you're going to need to guide it like the Navigator in pair programming
- AI Agents are best if they can validate their output:
    - Give it all the context it'll need to solve a problem
        - If it needs some context from another directory, make sure it sees those files
    - Ask them to write tests in a TDD way
- If you already have an idea how to solve a problem, pass that information along
- Follow along with [this page](https://dub.sh/ztgUYjj). It'll be worth your while


My next LinkedIn post will cover how to get the most out of AI agents. See you there!
