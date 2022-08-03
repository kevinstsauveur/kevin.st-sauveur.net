---
author: "Kevin St-Sauveur"
title: "Encrypt everything? To what extent?"
date: "2022-07-17"
description: "The dilemma between secure and safe from a data recovery stand point."
tags: ["Blog", "Tech", "Data loss", "Secure vs safe", "Data recovery", "Backup"]
categories: ["Tech"]
---

One would say to encrypt everything, but to what extent? The dilemma between secure and safe from a data recovery stand point.

<center>
<picture>
    <source type="image/avif" srcset="/img/blog/harddrives.avif" >
    <source type="image/webp" srcset="/img/blog/harddrives.webp" >
    <img loading="lazy" src="/img/blog/harddrives.jpg" alt="Harddrives picture" style="width:20em;">
</picture>
</center>

## Encryption you say?

Encryption is the process of scrambling data so that it cannot be descrambled. There are several types of encryption (such as asymmetric encryption and symmetric encryption). These methods are used to ensure that no unauthorized user can access your sensitive information, thus protecting your data.

## Why not encrypt everything?

Today, the _modus operandi_ of the media and all those in charge of security ([InfoSec](https://en.wikipedia.org/wiki/Information_security)) is to encrypt everything. From data at rest to data in transit to data in memory, the golden rule would be that everything must be encrypted from [end-to-end](https://en.wikipedia.org/wiki/End-to-end_encryption). Every data state presents a risk of discovery or exposure. While the risks are not the same for all these states, the goal is to protect your data from malicious actions: [Ransomware](https://en.wikipedia.org/wiki/Ransomware), data breach, unauthorized access, physical theft, etc. Who wouldn't want their data to be secure at all times, right? Attack vectors and threat levels often assume that everything must be locked down, permanently and as secure as possible.

## The problem with encryption from a data recovery stand point

Data recovery experts would say that if you don't have strong encryption on your local drive, on your backups, on your local accounts, then the worst that can happen in the event of a theft (let's say someone breaks into your house and steals your computer or someone steals your phone on the subway), you can easily replace your device and regain access to your data since you have a proper unencrypted backup. **BUT**, _BUT_, **_BUT_**, one day you could be browsing reddit - or any other website - and see yourself (emails, intimate photos, full identity, medical records, private messages, etc. ) and there's no way to go back. It would be permanently written into the infinite memory of the web. However, all this data ~~is~~ were yours, it is sensitive and could be extremely damaging if it were publicly available.

Data theft is a growing threat, which is exactly why a lot of information security experts keep telling you that it's better to encrypt everything to ensure that **if anything fails, it fails secure rather than safe**. But is that really what you want?

## The dilemma : Safe vs. Secure

Your data is **safe** when you have copies from which you can restore it in case of loss or corruption. Your data is **secure** when it is protected from unauthorized access that could result in data compromise, corruption or deletion.

Let's say you encrypt everything and everything is secure (disks, backups, online accounts protected with MFA and unique passwords). A case scenario would be that you lose access to everything. If a fire happens and it takes your hardware security key, your phone, your laptop, your backups, that means you no longer have access to your MFA or password manager. This also means that you have no way to recover data from your cloud backups, as they are, of course, password protected. You can get new devices, but you no longer have access to those backups or accounts. Bye-bye to your dog pictures, travel journal, family records or any important information. Without decryption keys, in your eyes, your data is written in the equivalent of random strings or unreadable binary blobs. It's lost, forever.

This is exactly how encryption ransomware works. Your data is locked away where you can't access it in the hopes that it's valuable enough to you to pay for the decryption key. And yes, this is a growing trend. [According to Palo Alto](https://unit42.paloaltonetworks.com/ransomware-threat-report-highlights/), the average ransom paid by victim organizations in Europe, the U.S. and Canada has nearly tripled from $115,123 in 2019 to $312,493 in 2020.

The paradox is that data loss impacts more people than data theft, which is why sometimes fail safe is more suitable than fail secure.

## End word

### Always reevaluate

Don't hesitate to re-evaluate your backup strategies. The data you choose to keep safe today may be the data you want to keep secure tomorrow.

The watchword would be to **encrypt everything that you would rather lose than to be recovered**. The risk of choosing one option is the benefit of the other. **Don't encrypt anything you would rather have stolen than lose.**
