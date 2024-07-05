---
title: "Code-based Cryptography"
layout: page
---

*[Historic record of description of my research topic _Code-based
Cryptography_ while I worked as Post-Doctoral Researcher at DTU
from 2011 to 2013].*

cbcrypto stands for _code-based cryptography_, a field that combines error-correcting codes and cryptography. Code-based cryptography provides alternatives to currently used state-of-the-art public-key cryptographic algorithms which do not hold up against quantum cryptanalysis. Learn more about post-quantum cryptography here [http://pqcrypto.org/](http://pqcrypto.org/) and here [https://csrc.nist.gov/Projects/Post-Quantum-Cryptography](https://csrc.nist.gov/Projects/Post-Quantum-Cryptography) .

### Motivation why we need alternative cryptosystems

Almost all data is nowadays stored electronically. Everyone is concerned with privacy and with secure handling of personal data. Banks, hospitals, governments, and private companies will only use encryption techniques which are well studied and which are easy to handle. Long-term storage of sensitive data requires higher security levels than a one-time key-exchange protocol on a cell phone. Data which needs to be stored securely for decades should be encrypted using algorithms which will not fall prey to attacks by future computing devices. The aim of this project is to look into alternative cryptosystems which also withstand attacks on quantum computers – machines which allow much more parallelism than conventional computers. Currently only small quantum computers have been built. Realizing a large quantum computer which can pose a threat to RSA and Elliptic-Curve Cryptography is an enormous challenge and it is unclear when physicists will succeed in building such machines. However, there is plenty of research going on: the [National Institute of Standards and Technology](http://www.nist.gov/index.html) (NIST) as only one example is massively supporting research in quantum physics.

### **My research on code-based cryptography**

As postdoctoral researcher I ran my own research project that was funded by a Technology and Production Sciences grant by the [Danish Council for Independent Research](http://fivu.dk/forskning-og-innovation/tilskud-til-forskning-og-innovation/hvem-har-modtaget-tilskud/2011/bevillinger-fra-det-frie-forskningsrad-2502-teknologi-og-produktion-2013-maj-2011) under grant number 11-105325. This was an individual postdoc grant with duration from September 2011 to November 2013.

#### Project description

Post-quantum cryptography deals with cryptosystems which run on conventional computers and whose security still holds up against quantum computers. A suitable candidate is _code-based cryptography_. The basic idea was developed by [Robert J. McEliece](http://ipnpr.jpl.nasa.gov/progress_report2/42-44/44N.PDF). Other than RSA and ECC code-based public-key cryptography has not shown any vulnerabilities to attacks with quantum computers and the best attacks on conventional computers and on quantum computers all take exponential time. The strength of McEliece's public-key cryptosystem is very fast encryption, but it is not used in practice as RSA and ECC provide much smaller key sizes. This does not mean that code-based cryptography is infeasible, it is just not competitive in a pre-quantum world. The main objective in code-based cryptography is to reduce the size of the encryption and decryption keys. The main idea behind reducing key sizes is to find alternatives to McEliece's choice of classical Goppa codes. The goal of this project is to examine generic and structural attacks to come up with alternative designs and to find good parameters and setups for various security levels.

### Workshops on Code-based Cryptography

I actively contributed to a couple of workshops on the topic. Here an overview:

- CBC 2009 - INRIA Rocquencourt, France (presentation) [https://www.rocq.inria.fr/secret/CBCrypto/](https://www.rocq.inria.fr/secret/CBCrypto/)
- CBC 2011 - Technische Universiteit Eindhoven, The Netherlands (co-organizer; in conjunction with my Ph.D. defense) [http://www.win.tue.nl/cccc/cbc/](http://www.win.tue.nl/cccc/cbc/index.html)
- CBC 2012 - Danmarks Tekniske Universitet, Denmark (organizer) [https://2012.cbc.pqcrypto.org/](https://2012.cbc.pqcrypto.org/)
- CBC 2013 - INRIA Paris, France (program committee)  [http://cbc2013.inria.fr/index.php?page=home](http://cbc2013.inria.fr/index.php?page=home)


