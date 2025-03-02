# TAO - Designed for the Music Economy

## Preface

### Tao's vision and mission

Our mission is to be a leading force in building the Internet of Value, and its infrastructure and applying it specifically towards addressing the pain points of the music economy. 
We are working to create an alternative, scalable financial system which is more secure, transparent, efficient, inclusive and equitable for everyone.

Tao is an innovative solution to the scalability problem with the Tao 1.0 blockchain. 
Tao relies on a system of 150 Validators with Delegated Proof of Stake (DPOS) consensus that can support near-zero fee, and 2-second transaction confirmation time. 
Security, stability and chain finality are guaranteed via novel techniques such as double validation, staking via smart-contracts and "true" randomization processes. 

Tao supports all EVM-compatible smart-contracts, protocols, and atomic cross-chain token transfers. 
New scaling techniques such as sharding, EVM parallelisation, private-chain generation, hardware integration will be continuously researched and incorporated into Tao's Validator architecture which will be an ideal scalable smart-contract public blockchain for decentralized apps, token issuances and token integrations for stakeholders in the music economy of any size.

### Scope

This document describes Tao’s initial draft for the Tao blockchain’s economics system.

## Validators

- **Validators** are full-nodes that create, verify and validate new blocks in Tao’s platform. 

- **Validator Candidate**: Any account can deposit 100K TAO using the official on-chain governance d-app to become a Validator Candidate. 
100K TAO deposit can earn staking rewards. 
A Candidate can resign, but the tokens will be locked for the next 30 days (1,296,000 blocks) after the resignation. 

- **Becoming a Validator**: A Candidate becomes a Validator when the user belongs to top 150 most voted Candidates in each epoch. 
A Validator can resign, but the tokens  will be locked for the next 30 days after the resignation.

- **Reward**: The reward a Validator receives in each epoch is proportional to the number of signatures he/she  signs.

## Token Voting and Staking

-   **Token  voting**: Token holders can vote for Validator Candidates by sending TAO to each Candidate specific voting address using the official governance d-app. Top 150 most voted Candidates will become Validators. 
Token holders can un-vote a Candidate, but the tokens will be locked for the next 48 hours (86,400  blocks) after the un-voting.   

-   **Staking**: Validator token  deposits, and all  tokens used to vote for Validators will enter staking program, and earn block rewards in each epoch, plus any fees. 
Tokens used to vote for Candidates who do not become Validators will not earn staking reward.

## Token Emission Schedule

-   **Following the fundraising commitment**: The total amount of tokens at the genesis block is 55 million TAO tokens in circulation; 
12 millions are reserved for the team vested over the next 4 years; 
16 millions are reserved for strategic partners, and an ecosystem building fund which totals 83 millions tokens. 
Plus, 17 millions are reserved as block rewards for the next 8 years, the amount of tokens  in circulation at the end of the 8th year  after the genesis block is around 100 million TAO. 
After the mainnet: the block reward for the first and second year is  4 million TAO annually; the block reward for the 3rd, 4th, 5th year is 2 millions TAO annually ; and the block reward for the 6th, 7th and 8th year is 1 million TAO annually . 
Subsequently, the block reward will be halted, or activated at a number less than or equal to 1 million TAO annually.


-   **Implementation**: Each epoch consists of 360 blocks, which will reward a total of 360 TAO in the first two years. 
360 TAO will be divided to all the Validators proportional to the number of signatures they sign during the epoch. 
Afterward, the reward achieved by each Validator  will be divided into three portions. 
The first portion of 40% called “Infrastructure Reward” goes to the Validator. 
The second portion of 50% called “Staking Reward” goes to the pool of all voters for that Validator which is shared proportionally based on the token stake. 
The last portion of 10% called “Governors Reward” goes to a special account controlled by the Tao Board of Governors, which is run by Tao company initially. 

## Voting/Staking Consideration

### Candidate/Validator incentives

Validators will receive a significant amount of block rewards, which likely exceeds the cost for running the infrastructure. 
However, Validators need to invest in Tao by depositing  at least 100K Tao, and stake them for a long term. 
Furthermore, after depositing 100K TAO to become a Candidate, if the account cannot become a Validator (has less votes than Top  150 most voted  Candidates), he/she will receive no rewards. 
Therefore, Candidates have an incentive to do as much as they can such as signaling their capability to support Tao to get into top 150 most voted Candidates.

### Token voter incentives

