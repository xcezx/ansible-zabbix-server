zabbix-server [![Build Status](https://travis-ci.org/xcezx/ansible-zabbix-server.svg)](https://travis-ci.org/xcezx/ansible-zabbix-server)
========

install and configuration zabbix-server

Requirements
------------

- `mysqld`
- `MySQL-python`

Role Variables
--------------

- `zabbix_server_install_packages`
- `zabbix_server_settings`
  - `AlertScriptsPath`
  - `AllowRoot`
  - `CacheSize`
  - `CacheUpdateFrequency`
  - `DBHost`
  - `DBName`
  - `DBPassword`
  - `DBPort`
  - `DBSchema`
  - `DBSocket`
  - `DBUser`
  - `DebugLevel`
  - `ExternalScripts`
  - `Fping6Location`
  - `FpingLocation`
  - `HistoryCacheSize`
  - `HistoryTextCacheSize`
  - `HousekeepingFrequency`
  - `Include`
  - `JavaGateway`
  - `JavaGatewayPort`
  - `ListenIP`
  - `ListenPort`
  - `LoadModule`
  - `LoadModulePath`
  - `LogFile`
  - `LogFileSize`
  - `LogSlowQueries`
  - `MaxHousekeeperDelete`
  - `NodeID`
  - `NodeNoEvents`
  - `NodeNoHistory`
  - `PidFile`
  - `ProxyConfigFrequency`
  - `ProxyDataFrequency`
  - `SenderFrequency`
  - `SNMPTrapperFile`
  - `SourceIP`
  - `SSHKeyLocation`
  - `StartDBSyncers`
  - `StartDiscoverers`
  - `StartHTTPPollers`
  - `StartIPMIPollers`
  - `StartJavaPollers`
  - `StartPingers`
  - `StartPollersUnreachable`
  - `StartPollers`
  - `StartProxyPollers`
  - `StartSNMPTrapper`
  - `StartTimers`
  - `StartTrappers`
  - `StartVMwareCollectors`
  - `Timeout`
  - `TmpDir`
  - `TrapperTimeout`
  - `TrendCacheSize`
  - `UnavailableDelay`
  - `UnreachableDelay`
  - `UnreachablePeriod`
  - `ValueCacheSize`
  - `VMwareCacheSize`
  - `VMwareFrequency`

Dependencies
------------

- `xcezx.zabbix-repository`

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xcezx.zabbix-server }

License
-------

BSD
