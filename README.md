# Lecture Slides

- [Lecture 1 2019-10-01](./2019-10-01.pdf) Introduction, Systems and e-mail recovery.
- [Lecture 2 2019-10-04](./2019-10-04.pdf) Safety VS Security, Security Terminology, Introduction to Spectre/Meltdown. [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture2-specter-meltdown)
- [Lecture 3 2019-10-08](./2019-10-08.pdf) Buffer overflow, refresher on assembly, refresher on stack and some countermeasures. [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture3-buffer-overflow)
- [Lecture 4 2019-10-11](./2019-10-11.pdf) Canary, Guard Page, Bound Checking, Fat addresses and Worms. check associated reading material [here](https://github.com/bris-sys-sec/reading/tree/master/lecture3-buffer-overflow) and [there](https://github.com/bris-sys-sec/reading/tree/master/lecture4-worms)
- [Lecture 5 2019-10-15](./2019-10-15.pdf) Concurrency-related vulnerabilities, examples (access system call, how not to implement access control and dirty cow). [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture5-concurrency)
- [Lecture 6 2019-10-18](./2019-10-18.pdf) Browser security, same origin policy, XSS, DNS exploit, (not) private browsing. [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture6-browser)
- [Lecture 7 2019-10-22](./2019-10-22.pdf) Client side timing attacks. [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture7-timing-attack)
- [Lecture 8 2019-10-25](./2019-10-25.pdf) Public Key Infrastructure, Certificates. [RFC 5280](https://tools.ietf.org/html/rfc5280), [RFC 8446](https://tools.ietf.org/html/rfc8446)
- [Lecture 9 2019-10-29](./2019-10-29.pdf) Anonymous communication, anonymity, unlikability, unobservability, VPN, TOR. [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture9-anonimity), also have a look at this [RFC 8484](https://tools.ietf.org/html/rfc8484).
- [Lecture 10 2019-11-01](./2019-11-01.pdf) OSI Model, TCP stack, Type of Network attack, DNS poisoning, Slow Loris attack. [RFC 1180](https://tools.ietf.org/html/rfc1180)
- [Lecture 11 2019-11-05](./2019-11-05.pdf) Firewalls, DMZ, Linux IP table. [RFC 4948](https://tools.ietf.org/html/rfc4948)
- [Lecture 12 2019-11-08](./2019-11-08.pdf) Authentication, Password and its alternatives, 2FA. [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture11-authentication)
- [Lecture 13 2019-11-15](./2019-11-15.pdf) Access Control, RBAC, Bell Lapadula, Biba, Chinese Wall, Clark-Wilson Model [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture12-access-control)
- [(Guest) Lecture 14 and 15 2019-11-26](./2019-11-26.pdf) Fuzzing, Concurrency vulnerabilities [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture14-fuzzing)
- [Lecture 16 2019-12-06](./2019-12-06.pdf) Blockchain, Proof of Work, Transaction, Distributed Ledger [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture16-blockchain)
- [Lecture 17 2019-12-10](./2019-12-10.pdf) Virtual Machines, Containers, Unikernels and SGX [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture17-virtualisation-and-isolation)
- [Lecture 18 2019-12-13](./2019-12-13.pdf) Rootkit, ROP, Remote Attestation, Secure Boot and TPM [check associated reading material](https://github.com/bris-sys-sec/reading/tree/master/lecture18-rootkit-and-hardware)

# Exam and what to expect

The exam is divided into three parts:
- **Question 1** (30pt): 5 simple knowledge questions (e.g. What is proof of work and how can it be used?)
- **Question 2** (30pt): 2 problem. One covering material seen during the lectures, one covering material seen in Coursework 1.
- **Question 3** (40pt): **ONE** essay-style question to chose among three. One is based on material seen during courseworks, the two others on material seen only during lectures.

The goal of the exam is not to trick you. The questions are relatively simple and fair.
You won't be expected to write any code, but you should be able to explain to a technical audience how things work.

In addition, I strongly recommend you read (at least) the additional material associated with the following lectures:
- Lecture 3;
- Lecture 4;
- Lecture 12;
- Lecture 16;
- Lecture 17.
