# Ghosbuster Pacman AI

## Project Description
In the "Ghostbusters" variant of Pacman, players navigate a world where Pacman, driven by the legends of his ancestor Grandpac, becomes a ghost hunter. However, the challenge is that these ghosts are invisible. The game employs a unique inference system, allowing Pacman to estimate ghost positions based on the noises they make. Through the project, we are assigned to leverage Bayes Nets for both exact and approximate inferences.

The primary objective is to refine ghost position estimations, aiding Pacman in his vengeful quest. The game interface provides players with fluctuating distance readings, indicating the proximity of the elusive ghosts.

<img src="assets/pacman.png" width="80%"/>

## Buster Agents
The GreedyBustersAgent is an AI-driven agent that aggressively approaches the closest ghost. The file emphasizes the belief distributions in estimating ghost positions and utilizes distance calculations to guide Pacman's actions.

## Factor operations
The factor operations module execute various operations on factors, which are the basic building blocks of a probabilistic graphical model, specifically Bayesian networks. The functions implement joint and elimination operations, which are fundamental in making inferences in a Bayesian network.

## Inference
Inference module establishes a robust framework for probabilistic reasoning within a game scenario featuring Pacman and ghosts. By leveraging a Bayesian Network, it models the intricate relationships among Pacman's position, the ghosts' whereabouts, and the observed distances from Pacman to these ghosts. With this structure in place, advanced probabilistic inference techniques can be applied to deduce the game state based on specific evidence, like the imprecise measurements of distances to the ghosts. In essence, this code underpins a sophisticated tracking system designed to precisely and swiftly ascertain a ghost's position in the game, factoring in observational uncertainties and game dynamics.
