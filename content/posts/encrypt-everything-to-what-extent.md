---
author: "Kevin St-Sauveur"
title: "Encrypt everything? To what extent?"
date: "2022-07-17"
description: "The dilemma between secure and safe from a data recovery stand point."
tags: ["Blog", "Tech", "Data loss", "Secure vs safe", "Data recovery", "Backup"]
categories: ["Tech"]
---

One would say to encrypt everything, but to what extent? The dilemma between secure and safe from a data recovery stand point.

## Encryption you say?

Encryption is the process of scrambling data in a way that it can't be unscrambled. There are multiple types of encryption (such as Asymmetric Encryption and Symmetric Encryption) and these methods are used to ensure that no unauthorized users access your sensitive information, thus protecting your data.

## Why not encrypt everything?

Nowadays, the *modus operandi* of media and all [InfoSec](https://en.wikipedia.org/wiki/Information_security) people would be to encrypt everything. From data at rest to data in transit to data in memory, the gold standard would be that everything must be [End-to-End Encrypted](https://en.wikipedia.org/wiki/End-to-end_encryption). Each state of data faces the risk of discovery or exposure. Even if the risks are not the same across all of these states, the goal is to protect your data from malicious actions: [Ransomware](https://en.wikipedia.org/wiki/Ransomware), data breaches, unauthorized access, physical theft, etc. Who would not want their data secure at all time, right? Attack vectors and threat levels often says that everything must be locked down, always and as secure as it can be.

## The problem with encryption from a data recovery stand point

Data recovery experts would say that if you don't have strong encryption on your local drive, on your backups, on your local accounts, then the worst that could happen in the event of theft (let's say if someone breaks into your home and stole your computer or someone stole your phone in the metro), you can easily replace your device and regain access to your data given that you have a proper non-encrypted backup. **BUT**, *BUT*, **_BUT_**, one day, you might be browsing reddit -or any other website- and see yourself (emails, intimate photos, full identity, health records, private messages, etc.) and there's no way to take any of that back. It would be permanently written in the endless memory of the web. However, all this data ~~is~~ was yours, it's sensible and could be extremely damageable if publicly accessible.

Data theft is such a growing threat, it is exactly why a lot of information security experts keep telling you why we are better off encrypting everything thus making sure **if anything fails, it fails secure rather than safe**. But is that really what you want?

## The dilemma : Safe vs. Secure

Your data is **safe** when you have copies to restore from in the event of a loss or corruption. Your data in **secure** when it's protected from unauthorized access that could result in compromised data, corruption or deletion.

Let's say you encrypt everything and everything is secure (drives, backups, online accounts locked with MFA and unique passwords). A case scenario would be that you lose access to everything. If a fire happens and it takes out your hardware security key, your phone, your laptop, your backups, that means you no longer have access to your MFA or password manager. This also means you got no way to perform data recovery of your backups in the cloud because they are, of course, password protected. You may get new devices, but you no longer have access to these backups or accounts. Bye-bye to your dog photos, your travel journal, your family records or any important information. Without decryption keys, to your eyes, your data is written in the equivalent of non-readable random strings or binary blobs. It's lost, forever.

That is exactly how encrypting ransomware works. Your data gets locked away where you can't get access to it in the hopes it's valuable enough to your eyes to pay for the decryption key. And yes, this is a growing trend. [According to Palo Alto](https://unit42.paloaltonetworks.com/ransomware-threat-report-highlights/), the average ransom paid by victim organizations in Europe, the US and Canada has almost trebled from $115,123 in 2019 to $312,493 in 2020.

The paradox is that data loss is impacting more people than data theft and this is why sometimes fail safe is more suitable than fail secure.

## End word

### Always reevaluate

Don't hesitate to reevaluate your backup strategies. The data that you've chosen to keep safe today may be the one you would want to keep secure tomorrow.

The watchword would be to **encrypt everything that you would rather lose than to be recovered**. The risk of choosing one option is the benefit of the other. **Don't encrypt anything you would rather have stolen than lose.**

### Backup, Backup, Backup

To minimize data loss, remember that no matter how you store your data, always use the 3-2-1 rule:

- Keep three (3) copies of your data.
- Store two (2) backup copies on different storage media, avoiding online real time sync.
- Stock one (1) backup copy in a remote location.