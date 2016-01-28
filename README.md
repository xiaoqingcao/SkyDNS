# SkyDNS
SkyDNS is a distributed service for announcement and discovery of services. It leverages Raft for high-availability and consensus, and utilizes DNS queries to discover available services. This is done by leveraging SRV records in DNS, with special meaning given to subdomains, priorities and weights.
