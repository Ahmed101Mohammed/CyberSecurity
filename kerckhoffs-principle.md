# Kerckhoffs's Principle
- Believes only secrecy of the key provides security.
- Shannon's maxim state the enemy knows the system.
- It's very hard to keep the details of a popular algorithm secret. Thinking you're achieving security like this is called security through obscurity.
- To really make a robust encryption algorithm, is by let lots of cryptographers to try to find flaws.
- If you debend on an algorithm, if it hacked, you will need to change it in every place it used, but if you debend on key, it's easy to change the key, than the algorithm.
- You can switch keys over specific intervals to limit the impact of any potental leak.
- Switching between encrypton algorithms over intervals is not practical.

## Security through obscurity
- It's when you rely on the secrecy of the design and the implementaion of a system as your security.

- There could be many vulnerabilities in such a system. but if no one knows about a system or its flaws, according to security through obscurity, attacks can be prevented. Sounds like an ostrih sticking his head in the sand.