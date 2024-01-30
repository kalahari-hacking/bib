# Bibliography

## In Proceedings of the 12th USENIX Security Symposium, 8 2003.

S. A. Crosby and D. S. Wallach. Denial of service via algorithmic com-
plexity attacks. 

> We present a new class of low-bandwidth denial of service attacks 
> that exploit algorithmic deficiencies in many common applications’ 
> data structures. Frequently used data structures have “average-case”
> expected running time that’s far more efficient than the worst 
> case. For example, both binary trees and hash tables can 
> degenerate to linked lists with carefully chosen input. We show 
> how an attacker can effectively compute such input, and we 
> demonstrate attacks against the hash table implementations in two 
> versions of Perl, the Squid web proxy, and the Bro intrusion 
> detection system. Using bandwidth less than a typical dialup 
> modem, we can bring a dedicated Bro server to its knees; after six 
> minutes of carefully chosen packets, our Bro server was dropping as 
> much as 71% of its traffic and consuming all of its CPU. We show 
> how modern universal hashing techniques can yield performance 
> comparable to commonplace hash functions while being provably 
> secure against these attacks.

<https://www.usenix.org/legacy/events/sec03/tech/full_papers/crosby/crosby.pdf>
