<!-- toc -->

# MISP Attribute Categories vs Types (MISP version 2.4)


|Category| Internal reference | Targeting data | Antivirus detection | Payload delivery | Artifacts dropped | Payload installation |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|
|md5| | | | X | X | X |
|sha1| | | | X | X | X |
|sha256| | | | X | X | X |
|filename| | | | X | X | X |
|pdb| | | | | X | |
|filename&#124;md5| | | | X | X | X |
|filename&#124;sha1| | | | X | X | X |
|filename&#124;sha256| | | | X | X | X |
|ip-src| | | | X | | |
|ip-dst| | | | X | | |
|hostname| | | | X | | |
|domain| | | | X | | |
|domain&#124;ip| | | | | | |
|email-src| | | | X | | |
|email-dst| | | | X | | |
|email-subject| | | | X | | |
|email-attachment| | | | X | | |
|url| | | | X | | |
|http-method| | | | | | |
|user-agent| | | | X | | |
|regkey| | | | | X | |
|regkey&#124;value| | | | | X | |
|AS| | | | X | | |
|snort| | | | | | |
|pattern-in-file| | | | X | X | X |
|pattern-in-traffic| | | | X | | X |
|pattern-in-memory| | | | | X | X |
|yara| | | | X | X | X |
|vulnerability| | | | X | | X |
|attachment| | | X | X | X | X |
|malware-sample| | | | X | X | X |
|link| X | | X | X | | |
|comment| X | X | X | X | X | X |
|text| X | | X | X | X | X |
|other| X | | X | X | X | X |
|named pipe| | | | | X | |
|mutex| | | | | X | |
|target-user| | X | | | | |
|target-email| | X | | | | |
|target-machine| | X | | | | |
|target-org| | X | | | | |
|target-location| | X | | | | |
|target-external| | X | | | | |
|btc| | | | | | |
|iban| | | | | | |
|bic| | | | | | |
|bank-account-nr| | | | | | |
|aba-rtn| | | | | | |
|bin| | | | | | |
|cc-number| | | | | | |
|prtn| | | | | | |
|threat-actor| | | | | | |
|campaign-name| | | | | | |
|campaign-id| | | | | | |
|malware-type| | | | X | | X |
|uri| | | | | | |
|authentihash| | | | X | X | X |
|ssdeep| | | | X | X | X |
|imphash| | | | X | X | X |
|pehash| | | | X | | X |
|sha-224| | | | | | |
|sha-384| | | | | | |
|sha-512| | | | | | |
|sha-512/224| | | | | | |
|sha-512/256| | | | | | |
|tlsh| | | | X | | X |
|filename&#124;authentihash| | | | X | X | X |
|filename&#124;ssdeep| | | | X | X | X |
|filename&#124;imphash| | | | X | X | X |
|filename&#124;pehash| | | | X | X | X |
|filename&#124;sha-224| | | | | | |
|filename&#124;sha-384| | | | | | |
|filename&#124;sha-512| | | | | | |
|filename&#124;sha-512/224| | | | | | |
|filename&#124;sha-512/256| | | | | | |
|filename&#124;tlsh| | | | X | X | X |
|windows-scheduled-task| | | | | X | |
|windows-service-name| | | | | X | |
|windows-service-displayname| | | | | X | |
|whois-registrant-email| | | | | | |
|whois-registrant-phone| | | | | | |
|whois-registrant-name| | | | | | |
|whois-registrar| | | | | | |
|whois-creation-date| | | | | | |
|targeted-threat-index| | | | | | |
|mailslot| | | | | | |
|pipe| | | | | | |
|ssl-cert-attributes| | | | | | |
|x509-fingerprint-sha1| | | | X | X | X |

