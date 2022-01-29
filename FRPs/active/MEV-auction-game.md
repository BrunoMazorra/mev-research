---
id: 
title: MEV Auction equilibrium
team: @obadiaa @fiiiu @BrunoMazorra
created: 2022-01-24
---

# MEV Auction games

## Background and Problem Statement
In [Flashboys 2.0.]( https://arxiv.org/pdf/1904.05234.pdf) Philip Daian et al. proposed a formalization of the price gas auction (PGA) model and proved mathematically and empirically the existence of Grim-Trigger Nash equilibrium under certain constraints. However, different chains and protocols emerged, such as Polygon and mev-geth. This induced to new MEV auction games, that could  potentially bring new incentives to searchers. Leading to different Nash equilibrium strategies, negative externalities and validators expected revenue.

The goal of this FRP is to survey the games and the Nash equilibrium of MEV extraction in PGA auctions, private mempools, Flashbots auctions, and the composition of all of them. Further, we will initially focus on a proper game theory formalization of latency, gas optimization, extractable value optimization, and action space of the games. With a proper formalization, we expect to find and characterize all the Nash equilibrium of MEV auction games, providing data and mathematical proofs to show the results obtained. We suspect that in each game, the players will have different strategies such as spamming, cartelizing, censoring and/or improving geographic localization to maximize their payoff.

## Plan and Deliverables

- Formalize the PGA in different domains and the Flashbots Auction game.
- Try to provide a universal framework that parametrize all standard MEV-auction games,
- Try to find all Nash equilibrium strategies in the MEV auction game. Moreover, precise the existence of evolutionary stable Nash equilibrium strategies.
- Provide data of different chains (Polygon, Bsc, AVAX, Arbitrum,...) and extractable value domains (Arbitrage, Liquidations,...) to contrast with the theoretical results obtained. 
- Compare the negative externalities on users and searchers of these MEV auctions games.
- If the results are accurate enough, provide a new tool in the MEV explorer that characterizes the competitiveness of MEV extraction in different domains and chains.



## References

- [MEV in 2021](https://www.youtube.com/watch?v=V_wlCeVWMgk&ab_channel=Flashbots)
- [Flashboys 2.0.](https://arxiv.org/pdf/1904.05234.pdf)
- [Evolutionary games](https://www.researchgate.net/publication/225998108_Evolution_in_games_with_a_continuous_action_space)
- [MEV explorer](https://explore.flashbots.net/)
- [Auction theory](http://www2.econ.iastate.edu/tesfatsi/AuctionTheoryGuideToLit.Klemperer.pdf)
