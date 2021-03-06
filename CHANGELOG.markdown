CHANGELOG
=====

ZkClient 0.12 (???)
---------------
- ...

ZkClient 0.11 (Okt 2018)
---------------
- Upgrade to Zookeeper 3.4.13 (from 3.4.8)
  - Fix UnknownHostException if one of the server hosts is currently not available


ZkClient 0.10 (Nov 2016)
---------------
- #56: Switch from Log4j to Slf4j
- #41: Provide more information about zookeeper server in case of connection errors


ZkClient 0.9 (June 2016)
---------------
- Upgrade to Zookeeper 3.4.8 (from 3.4.6)


ZkClient 0.8 (Mar 2016)
---------------
- #45: Support for conditional deletes
- Adding ZkAuthFailedException
- exclude org.apache.jute and zookeeper.proto from imported packages of MANIFEST.MF


ZkClient 0.7 (Nov 2015)
---------------
- #38: wait on SaslAuthenticated event when SASL is enabled


ZkClient 0.6 (Aug 2015)
---------------
- Adding setAcl and getAcl methods to zkClient so users can setAcls not just during creation but after creation of node as well.
- Upgrade to Zookeeper 3.4.6 (from 3.4.3)


ZkClient 0.5 (Apr, 2015)
---------------
- Upgrade to zookeeper 3.4.3 (from 3.3.1)
- Added support for multiops support
- Add an option to ZkClient to specify operation retry timeout
- Support for ACLs
- #25: fail retryUntilConnected actions with clear exception in case client gets closed


ZkClient 0.4 (Oct, 2013)
---------------
- Support for handling SessionEstablishmentErrors