|Category| Persistence mechanism | Network activity | Payload type | Attribution | External analysis | Financial fraud |
| --- |:---:|:---:|:---:|:---:|:---:|:---:|
|md5| | | | | X | |
|sha1| | | | | X | |
|sha256| | | | | X | |
|filename| X | | | | X | |
|pdb| | | | | | |
|filename&#124;md5| | | | | X | |
|filename&#124;sha1| | | | | X | |
|filename&#124;sha256| | | | | X | |
|ip-src| | X | | | X | |
|ip-dst| | X | | | X | |
|hostname| | X | | | X | |
|domain| | X | | | X | |
|domain&#124;ip| | X | | | X | |
|email-src| | | | | | |
|email-dst| | X | | | | |
|email-subject| | | | | | |
|email-attachment| | | | | | |
|url| | X | | | X | |
|http-method| | X | | | | |
|user-agent| | X | | | X | |
|regkey| X | | | | X | |
|regkey&#124;value| X | | | | X | |
|AS| | X | | | X | |
|snort| | X | | | X | |
|pattern-in-file| | X | | | X | |
|pattern-in-traffic| | X | | | X | |
|pattern-in-memory| | | | | X | |
|yara| | | | | | |
|vulnerability| | | | | X | |
|attachment| | X | | | X | |
|malware-sample| | | | | X | |
|link| | | | | X | |
|comment| X | X | X | X | X | X |
|text| X | X | X | X | X | X |
|other| X | X | X | X | X | X |
|named pipe| | | | | | |
|mutex| | | | | | |
|target-user| | | | | | |
|target-email| | | | | | |
|target-machine| | | | | | |
|target-org| | | | | | |
|target-location| | | | | | |
|target-external| | | | | | |
|btc| | | | | | X |
|iban| | | | | | X |
|bic| | | | | | X |
|bank-account-nr| | | | | | X |
|aba-rtn| | | | | | X |
|bin| | | | | | X |
|cc-number| | | | | | X |
|prtn| | | | | | X |
|threat-actor| | | | X | | |
|campaign-name| | | | X | | |
|campaign-id| | | | X | | |
|malware-type| | | | | | |
|uri| | X | | | | |
|authentihash| | | | | | |
|ssdeep| | | | | | |
|imphash| | | | | | |
|pehash| | | | | | |
|sha-224| | | | | | |
|sha-384| | | | | | |
|sha-512| | | | | | |
|sha-512/224| | | | | | |
|sha-512/256| | | | | | |
|tlsh| | | | | | |
|filename&#124;authentihash| | | | | | |
|filename&#124;ssdeep| | | | | | |
|filename&#124;imphash| | | | | | |
|filename&#124;pehash| | | | | | |
|filename&#124;sha-224| | | | | | |
|filename&#124;sha-384| | | | | | |
|filename&#124;sha-512| | | | | | |
|filename&#124;sha-512/224| | | | | | |
|filename&#124;sha-512/256| | | | | | |
|filename&#124;tlsh| | | | | | |
|windows-scheduled-task| | | | | | |
|windows-service-name| | | | | | |
|windows-service-displayname| | | | | | |
|whois-registrant-email| | | | X | | |
|whois-registrant-phone| | | | X | | |
|whois-registrant-name| | | | X | | |
|whois-registrar| | | | X | | |
|whois-creation-date| | | | X | | |
|targeted-threat-index| | | | | | |
|mailslot| | | | | | |
|pipe| | | | | | |
|ssl-cert-attributes| | | | | | |
|x509-fingerprint-sha1| | X | | X | X | |

|Category| Other |
| --- |:---:|
|md5| |
|sha1| |
|sha256| |
|filename| |
|pdb| |
|filename&#124;md5| |
|filename&#124;sha1| |
|filename&#124;sha256| |
|ip-src| |
|ip-dst| |
|hostname| |
|domain| |
|domain&#124;ip| |
|email-src| |
|email-dst| |
|email-subject| |
|email-attachment| |
|url| |
|http-method| |
|user-agent| |
|regkey| |
|regkey&#124;value| |
|AS| |
|snort| |
|pattern-in-file| |
|pattern-in-traffic| |
|pattern-in-memory| |
|yara| |
|vulnerability| |
|attachment| |
|malware-sample| |
|link| |
|comment| X |
|text| X |
|other| X |
|named pipe| |
|mutex| |
|target-user| |
|target-email| |
|target-machine| |
|target-org| |
|target-location| |
|target-external| |
|btc| |
|iban| |
|bic| |
|bank-account-nr| |
|aba-rtn| |
|bin| |
|cc-number| |
|prtn| |
|threat-actor| |
|campaign-name| |
|campaign-id| |
|malware-type| |
|uri| |
|authentihash| |
|ssdeep| |
|imphash| |
|pehash| |
|sha-224| |
|sha-384| |
|sha-512| |
|sha-512/224| |
|sha-512/256| |
|tlsh| |
|filename&#124;authentihash| |
|filename&#124;ssdeep| |
|filename&#124;imphash| |
|filename&#124;pehash| |
|filename&#124;sha-224| |
|filename&#124;sha-384| |
|filename&#124;sha-512| |
|filename&#124;sha-512/224| |
|filename&#124;sha-512/256| |
|filename&#124;tlsh| |
|windows-scheduled-task| |
|windows-service-name| |
|windows-service-displayname| |
|whois-registrant-email| |
|whois-registrant-phone| |
|whois-registrant-name| |
|whois-registrar| |
|whois-creation-date| |
|targeted-threat-index| |
|mailslot| |
|pipe| |
|ssl-cert-attributes| |
|x509-fingerprint-sha1| |

