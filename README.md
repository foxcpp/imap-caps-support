IMAP clients capability support status index
=============================================

**Disclaimer:** Updated when I feel like it, correct as I like it.

The table for servers support can be found on imapwiki:
https://www.imapwiki.org/Specs

Capabilities list taken from related IANA registry at 2019-06-01.
Obsolete extensions are not included.

A client is considered to support extension if it checks its support on the
server by looking at returned capabilities list. Even if it doesn't actually
makes any use of it.

**Legend:** `?` - unknown, `+` - supports, `-` - doesn't support (check git blame
for update timestamp)

Capability Name                    | Thunderbird | KMail | Roundcube | Rainloop | mutt | balsa | geary |
-----------------------------------|:-----------:|:-----:|:---------:|:--------:|:----:|:-----:|:-----:|
[ACL][RFC4314]                     |      +      |   +   |     +     |    -     |  +   |   +   |   ?   | 
[ANNOTATE-EXPERIMENT-1][RFC5257]   |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[APPENDLIMIT][RFC7889]             |      -      |   -   |     -     |    -     |  -   |   -   |   ?   | 
[BINARY][RFC3516]                  |      -      |   -   |     +     |    -     |  -   |   +   |   ?   | 
[CATENATE][RFC4469]                |      -      |   -   |     -     |    -     |  -   |   -   |   ?   | 
[CHILDREN][RFC3348]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[COMPRESS=DEFLATE][RFC4978]        |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[CONDSTORE][RFC7162]               |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[CONTEXT=SEARCH][RFC5267]          |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[CONTEXT=SORT][RFC5267]            |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[CONVERT][RFC5259]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[CREATE-SPECIAL-USE][RFC6154]      |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[ENABLE][RFC5161]                  |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[ESEARCH][RFC4731]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[ESORT][RFC5267]                   |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[FILTERS][RFC5466]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[I18NLEVEL=1][RFC5255]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[I18NLEVEL=2][RFC5255]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[ID][RFC2971]                      |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[IDLE][RFC2177]                    |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[IMAPSIEVE=][RFC6785]              |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LANGUAGE][RFC5255]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LIST-EXTENDED][RFC5258]           |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LIST-MYRIGHTS][RFC8440]           |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LIST-STATUS][RFC5819]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LITERAL+][RFC7888]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LITERAL-][RFC7888]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LOGIN-REFERRALS][RFC2221]         |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[LOGINDISABLED][RFC2595]           |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[MAILBOX-REFERRALS][RFC2193]       |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[METADATA][RFC5464]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[METADATA-SERVER][RFC5464]         |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[MOVE][RFC6851]                    |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[MULTIAPPEND][RFC3502]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[MULTISEARCH][RFC7377]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[NAMESPACE][RFC2342]               |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[NOTIFY][RFC5465]                  |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[OBJECTID][RFC8474]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[QRESYNC][RFC7162]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[QUOTA][RFC2087]                   |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[REPLACE][RFC8508]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[RIGHTS=][RFC4314]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[SASL-IR][RFC4959]                 |      ?      |   +   |     +     |    +     |  +   |   +   |   +   | 
[SAVEDATE][RFC8514]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[SEARCH=FUZZY][RFC6203]            |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[SEARCHRES][RFC5182]               |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[SORT][RFC5256]                    |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[SORT=DISPLAY][RFC5957]            |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[SPECIAL-USE][RFC6154]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[STARTTLS][RFC2595]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[STATUS=SIZE][RFC8438]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[THREAD][RFC5256]                  |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[UIDPLUS][RFC4315]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[UNAUTHENTICATE][RFC8437]          |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[UNSELECT][RFC3691]                |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[URLFETCH=BINARY][RFC5524]         |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[URL-PARTIAL][RFC5550]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[URLAUTH][RFC4467]                 |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[UTF8=ACCEPT][RFC6855]             |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[UTF8=ONLY][RFC6855]               |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 
[WITHIN][RFC5032]                  |      ?      |   ?   |     ?     |    ?     |  ?   |   ?   |   ?   | 

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
