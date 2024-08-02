# vCenter Server 6.7 Update 1 Build 10244745 Advanced Settings

Total: 694

| Name | Description | Value |
|---|---|---|
| ads.checkInterval | User validation interval | 1440  |
| ads.checkIntervalEnabled | Enable user validation | True  |
| ads.maxFetch | Maximum users to retrieve | 5000  |
| ads.maxFetchEnabled | Enable user retrieve limits | True  |
| ads.timeout | User retrieve timeout | 60  |
| alarms.version | Default alarm upgrade version | 61  |
| client.timeout.long | Long operation client timeout | 120  |
| client.timeout.normal | Client timeout | 30  |
| client.VerifySSLCertificates | Verify SSL certificates | True  |
| config.alarms.vim.version |  | vim.version.version13  |
| config.drs.kvstore.local |  | False  |
| config.log.compressOnRoll |  | true  |
| config.log.level |  | info  |
| config.log.maxFileNum |  | 30  |
| config.log.maxFileSize |  | 52428800  |
| config.log.outputToConsole |  | false  |
| config.log.outputToFiles |  | true  |
| config.log.outputToSyslog |  | false  |
| config.log.syslog.facility |  | local4  |
| config.log.syslog.ident |  | vpxd  |
| config.log.syslog.logHeaderFile |  | /var/run/vmware/vpxdLogHeader.txt  |
| config.registry.DB.key_2 |  | vc  |
| config.registry.DB.key_3 |  | *6zvZcyN+An0CP4TeHsPvmdk+4PUjXLMr+Fkyt3rjOzCFkcv6itRKS6vb3x3dR1iL  |
| config.registry.key_EvaluationExpiryDate |  | AQD+yggAAABvb2gYHSLj6EQAAACwCsrxHmp1MWSoIRD9Z37FVoCdbV6IHH9WoF8r9OVsTzgyj+gdMPfmFm8C0jf7yLlMcABOm4cHTRzLK7KHC4Hy1Luu8A==  |
| config.task.minCompletedLifetime |  | 60  |
| config.vmacore.cacheProperties |  | true  |
| config.vmacore.ssl |  |   |
| config.vmacore.threadPool.TaskMax |  | 90  |
| config.vmacore.threadPool.threadNamePrefix |  | vpxd  |
| config.vmomi.validation |  |   |
| config.vpxd.cert.prefix.solutionUser |  | vcsoluser  |
| config.vpxd.cert.prefix.ssl |  | rui  |
| config.vpxd.enableDebugBrowse | Debug Managed Object Browser enabled | True  |
| config.vpxd.filterOverheadLimitIssues |  | true  |
| config.vpxd.heartbeat.udp-port |  | 902  |
| config.vpxd.hostGateway.enabled |  | true  |
| config.vpxd.hostGateway.gatewaySource |  | ComponentManager  |
| config.vpxd.hostnameUrl |  | vcsa.williamlam.com  |
| config.vpxd.hostProfiles.disableSecureManager |  | false  |
| config.vpxd.hostProfiles.drsReservedCapacity |  | 100  |
| config.vpxd.hostProfiles.enterMMTimeout |  | 3600  |
| config.vpxd.hostProfiles.metadataCacheEnabled |  | true  |
| config.vpxd.hostProfiles.rebootTimeout |  | 3600  |
| config.vpxd.hostProfiles.statefulCollectHostSpec |  | false  |
| config.vpxd.licenseEdition |  | vc  |
| config.vpxd.memChecker.memStopInMB |  | 1024  |
| config.vpxd.network.rollback |  | true  |
| config.vpxd.odbc.dbtype |  | embedded  |
| config.vpxd.odbc.dbversion |  | PostgreSQL 9.6.9  |
| config.vpxd.odbc.dsn |  | VMware VirtualCenter  |
| config.vpxd.rhttpproxy.httpport |  | 80  |
| config.vpxd.rhttpproxy.httpsport |  | 443  |
| config.vpxd.secureSoapPort |  | 8089  |
| config.vpxd.soapPort |  | 8085  |
| config.vpxd.ssl.CAPath |  | /etc/ssl/certs  |
| config.vpxd.sso.admin.uri |  | vcsa.williamlam.com  |
| config.vpxd.sso.default.admin |  | Administrator@vsphere.local  |
| config.vpxd.sso.default.isGroup |  | false  |
| config.vpxd.sso.groupcheck.uri |  | vcsa.williamlam.com  |
| config.vpxd.sso.solutionUser.certificate |  | /etc/vmware-vpx/ssl/vcsoluser.crt  |
| config.vpxd.sso.solutionUser.name |  | vpxd-7cbc8f10-32f6-4a16-b044-199248a0e192@vsphere.local  |
| config.vpxd.sso.solutionUser.privateKey |  | /etc/vmware-vpx/ssl/vcsoluser.key  |
| config.vpxd.sso.sts.uri |  | vcsa.williamlam.com  |
| config.vpxd.support.scriptDirectory |  | /usr/lib/vmware-vpx  |
| config.vpxd.vcha.drsAntiAffinity |  | true  |
| config.vpxd.vecs.storeName |  | vpxd  |
| config.vpxd.vsan.dynmgr.enable |  | true  |
| config.vpxd.vsan.hostaffinity.enable |  | false  |
| config.workflow.port |  | WORKFLOW_PORT  |
| DBProc.Log.Buffer | DB procedures log buffer | 5000  |
| DBProc.Log.Debug.Info |  | ON  |
| DBProc.Log.Event.Purge |  | 10  |
| DBProc.Log.Stats.Purge |  | 10  |
| DBProc.Log.Topn.Purge |  | 5000  |
| etc.issue | /etc/issue | VMware vCenter Server Appliance 6.7.0.20000 Type: vCenter Server with an embedded Platform Services Controller  |
| etc.motd | /etc/motd |   |
| event.batchsize | Batch size in cleanup events procedure | 2000  |
| event.maxAge | Maximum event age | 30  |
| event.maxAgeEnabled | Enable event cleanup | True  |
| instance.id | Instance ID | 54  |
| LicenseServer.matchHostToVirtualCenter | Match host license server to vCenter | True  |
| log.level | Logging level | info  |
| logger.[SSO] |  | info  |
| logger.[SSO][AdminAdapter] |  | info  |
| logger.[SSO][AuthTokenFactory] |  | info  |
| logger.[SSO][DomainIdNormalizer] |  | info  |
| logger.[SSO][GroupcheckAdapter] |  | info  |
| logger.[SSO][LookupServiceImpl] |  | info  |
| logger.[SSO][SsoAdminFacadeImpl] |  | info  |
| logger.[SSO][SsoCertificateManagerImpl] |  | info  |
| logger.[SSO][SsoWrapperImpl] |  | info  |
| logger.Alarm |  | info  |
| logger.alarmMo |  | info  |
| logger.AlarmXAction |  | info  |
| logger.App |  | info  |
| logger.AssetPropertiesUpdater |  | info  |
| logger.Attestation |  | info  |
| logger.Auth_win32 |  | info  |
| logger.Authorize |  | info  |
| logger.AuthorizeManager |  | info  |
| logger.AuthzStorageProvider |  | info  |
| logger.BackupRestore |  | info  |
| logger.bufferedClientRequest |  | info  |
| logger.CallbackServiceManager |  | info  |
| logger.CatalogSyncManager |  | info  |
| logger.cdrsPlmt |  | info  |
| logger.CertificateClientLogin |  | info  |
| logger.certmgrLogger |  | info  |
| logger.certRequestHandler |  | info  |
| logger.certUtils |  | info  |
| logger.changeTag |  | info  |
| logger.checkswapPlacementInfo |  | info  |
| logger.ClientAdapterBase |  | info  |
| logger.ClientPreload |  | info  |
| logger.ClientUpgrader |  | info  |
| logger.clusterCache |  | info  |
| logger.clusterChecker |  | info  |
| logger.cnxmgrLogger |  | info  |
| logger.componentManagerUtil |  | info  |
| logger.ComputeResEventMgr |  | info  |
| logger.ComputeResLock |  | info  |
| logger.ConfigIssue |  | info  |
| logger.copySpecUtil |  | info  |
| logger.coreanchor |  | info  |
| logger.coredvsSync |  | info  |
| logger.corehostCapsule |  | info  |
| logger.corehostSync |  | info  |
| logger.corestress |  | info  |
| logger.coreunitTest |  | info  |
| logger.corevalidate |  | info  |
| logger.CpuFeatures |  | info  |
| logger.Crypter |  | info  |
| logger.CryptHelper |  | info  |
| logger.CryptoManager |  | info  |
| logger.CryptoManagerKmipWrapper |  | info  |
| logger.CryptUtil |  | info  |
| logger.Daemon |  | info  |
| logger.DAS |  | info  |
| logger.dasVm |  | info  |
| logger.Datastore |  | info  |
| logger.DbBulkLoader |  | info  |
| logger.dbDvs |  | info  |
| logger.DbHelper |  | info  |
| logger.dbHost |  | info  |
| logger.DbLoad |  | info  |
| logger.DbMonitoring |  | info  |
| logger.DbParallelLoader |  | info  |
| logger.dbPort |  | info  |
| logger.dbPortgroup |  | info  |
| logger.dbQuery |  | info  |
| logger.DbSchemaHash |  | info  |
| logger.dbuHelper |  | info  |
| logger.DbUtil |  | info  |
| logger.DebugBrowser |  | info  |
| logger.DebugBrowser.HTTPService |  | info  |
| logger.DebugBrowser.HTTPService.HttpConnection |  | info  |
| logger.Default |  | info  |
| logger.doImpersonate |  | info  |
| logger.drmLogger |  | info  |
| logger.drsExec |  | info  |
| logger.DvpgSender |  | info  |
| logger.DvsCore |  | info  |
| logger.DvsHostMethodDispatcher |  | info  |
| logger.dvsKeeper |  | info  |
| logger.DvsLock |  | info  |
| logger.DvsUtils |  | info  |
| logger.dynamicMethodValidator |  | info  |
| logger.EventLsNotificationsProcessor |  | info  |
| logger.EventTaskCleanup |  | info  |
| logger.EventTypes |  | info  |
| logger.ExtensionParser |  | info  |
| logger.ExternalStatsManager |  | info  |
| logger.FailoverClusterConfigurator |  | info  |
| logger.FailoverClusterManager |  | info  |
| logger.FailoverClusterOperator |  | info  |
| logger.FairScheduler |  | info  |
| logger.featureiorm |  | info  |
| logger.featureldp |  | info  |
| logger.FirewallRulesets |  | info  |
| logger.firewallrulesets |  | info  |
| logger.ftUtils |  | info  |
| logger.GuestName |  | info  |
| logger.guestops |  | info  |
| logger.halhost |  | info  |
| logger.halservices |  | info  |
| logger.hbr |  | info  |
| logger.Health |  | info  |
| logger.healthCheck |  | info  |
| logger.Heartbeat |  | info  |
| logger.HostAccess |  | info  |
| logger.HostCnx |  | info  |
| logger.hostdcnx |  | info  |
| logger.hostdcompRes |  | info  |
| logger.hostdds |  | info  |
| logger.hostddvs |  | info  |
| logger.hostdevent |  | info  |
| logger.hostdhost |  | info  |
| logger.hostdhostConfig |  | info  |
| logger.hostdlicenseMgr |  | info  |
| logger.hostdlocalizationMgr |  | info  |
| logger.hostdstats |  | info  |
| logger.hostdstorageSystem |  | info  |
| logger.hostdvm |  | info  |
| logger.hostdVMotion |  | info  |
| logger.HostGateway |  | info  |
| logger.hostInvtOps |  | info  |
| logger.hostMethod |  | info  |
| logger.hostOp |  | info  |
| logger.HostOps |  | info  |
| logger.HostPicker |  | info  |
| logger.hostPropertyTracker |  | info  |
| logger.HostRecover |  | info  |
| logger.hostStateSyncer |  | info  |
| logger.HostSyncLockHelper |  | info  |
| logger.HostUpgrader |  | info  |
| logger.HTTP server |  | info  |
| logger.HTTP server /folder |  | info  |
| logger.HTTP session map |  | info  |
| logger.HttpConnectionPool-000000 |  | info  |
| logger.HttpConnectionPool-000001 |  | info  |
| logger.HttpConnectionPool-000003 |  | info  |
| logger.HttpConnectionPool-000004 |  | info  |
| logger.HttpConnectionPool-000005 |  | info  |
| logger.HttpConnectionPool-000006 |  | info  |
| logger.HttpConnectionPool-000007 |  | info  |
| logger.HttpConnectionPool-000008 |  | info  |
| logger.HttpConnectionPool-000009 |  | info  |
| logger.HttpConnectionPool-000010 |  | info  |
| logger.HttpConnectionPool-000011 |  | info  |
| logger.HttpConnectionPool-000012 |  | info  |
| logger.HttpConnectionPool-000013 |  | info  |
| logger.HttpConnectionPool-000015 |  | info  |
| logger.HttpNfcBridgeHandler |  | info  |
| logger.HttpNfcTicket |  | info  |
| logger.HttpSvc |  | info  |
| logger.HttpSvc.HTTPService |  | info  |
| logger.HttpSvc.HTTPService.HttpConnection |  | info  |
| logger.httpUtil |  | info  |
| logger.infraUpdateHa |  | info  |
| logger.InternalSvc |  | info  |
| logger.Invt |  | info  |
| logger.InvtCache |  | info  |
| logger.InvtDatacenter |  | info  |
| logger.InvtDomain |  | info  |
| logger.InvtDVPortGroup |  | info  |
| logger.InvtDVS |  | info  |
| logger.InvtGroup |  | info  |
| logger.InvtHost |  | info  |
| logger.InvtHostCnx |  | info  |
| logger.InvtHostDb |  | info  |
| logger.InvtId |  | info  |
| logger.InvtListener |  | info  |
| logger.InvtNetwork |  | info  |
| logger.InvtResGroup |  | info  |
| logger.InvtStoragePod |  | info  |
| logger.InvtVm |  | info  |
| logger.InvtVmDb |  | info  |
| logger.IO |  | quiet  |
| logger.Iofilter |  | info  |
| logger.IpAllocator |  | info  |
| logger.ipfix |  | info  |
| logger.journal |  | info  |
| logger.journalIO |  | quiet  |
| logger.lacp |  | info  |
| logger.licenseAssignmentChangeNotifier |  | info  |
| logger.licenseAssignmentCleaner |  | info  |
| logger.licenseClient |  | info  |
| logger.licenseClientCached |  | info  |
| logger.licenseClientFaultTolerance |  | info  |
| logger.licenseClientStarter |  | info  |
| logger.LicenseManager |  | info  |
| logger.LicenseServiceClientCachedImpl |  | info  |
| logger.LicenseServiceClientImpl |  | info  |
| logger.licenseServiceDiscovery |  | info  |
| logger.licenseServiceProxy |  | info  |
| logger.licenseViolationRemediator |  | info  |
| logger.Locale |  | info  |
| logger.localizationMgr |  | info  |
| logger.Lock |  | info  |
| logger.LogBundler |  | info  |
| logger.LSClient |  | info  |
| logger.LsNotificationsRetriever |  | info  |
| logger.lunUtil |  | info  |
| logger.Mail_win32 |  | info  |
| logger.Main |  | info  |
| logger.Memory checker |  | info  |
| logger.mergeOp |  | info  |
| logger.MethodValidator |  | info  |
| logger.MoAlarmMonitor |  | info  |
| logger.MoAuthMagr |  | info  |
| logger.MoBase |  | info  |
| logger.MoCbrcManager |  | info  |
| logger.MoCluster |  | info  |
| logger.moClusterProfile |  | info  |
| logger.moClusterProfileMgr |  | info  |
| logger.moComplianceManager |  | info  |
| logger.MoComputeRes |  | info  |
| logger.MoCustSpecMgr |  | info  |
| logger.MoDatacenter |  | info  |
| logger.MoDatastore |  | info  |
| logger.MoDatastoreBrowser |  | info  |
| logger.MoDiagnosticMgr |  | info  |
| logger.MoDVPortGroup |  | info  |
| logger.MoDvs |  | info  |
| logger.MoDvsManager |  | info  |
| logger.MoDVSwitch |  | info  |
| logger.MoEnvBrowser |  | info  |
| logger.MoEsxAgentConfigMgr |  | info  |
| logger.MoEvent |  | info  |
| logger.MoExtensionMgr |  | info  |
| logger.MoFields |  | info  |
| logger.MoFileMgr |  | info  |
| logger.MoGuestCustMgr |  | info  |
| logger.MoHost |  | info  |
| logger.MoHostConfig |  | info  |
| logger.moHostProfile |  | info  |
| logger.moHostProfileMgr |  | info  |
| logger.MoHttpNfcLease |  | info  |
| logger.MoIpPoolMgr |  | info  |
| logger.MoLicenseDataMgr |  | info  |
| logger.MoLicenseMgr |  | info  |
| logger.MoLock |  | info  |
| logger.MoLocMgr |  | info  |
| logger.MoNetworkManager |  | info  |
| logger.MoOptionMgr |  | info  |
| logger.MoOvfMgr |  | info  |
| logger.MoPerfManager |  | info  |
| logger.moProfile |  | info  |
| logger.moProfileMgr |  | info  |
| logger.MoResGroup |  | info  |
| logger.MoReverseProxy |  | info  |
| logger.MoScheduledTask |  | info  |
| logger.MoSearchIndex |  | info  |
| logger.MoServiceInstance |  | info  |
| logger.MoSessionMgr |  | info  |
| logger.MoSnapshot |  | info  |
| logger.MoStoragePod |  | info  |
| logger.MoSystemDebugMgr |  | info  |
| logger.MoTask |  | info  |
| logger.MoTransEVCMgr |  | info  |
| logger.MoVApp |  | info  |
| logger.MoVAppPowerOp |  | info  |
| logger.moveOp |  | info  |
| logger.MoVirtualDiskMgr |  | info  |
| logger.MoVmciAccessMgr |  | info  |
| logger.MoVStorageObjectMgr |  | info  |
| logger.NfcMgr |  | info  |
| logger.NfcServiceProxy |  | info  |
| logger.OCM |  | info  |
| logger.OMM |  | info  |
| logger.OMMHCC |  | info  |
| logger.OMMHostInfo |  | info  |
| logger.OMMHSC |  | info  |
| logger.OMMOutputCache |  | info  |
| logger.OMMVmInfo |  | info  |
| logger.OpaqueChannel |  | info  |
| logger.OsLayer_linux |  | info  |
| logger.OsLayer_win32 |  | info  |
| logger.overheadMemory |  | info  |
| logger.OvfConsumers |  | info  |
| logger.OvfEnv |  | info  |
| logger.pbm |  | info  |
| logger.PcLsNotificationsProcessor |  | info  |
| logger.PerfCluster |  | info  |
| logger.PerfCounter::Registry |  | info  |
| logger.PerfProvider |  | info  |
| logger.PerfVmOps |  | info  |
| logger.PortSender |  | info  |
| logger.PriorityInfo.16 |  | info  |
| logger.PriorityInfo.4 |  | info  |
| logger.PriorityInfo.8 |  | info  |
| logger.profileExtract |  | info  |
| logger.profileUtil |  | info  |
| logger.PropertyCache |  | info  |
| logger.PropertyCollector |  | info  |
| logger.PropertyJournal |  | info  |
| logger.PropertyProvider |  | info  |
| logger.provisioning |  | info  |
| logger.proxyManagedObjectImpl |  | info  |
| logger.pvlan |  | info  |
| logger.QuickStats |  | info  |
| logger.ResMgr |  | info  |
| logger.ResourceMgr |  | info  |
| logger.ResourcePlanningMgr |  | info  |
| logger.ResPoolTree |  | info  |
| logger.sdrsLogger |  | info  |
| logger.secondaryVmCreator |  | info  |
| logger.ServerAccess |  | info  |
| logger.Service |  | info  |
| logger.ServiceMgrImpl |  | info  |
| logger.session pool |  | info  |
| logger.SessionPropertiesFilter |  | info  |
| logger.SimpleCommandImpl |  | info  |
| logger.sms |  | info  |
| logger.Snmp |  | info  |
| logger.SOAP-1 |  | info  |
| logger.SOAP-10 |  | info  |
| logger.SOAP-11 |  | info  |
| logger.SOAP-12 |  | info  |
| logger.SOAP-13 |  | info  |
| logger.SOAP-14 |  | info  |
| logger.SOAP-15 |  | info  |
| logger.SOAP-16 |  | info  |
| logger.SOAP-17 |  | info  |
| logger.SOAP-18 |  | info  |
| logger.SOAP-19 |  | info  |
| logger.SOAP-2 |  | info  |
| logger.SOAP-20 |  | info  |
| logger.SOAP-21 |  | info  |
| logger.SOAP-22 |  | info  |
| logger.SOAP-23 |  | info  |
| logger.SOAP-24 |  | info  |
| logger.SOAP-25 |  | info  |
| logger.SOAP-26 |  | info  |
| logger.SOAP-27 |  | info  |
| logger.SOAP-28 |  | info  |
| logger.SOAP-29 |  | info  |
| logger.SOAP-3 |  | info  |
| logger.SOAP-30 |  | info  |
| logger.SOAP-31 |  | info  |
| logger.SOAP-32 |  | info  |
| logger.SOAP-33 |  | info  |
| logger.SOAP-34 |  | info  |
| logger.SOAP-35 |  | info  |
| logger.SOAP-36 |  | info  |
| logger.SOAP-37 |  | info  |
| logger.SOAP-38 |  | info  |
| logger.SOAP-39 |  | info  |
| logger.SOAP-4 |  | info  |
| logger.SOAP-40 |  | info  |
| logger.SOAP-41 |  | info  |
| logger.SOAP-42 |  | info  |
| logger.SOAP-43 |  | info  |
| logger.SOAP-44 |  | info  |
| logger.SOAP-45 |  | info  |
| logger.SOAP-46 |  | info  |
| logger.SOAP-47 |  | info  |
| logger.SOAP-48 |  | info  |
| logger.SOAP-49 |  | info  |
| logger.SOAP-5 |  | info  |
| logger.SOAP-50 |  | info  |
| logger.SOAP-51 |  | info  |
| logger.SOAP-52 |  | info  |
| logger.SOAP-53 |  | info  |
| logger.SOAP-54 |  | info  |
| logger.SOAP-55 |  | info  |
| logger.SOAP-56 |  | info  |
| logger.SOAP-57 |  | info  |
| logger.SOAP-58 |  | info  |
| logger.SOAP-59 |  | info  |
| logger.SOAP-6 |  | info  |
| logger.SOAP-60 |  | info  |
| logger.SOAP-61 |  | info  |
| logger.SOAP-62 |  | info  |
| logger.SOAP-63 |  | info  |
| logger.SOAP-64 |  | info  |
| logger.SOAP-65 |  | info  |
| logger.SOAP-66 |  | info  |
| logger.SOAP-67 |  | info  |
| logger.SOAP-68 |  | info  |
| logger.SOAP-69 |  | info  |
| logger.SOAP-7 |  | info  |
| logger.SOAP-70 |  | info  |
| logger.SOAP-8 |  | info  |
| logger.SOAP-9 |  | info  |
| logger.SoapAdapter |  | info  |
| logger.SoapAdapter.HTTPService |  | info  |
| logger.SoapAdapter.HTTPService.HttpConnection |  | info  |
| logger.SSL SoapAdapter |  | info  |
| logger.SSL SoapAdapter.HTTPService |  | info  |
| logger.SSL SoapAdapter.HTTPService.HttpConnection |  | info  |
| logger.ssoCertificate |  | info  |
| logger.SsoClient |  | info  |
| logger.SSPI |  | info  |
| logger.StateLock |  | info  |
| logger.Stats |  | info  |
| logger.StatsAggregator |  | info  |
| logger.StatsCollector |  | info  |
| logger.StatsFilter |  | info  |
| logger.StatsMetadata |  | info  |
| logger.stressOption |  | info  |
| logger.SupportMgr |  | info  |
| logger.svcUtils |  | info  |
| logger.sysCommandAdapter |  | info  |
| logger.tagMgr |  | info  |
| logger.Task |  | info  |
| logger.TaskInfo |  | info  |
| logger.ThreadPool |  | info  |
| logger.TopnMetadata |  | info  |
| logger.Translator |  | info  |
| logger.TxnMgr |  | info  |
| logger.Url_win32 |  | info  |
| logger.User |  | info  |
| logger.UtilEx |  | info  |
| logger.VapiAuthzFilter |  | info  |
| logger.VapiEndpoint |  | info  |
| logger.VapiEndpoint.HTTPService |  | info  |
| logger.VapiEndpoint.HTTPService.HttpConnection |  | info  |
| logger.VapiRequestHandler |  | info  |
| logger.VapiSamlVerifyFilter |  | info  |
| logger.VAppConfig |  | info  |
| logger.VAppExport |  | info  |
| logger.VAppImport |  | info  |
| logger.VAppLocker |  | info  |
| logger.VAppProperties |  | info  |
| logger.VAppUtil |  | info  |
| logger.VAppVmConfig |  | info  |
| logger.VcChangeDataCapture |  | info  |
| logger.VchaServiceClientAdapter |  | info  |
| logger.VcQueryService |  | info  |
| logger.VdbOpJournal |  | info  |
| logger.ViewManager |  | info  |
| logger.VimVapiSamlHokHandler |  | info  |
| logger.VimVapiSessionHandler |  | info  |
| logger.VimVapiSessionSvc |  | info  |
| logger.VimVapiUserPassHandler |  | info  |
| logger.virtualDiskMgr |  | info  |
| logger.VmCheck |  | info  |
| logger.vmconfig |  | info  |
| logger.VmCustomizer |  | info  |
| logger.vmft |  | info  |
| logger.vmguest |  | info  |
| logger.vmMonitor |  | info  |
| logger.vmmoVm |  | info  |
| logger.Vmomi |  | info  |
| logger.vmomi.soapStub[0] |  | info  |
| logger.vmomi.soapStub[10] |  | info  |
| logger.vmomi.soapStub[11] |  | info  |
| logger.vmomi.soapStub[12] |  | info  |
| logger.vmomi.soapStub[13] |  | info  |
| logger.vmomi.soapStub[14] |  | info  |
| logger.vmomi.soapStub[2] |  | info  |
| logger.vmomi.soapStub[3] |  | info  |
| logger.vmomi.soapStub[5] |  | info  |
| logger.vmomi.soapStub[6] |  | info  |
| logger.vmomi.soapStub[7] |  | info  |
| logger.vmomi.soapStub[8] |  | info  |
| logger.vmomi.soapStub[9] |  | info  |
| logger.VmProv |  | info  |
| logger.Vmprov |  | info  |
| logger.vmProvCheckUtil |  | info  |
| logger.VmprovUtil |  | info  |
| logger.VmprovXaction |  | info  |
| logger.VmScreenShot |  | info  |
| logger.vmsnapshot |  | info  |
| logger.vmSpaceUtil |  | info  |
| logger.vmStateSyncer |  | info  |
| logger.vmTestSet |  | info  |
| logger.VmValidate |  | info  |
| logger.Vod |  | info  |
| logger.vpxaAuthorize |  | info  |
| logger.vpxaDaemon |  | info  |
| logger.vpxaDatastore |  | info  |
| logger.vpxaDatastoreContext |  | info  |
| logger.vpxahttpHandler |  | info  |
| logger.vpxaInvtHost |  | info  |
| logger.vpxaInvtHostCnx |  | info  |
| logger.vpxaInvtVm |  | info  |
| logger.vpxaLegacyHost |  | info  |
| logger.vpxaMain |  | info  |
| logger.vpxaMoHostConfig |  | info  |
| logger.vpxaMoLicenseMgr |  | info  |
| logger.vpxaMoService |  | info  |
| logger.vpxaMoVm |  | info  |
| logger.vpxaMoVMotion |  | info  |
| logger.vpxaNameReserve |  | info  |
| logger.vpxaSessionManager |  | info  |
| logger.vpxaStatsMetadata |  | info  |
| logger.vpxaTaskInfo |  | info  |
| logger.vpxaVmConfigInfo |  | info  |
| logger.vpxaVmomi |  | info  |
| logger.vpxaVmprov |  | info  |
| logger.vpxaVmprovUtil |  | info  |
| logger.vpxCertificate |  | info  |
| logger.vpxCommon |  | info  |
| logger.vpxCrypt |  | info  |
| logger.Vpxd.MemChecker |  | info  |
| logger.vpxDas |  | info  |
| logger.VpxdAuthClient |  | info  |
| logger.VpxdHostConnection |  | info  |
| logger.vpxdUtil |  | info  |
| logger.vpxdVdb |  | info  |
| logger.vpxdvpxdSignal |  | info  |
| logger.vpxFileCopier |  | info  |
| logger.vpxFileInfo |  | info  |
| logger.vpxJournalEntry |  | info  |
| logger.vpxLro |  | info  |
| logger.VpxMutex |  | info  |
| logger.vpxNfcClient |  | info  |
| logger.vpxNfcServer |  | info  |
| logger.vpxPowerExec |  | info  |
| logger.VpxProfiler |  | info  |
| logger.vpxResultFilter |  | info  |
| logger.vpxTaskInfo |  | info  |
| logger.vpxUrl |  | info  |
| logger.vpxUrlHelper |  | info  |
| logger.vpxUtil |  | info  |
| logger.Vsan |  | info  |
| logger.VsanHealthServiceClientAdapter |  | info  |
| logger.vspan |  | info  |
| logger.VTpmManager |  | info  |
| logger.vumOp |  | info  |
| logger.VvolInfoMgr |  | info  |
| logger.VvolVasaMgr |  | info  |
| logger.Webserver |  | info  |
| logger.WorkQueue.HostProfile |  | info  |
| logger.WorkQueue.vmacoreDefaultIOCompletionQueue |  | info  |
| logger.WorkQueue.vmacoreDefaultIOQueue |  | info  |
| logger.WorkQueue.vmacoreDefaultLongTaskQueue |  | info  |
| logger.WorkQueue.vpxd.alarms.notification.queue |  | info  |
| logger.WorkQueue.vpxd.alarms.persister.queue |  | info  |
| logger.WorkQueue.vpxd.events.burstfilter |  | info  |
| logger.WorkQueue.vpxd.ovfconsumers.queue |  | info  |
| logger.WorkQueue.vpxd.stats.persister.queue |  | info  |
| mail.sender | Mail sender |   |
| mail.smtp.password | SMTP server password |   |
| mail.smtp.port | SMTP server port | 25  |
| mail.smtp.server | SMTP server |   |
| mail.smtp.username | SMTP server username |   |
| Misc.vCenterServerUpdateLevel | The update level of vCenter Server | 0  |
| Perf.Stats.MaxCollectionThreads | Maximum statistics collection threads | 2  |
| schema.version.major | Major database version | 1  |
| schema.version.minor | Minor database version | 0  |
| snmp.receiver.1.community | First SNMP receiver community | public  |
| snmp.receiver.1.enabled | Enable first SNMP receiver | True  |
| snmp.receiver.1.name | First SNMP receiver name | localhost  |
| snmp.receiver.1.port | First SNMP receiver port | 162  |
| snmp.receiver.2.community | Second SNMP receiver community |   |
| snmp.receiver.2.enabled | Enable second SNMP receiver | False  |
| snmp.receiver.2.name | Second SNMP receiver name |   |
| snmp.receiver.2.port | Second SNMP receiver port | 162  |
| snmp.receiver.3.community | Third SNMP receiver community |   |
| snmp.receiver.3.enabled | Enable third SNMP receiver | False  |
| snmp.receiver.3.name | Third SNMP receiver name |   |
| snmp.receiver.3.port | Third SNMP receiver port | 162  |
| snmp.receiver.4.community | Fourth SNMP receiver community |   |
| snmp.receiver.4.enabled | Enable fourth SNMP receiver | False  |
| snmp.receiver.4.name | Fourth SNMP receiver name |   |
| snmp.receiver.4.port | Fourth SNMP receiver port | 162  |
| SSL.Version | SSL version | all  |
| task.batchsize | Batch size in cleanup tasks procedure | 2000  |
| task.maxAge | Maximum task age | 30  |
| task.maxAgeEnabled | Enable event cleanup | True  |
| vgpu.hotmigrate.enabled | vGPU hot migration | False  |
| VirtualCenter.AutoManagedIPV4 | Automatically discovered vCenter management IPv4 address |   |
| VirtualCenter.AutoManagedIPV6 | Automatically discovered vCenter management IPv6 address |   |
| VirtualCenter.DataCollector.ConsentData | Configuration of the Customer Experience Improvement Program | null  |
| VirtualCenter.DataCollector.Enabled | Deprecated. See: VirtualCenter.DataCollector.ConsentData | False  |
| VirtualCenter.DataCollector.Schedule | Customer experience improvement program data collection schedule |   |
| VirtualCenter.DBPassword | Database password |   |
| VirtualCenter.FQDN | vCenter FQDN | vcsa.williamlam.com  |
| VirtualCenter.HostBiosUuid | VirtualCenter Host Bios Uuid | 420e70b1-570c-bafe-7fa3-db35f7abe912  |
| VirtualCenter.InstanceName | Instance name | vcsa.williamlam.com  |
| VirtualCenter.ManagedIP | vCenter management IP address |   |
| VirtualCenter.MaxDBConnection | Maximum database connections | 50  |
| VirtualCenter.VimApiUrl | VIM API URL | vcsa.williamlam.com  |
| VirtualCenter.VimPasswordExpirationInDays | Password expiration | 30  |
| vpxd.cert.threshold | Certificate Management Threshold (in days) | 30  |
| vpxd.certmgmt.certs.cn.country | Country Name for the ESXi Host Certificates | US  |
| vpxd.certmgmt.certs.cn.email | Email address for the ESXi Host Certificates | vmca@vmware.com  |
| vpxd.certmgmt.certs.cn.localityName | Locality Name for ESXi Host Certificates | Palo Alto  |
| vpxd.certmgmt.certs.cn.organizationalUnitName | Organizational Unit Name for ESXi Host Certificates | VMware Engineering  |
| vpxd.certmgmt.certs.cn.organizationName | Organization Name for ESXi Host Certificates | VMware  |
| vpxd.certmgmt.certs.cn.state | State Name for ESXi Host Certificates | California  |
| vpxd.certmgmt.certs.daysValid | ESXi Certificate Validity Period (in days) | 1825  |
| vpxd.certmgmt.certs.hardThreshold | ESXi Certificate Management Hard Threshold (in days) | 30  |
| vpxd.certmgmt.certs.minutesBefore |  | 1440  |
| vpxd.certmgmt.certs.pollIntervalDays | ESXi Certificate Validity Check Interval (in days) | 5  |
| vpxd.certmgmt.certs.softThreshold | ESXi Certificate Management Soft Threshold (in days) | 240  |
| vpxd.certmgmt.mode | ESXi Certificate Management Mode | vmca  |
| vpxd.event.burstFilter.compressToDb | Enable burst filter on the database | True  |
| vpxd.event.burstFilter.compressToSyslog | Enable burst filter on the syslog stream | False  |
| vpxd.event.features.VC_Events_Retention |  | True  |
| vpxd.event.syslog.enabled | Enable syslog streaming | True  |
| vpxd.hostkey.newIfMissing | Generate a new host key if the host key is not available | True  |
| vpxd.httpClientIdleTimeout | Http Client Pool Idle Timeout | 900  |
| vpxd.kmscert.threshold | KMS Certificate Management Threshold (in days) | 30  |
| vpxd.license.data | License data | AQD+yggAAABvb2gYHSLj6EQAAACwCsrxHmp1MWSoIRD9Z37FVoCdbV6IHH9WoF8r9OVsTzgyj+gdMPfmFm8C0jf7yLlMcABOm4cHTRzLK7KHC4Hy1Luu8A==  |
| vpxd.license.ForceDownloadDLF | Force Download DLF | False  |
| vpxd.locale | Server locale |   |
| vpxd.motd | Global message |   |
| vpxd.npivWwnGeneration.portWwnNumber | Generation port WWN number | 4  |
| vpxd.npivWwnGeneration.singleNodeWwn | Generation single node WWN | True  |
| vpxd.usageStats.duration | Usage statistics duration | 1209600  |
| vpxd.usageStats.level | Usage statistics level | 0  |
| vpxd.usageStats.persist | Save usage statistics to the database | True  |
| vpxd.vdb.space.errorPercent | The used database space that triggers an error event | 95  |
| vpxd.vdb.space.warningPercent | The used database space that triggers a warning event | 80  |
| vpxd.vod.persist | Save usage statistics to a file | True  |
| vpxd.webscriptLauncher.enabled | Enable webscript launcher page | True  |
| vrdma.uuid |  | 52 dd d1 33 b3 ce 33 b1-da 69 cc 8b 2e 21 51 fd  |
| WebService.Ports.http | HTTP port number | 80  |
| WebService.Ports.https | HTTPS port number | 443  |
| wwn.instance.id | WWN instance | 0  |

