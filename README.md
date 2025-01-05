# Identifying Critical Touchpoints in Purchaser Journey

## Background
This project leverages a Markov Chain model to analyze and better understand the sequence of interactions in a purchaser's journey. By modeling the transitions between various customer interactions, the analysis identifies which touchpoints are most likely to lead to a purchase. This insight can inform strategic decisions in multiple areas, including:
- Multi-Touch Attribution: Assigning credit to different touchpoints in the marketing funnel to understand their impact on purchases.
- Web Journey Optimization: Identifying high-impact interactions to improve the user experience and drive purchases.
- A/B Testing Recommendations: Highlighting areas in the purchaser's journey where experiments could optimize purhase rates.

## Technique
The Markov Chain method is helpful in understanding how individuals move through a series of steps, pages in a website, or series of actions. This approach evaluates the liklihood of transitioning from one "state" to the next. By treating each action as a state and calculating the probabilities of transitioning from one state to another, the Markov Chain method can help identify the most impactful touchpoints. This method can also be used to evaluate removal effects, by determining how removal of a state will impact the overall flow of actions.

## Data Overview
The dataset was created by ChatGPT and mimics individual events for prospective purchasers.