Token voters should vote for Candidates who signal a strong support for Tao because if the Candidate does not become a Validator, voters will not receive any rewards. 
However, token voters should also vote for the less voted Candidates because the most voted Candidates will receive less reward per token stake comparatively. 

## Long Term Platform Economics Consideration

### P/E theory of token value

Equity price can often be a multiple of annual earnings a company generates. In the case of a blockchain platform, earnings could be considered as the total rewards and fees that the platform produces. 
The multiples for technology startups in the early days could exceed 200 which is where Ethereum network is approximately at the moment.  

### Quantity theory of money for token value

In this theory, the total amount of TAO can be considered the money supply for the blockchain economy including all the d-apps and tokens on top of Tao. 
Assuming a constant price, and velocity of money, demand for money will raise proportionally to the total amount of activities of the whole blockchain network, which will raise the price of TAO if the supply of Tao is fixed, or the inflation rate is very small. 
Tao’s advantages of minimal transaction fee, and very fast confirmation time could spur a massive amount of activities for Tao tokens, and other tokens on top of Tao.    

### Store of value theory of token value

Blockchain native tokens can be considered as the means of fundraising, or the store of value within their own blockchain economy if the supply of the token is fixed, or the inflation rate is very small, and predictable. 
These conditions are applying to Ether and Bitcoin at the moment, and can be applying to TAO token in the future as the Tao’s economy grows. 

### Built-in decentralized exchange
Tao roadmap includes a built-in decentralized exchange, in which a portion of fees will be added to the pool of epoch rewards. These fees could be substantial if there are many valuable tokens on top of Tao. 
This extra feature can increase the future earnings of the network, and raise TAO price based on the P/E theory.

## Decentralized Governance

### Become a Validator

Becoming a Validator is an important signal of long-term support for Tao platform. 
We would welcome other entities to become a Validator, to show their supports by helping the network, and gradually decentralize the platform governance.  

### Board of Governors

It is postulated that Tao platform would later be coordinated by non-profit body such as Board of Governors amongst many other decentralized bodies which receive a steady amount of income from the network, and act solely in the interest of the network.

### Technical decision making

The technical decisions should be considered, debated, and decided upon by qualified experts based on the long-term interest of the network.

### Economic decision making

The economic decisions such as the amount of block rewards, inflation rate, the division of block rewards might be based on the consensus of majority of the Validators (with their voters). 
Board of Governors could be one of the coordinating bodies for these activities using the official governance d-app.

## Appendix A: History of the Project

Tao Network raised funds to build Tao blockchain platform in early 2016. 

## Appendix B: Reward Calculation Formula and Details

### General notations

-   N: the current number of validators, maximum of N = 1..150
-   $M_1$, $M_2$, .., $M_N$: the set of validators in the current epoch
-   $C_1$, $C_2$, .., $C_N$: the number of signatures a validator has made
-   $S_1$, $S_2$, .., $S_N$: the total amount of staked (including deposited and voted) TAO for a validator
-   $D_1$, $D_2$, .., $D_N$: the amount of deposited TAO by a validator
-   X: the total reward per epoch for all validators
-   Total reward per validator = Infrastructure reward + staking reward
-   MN: stand for validator

Reward divided to Validator $M_i$: 			$R_i = \frac{C_i*X}{\sum_{i=1}^{N}C_i}$

Reward per epoch:   

-   Validator infrastructure reward: 		0.4$R_i$

-   Voter with 1k voted TAO: 				$\frac{0.5R_i*1000}{S_i}$

-   Validator staking reward: 			$\frac{0.5R_i*D_i}{S_i}$

Reward per week (48 * 7 = 336 epochs):
	
-   Validator infrastructure reward: 		336 * 0.4$R_i$

-   Voter with 1k voted TAO: 				336 * $\frac{0.5R_i*1000}{S_i}$

-   Validator staking reward: 			336 * $\frac{0.5R_i*D_i}{S_i}$

Reward per year (48 * 365 = 17520 epochs):

-   Validator infrastructure: 				17520 * 0.4$R_i$

-   Voter with 1k voted TAO:				17520 * $\frac{0.5R_i*1000}{S_i}$

-   Validator staking reward: 			17520 * $\frac{0.5R_i*D_i}{S_i}$

-   Total reward for a validator:		17520 * 0.4$R_i$ + 17520 * $\frac{0.5R_i*D_i}{S_i}$

### Applying the reward calculation formula to specific scenarios 

