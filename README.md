# Karna

## Overview

Karna is an Hyperledger fabric-based Decentralised Application that enables charities to collect and track their donations directly on the blockchain. The decentralised nature of blockchain allows users to see all of their donations in one place, as well as a transparent view of how their donations were used.

## Features

* Realtime financial transparency in charity donation and distribution.
* Donation can be tracked from any part of the world which ensures trust and supports charity without the fear of the money being used for other reasons.
* Users can also choose to receive a refund if a given cause fails to achieve its goals stated on the platform.

## Workflow

All the organisations will be able to list out some causes for which they are collecting funds as charity. Each cause will also have a final amount to be collected. Donors can donate to these cause(s) listed out by the organisation(s).  If any of the transactions doesn't reach the end cause for any reason, then the smart contract would ensure that the amount is reverted to the donor. Also, all the donors will be able to track their amounts as it goes through the organisations to aid the final cause.

## Impact on society

* People will get motivated to contribute to social causes. Currently, the majority of people have trust issues on the organisation collecting funds, especially in India. This application will prove really useful in raising charity, for example in cases like Kerela Relief Funds, funds for the cause of martyred members of CRPF, etc.
* This will also boost up the spirit of NGOs and social enterprises to contribute to the cause because use of blockchain will ensure that any middleman involved does not alter the actual transaction started by the donor.

## Communication

Please join our Karna channel on Discord server at https://discord.gg/7Dykj7d to discuss anything regarding the project.


## Install and contribute
```Open Git BASH on Windows or Terminal in Linux/MacOS and enter the following: 
$ git clone https://github.com/dsciitpatna/Project-Karna.git
```

* You should Discord server to stay connected with mentors and other contributors.
* Raise an issue before making Pull Requests.

## Implementation
    Karna is implemented on Hyperledger-fabric network **Dnation Network**
###### Players of Donation Network
 **Peers :**
1.NGOs : NGO peers propose project to be funded by Donors.
2.Validation Authority (VA) : Validation Authority (VA) will register valid NGO to the Donation Network. Validation Authority is also responsible for endorsing every donation request generated                               by donor.
**Orderer :**
1.Validation Authority is itself will provide ordering service for Donation network.
###### About Project
In the Donation network **Project** are plan proposed by the NGO to solve any problem in our socity.Projects can be created by any NGO present in **Donation Network**.Every Project will have pre-defined cases at which will remaining money will revert back to donors.Any function like *giveDonation* to project should be endorsed by all the Validation Authority and NGO who have proposed that project. 

## Technology stack to be used for the project

* Golang
* Docker
* Basic knowledge of how transaction works in Hyperledger-fabric would also help.