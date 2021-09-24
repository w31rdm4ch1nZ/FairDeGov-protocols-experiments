# FairDeGov - and its threat modeling resulting design
**[BRAINSTORMING PHASE]** - Ideas for a simple DeGov design template for a "hypercryptoized" world. Heavily influenced by Vitalik Buterin and Jean-Philippe Vergne works.


*Criteria for a governance process, in context of DeGov or a DAO:* 

- avoid the *unfairness* arising with advantage on the first movers/earlys investors in the governance, and the one linked to already existing capital of an actor in the DAO (be it acquired with the protocol or outside it) => leads to a kabbalah (relatively *unfair information and decision distribution*).
   → all based on the core assumption that people acting for the common good, or any optimal outcome for a common good should factor the commitment of an individual in the protocol building (assuming goals of the protocol are not anymore in the discussion phase and have been formlaized clearly, under the definition of a policy on-chain or mixing off-chain and on-chain - more on that later). It certainly requires a mixture of metrics. 
- which leads to the following, allowing new comers the same degree of acces to information and decision as the early inverstors now have. Basically, designing and implementing mechanisms that are running backward the accumulation of power position in a (e.g. DeFi) protocol. What does it mean concretely?
   → enabling a scoring system that can then be used to weigh in protocol's voting events - through POAP (which very interestingly opens the door to another criteria than the dominant “more skin in the game ⇔ more money at stake” used in proof-of-stake mechnanisms, or simply by holding more token (which can be bought on an open market like DEXs and CEXs). So it becomes harder for this protocol to get hijacked by billionaires or big corporations/investment funds. 
   → enabling every new comers to have acessible the information so anyone motivated can jump in the discussions and make informed decisions regarding the protocol, from how and when to use it at ones best advantage, to discussing in an argumented way vote proposition and voting. (again, vs. kabbalah/esoteric knowledge) => see OlympusDAO for their impressive work on both aspects (the POAP being used - I don't know if it's then used other than for a “status/social recognition”... but in any case it could be)

Another threat is price manipulation and extreme volatility events (encompassing the ones that are consequences of malicious intent, and the "accidental" ones):
- Is a governance token that is issued through the standard ERC20 (for Ethereum), meaning transferrable, and with liquidity on markets (DEXs and CEXs) an actual good solution for governance? It might be the result of a design flaw when bundling several functions in one (that might be better achieved through seperate vehicles)?:
   →  protocols' users incentivization by rewarding them through, following the dominant model (as far as Iknow) staking (protocol stability built on staking) -> issuing a gov token (the same that supports a protocol's inflow necessary to maintainting its function, directly or indirectly) -> making this token transferrable and creating markets for it.


Great use case (no need for other retributions to the user than the use case itself) and “minimal governance” (a la rari capital), maximum algorithmic on-chain "gov" is still I think the optimal solution to most threats on a protocol. 
But some protocols need sub-optimal solutions as they require more flexibility.
	-> to flesh it, think of a Web3 dApp vs. a stablecoin = I think a stablecoin has to aim at reducing to almost 0 the off-chain and manual governance, while a Web3 dApp should require in many case off-chain and human gov as part of the core-logic of its use case.