Note that, for simplification of illustration: 

-   The total amount of staked TAO for all validators is equal 

-   The signatures for all validators in the scenarios are equal 

With these assumptions, all validators receive the same divided reward (R) and the same infrastructure reward. 
Furthermore, the reward for Voters with 1k voted TAO is equal regardless of which the amount is voted for.

### Scenario 1: 50 Validators, 2.5 million token voting, a total of 7.5 million token locked.

N = 50, X = 360, $S_1 = S_2 = .. = S_{50} = 5 000 000 / 50 = 100k$ TAO

$C_1 = C_2 = .. = C_{50}$

Therefore, $R_1 = R_2 = .. = R_{50} = R = X/50 = 7.5$ TAO

#### Reward per epoch:

-   MN infrastructure reward = 0.4 * 5 = 2 TAO

-   For Voter with 1k voted = (0.5 * 5 * 1000) / 100k = 0.025 TAO

-   MN staking reward with 100k TAO deposited: 100 * 0.025 = 2.5 TAO

#### Reward per week: 
   
-   MN infrastructure reward = 336 * 2 = 672 TAO
   
-   For Voter with 1k voted = 336 * 0.025 = 8.4 TAO
   
-   MN staking reward with D = 100k TAO deposited: 336 * 2.5 = 840 TAO

#### Reward per year: 
   
-   MN infrastructure reward = 17520 * 2 = 35 040 TAO

-   For Voter with 1k voted = 17520 * 0.025 = 438 TAO

-   MN staking reward with 100k deposited: 17520 * 2.5 = 43800 TAO

-   Total reward per MN with D = 100k deposited: 35 040 + 43 800 = 78 840 TAO

### Scenario 2: 100 Validators, 3 million token voting, a total of 13 million token locked.

N = 100, X = 360, $S_1 = S_2 = .. = S_{100} = 13 000 000 / 100 = 130k$ TAO

$C_1 = C_2 = .. = C_{100}$

Therefore, $R_1 = R_2 = .. = R_{100} = R = X/100 = 3.6$ TAO

#### Reward per epoch:
    
-   MN infrastructure reward = 0.4 * 2.5 = 1 TAO

-   For Voter with 1k voted = (0.5 * 2.5 * 1000) / 80k = 0.015625

-   MN staking reward with D = 100k deposited: 100 * 0.015625 = 1.5625 TAO

#### Reward per week: 
   
-   MN infrastructure reward = 336 * 1 = 336 TAO
   
-   For Voter with 1k voted = 336 * 0.015625 = 5.25 TAO
   
-   MN staking reward with D = 100k deposited: 336 * 1.5625 = 525 TAO

#### Reward per year: 

-   MN infrastructure reward = 17520 * 1 = 17 520 TAO

-   For Voter with 1k voted = 17520 * 0.015625 = 273.75 TAO

-   MN staking reward with D = 100k deposited: 175 20 * 1.5625 = 27375 TAO

-   Total reward per MN with D = 100k deposited: 17 520 + 27 375 = 44875 TAO

### Scenario 3: 150 Validators, 12.5 million token voting, a total of 27.5 million token locked.

N = 150, X = 360, $S_1 = S_2 = .. = S_{150} = 27 700 000 / 150 = 183 333.33$ TAO

$C_1 = C_2 = .. = C_{150}$

Therefore, $R_1 = R_2 = .. = R_{150} = R = X/150 = 2.4$ TAO

#### Reward per epoch:

-   MN infrastructure reward = 0.4 * 1.6667 = 0.6667 TAO

-   For Voter with 1k voted = (0.5 * 1.6667 * 1000) / 133 333 = 0.00625 TAO
    
-   MN staking reward with 100k deposited: 100 * 0.00625 = 0.625 TAO

#### Reward per week: 

-   MN infrastructure reward = 336 * 0.6667 = 224 TAO

-   For Voter with 1k voted = 336 * 0.00625 = 2.1 TAO
   
-   MN staking reward with D = 100k deposited: 336 * 0.625 = 210 TAO

#### Reward per year: 
   
-   MN infrastructure reward = 17520 * 0.6667 = 11 680 TAO
   
-   For Voter with 1k voted = 17520 * 0.00625 = 109.5 TAO
   
-   MN staking reward with D = 100k deposited: 175 20 * 0.625 = 10950 TAO
   
-   Total reward per MN with D = 100k deposited: 11 680 + 10 950 = 22630 TAO


