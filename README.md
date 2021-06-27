**Formalizing the Blockchain-based BlockVoke Protocol for Fast Certificate Revocation Using Colored Petri Nets**

This repository hosts appendix files for the BlockVoke publication

# Abstract #
Protocol flaws such as the well-known Heartbleed bug, security and privacy issues, or incomplete specifications, in general, pose risks to the direct users of a protocol and further stakeholders. Formal methods, such as Colored Petri Nets (CPNs), facilitate the design, development, analysis, and verification of new protocols, the detection of flaws and the mitigation of identified security risks. BlockVoke is a blockchain-based scheme that decentralizes certificate revocations, allows certificate owners and certificate authorities to revoke certificates, and rapidly distributes revocation information. CPNs in particular are well-suited to formalize blockchain-based protocols -- thus, in this work, we formalize the BlockVoke protocol using CPNs, resulting in a verifiable CPN model and a formal specification of the protocol. We utilize an agent-oriented modeling (AOM) methodology to create goal models and corresponding behavior interface models of BlockVoke. Subsequently, protocols semantics are defined, and the CPN models are derived and implemented using CPN Tools. Moreover, a full state-space analysis of the resulting CPN model is performed to derive relevant model properties of the protocol. The result is a complete and correct formal BlockVoke specification used to guide future implementations and security assessments.

# Appendix Files#

* [BlockVoke CPN Model](./2021-05-31_BlockVoke-Journal-Paper--MDPI/20210530_BlockVoke--CPN-v04.cpn "BlockVoke CPN Model") 
  This file provides the BlockVoke CPN Model compatible with [CPN Tools](https://cpntools.org/) version 4.0.1

* [BlockVoke CPN Model Protocol Semantics](./2021-05-31_BlockVoke-Journal-Paper--MDPI/20210530_BlockVoke--CPN-Protocol-Semantics.pdf "BlockVoke CPN Model Protocol Semantics") 
  This document provides the complete Protocol Sematics for the BlockVoke CPN Model

* [BlockVoke Behavioural Interface Model](./2021-05-31_BlockVoke-Journal-Paper--MDPI/20210530_BlockVoke--BIM.pdf "BlockVoke Behavioural Interface Model") 
  This docuement provides the complete Behavioural Interface Model for BlockVoke

* [BlockVoke Agent-Oriented Goal Model](./2021-05-31_BlockVoke-Journal-Paper--MDPI/20210530_BlockVoke--AOM-Goal-Model.pdf "BlockVoke Agent-Oriented Goal Model") 
  This docuement provides the complete Agent-Oriented Goal Model for BlockVoke

* [BlockVoke CPN Model state space report](./2021-05-31_BlockVoke-Journal-Paper--MDPI/20210528_BlockVoke--State-Space-Analysis-v4.txt "BlockVoke CPN Model state space report") 
  This file provides the state space report for the BlockVoke CPN Model, computed using the state space tool of [CPN Tools](https://cpntools.org/) version 4.0.1


