---
title: Will fully homomorphic encryption break the big data market?
date: 2022-02-10 23:11:11
tags:
  - fhe
  - fully homomorphic encryption
  - data harvesting
  - big data

categories:
  - thoughts
---

# What is fully homomorphic encryption?

<p>Fully homomorphic encryption (FHE), often considered the holy grail of cyber-security by the experts (Van Dijk and Juels, 2010)<sup>[1]</sup>, is
an emerging, but not new concept which allows computations on encrypted data.</p>

<p>Taking regular encryption, if the encrypted data would be required to be modified, the data would first need to be
decrypted, altered with the desired computations and then re-encrypted.</p>

<p>FHE allows applications to perform the desired computations without ever having the need to decrypt
the original data, preserving the end-to-end privacy.</p>

![Fully homomorphic encryption diagram](images/fhe-and-data-harvesting-market/fhe-diagram.png)

## So what is the big deal about it?

<p>Due to the nature of FHE not requiring the data to be decrypted to perform calculations,
privacy becomes a lot easier, where users would be able to delegate computation to 3rd parties
such as cloud providers, where the cloud provider wouldn't have access to the users data at all,
keeping the secrets secret only for the data owner who has the private key.</p>

<p>In today's world, security plays a big part in our every day life, especially when it comes to online security.
Take Google for example, in the midst of 2010, a Google employee was fired for reportedly accessing
communications of at least four minors with Google accounts, spying on Google Voice call logs, chat transcripts
and contact lists<sup>[2]</sup>.
All of our messages, photos, even our life revolve around the internet in one form or another.</p>

<p>An implementation of FHE might have prevented this, where messages exchanged would have been performed over
some FHE supported protocol, where the data is only readable by the data owner, but communication could still proceed
via the use of FHEs unique behaviour of being able to compute on encrypted data.</p>

## Drawbacks of fully homomorphic encryption

<p>The main problem with fully homomorphic encryption at this day and age is performance.
Simply put, FHE is currently quite inefficient. Some simple operations can take anywhere from seconds to hours<sup>[3]</sup>.
There are trade-offs to speed it up, but at the cost of utility, and vice-versa, sacrificing performance for better utility.
The security could also be traded for better performance and utility, but what's the point?
This sort of becomes quite similar to the CAP theorem within databases, where any distributed data store can only provide two of the following three
guarantees: consistency, availability, partition tolerance. Or in FHEs terms, performance, utility, protection.</p>

## FHE and the big data market

<p>An internet user may not think twice about the data that they share on the internet.
However, the tin-foil security people will know how big the big data market actually is.
In U.S. alone, the big data market is estimated at $50.1 billion in 2021, with predictions that it will reach
$234.6 billion by 2026<sup>[4]</sup>.</p>

<p>Big data is generated from a variety of sources, such as, RFID readers, social networks, sensor networks, internet text and documents, call registers,
internet search indexing, scientific research studies, medical records, military surveillance, and eCommerce among others.
Big data comprises gathering, analyzing, and using massive amounts of digital information to improve business operations, such as: Getting a 360-degree view of their audiences.</p>

![Big data life-cycle](images/fhe-and-data-harvesting-market/big-data-lifecycle.png)

<p>Big data also comes with a risk. If data falls into the wrong hands, it can be used for targeted phishing, scams and spread disinformation<sup>[5]</sup>.
Every year the number of data breaches increase, which just shows how important it is to keeping our data secure.</p>

<p>With the help of FHE, people would be able to ensure the safety of their data within sites such as social media or even within the government.
This begs the question: what will happen to the big data companies if FHE becomes a modern practice and the performance issues have been resolved?</p>

<p>How would the big data companies be able to harvest the data if the data is encrypted? Without having access to the decrypted data,
big data companies would not be able to perform the normal processing of data, no phone number extractions, no medical records, no usable digital information.
This would surely spell out a disaster for them, as their data is no longer a 360-degree view of the audience, but rather of some scrambled nonsense bits and bytes.
Benefit for the common internet user, destroying the big data market.</p>

<p>On the other hand, there may be a push to focus elsewhere. Rather than the actual information, big data could shift their focus to the functions performed on the data.
A move towards processing and analysing the functions performed on data encrypted with FHE could still allow analysis and processing of data, but move the focus
towards what is actually being done with the data.</p>

<p>Because companies now wouldn't be dealing with what may have been private users data, this could even spark a wider
boom in the big data market, where it's easier for companies to be on track in terms of different laws and governance around data, such as GDPR, and making data breaches far less
impactful for the regular customers.</p>

<p>But for now, we are still far away from this dream that fully homomorphic encryption promises us.</p>

## Resources
- [1] - [On the Impossibility of Cryptography Alone for Privacy-Preserving Cloud Computing](http://www.arijuels.com/wp-content/uploads/2013/09/vDJ10.pdf)
- [2] - [Ex-Googler Allegedly Spied on User E-Mails, Chats](https://www.wired.com/2010/09/google-spy/)
- [3] - [Implementing Gentry’s Fully-Homomorphic Encryption Scheme](https://link.springer.com/chapter/10.1007/978-3-642-20465-4_9)
- [4] - [Global Big Data Market to Reach $234.6 Billion by 2026 ](https://www.prnewswire.com/news-releases/global-big-data-market-to-reach-234-6-billion-by-2026--301322252.html)
- [5] - [Is Big Data Dangerous?](https://careerfoundry.com/en/blog/data-analytics/is-big-data-dangerous/)
- [Fully Homomorphic Encryption](https://www.sciencedirect.com/topics/computer-science/fully-homomorphic-encryption)