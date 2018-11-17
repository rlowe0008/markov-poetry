# Markov Poetry
Markov Poetry is a Web app that generates poetry using Markov Chains. 

### What is a Markov Chain?
> A Markov chain is a stochastic model describing a sequence of possible events in which the probability of each event depends only on the state attained in the previous event.
[Wikipedia](https://en.wikipedia.org/wiki/Markov_chain)

In this page the 'event' is the selection of the next word in the poem, so each word is selected based on the likelihood of that word following the preceeding word.

- [A good explanation of Markov Chains](http://setosa.io/blog/2014/07/26/markov-chains/)

In this example, a dictionary of rhyming words was parsed by a Python program to form sets of rhyming words, which are randomly selected based on the given rhyme scheme. Lines are then constructed in reverse, with the preceeding word randomly selected from a list of words likely to come before that word.

Text was taken from various sources across the web, largely from [Project Gutenberg](https://www.gutenberg.org/wiki/Main_Page).