### Categories

*   **Internal reference**: Reference used by the publishing party (e.g. ticket number)
*   **Targeting data**: Targeting information to include recipient email, infected machines, department, and or locations.<br/>
*   **Antivirus detection**: List of anti-virus vendors detecting the malware or information on detection performance (e.g. 13/43 or 67%). Attachment with list of detection or link to VirusTotal could be placed here as well.
*   **Payload delivery**: Information about the way the malware payload is initially delivered, for example information about the email or web-site, vulnerability used, originating IP etc. Malware sample itself should be attached here.
*   **Artifacts dropped**: Any artifact (files, registry keys etc.) dropped by the malware or other modifications to the system
*   **Payload installation**: Location where the payload was placed in the system and the way it was installed. For example, a filename|md5 type attribute can be added here like this: c:\windows\system32\malicious.exe|41d8cd98f00b204e9800998ecf8427e.
*   **Persistence mechanism**: Mechanisms used by the malware to start at boot. This could be a registry key, legitimate driver modification, LNK file in startup
*   **Network activity**: Information about network traffic generated by the malware
*   **Payload type**: Information about the final payload(s). Can contain a function of the payload, e.g. keylogger, RAT, or a name if identified, such as Poison Ivy.
*   **Attribution**: Identification of the group, organisation, or country behind the attack
*   **External analysis**: Any other result from additional analysis of the malware like tools output Examples: pdf-parser output, automated sandbox analysis, reverse engineering report.
*   **Financial fraud**: Financial Fraud indicators, for example: IBAN Numbers, BIC codes, Credit card numbers, etc.
*   **Other**: Attributes that are not part of any other category

### Types

