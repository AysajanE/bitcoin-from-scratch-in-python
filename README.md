# Bitcoin from Scratch in Python

Reference: http://karpathy.github.io/2021/06/21/blockchain/

Andrej Karpathy GitHub Repository: https://github.com/karpathy/cryptos

In this notebook, I will explore Bitcoin protocol from scratch by re-doing Andrej Karpathy's Bitcoin implementation from 2021 June. NOTE that this is Andrej Karpathy's intellectual work. I am merely re-implementing his implementation, with the goal of deepen my own understanding of Bitcoin's technical background. This is neither fork nor copy-paste. I wrote this entire notebook word by word.

Bitcoin was proposed in the white paper "Bitcoin: A Peer-to-Peer Electronic Cash System" 
(can be found here: https://bitcoin.org/bitcoin.pdf) in October 2008 by Satoshi Nakamoto, whom to date we still don't know much about.

It has been quite some time that I want to know more about Bitcoin, from both a technoplogy perspective and monetary policy perspective. And of course, I want to invest in BTC, so I need to know what I am putting my money into.
Luckily sometime last year I discovered this excellent blog post by Andrej Karpathy about implementing Bitcoin from scratch in Python without using any custom dependencies for Bitcoin. 
There is no better way of learning something new from doing it, experimenting it yourself. So I decided to re-do what Andrej did once I had time.

Finally, it is time for this exploration. 

In this notebook, I re-do what Andrej did line by line. There is no copy-paste, only typing line by line and understanding what those
lines of codes do and why. At the end, I also broadcast my transactions to the Bitcoin testnet to see if they work properly (and they did). 
I tried to do the bonus exercise at the end (steal all of Andrej's BTC from one of his testnet wallets) but having issues with signatures, 
even though I believe I did everything correct. I will play around with it a little bit more.

Note that many of the words in the notebook are also his. So most of the credit goes to Andrej Karpathy. He did such an excellent work and shared with everyone over the Internet.
Additionally, I added explanations for some of the context that I was not familiar with. My goal is to make it more accessible to someone who do not have technological beckground. 

This entire process was extremely beneficial and valuable. If you want to know what's under the hood of Bitcoin, this notebook can be an excellent place to start. 

Enjoy!!



