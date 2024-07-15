# Anagrams

In this exercise, you'll write a program that returns all anagrams of a given word. 

## What are anagrams again?

An anagram is a word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once. For instance, the word "listen" is an anagram of "silent". Another examples if the word "wolf". Here's all the anagrams of the word "wolf":

- wolf
- flow
- fowl

## Setting up your project

It's up to you to decide what type of application to build. You might opt for a simple console/terminal application. Or perhaps you're more comfortable building a web application. You can use any programming language you're comfortable with.

## Exercise 1: Check if two words are anagrams

Build a program that takes in two inputs, and responds with whether or not the two words are anagrams of each other. The response should be in the form of an emoji. For example, if the two words are anagrams, the program should respond with a thumbs-up emoji. If they are not anagrams, the program should respond with a thumbs-down emoji.

```txt
Input: `fowl, wolf`
Output: `👍`

Input: `apple, orange`
Output: `👎`
```

### Tips

There are many ways to check if two words are an anagram of each other. You can try asking Copilot Chat for help. Alternatively, you could also try to just start typing the function and let Copilot complete it. Don't forget you can always cycle through the different suggestions!

## Exercise 2: Find all anagrams of a given word

In the [word list folder][1] you'll find 4 lists of words. Together, these capture a large portion of the English language. 

Your task is to build a program that takes in a word and returns all anagrams of that word that are present in the word list. When there are no anagrams found, the program should respond with a message saying so.

```txt
Input: `wolf`
Output: `wolf, flow, fowl`

Input: `listen`
Output: `listen, silent, enlist`

Input: `apple`
Output: `apple`

Input: `qwerty`
Output: `No anagrams found.`
```

### Tips

Getting stuck on loading the word files? Try asking Copilot chat for help. You might want to merge all the word lists into one big list. 

## Exercise 3: Write unit tests for your code.

Or well, I say write, but perhaps Copilot can do this for you? You'll likely have to refactor your code a bit to make it testable, but Copilot Chat should be able to assist with this!

[1]: ./WordLists
