# Bitcoin from Scratch in Python

Reference: http://karpathy.github.io/2021/06/21/blockchain/

In this notebook, I will explore Bitcoin protocol from scratch. Bitcoin was proposed in the white paper "Bitcoin: A Peer-to-Peer Electronic Cash System" 
(can be found here: https://bitcoin.org/bitcoin.pdf) in August 2008 by Satoshi Nakamoto, whom to date we still don't know much about.

It has been quite some time that I want to know more about Bitcoin, from both a technoplogy perspective and monetary policy perspective. 
Luckily sometime last year I discovered this excellent blog post by Andrej Karpathy about implementing Bitcoin from scratch in Python without using any dependencies. 
There is no better way of learning something new from doing it, experimenting it yourself. So I decided to re-do what Andrej did once I had time.

Finally, it is time for this exploration. 

In this notebook, I redo what Andrej did line by line. There is no copy-paste, only typing line by line and understanding what those
lines of codes do and why. At the end, I also broadcast my transactiion to the Bitcoin testnet to see if it works properly (and it did). 
I tried to do the bonus exercise at the end (steal all of Andrej's BTC from one of his testnet wallets) but having issues with signatures, 
even though I believe I did everything correct. I will play around with it a little bit more.

Note that many of the words in the notebook are also his. So most of the credit goes to Andrej Karpathy. He did such an excellent work and shared with Internet.
I merely typed out everything he did while trying to understand the mechanism behind Bitcoin. 
Additionally, I added explanations for some of the context that I was not familiar with. 

This entire process was extremely beneficial and valuable.



