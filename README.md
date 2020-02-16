<img src="./img/header.png"> 

[![Stars on GitHub](https://img.shields.io/github/stars/simple-restricted-token/simple-restricted-token.svg?style=social)](https://github.com/simple-restricted-token/simple-restricted-token/stargazers)  [![Fork on GitHub](https://img.shields.io/github/forks/simple-restricted-token/simple-restricted-token.svg?style=social)](https://github.com/simple-restricted-token/simple-restricted-token/network/members)

*Designed with input from issuers, securities law firms, and exchanges.*

The EIP is open for comment [here](https://github.com/ethereum/EIPs/issues/1404).

## ERC-1404 in the Wild

### Books

[Security Tokens and Stablecoins](https://www.barnesandnoble.com/w/security-tokens-and-stablecoins-quick-start-guide-weimin-sun/1131505418) by Weimin Sun, Xun (Brian) Wu, Angela Kwok

### SEC Filings

[Aptorum Group Ltd. F-1 Filing](https://www.sec.gov/Archives/edgar/data/1734005/000121390019020694/ff12019a4_aptorumgroup.htm)

[Digital Innovative Ltd. F-4 Filing](https://www.sec.gov/Archives/edgar/data/1790515/000149315219018274/formf-4a.htm)

[Theseus Debt Fund N-2 Filing](https://www.sec.gov/Archives/edgar/data/1780267/000119312519189247/d97053dn2.htm)

[Arca US Treasury Fund N-2 Filing](https://www.sec.gov/Archives/edgar/data/1758583/000121465920001068/f26205n2.htm)

[Diginex Limited F-4/A Filing](https://www.sec.gov/Archives/edgar/data/1790515/000149315220001615/formf-4a.htm)

### Educational

[Example code implementation](https://github.com/bitcademyfb/bitcademy-erc1404)

[Hashgard.io Study](https://hashgard-io.oss-cn-hongkong.aliyuncs.com/Hashgard-Lab-STO-Report.pdf)

[DeFi Prime](https://defiprime.com/erc-1404)

### Community Deployments

[Enforcing FINRA Rule 3220](https://medium.com/tokensoft/fidelity-labs-completes-proof-of-concept-with-tokensoft-bd18cc8161d)  at Fidelity Investments

[Fairmint](https://github.com/Fairmint/c-org/wiki)

[Civil](https://github.com/joincivil/Civil)

[OpenLaw](https://twitter.com/r_ross_campbell/status/1211777786370822149?s=20)

[SablierHQ](https://www.sablier.finance/) [Example](https://twitter.com/r_ross_campbell/status/1221116412468645889?s=20)

[Elixxir](https://finance.yahoo.com/news/xx-network-announces-support-early-140000046.html)

[Smart Pharma Token and IDAX](https://www.businesswire.com/news/home/20190711005283/en/Smart-Pharma-Token-SMPT-Debuts-Initial-Listing)

[Sarson Funds and Vertalo](https://www.benzinga.com/pressreleases/19/12/p14948344/sarson-funds-leverages-vertalo-to-pick-winners-in-race-for-security-tokenization-protocol-narrowin)

### Chatter

[Ryan Adams](https://twitter.com/RyanSAdams/status/1187006051696173057?s=20)

[Ross Campbell](https://twitter.com/r_ross_campbell/status/1211777786370822149?s=20)

[DeFi Prime](https://twitter.com/defiprime/status/1133385315400507392?s=20)

## Video Walkthroughs

##### SF Cryptocurrency Devs Presentation on ERC-1404, Harbor R-Token, and Polymath ST-20

<a href="https://www.youtube.com/watch?v=DCCXEQfX0w8" target="_blank"><img src="/img/sfc-devs.png" width="300" border="10" /></a>

##### ERC-1404 and How Open-Source Standards will Accelerate Security Token Adoption

<a href="https://www.youtube.com/watch?v=qQQkn361niI" target="_blank"><img src="/img/blockchain-devs.png" width="300" border="10" /></a>

## Blog

### ERC-1404 Articles on Medium

Read more about ERC-1404, its features and benefits at our [Medium blog](https://medium.com/erc1404).

[ERC-1404 one year later](https://medium.com/tokensoft/erc-1404-one-year-later-1bf2d8c93432)

[ERC-1404 found in SEC filings](https://www.prnewswire.com/news-releases/ethereums-erc-1404-included-in-sec-filings-300943573.html)

## Features

### Know Your Token Holders

Know who your token holders are at all times and maintain a whitelist of investor addresses. From re-running sanctions checks to requiring accredited investors only, the simple restricted token standard helps token issuers manage their compliance requirements.

### Enforce Complex Restrictions

Enforce complex transfer restrictions. Such as: 

* A preventative poison pill provision, to restrict the maximum ownership of a single individual or entity. 
* The ability to prevent token holders in a single jurisdiction to trade with token holders in another jurisdiction.
* The ability for the issuer to revoke a token if necessary.

### Support for Branded Standards

Integrate one standard for global adoption while meeting your compliance requirements. Supports branded standards like Polymath's ST-20 or Harbor's R-Token. See [examples](https://github.com/simple-restricted-token/simple-restricted-token/tree/master/contracts/examples/other-standards) here.

## Commonly Implemented Features

* Ability to Revoke and Reassign
* Ability to Create Multiple Lists
* Ability to Freeze a Token
* Ability to Approve or Reject a Transaction

## Commonly Implemented Roles

Role | Example Entity | Actions |
--- | --- | ---
Owner | Issuer | Assign / Revoke Admin + Everything Below |
Administrator | Transfer Agent or Trading Venue | Authorize, Freeze, Revoke, Reassign
Investor | Individual or Entity | Send and Receive

## Built With The Ecosystem In Mind

### Issuers

If you're seeking to issue a security token, ERC-1404 provides all the tools you need to follow your counsel's guidance with respect to compliance requirements.

### Exchanges

This standard was designed with significant input from the major exchanges to be interoperable across exchanges and easy to integrate on any stack. If this standard does not meet your needs, please open up a Github issue [here](https://github.com/simple-restricted-token/simple-restricted-token/issues).
  
### Legal Counsel or Compliance Teams

It may be challenging to navigate transfer restrictions in the open source world of blockchain. ERC-1404 provides the tools necessary for your issuers to comply with the applicable domestic and international regulatory requirements.

## Development Sponsors

<a href="https://www.tokensoft.io" target="_blank"><img src="https://github.com/simple-restricted-token/ERC-1404/blob/master/img/logo_color.png?raw=true" width="200" /></a>
