
#  Wallets

<fig desktop="half,right">
	<fig-img
		src="/images/wallets/bitcoin-org-choose-your-wallet.png"
		width="2390"
		height="2854"
		alt="Bitcoin.org - Choose your wallet"
	/>
	<fig-cap
		caption="The wallet download page on Bitcoin.org."
		title="Bitcoin.org"
		link="https://bitcoin.org/en/choose-your-wallet"
	/>
</fig>

One of the first things users need to do is to choose, install and set up a wallet. Users might expect there to be one official wallet they can trust and that will work across their devices, just like they would with other software. Since Bitcoin is an open-source project, so there are no barriers for anyone to start building their own wallet.

Bitcoin.org presents a grid 21 different wallets to users - with little guidance on how to make a choice. This is somewhat intentional, since the website needs to stay neutral in the spirit of [open-source](https://en.wikipedia.org/wiki/Open-source_model) and [decentralization](https://en.wikipedia.org/wiki/Decentralization). But it still poses a problem for new users. They will put real money into a system they have never used before and are anxious to start things off well.

Looking at other cryptocurrencies, there is another factor in play. Many projects are [forks](https://en.wikipedia.org/wiki/Fork_(software_development)), which means they took the codebase of another project to start their own. The result is that the wallet may look like the wallet of the project they forked from, with minor modifications (like logo and color palette). This is great on the one hand, since it allows development teams to quickly kickstart their work. It also means that existing design issues spread, and wallets sometimes look a bit thrown together. It's also important to recognize that many projects are young and the software will quickly evolve and improve. What you see now is likely to be a work in progress.

Another factor is that having a wallet is useless if you don't own any cryptocurrency. That's why many users are recommended to start with wallets that supports purchases via fiat money (like [Coinbase](https://www.coinbase.com/join/59bfa245c26808011d39d833)).

<image-grid count="2" width="400" mobileWidth="80%">
	<image-grid-img
		src="/images/sending/bitcoin-core-sending.png"
		width="1516"
		height="1066"
		alt="Bitcoin Core wallet - initial launch"
		caption="Functional."
		title="Bitcoin Core, V 0.16.2, July 29, 2018"
		link="https://bitcoin.org/en/download"
	/>
	<image-grid-img
		src="/images/home/lightning-wallet-home.png"
		width="1760"
		height="1224"
		alt="Lightning desktop wallet - receive"
		caption="User-friendly."
		title="Lightning wallet"
		link="https://github.com/lightninglabs/lightning-app"
	/>
</image-grid>

---

## Basic functionality

The core of each wallet is about sending and receiving money. To support this, there also needs to be basic settings, security and address management. Since this is core functionality, check the respective sections for more elaborate information.

- [Creating a wallet](creating-a-wallet)
- [Sending](sending)
- [Requesting](requesting)
- [Transactions](transactions)
- [Addresses](addresses)
- [Home screens](home-screens)

Even if a project has a web wallet, mobile wallet and desktop wallet, this is the functionality that's usually consistent across all of them.

## Advanced functionality

Beyond the basics, the features you find in different wallets are based on the particular functionality and use cases of each project, as well as device capabilities (for example, a smartphone can't run a [full node](https://bitcoin.org/en/full-node) usually). Here are a few common ones:

#### Mining

<fig desktop="half,right">
	<fig-img
		src="/images/wallets/monero-mining.png"
		width="2048"
		height="1536"
		alt="Mining screen in the Monero desktop wallet"
	/>
</fig>

[Mining](https://en.wikipedia.org/wiki/Bitcoin_network#Mining) is about running software that helps process transactions in the network. The [Monero desktop wallet](https://getmonero.org/downloads/), for example, has a one-click mining feature. This not only allows users to make a little money, but by making the functionality widely accessible, it helps decentralize and strengthen the network.

<break />

### Staking

<fig desktop="half,right">
	<fig-img
		src="/images/wallets/staking.png"
		retina="/images/wallets/staking@2x.png"
		width="620"
		height="256"
		alt="Cryptocurrency staking details"
	/>
</fig>

[Proof-of-stake](https://en.wikipedia.org/wiki/Proof-of-stake) projects allow users to earn interest on their coins by having wallets online 24/7 to contribute to the network. Unlike mining, this does not require extensive computing power, but it does require having an investment. The interest earned is usually proportional to the amount held (in mining, it's proportional to how much computing power you provide). Staking typically happens automatically and does not need a complex UI around it. The most important information is whether staking is active, and how often rewards are likely to be received (which is not a fixed schedule, but an estimate).

<break />

### Masternodes

<fig desktop="half,right">
	<fig-img
		src="/images/wallets/masternodes.png"
		retina="/images/wallets/masternodes@2x.png"
		width="620"
		height="307"
		alt="Cryptocurrency masternode details"
	/>
</fig>

Masternodes are one level-up of staking (more in the [Wikipedia article about Dash](https://en.wikipedia.org/wiki/Dash_(cryptocurrency))). They are also wallets that are online 24/7 to participate in the network, but have fixed requirements for the amount of money held (for example, Dash requires a collateral of 1,000 coins). This is a higher commitment than staking but also typically earns a higher interest. Masternodes have a more complex setup and are many times hosted on third-party servers and remotely controlled via wallets users run on their own devices. So while the UI demands are a little higher, the user is likely to be more technically proficient.

<break />

### More to come

Signing messages, [smart contracts](https://en.wikipedia.org/wiki/Smart_contract), [hardware wallet](https://bitcoin.org/en/wallets/hardware/) integration, and various other functionality can be found in some wallets. I will add more details on the most important ones over time. Stay tuned.

---

## Paper wallets

<fig desktop="half,right">
	<fig-img
		src="/images/wallets/walletgenerator-paper-wallet.png"
		width="600"
		height="438"
		alt="Bitcoin paper wallet template"
	/>
	<fig-cap
		caption="A Bitcoin paper wallet template."
		title="Walletgenerator.net"
		link="https://walletgenerator.net"
	/>
</fig>

The safest backup is a paper wallet. It can simply be your wallet seed written on a piece of paper, or a nicely printed template. The biggest advantage is that a paper wallet cannot be hacked (although it can still be stolen).

This is another aspect of cryptocurrencies that is not obvious to many. Wallet seeds can be created by computers that have never been online. Money can be sent to wallet addresses, without the wallet having ever been connected to (or registered with) the network.

So as backwards as it may sound for a digital currency, printing the seed and filing the paper away is a great security practice. 

---

## Hardware wallets

<fig desktop="half,right" drop="false">
	<fig-img
		src="/images/wallets/ledger-nano-s.jpg" 
		width="1227" 
		height="944" 
		alt="Ledger Nano S"
	/>
	<fig-cap
		caption="The Ledger Nano S hardware wallet."
		title="ledger.com"
		link="https://www.ledger.com?r=21196520a426"
	/>
</fig>

Hardware wallets are incredibly important for secure storage, but are currently not yet part of this handbook. [Ledger](https://www.ledger.com?r=21196520a426) and [Trezor](https://trezor.io/) are two popular choices.