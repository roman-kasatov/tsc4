## My solutions for TON Smart Challenge #4
The goal of the competition is to write smart contracts for 5 problems.

####  Here is a part of original readme prepared by TON Foundation

## 📝 Tasks

1. [task1](/contracts/1.fc) - Find branch of the cell tree
2. [task2](/contracts/2.fc) - Matrix multiplier
3. [task3](/contracts/3.fc) - Find and replace binary substring 
4. [task4](/contracts/4.fc) - Caesar Cipher
5. [task5](/contracts/5.fc) - Fibonacci sequence

Each of the tasks has two parts:

- 📋 A comment with a description of what the smart contract should do.
- 💻 The code of the smart contract with one or more functions marked as `testable`.

The goal of the contestants is to provide a code that matches the description.
Each task may give the contestant either 0 or 5 to 6 score points: 5 for all tests passed plus "gas-score" from 0 to 1 (0 for "infinite" gas consumption, 1 for 0 gas consumption, dependence is inverse exponent).
Each TVM execution is limited to 100,000,000 (hundred million) gas units.
This limit is high enough that it only rules out infinite loops. Any practical solution, regardless of how (un)optimized it is, will fit.

We ask participants not to change the signature (number, order, and types of arguments and result) of `testable` functions for us to be able to evaluate their submission.

## 📚 Getting Started with TON

For those new to TON development, begin with:

- [Developers Portal](https://ton.org/dev?filterBy=developSmartContract)
- [TON Documentation](https://docs.ton.org)
- [Awesome TON Resources](https://github.com/ton-community/awesome-ton)

Dive deeper into TON with these essential reads:
- [Understanding TON Concepts](https://docs.ton.org/learn/introduction)
- [Writing Smart Contracts](https://docs.ton.org/develop/smart-contracts/)
- [Introduction to FunC](https://docs.ton.org/develop/func/overview)

For pre-built smart contract examples, visit [this section](https://docs.ton.org/develop/smart-contracts/examples).

Stay updated and join discussions on TON Developer Chats:
- English: [@tondev_eng](https://t.me/tondev_eng)
- Chinese: [@tondev_zh](https://t.me/tondev)
- Russian: [@tondev](https://t.me/tondev)

For FunC learners, join the discussion at [@ton_learn](https://t.me/ton_learn).

## 🛠️ Tools for Compilation and Testing

While we recommend [blueprint](https://github.com/ton-org/blueprint) for working with FunC contracts, [toncli](https://ton.org/docs/develop/smart-contracts/testing/toncli) is also a viable option for compiling and local testing.

For a more streamlined coding experience, consider using [IDE plugins](https://docs.ton.org/develop/smart-contracts/environment/ide-plugins) for syntax highlighting.


