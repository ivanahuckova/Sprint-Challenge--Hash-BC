# Sprint Challenge: Hash Tables and Blockchain

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint, we learned how hash tables combine two data structures to get the best of both worlds and were introduced into the fascinating world of blockchains. In your challenge this week, you will demonstrate proficiency by solving algorithms in Python using hash tables and add another key feature to your blockchain.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in Python and your command of the concepts and techniques in related to hash tables and blockchains.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

This sprint challenge is divided up into three parts: Hash tables (24 points), blockchain (12 points) and a short interview (20 points). There is also a stretch goal in the blockchain section which should only be attempted after the rest of the problems have been completed.

## Interview Questions

During your challenge, you will be pulled aside by a PM for a 5 minute interview. During this interview, you will be expected to answer the following three questions:

-   1. What is a blockchain and how does it work?
       `A blockchain is a decentralized trustness verifications - which means that it is ledger/transactions records are shared across a network of computers. There are three principal technologies that combine to create a blockchain. 1) private key cryptography (SHA256), 2) a distributed network with a shared ledger and 3) an incentive to service the network’s transactions, record-keeping and security.`
-   2. What is an array and how does it work?

```Arrays are among the oldest and most important data structures, and are used by almost every program. They are also used to implement many other data structures, such as lists.,

Array is a homogeneous collection of elements of same data types where the data types can be int, char, float etc…. The elements of an array are numbered. We call that number the index of the array element. They are storred as a block of memory.

```

-   3. What is a hash table and how does it work?

```A hash table is a data structure that is used to store keys/value pairs. It uses a hash function to compute an index into an array in which an element will be inserted or searched.
One problem—what if two keys hash to the same index in our array? This is called a hash collision. There are a few different strategies for dealing with them.

Here's a common one: instead of storing the actual values in our array, let's have each array slot hold a pointer to a linked list holding the counts for all the words that hash to that index
```

You will receive points at the PM's discretion based on the following criteria:

-   20: Would love to have this person on my team!
-   14: Wouldn't mind working with this person.
-   10: Knowledge is lacking OR poor communication skills
-   6: Knowledge is lacking AND poor communication skills
-   2: You get 2 points for showing up

## Project Set Up

#### [Hash Tables]

For the hash tables portion of the sprint challenge, you'll be working through two algorithm problems that are amenable to being solved efficiently using a hash table. You know the drill at this point. Navigate into each exercise's directory, read the instructions for the exercise laid out in the README, implement your solution in the .py skeleton file, then make sure your code passes the tests by running the test script with make tests.

A hash table implementation has been included for you already. Your task is to get the tests passing (ideally using a hash table to do it). You can remind yourself of what hash table functions are available by looking at the hashtable.py file that is included in each exercise directory (note that the hash table implementations for both exercises differ slightly).

_You may not use any advanced built-in Python functions to solve these problems._

#### [Blockchain]

For the blockchain portion of the challenge, you will be writing code for a new miner that will solve a different Proof of Work algorithm than the one we have been working with.

Your goal is to mine at least one coin. Keep in mind that with many people competing over the same coins, this may take a long time. By our math, we expect that an average solution should be the first to find a solution at least once in an hour or two of mining.

## Minimum Viable Product

You can earn 35 points from the main coding portion of the sprint challenge. Be sure to budget your time wisely. The Blockchain challenge is fun, but it is only 1/3 of the points availible for the coding portion of this challenge.

#### [Blockchain](https://github.com/LambdaSchool/Sprint-Challenge--Hash-BC/tree/master/blockchain) - 12 pts

-   ex1 - 12 pts

#### [Hash Tables](https://github.com/LambdaSchool/Sprint-Challenge--Hash-Theory/tree/master/hash-tables) - 24 pts

-   ex1 - 12 pts
-   ex2 - 12 pts

Both Hash Table problems will be graded as follows:

-   1: Code attempted
-   2: Code resembles the correct solution
-   3: Tests pass
-   4: Tests pass, using the existing hash table implementation, no flake8 complaints
-   5: Tests pass, using the existing hash table implementation, no flake8 complaints, linear runtime complexity

### Grading

Students can receive up to 55 points in total for this Sprint Challenge (not including 4 extra credit points).

-   **Challenge**: 35
-   **Interview**: 20

---

The score distributions are as follows:

-   **3**: >= 48 points
-   **2**: >= 35 points
-   **1**: < 34 points
