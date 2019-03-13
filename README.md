[![Build Status](https://api.travis-ci.com/ytti/icmp-eo-timestamp.svg)](https://travis-ci.com/ytti/icmp-eo-timestamp)

# ICMP Extension Object for Timestamps

ICMP Extension Object for Timestamp is a draft which documents how a host can
add timestamps to some ICMP messages, such as TTL exceeded and unreachable.

Using these timestamps host originating traceroute can render unidirectional
latencies, giving more diagnostic power to traceroute allowing traceroute to
further reduce outage times by allowing more rapid troubleshooting.

# Authoring Conventions

* One sentence per line, this makes diff viewing easiest.
* Only edit the .[xml] file (the .[txt] and .[html] files are computer generated).
* Be sure to keep track of the names of contributors through the Acknowledgements section and the git log.

# Note Well

This repository relates to activities in the Internet Engineering Task Force
(IETF). All material in this repository is considered Contributions to the IETF
Standards Process, as defined in the intellectual property policies of IETF
currently designated as BCP 78 (https://www.rfc-editor.org/info/bcp78), BCP 79
(https://www.rfc-editor.org/info/bcp79) and the IETF Trust Legal Provisions
(TLP) Relating to IETF Documents (http://trustee.ietf.org/trust-legal-provisions.html).

Any edit, commit, pull request, issue, comment or other change made to this
repository constitutes Contributions to the IETF Standards Process
(https://www.ietf.org/).

You agree to comply with all applicable IETF policies and procedures,
including, BCP 78, 79, the TLP, and the TLP rules regarding code components
(e.g. being subject to a Simplified BSD License) in Contributions.

[xml]: https://ytti.github.io/icmp-eo-timestamp/draft-ytti-intarea-icmp-eo-timestamp.xml
[txt]: https://ytti.github.io/icmp-eo-timestamp/draft-ytti-intarea-icmp-eo-timestamp.txt
[html]: https://ytti.github.io/icmp-eo-timestamp/draft-ytti-intarea-icmp-eo-timestamp.html
