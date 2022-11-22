# Why?

We want to strengthen digital self-defense. This ProxyStore is part of a larger concept that you can find [at dys2p.com](https://dys2p.com/konzept.html).

## Risks and problems when shopping on the Internet

Online shopping is convenient, but often problematic from a privacy and data protection perspective. Most online stores require a lot of data from you. You are often asked to create an account to which your data is permanently linked. But even without an account, you usually receive an invoice by default. Invoices and billing data must be stored for years. Payment providers and delivery services also notice who you are and where you shop, of course.

**Breaches and Leaks:** Not a day goes by without an online store being hacked or a customer database being stolen – whether by external players or by insiders. Some of these data collections end up publicly on the Internet, others circulate in confidential groups of people only.

**Surveillance:** Large amounts of data are awaking the interest of government agencies. Big platforms like amazon hold information about almost each of us. Police and intelligence agencies are also interested in this data. You have nothing to hide? The government's digital desires create a climate of surveillance that also affects you.

**Data trading and advertising:** Even after the General Data Protection Regulation has come into force, sharing customer data on the Internet is often part of the business model. Do you always read the small print? For a long time now, we have not only received advertising by e-mail, phone call or mail. Advertising service providers promise to be able to identify you across different websites ("tracking"), and the "advertising ID" of many smartphones supports them in this. While the benefits of online advertising are debatable, customer databases are clearly considered an asset. When a company is sold, customer data usually falls into new hands as well.

**Payment and Delivery:** Without a credit card or PayPal account, many things in the digital world are out of reach. Having nosy roommates or neighbors, you may not even dare to order them.

## Leaks – oops!

Outdated software in use, a faulty configuration, careless handling or some other cause – and your data is suddenly accessible to people for whom it was not intended. Oops. Depending on their intention and the data involved, different actions to your detriment can follow:

* Use of data for commercial purposes
  * Identity theft
  * Spam and phishing
  * Extortion & reputational damage
* Use of data for political purposes, espionage
* Stalking and doxing

### Pivot point: e-mail addresses

Most services identify and contact you via your email address. Only in some cases a username is also required. Your e-mail address can be used not only for "marketing purposes" ([spam](https://en.wikipedia.org/wiki/Email_spam)) and other unwanted contact, but also for [phishing](https://en.wikipedia.org/wiki/Phishing). Moreover, attackers can try to guess your password. If they don't succeed with "123456" or your pet's name, they can [try](https://en.wikipedia.org/wiki/Brute-force_attack) other popular passwords or entries from a dictionary. If you use the same password somewhere else, they may already know it.

### Password hashes

Internet services usually do not store the plaintext of passwords, only a [hash value](https://en.wikipedia.org/wiki/Hash_function). However, due to faulty implementations or negligence, passwords can also exist in plain text. As the computing power of computers increases and cryptographic research progresses, the demands on hash functions also increase. If an outdated hash method is used, stored hash values can be analyzed with [rainbow tables](https://en.wikipedia.org/wiki/Rainbow_table), for example, to obtain the password in plain text. There are service providers who specialize in precisely this.

### Access to accounts and information

The combination of an e-mail address and a plaintext password (or variations of it) can be tried not only on the e-mail account itself, but also on other services. From an attacker's point of view, this [credential stuffing](https://en.wikipedia.org/wiki/Credential_stuffing) is quiet successful, since many people use the same credentials at different Internet services. After a successful login, the password can often be changed and the account thus taken over (account hijacking). Someone gets not only access to stored information, but can also request further information (e.g., according to the right of access of the GDPR) and perform interactions on your behalf.

Use [password managers](https://www.privacytools.io/software/passwords/) with a randomly generated passphrase for each service. If possible, use [two-factor authentication or multi-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication) to secure accounts better.

Collected personal information (e.g., first and last name, gender, date of birth), contact information (e.g., phone number, shipping and billing address), payment information (e.g., bank account information, credit card information), platform information (e.g., login date, IP addresses, system information, history), and additional evidence such as a copy of an ID or ID number can be misused in a variety of ways. The more information available, the more successful attacks can be.

### Example case: using data for commercial purposes

On June 25, 2020, someone was able to obtain more than 1,075,000 email addresses and other customer data of more than 272,000 individuals, including, in addition to the email address, the first and last name, an address (street, house number, zip code, city, and country), and a phone number. The affected company – Ledger – is selling hardware wallets with purpose to secure cryptocurrency wallets. Since then, there has been a wide range of actions to the detriment of those affected.

Such databases are often redistributed and used by various players. Ledger's customer data has been used for numerous phishing campaigns in multiple languages and through various communication channels (email, SMS). According to [company information](https://www.ledger.com/phishing-campaigns-status#phishing-campaigns), 527 phishing websites have been taken offline in this context since October 22, 2020. Because the dataset also contained phone numbers, players were able to use [SIM swapping](https://en.wikipedia.org/wiki/SIM_swap_scam) to take over the phone numbers often used for two-factor authentication, and gain further access, e.g., [on accounts at cryptocurrency exchanges](https://web.archive.org/web/20210126113423/www.coindesk.com/ledger-leak-sim-swap-home-invasion-threats).

An increased amount of phishing and spam emails is quite normal after such an incident. What stands out in this case is that Ledger customers are threatened with [break-ins](https://web.archive.org/web/20210126114520/https://www.reddit.com/r/ledgerwallet/comments/kh8q82/fantastic/), kidnapping, and death ([1](https://web.archive.org/web/20210126114848/https://www.reddit.com/r/ledgerwalletleak/comments/ki1nsz/received_phone_call_threatening_kidnapping_and/), [2](https://web.archive.org/web/20210126115052/https://www.reddit.com/r/CryptoCurrency/comments/kx9sy0/my_dad_just_received_a_death_threat_on_his/)) in order to extort money.

Such events should not be regarded separately, but in the context of other leaks and public information from the Internet. [According to haveibeenpwned](https://web.archive.org/web/20201220212750/https://twitter.com/haveibeenpwned/status/1340770769106731008), 69% of the email addresses were already included in previous known leaks. The [haveibeenpwned](https://haveibeenpwned.com) service can be used to search numerous known data leaks for email addresses.

### Example case: using data for political purposes

A security incident at "Impact Mailorder" shows how ordering subcultural clothing and goods can land you on death lists of right-wing terrorist groups like "Nordkreuz".

On January 20, 2015, one or more persons obtained the customer database of the German online mail order company "Impact Mailorder". Shortly thereafter, a text entitled "impact-mailorder.de hacked by National Sozialistische Hacker Crew" was published on pastebin.com, which contained 108 swastikas, links to download the data and an excerpt of 250 personal data records. The database includes about 40,000 entries with first names, last names, streets, house numbers, zip codes and cities, phone numbers and e-mail addresses of customers. It spread quickly in neo-Nazi circles. A few days later, on January 29, 2015, another text appeared, again with 108 swastikas and links to download the data of another 15,000 people.

Since then, this data has been disseminated in whole or in part in right-wing circles, sometimes under other names such as "Antifa List" or "Members of Antifa". The data has been used and disseminated by a spin-off of the German "young nationalists" ("JN"), by [the right-wing populist party "AfD"](https://web.archive.org/web/20201109025731/https://www.hz.de/meinort/heidenheim/merz-verbreitete-geklaute-adressen-31284866.html), and by right-wing extremist and right-wing terrorist groups such as ["Nordkreuz"](https://de.wikipedia.org/wiki/Nordkreuz), ["Revolution Chemnitz"](https://web.archive.org/web/20190711223234/https://www.tagesspiegel.de/politik/rechter-terror-revolution-chemnitz-hatte-zugriff-auf-24-300-daten-von-linken-und-punks/24578260.html) and ["Aryan Circle Germany"](https://de.wikipedia.org/wiki/Aryan_Circle_Germany). "Nordkreuz" enriched the data with information from police databases in order to – according to a recorded statement by a member of Nordkreuz – find "left-wing personalities" and "liquidate them in case of conflict." More than six years after the security incident, the data is still roaming around, most recently in conspiracist Telegram groups.

Security incidents like this, with the risk of physical harm and death threats, are a rarity, but every security incident poses unnecessary risks. Using services like [haveibeenpwned](https://haveibeenpwned.com) or HPI's [Leak Checker](https://sec.hpi.de/ilc/search?lang=de), you can check on your own whether your email address is contained in known data leaks.

## Surveillance – nothing to hide?

Government's desires do not stop at the Internet. On the contrary, digitization is opening up surveillance possibilities that were previously unthinkable. "Data retention" and digital dragnet searches, the "federal Trojan", identification obligations, the planned introduction of a citizen ID, and data protection disasters such as the German "electronic lawyer's mailbox" are just a few examples of dangerous instruments that are often said to "be not allowed to fall into the wrong hands." In fact, the very possibility of using these instruments poses a risk. The frequently demanded lowering of the hurdles under which authorities are allowed to access the collected data does the rest.

State surveillance of the analog and digital world is often justified by the "security" of the citizens under surveillance, without considering the counterarguments. Yet a real consequence is that people change their behavior at the mere possibility of being monitored – surveillance creates subordinates. Surveillance apparently hardly solves real problems – otherwise the constant demand for new surveillance powers cannot be explained.

## Data trading and advertising

The [privacy handbook](https://privacy-handbuch.de/handbuch_11.htm) and [selbstdatenschutz.info](https://web.archive.org/web/20210618051140/https://www.selbstdatenschutz.info/datenkraken/) provide a good overview of players, methods and business models of digital data trading and user tracking.

## Literature tips

* [Cory Doctorow: Data – the new oil, or potential for a toxic oil spill?](https://www.kaspersky.com/blog/secure-futures-magazine/data-new-toxic-waste/34184/)
* [J. Onaolapo, E. Mariconti, G. Stringhini 2016: What Happens After You Are Pwnd: Understanding The Use Of Leaked Webmail Credentials In The Wild](https://www.researchgate.net/publication/310116406_What_Happens_After_You_Are_Pwnd_Understanding_The_Use_Of_Leaked_Webmail_Credentials_In_The_Wild)