*   **md5**: You are encouraged to use filename|md5 instead. A checksum in md5 format, only use this if you don't know the correct filename
*   **sha1**: You are encouraged to use filename|sha1 instead. A checksum in sha1 format, only use this if you don't know the correct filename
*   **sha256**: You are encouraged to use filename|sha256 instead. A checksum in sha256 format, only use this if you don't know the correct filename
*   **filename**: Filename
*   **pdb**: Microsoft Program database (PDB) path information
*   **filename|md5**: A filename and an md5 hash separated by a | (no spaces)
*   **filename|sha1**: A filename and an sha1 hash separated by a | (no spaces)
*   **filename|sha256**: A filename and an sha256 hash separated by a | (no spaces)
*   **ip-src**: A source IP address of the attacker
*   **ip-dst**: A destination IP address of the attacker or C&C server. Also set the IDS flag on when this IP is hardcoded in malware
*   **hostname**: A full host/dnsname of an attacker. Also set the IDS flag on when this hostname is hardcoded in malware
*   **domain**: A domain name used in the malware. Use this instead of hostname when the upper domain is important or can be used to create links between events.
*   **domain|ip**: A domain name and its IP address (as found in DNS lookup) separated by a | (no spaces)
*   **email-src**: The email address (or domainname) used to send the malware.
*   **email-dst**: A recipient email address that is not related to your constituency.
*   **email-subject**: The subject of the email
*   **email-attachment**: File name of the email attachment.
*   **url**: url
*   **http-method**: HTTP method used by the malware (e.g. POST, GET, ...).
*   **user-agent**: The user-agent used by the malware in the HTTP request.
*   **regkey**: Registry key or value
*   **regkey|value**: Registry value + data separated by |
*   **AS**: Autonomous system
*   **snort**: An IDS rule in Snort rule-format. This rule will be automatically rewritten in the NIDS exports.
*   **pattern-in-file**: Pattern in file that identifies the malware
*   **pattern-in-traffic**: Pattern in network traffic that identifies the malware
*   **pattern-in-memory**: Pattern in memory dump that identifies the malware
*   **yara**: Yara signature
*   **vulnerability**: A reference to the vulnerability used in the exploit
*   **attachment**: Please upload files using the <em>Upload Attachment</em> button.
*   **malware-sample**: Please upload files using the <em>Upload Attachment</em> button.
*   **link**: Link to an external information
*   **comment**: Comment or description in a human language. This will not be correlated with other attributes
*   **text**: Name, ID or a reference
*   **other**: Other attribute
*   **named pipe**: Named pipe, use the format \.\pipe\<PipeName>
*   **mutex**: Mutex, use the format \BaseNamedObjects\<Mutex>
*   **target-user**: Attack Targets Username(s)
*   **target-email**: Attack Targets Email(s)
*   **target-machine**: Attack Targets Machine Name(s)
*   **target-org**: Attack Targets Department or Organization(s)
*   **target-location**: Attack Targets Physical Location(s)
*   **target-external**: External Target Organizations Affected by this Attack
*   **btc**: Bitcoin Address
*   **iban**: International Bank Account Number
*   **bic**: Bank Identifier Code Number
*   **bank-account-nr**: Bank account number without any routing number
*   **aba-rtn**: ABA routing transit number
*   **bin**: Bank Identification Number
*   **cc-number**: Credit-Card Number
*   **prtn**: Premium-Rate Telephone Number
*   **threat-actor**: A string identifying the threat actor
*   **campaign-name**: Associated campaign name
*   **campaign-id**: Associated campaign ID
*   **malware-type**:
*   **uri**: Uniform Resource Identifier
*   **authentihash**: You are encouraged to use filename|authentihash instead. Authenticode executable signature hash, only use this if you don't know the correct filename
*   **ssdeep**: You are encouraged to use filename|ssdeep instead. A checksum in the SSDeep format, only use this if you don't know the correct filename
*   **imphash**: You are encouraged to use filename|imphash instead. A hash created based on the imports in the sample, only use this if you don't know the correct filename
*   **pehash**: PEhash - a hash calculated based of certain pieces of a PE executable file
*   **sha-224**: You are encouraged to use filename|sha224 instead. A checksum in sha224 format, only use this if you don't know the correct filename
*   **sha-384**: You are encouraged to use filename|sha384 instead. A checksum in sha384 format, only use this if you don't know the correct filename
*   **sha-512**: You are encouraged to use filename|sha512 instead. A checksum in sha512 format, only use this if you don't know the correct filename
*   **sha-512/224**: You are encouraged to use filename|sha512/224 instead. A checksum in sha512/224 format, only use this if you don't know the correct filename
*   **sha-512/256**: You are encouraged to use filename|sha512/256 instead. A checksum in sha512/256 format, only use this if you don't know the correct filename
*   **tlsh**: You are encouraged to use filename|tlsh instead. A checksum in the Trend Micro Locality Sensitive Hash format, only use this if you don't know the correct filename
*   **filename|authentihash**: A checksum in md5 format
*   **filename|ssdeep**: A checksum in ssdeep format
*   **filename|imphash**: Import hash - a hash created based on the imports in the sample.
*   **filename|pehash**: A filename and a PEhash separated by a |
*   **filename|sha-224**: A filename and a sha-224 hash separated by a |
*   **filename|sha-384**: A filename and a sha-384 hash separated by a |
*   **filename|sha-512**: A filename and a sha-512 hash separated by a |
*   **filename|sha-512/224**: A filename and a sha-512/224 hash separated by a |
*   **filename|sha-512/256**: A filename and a sha-512/256 hash separated by a |
*   **filename|tlsh**: A filename and a Trend Micro Locality Sensitive Hash separated by a |
*   **windows-scheduled-task**: A scheduled task in windows
*   **windows-service-name**: A windows service name. This is the name used internally by windows. Not to be confused with the windows-service-displayname.
*   **windows-service-displayname**: A windows service's displayname, not to be confused with the windows-service-name. This is the name that applications will generally display as the service's name in applications.
*   **whois-registrant-email**: The e-mail of a domain's registrant, obtained from the WHOIS information.
*   **whois-registrant-phone**: The phone number of a domain's registrant, obtained from the WHOIS information.
*   **whois-registrant-name**: The name of a domain's registrant, obtained from the WHOIS information.
*   **whois-registrar**: The registrar of the domain, obtained from the WHOIS information.
*   **whois-creation-date**: The date of domain's creation, obtained from the WHOIS information.
*   **targeted-threat-index**:
*   **mailslot**: MailSlot interprocess communication
*   **pipe**: Pipeline (for named pipes use the attribute type "named pipe")
*   **ssl-cert-attributes**: SSL certificate attributes
*   **x509-fingerprint-sha1**: X509 fingerprint in SHA-1 format
