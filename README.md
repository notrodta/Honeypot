# Honeypot

Create a repository on Github with a README.md that includes a brief writeup about your experiment. Include the following details:

Which Honeypot(s) you deployed
Any issues you encountered
A summary of the data collected: number of attacks, number of malware samples, etc.
Any unresolved questions raised by the data collected
Additionally, include a json export of the data you collected in the repo, instructions for which can be found in the next section.

A Honeypot is a decoy application that intentionally exposes insecure features that when it is expolited by an attacker, it will reveal information about the methd, tools and possibly the identity of the attacker.

# Dionaea
The Honeypot I deployed is dionaea. The purpose of dionaea is to trap malware exploiting vulnerabilities exposed by serveces offered to a network. The goal is to gain a copy of the malware.

# Issues encountered
When setting up my Google Cloud Platform, my firewall was not properly set up. This caused me to be unable to load my external IP in my browser. This was eventually fixed.

# Summary
At the time of writing, thee MHN server has recorded 3,573 attacks.

![](https://imgur.com/a/5YCsR)

# Json Export
I have included a json export of the data I collected in the repo called `session.json`
