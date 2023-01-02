Distributed key generation is a main component of threshold cryptosystems. It allows \\(n\\) participants to take part and generate a pair of public key and secret key according to
the distribution defined by the underlying cryptosystem without having to rely on a trusted party (dealer). Each participant in additional receive a partial secret key and a partial public key. While the public key is output in the clear, the private key is maintained as a (virtual) \\(t,n\\) secret shared via a secret sharing scheme, where each share is the partial secret key of a participant {{#cite GJKR99}}. No adversary is able to learn anything about the secret key if it does not control the required amount of participants.