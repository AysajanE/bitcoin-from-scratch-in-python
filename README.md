# Bitcoin from Scratch in Python

A study-oriented reconstruction of core Bitcoin mechanics in Python.

This repository documents my effort to understand Bitcoin by re-implementing and working through the ideas in Andrej Karpathy's "Bitcoin in Python from Scratch" material, then extending that exercise with my own notes, supporting analysis, and testnet experimentation. The point of this repo is not to present a new Bitcoin library. The point is to demonstrate hands-on protocol literacy.

## Why this repo exists

- Learn Bitcoin at the code level rather than only from high-level summaries.
- Connect blockchain interest with practical understanding of transactions, signatures, scripts, and testnet execution.
- Produce a notebook that is readable for people coming from economics, management science, or data backgrounds.

## What is in the repo

- `bitcoin-in-python.ipynb`: the main walkthrough notebook for reconstructing Bitcoin transaction and wallet mechanics in Python.
- `bitcoin-statistics.ipynb`: supplementary exploration of Bitcoin market and network data.
- `*.csv`, `*.json`, `*.png`: supporting datasets and plots used in the notebooks.

## Scope and attribution

This repository is inspired by:

- Andrej Karpathy's blog post: http://karpathy.github.io/2021/06/21/blockchain/
- Andrej Karpathy's reference repo: https://github.com/karpathy/cryptos

The underlying learning path and many of the concepts originate there. This repo is a personal reconstruction and study artifact, not a claim of authorship over the original teaching material. I wrote the notebook work myself as a way to internalize the implementation details and added context where helpful.

## What the work covers

- Bitcoin transaction structure
- Keys, signatures, and script validation
- UTXO-style reasoning
- End-to-end testnet transaction work
- Supporting descriptive analysis of Bitcoin data

## Running the notebooks

Open the notebooks in Jupyter and work through them in order:

```bash
jupyter notebook
```

Recommended starting point:

1. `bitcoin-in-python.ipynb`
2. `bitcoin-statistics.ipynb`

## References

- Satoshi Nakamoto, *Bitcoin: A Peer-to-Peer Electronic Cash System*: https://bitcoin.org/bitcoin.pdf
- Andrej Karpathy, *Bitcoin in Python from Scratch*: http://karpathy.github.io/2021/06/21/blockchain/


