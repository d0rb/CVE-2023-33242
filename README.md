# CVE-2023-33242
CVE-2023-33242  PoC
The simulated Lindell17 protocol is vulnerable to a bit extraction exploit, allowing an attacker to recover the private key by iteratively extracting individual bits of the key. The protocol is designed to generate ECDSA signatures in a client-server model, with each party holding a share of the ECDSA secret key. The vulnerability lies in the mishandling of aborts during signature attempts, enabling the attacker to extract bits of the secret key over multiple iterations.
