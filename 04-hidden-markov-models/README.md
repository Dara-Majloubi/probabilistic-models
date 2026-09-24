# Hidden Markov Models

Implementation and evaluation of inference and learning algorithms for discrete Hidden Markov Models (HMMs) using Python and NumPy.

## Overview

This section focuses on probabilistic inference and parameter learning in Hidden Markov Models.

The notebooks cover both inference with known HMM parameters and learning HMM parameters from observed sequences.

## Methods

### HMM Inference

The inference notebook implements:

- Forward algorithm for filtering
- Future-state prediction
- Stationary distribution
- Backward algorithm
- Forward-backward smoothing
- Viterbi decoding

### HMM Learning

The learning notebook implements:

- Likelihood forward messages
- Backward messages
- HMM sequence sampling
- Observation-sequence log-likelihood
- Baum-Welch parameter learning (Expectation-Maximization)

## Experiments

The notebooks use discrete HMM examples to evaluate:

- Filtering and prediction over observation sequences
- Smoothed posterior state distributions
- Most probable hidden-state sequences
- Sampling from an HMM
- Observation-sequence likelihood
- Parameter estimation from multiple observation sequences
- Training and test log-likelihood

## Notebooks

### 1. HMM Inference

`hmm_inference.ipynb`

Covers filtering, prediction, stationary distributions, backward messages, smoothing, and Viterbi decoding.

### 2. HMM Learning

`hmm_learning.ipynb`

Covers likelihood messages, HMM sequence generation, log-likelihood computation, and Baum-Welch parameter learning.

## Technologies

- Python
- NumPy
- Jupyter Notebook
- Hidden Markov Models
- Probabilistic Graphical Models

## Key Concepts

- Hidden states
- Observation models
- Transition probabilities
- Filtering
- Prediction
- Smoothing
- Viterbi decoding
- Maximum-likelihood learning
- Expectation-Maximization (EM)
- Baum-Welch algorithm

## Shared Utilities

The notebooks use shared helper definitions such as the HMM data structure, example models, categorical sampling, and plotting utilities.

These helpers are kept separate from the notebook implementations so that the algorithms remain focused and readable.
