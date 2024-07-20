# monorepo

**For this project, we will design and implement a multichain web3 application for buying and selling tokens using a general-purpose intent protocol.**

We are doing all that so that we can explore and understand:

- Why blockchains and web3 are considered as the next computing paradigm
- How to use intents and declarative paradigm to build decentralized applications
- How to use ethers, viem and other libraries to build web3 applications
- How to use nodejs, typeorm and postgreSQL to build scalable backend

To achieve these goals, we will be focusing on the following areas:

- Intro to blockchains
- Tools, languages and packages
- Code structure, patterns and organization
- Testing
- Using external APIs

At the end, we want to expose an api that returns the best time for bridging tokens via Stargate or any reasonable bridge.

This repo has some of the code snippets you need for being able to successfully complete this project. Some of the work will be split in weeks so that you can easily follow allow and do the work needed. Here is the rough outline of how we will progress. Each week, we build on the work from the previous week. The code for week `x` is saved in the branch called `felix-week-x`

:point_right: :point_right: :point_right: **Workshop 1**: `Introductions` - Get to know the Build Fellow and other students, ask questions about the project requirements, prepare your workspace.

https://openavenuesfoundation.sharepoint.com/:p:/r/sites/fellows/Shared%20Documents/4-%20Build%20Projects/Build%20Fellows%20Workspace/Felix%20Madutsa/BP%20-%2007,%202024%20-%20Workspace%20with%20students/Presentations/Week%201%20-%20Introductions.pptx?d=we8829585ceb14746aef0e8d4ac297c72&csf=1&web=1&e=y4GQNK

Optional Readings:

- Blockchain 101:
  - Blockchain 101 : https://www.youtube.com/watch?v=_160oMzblY8
  - What is a Blockchain https://www.youtube.com/watch?v=kHybf1aC-jE
- Tokens:
  - https://www.coinbase.com/learn/crypto-basics/what-is-a-token
  - Crypto Coin vs Token: https://www.youtube.com/watch?v=422HORNUfkU
  - How To Create a Token: https://www.youtube.com/watch?v=8N0lLN26BIE
- Token Trading:
  - Exploring the following DEXes: Uniswap ([app.uniswap.org](https://app.uniswap.org/swap))

**Workshop 2**: Project setup and tools – Setup the project and get familiar with the tools being used.

**Workshop 3**: Introduction to blockchains and token standards – Introduction to blockchains, tokens standards and intent protocols.

**Workshop 4**: Backend for listening to buy orders – Build the system for listening to buy orders being submitted to the protocol.

**Workshop 5**: Backend for listening to sell orders – Build the system for listening to sell orders being submitted to the protocol

**Workshop 6**: Backend for reconciling orders – Build the system for matching the orders with orders with the fill transactions.

**Workshop 7**: Backend for filling orders – Build and automated way to fill for orders based on whether it is profitable or not.

**Workshop 8**: Presentations - Polish your project deliverables and present them to the Build Fellow and other students in the final group session.
