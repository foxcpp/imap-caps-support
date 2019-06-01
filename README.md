IMAP clients capability support status index
=============================================

To help guide decisions about prioritizing extensions support in
implementations.

Disclaimer: Updated when I feel like it, correct as I like it.

Capabilities list taken from related IANA registry at 2019-06-01.
Obsolete extensions are not included.

Format
--------
```
CAPABILITYNAME [RFCXXX]
-------------------------
### Servers
- [ ] maddy VERSION
- [x] Dovecot VERSION
### Clients
- [x] Thunderbird VERSION
- [ ] K-Mail VERSION
```

Mark indicates presence of support, absence of mark and version indicates
no support, absence of mark and '???' version indicates unknown status.

A client is considered to support extension if it checks its support on the
server by looking at returned capabilities list. Even if it doesn't actually
makes any use of it.

A server is considered to support extension if it is included in returned
CAPABILITY response. Even if all operations defined by extension fail with
error.

Widespread open-source implementations
--------
### Clients
- KDE Mail (https://commits.kde.org/kmail?path=/)
- K-9 Mail (https://github.com/k9mail/k-9)
- Roundcube (https://github.com/roundcube/roundcubemail)
- Rainloop (https://github.com/RainLoop/rainloop-webmail)
- mutt

### Servers
- Dovecot (https://github.com/dovecot/core)
- Cyrus


ACL	[RFC4314]
---------------
### Clients
- [x] Thunderbird 60.6.1
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [x] Roundcube 1.3.9
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [x] Dovecot 2.3.4
- [x] Cyrus 3.0.8


APPENDLIMIT	[RFC7889]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

BINARY	[RFC3516]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CATENATE	[RFC4469]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CHILDREN	[RFC3348]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

COMPRESS=DEFLATE	[RFC4978]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CONDSTORE	[RFC7162]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CONTEXT=SEARCH	[RFC5267]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CONTEXT=SORT	[RFC5267]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CONVERT	[RFC5259]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

CREATE-SPECIAL-USE	[RFC6154]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

ENABLE	[RFC5161]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

ESEARCH	[RFC4731]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

ESORT	[RFC5267]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

FILTERS	[RFC5466]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

I18NLEVEL=1	[RFC5255]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

I18NLEVEL=2	[RFC5255]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

ID	[RFC2971]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

IDLE	[RFC2177]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

IMAPSIEVE=	[RFC6785]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LANGUAGE	[RFC5255]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LIST-EXTENDED	[RFC5258]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LIST-MYRIGHTS	[RFC8440]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LIST-STATUS	[RFC5819]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LITERAL+	[RFC7888]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LITERAL-	[RFC7888]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LOGIN-REFERRALS	[RFC2221]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

LOGINDISABLED	[RFC2595]/[RFC3501]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

MAILBOX-REFERRALS	[RFC2193]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

METADATA	[RFC5464]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

METADATA-SERVER	[RFC5464]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

MOVE	[RFC6851]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

MULTIAPPEND	[RFC3502]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

MULTISEARCH	[RFC7377]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

NAMESPACE	[RFC2342]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

NOTIFY	[RFC5465]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

OBJECTID	[RFC8474]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

QRESYNC	[RFC7162]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

QUOTA	[RFC2087]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

REPLACE	[RFC8508]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

RIGHTS=	[RFC4314]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

SASL-IR	[RFC4959]
-----------------------
### Clients
- [ ] Thunderbird ??
- [x] KDE Mail 19.04
- [ ] K-9 Mail ???
- [x] Roundcube 1.3.8
- [x] Rainloop 1.12
- [x] mutt 1.10.2
- [x] balsa 2.5.6
- [x] geary 0.12

### Server
- [x] Dovecot 2.3.4
- [x] Cyrus 3.0.8

SAVEDATE	[RFC8514]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

SEARCH=FUZZY	[RFC6203]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

SEARCHRES	[RFC5182]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

SORT	[RFC5256]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

SORT=DISPLAY	[RFC5957]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

SPECIAL-USE	[RFC6154]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

STARTTLS	[RFC2595][RFC3501]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

STATUS=SIZE	[RFC8438]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

THREAD	[RFC5256]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

UIDPLUS	[RFC4315]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

UNAUTHENTICATE	[RFC8437]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

UNSELECT	[RFC3691]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

URLFETCH=BINARY	[RFC5524]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

URL-PARTIAL	[RFC5550]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

URLAUTH	[RFC4467]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

UTF8=ACCEPT	[RFC6855]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

UTF8=ONLY	[RFC6855]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???

WITHIN	[RFC5032]
-----------------------
### Clients
- [ ] Thunderbird ??
- [ ] KDE Mail ???
- [ ] K-9 Mail ???
- [ ] Roundcube ???
- [ ] Rainloop ???
- [ ] mutt ???

### Server
- [ ] Dovecot ???
- [ ] Cyrus ???


[RFC4314]: https://tools.ietf.org/html/rfc4314
[RFC5257]: https://tools.ietf.org/html/rfc5257
[RFC7889]: https://tools.ietf.org/html/rfc7889
[RFC3501]: https://tools.ietf.org/html/rfc3501
[RFC3516]: https://tools.ietf.org/html/rfc3516
[RFC4469]: https://tools.ietf.org/html/rfc4469
[RFC3348]: https://tools.ietf.org/html/rfc3348
[RFC4978]: https://tools.ietf.org/html/rfc4978
[RFC7162]: https://tools.ietf.org/html/rfc7162
[RFC5267]: https://tools.ietf.org/html/rfc5267
[RFC5267]: https://tools.ietf.org/html/rfc5267
[RFC5259]: https://tools.ietf.org/html/rfc5259
[RFC6154]: https://tools.ietf.org/html/rfc6154
[RFC5161]: https://tools.ietf.org/html/rfc5161
[RFC4731]: https://tools.ietf.org/html/rfc4731
[RFC5267]: https://tools.ietf.org/html/rfc5267
[RFC5466]: https://tools.ietf.org/html/rfc5466
[RFC5255]: https://tools.ietf.org/html/rfc5255
[RFC5255]: https://tools.ietf.org/html/rfc5255
[RFC2971]: https://tools.ietf.org/html/rfc2971
[RFC2177]: https://tools.ietf.org/html/rfc2177
[RFC6785]: https://tools.ietf.org/html/rfc6785
[RFC5255]: https://tools.ietf.org/html/rfc5255
[RFC5258]: https://tools.ietf.org/html/rfc5258
[RFC8440]: https://tools.ietf.org/html/rfc8440
[RFC5819]: https://tools.ietf.org/html/rfc5819
[RFC7888]: https://tools.ietf.org/html/rfc7888
[RFC7888]: https://tools.ietf.org/html/rfc7888
[RFC2221]: https://tools.ietf.org/html/rfc2221
[RFC2595]: https://tools.ietf.org/html/rfc2595
[RFC3501]: https://tools.ietf.org/html/rfc3501
[RFC2193]: https://tools.ietf.org/html/rfc2193
[RFC5464]: https://tools.ietf.org/html/rfc5464
[RFC5464]: https://tools.ietf.org/html/rfc5464
[RFC6851]: https://tools.ietf.org/html/rfc6851
[RFC3502]: https://tools.ietf.org/html/rfc3502
[RFC7377]: https://tools.ietf.org/html/rfc7377
[RFC2342]: https://tools.ietf.org/html/rfc2342
[RFC5465]: https://tools.ietf.org/html/rfc5465
[RFC8474]: https://tools.ietf.org/html/rfc8474
[RFC7162]: https://tools.ietf.org/html/rfc7162
[RFC2087]: https://tools.ietf.org/html/rfc2087
[RFC8508]: https://tools.ietf.org/html/rfc8508
[RFC4314]: https://tools.ietf.org/html/rfc4314
[RFC4959]: https://tools.ietf.org/html/rfc4959
[RFC8514]: https://tools.ietf.org/html/rfc8514
[RFC6203]: https://tools.ietf.org/html/rfc6203
[RFC5182]: https://tools.ietf.org/html/rfc5182
[RFC5256]: https://tools.ietf.org/html/rfc5256
[RFC5957]: https://tools.ietf.org/html/rfc5957
[RFC6154]: https://tools.ietf.org/html/rfc6154
[RFC2595]: https://tools.ietf.org/html/rfc2595
[RFC3501]: https://tools.ietf.org/html/rfc3501
[RFC8438]: https://tools.ietf.org/html/rfc8438
[RFC5256]: https://tools.ietf.org/html/rfc5256
[RFC4315]: https://tools.ietf.org/html/rfc4315
[RFC8437]: https://tools.ietf.org/html/rfc8437
[RFC3691]: https://tools.ietf.org/html/rfc3691
[RFC5524]: https://tools.ietf.org/html/rfc5524
[RFC5550]: https://tools.ietf.org/html/rfc5550
[RFC4467]: https://tools.ietf.org/html/rfc4467
[RFC6855]: https://tools.ietf.org/html/rfc6855
[RFC5738]: https://tools.ietf.org/html/rfc5738
[RFC6855]: https://tools.ietf.org/html/rfc6855
[RFC5738]: https://tools.ietf.org/html/rfc5738
[RFC6855]: https://tools.ietf.org/html/rfc6855
[RFC6855]: https://tools.ietf.org/html/rfc6855
[RFC5738]: https://tools.ietf.org/html/rfc5738
[RFC6855]: https://tools.ietf.org/html/rfc6855
[RFC5032]: https://tools.ietf.org/html/rfc5032
