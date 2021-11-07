# phishing_kits_2021

A dataset of phishing kits in the wild.

## Notes

- ⚠️ The data are not cleaned thoroughly. It means the data contain FPs.
- The data have been collected through 2021/08/29 to 2021/11/07.
- The data only contain unique phishing kits. The uniqueness of kits is assured by a SHA256 hash of a kit.

## Dataset

- [Dataset(CSV)](./records.csv)

## Notable findings

### Postal/transport services are favorite targets

Probably because of the pandemic, postal/transport services are favorite targets of threat actors nowadays.

![img](https://urlscan.io/screenshots/249d4f74-e862-40dd-b12d-c81c8aebf557.png)
![img](https://urlscan.io/screenshots/9ee0eb52-a286-4cb0-808c-bb540b2d9ed9.png)
![img](https://urlscan.io/screenshots/a359a080-b5b1-4476-bcf2-35776b3e8573.png)
![img](https://urlscan.io/screenshots/f7504036-b2b5-4a9b-9c45-9cadff14cb57.png)
![img](https://urlscan.io/screenshots/ab825968-a028-4c2f-8fbc-58acba4c4035.png)

### (Vulnerable) WordPress is an easy mark

**15%** of phishing kits are deployed in WordPress websites.

WordPress is the most popular CMS in the world and vulnerable WordPress websites are targeted by threat actors to implant something including a phishing kit.

### Gov web sites are compromised sometimes

The following government domains are used for hosting phishing kits.

- `go.id`
- `gov.br`
- `gov.mz`
- `gov.ng`
- `gov.pk`

(Especially, Indonesia, [which is also known as a source of phishing scammers](http://www.deependresearch.org/2018/09/indonesian-spam-communities.html), has a bad posture. Multiple compromised `go.id` web sites have been observed)

It means that a more sophisticated threat actor could implant something more dangerous on there.
