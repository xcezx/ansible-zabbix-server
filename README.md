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
- `zabbix_server_AlertScriptsPath`
- `zabbix_server_AllowRoot`
- `zabbix_server_CacheSize`
- `zabbix_server_CacheUpdateFrequency`
- `zabbix_server_DBHost`
- `zabbix_server_DBName`
- `zabbix_server_DBPassword`
- `zabbix_server_DBPort`
- `zabbix_server_DBSchema`
- `zabbix_server_DBSocket`
- `zabbix_server_DebugLevel`
- `zabbix_server_ExternalScripts`
- `zabbix_server_Fping6Location`
- `zabbix_server_FpingLocation`
- `zabbix_server_HistoryCacheSize`
- `zabbix_server_HistoryTextCacheSize`
- `zabbix_server_HousekeepingFrequency`
- `zabbix_server_Include`
- `zabbix_server_JavaGateway`
- `zabbix_server_JavaGatewayPort`
- `zabbix_server_ListenIP`
- `zabbix_server_ListenPort`
- `zabbix_server_LoadModule`
- `zabbix_server_LoadModulePath`
- `zabbix_server_LogFile`
- `zabbix_server_LogFileSize`
- `zabbix_server_LogSlowQueries`
- `zabbix_server_MaxHousekeeperDelete`
- `zabbix_server_NodeID`
- `zabbix_server_NodeNoEvents`
- `zabbix_server_NodeNoHistory`
- `zabbix_server_PidFile`
- `zabbix_server_ProxyConfigFrequency`
- `zabbix_server_ProxyDataFrequency`
- `zabbix_server_SNMPTrapperFile`
- `zabbix_server_SSHKeyLocation`
- `zabbix_server_SSLCALocation`
- `zabbix_server_SSLCertLocation`
- `zabbix_server_SSLKeyLocation`
- `zabbix_server_SenderFrequency`
- `zabbix_server_SourceIP`
- `zabbix_server_StartDBSyncers`
- `zabbix_server_StartDiscoverers`
- `zabbix_server_StartHTTPPollers`
- `zabbix_server_StartIPMIPollers`
- `zabbix_server_StartJavaPollers`
- `zabbix_server_StartPingers`
- `zabbix_server_StartPollers`
- `zabbix_server_StartPollersUnreachable`
- `zabbix_server_StartProxyPollers`
- `zabbix_server_StartSNMPTrapper`
- `zabbix_server_StartTimers`
- `zabbix_server_StartTrappers`
- `zabbix_server_StartVMwareCollectors`
- `zabbix_server_Timeout`
- `zabbix_server_TmpDir`
- `zabbix_server_TrapperTimeout`
- `zabbix_server_TrendCacheSize`
- `zabbix_server_UnavailableDelay`
- `zabbix_server_UnreachableDelay`
- `zabbix_server_UnreachablePeriod`
- `zabbix_server_User`
- `zabbix_server_VMwareCacheSize`
- `zabbix_server_VMwareFrequency`
- `zabbix_server_ValueCacheSize`

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
