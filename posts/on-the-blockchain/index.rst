.. title: On the Blockchain
.. slug: on-the-blockchain
.. date: 2019-11-16 13:01:59 UTC
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
.. has_math: true

.. include:: common.rst

After a few months investigation it is time to report. Here it is: the Good, the
Bad, and the Ugly of the blockchain as |I| see it. You may whistle the
appropriate `theme tune`_ yourself if you like and imagine me dirty, bearded and
wearing a poncho.

.. _`theme tune` : https://www.youtube.com/watch?v=LQGGQ-FCe_w

.. TEASER_END

The Good
========
Years ago, when git was first released |I| thought to myself that there was an
awful lot more that could be done with its ideas than just version control.
Blockchain shares some these ideas: `Merkle trees`_, `cryptographic hashes`_.
This is all fascinating and clever stuff. |I| will not lecture on it here. Go
investigate and appreciate the elegance yourself.

.. _`Merkle trees` : https://en.wikipedia.org/wiki/Merkle_tree
.. _`cryptographic hashes` : https://en.wikipedia.org/wiki/Cryptographic_hash_function

The Bad
=======
Show me a use case, an honest use case that actual needs a blockchain. Not just
makes use of blockchain, but needs it and uses it to fully replace trust, or
centralization. As |I| see it, blockchain systems such as Bitcoin and Ethereum
offer perhaps half of what they claim. Yes, they have changed things, but they
have not eliminated much of what they claim; they have simply moved it elsewhere.

The technology does offer a novel combination of features, but it does
not eliminate all that it claims. Decentralized trust? Well, yes, the trust
model has been changed, but trust is still required. Anonymity? Well, my wallet
may be based on a public private key pair, but every transaction made is
permanently and publicly visible. A little bit of traffic analysis and world and
dog can know exactly what |I| have been up to now and throughout all the past.

|I| also suspect that there are twice as many crooks involved as even a skeptic
like myself would guess. Some very smart people are in the space, but there are
a lot of plain old fashioned con men and woman, too.

The Ugly
========
And finally, the ugly -- Proof of Work. Before investigating blockchain
this sounded dodgy due to purely ecological considerations, but |I| have
discovered more about it |I| dislike. Proof of Stake unfortunately suffers the same
problem. Let me explain.

The decentralized consensus that is so prized in blockchain technologies depends
upon the difficulty of finding cryptographic hashes. Quite elegantly, it is easy
to verify that one has a particular hash, while it is very difficult to calculate
it in the first place. For "difficult" here you may read "requires a *lot* of
computing resources." This is what leads to the horrible but true reports that
Bitcoin mining uses more electricity than many small countries. Computers these
days run on electricity after all.

The consensus oif a blockchain, its distributed "truth," relies on the compute
power that individuals are willing to spend. This incidentally leads to the 51%
chain attacks that you read about. A coalition of 51% of miners can take over a
chain and write what ever truth they want. The security of a blockchain is based
on economic incentives; spend enough money and bingo! You're the boss.

Think about this for a moment. Many years ago a man once wisely sung_, "Meet the
new boss. Same as the old boss." Does blockchain really change anything here?
In our unfortunate world, "truth" appears to be whatever gets shouted the
loudest. Want to control the truth? Well, buy into the main stream media. Sure,
it costs a lot, but it can be done [*cough, cough* Bezos *cough* WaPo *cough*].

.. _sung : https://www.youtube.com/watch?v=zYMD_W_r3Fg

Want to control the truth in a blockchain world? Simply buy a lot of compute
powerr. Sure it may trash the emvironment, but since when have people cared about
that? All it takes is compute power; i.e electricity; i.e. money.

What has changed?

Hands up who remembers Harry Enfield? Do we really want our truth to be determined
by `this guy`_ ? The conspicuous spending of Bitcoin mining is fine for defining
fashion, but not for guaranteeing Truth. While |I| personally do not go in for
expensive wrist watches or trendy footwear, |I| certainly do *not* want
"LoadsAMoney" determining my truth. That has only brought pain up to now.

.. _`this guy` : https://www.youtube.com/watch?v=ON-7v4qnHP8
