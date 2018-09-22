# BlockSec

Overview about projects created during the EOS Hackathon in London on 22/23 September 2018

## Brief

The goal of this project is to protect users from the fraudulent sites (such as phishing or spam websites). This works by checking the site certificate againt blacklisted on the EOS blockchain.

### Usage of the blockchain

The list of the public certificates is created and voted by the users using a voting widget, which is managed by EOS blockchain.

This way, such blacklist is flexible by being decentralized and dynamic.

### Innovation & Creativity

Comparing to other projects, BlockSec is protecting the content based on the associated public SSL certificate.

For comparison, some existing projects are blocking the content based on the hardcoded list of domains, which makes then not efficient by creating a huge list of domains which are very difficult to maintain. Secondly, such hardcoded lists can be easily workarounded by creating different patterns or domains right after it is blocked.

Nowadays it is very easy to get the SSL certificate issued by trusted authority. However, such issued certificates does not validate contents of the site (despite having a green padlock icon), which prove the point that the certificates were NEVER meant for that! In other words, a verified certificate can only verify that you are connecting to the scam-site, and it is up to user to decide whether he trust it or not.

By creating a smart contract which can warn users about the scam-sites based on actual public certificates which were black listed, it helps users to protect from scammers and phishing content.

### Impact

The app can potentially handle over a million websites where each certificate can be verified by trusted users. 

### Scalibility

The app is storing and managing the certificates by using EOS blockchain, making it flexible and scalable.

By implementing it using EOS blockchain, a network capable of processing millions of transactions per second, our app can be highly scalable.

## Installation

The protection can be enabled on any computer, tablet or a smart phone supporting a web browser, by installing an extension.

Steps to install extension:
1. Download the project.
2. Go to `chrome://extensions` (Chrome or Opera).
3. Select _Developer mode_, and _Load unpacked extension..._
4. Choose `extension/Chrome` folder of that project.