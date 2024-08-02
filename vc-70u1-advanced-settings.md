# vCenter Server 7.0 Update 1 Build 16860138 Advanced Settings

Total: 920

| Name | Description | Value |
|---|---|---|
| ads.checkInterval | User validation interval | 1440  |
| ads.checkIntervalEnabled | Enable user validation | True  |
| ads.maxFetch | Maximum users to retrieve | 5000  |
| ads.maxFetchEnabled | Enable user retrieve limits | True  |
| ads.timeout | User retrieve timeout | 60  |
| alarms.version | Default alarm upgrade version | -1  |
| alarms.versionEx | Default alarm extended version | 111.0.18  |
| client.timeout.long | Long operation client timeout | 120  |
| client.timeout.normal | Client timeout | 30  |
| client.VerifySSLCertificates | Verify SSL certificates | True  |
| config.alarms.vim.version |  | vim.version.v7_0_1_1  |
| config.drs.kvstore.local |  | False  |
| config.log.compressOnRoll |  | true  |
| config.log.level |  | info  |
| config.log.maxFileNum |  | 30  |
| config.log.maxFileSize |  | 52428800  |
| config.log.outputToConsole |  | false  |
| config.log.outputToFiles |  | true  |
| config.registry.DB.key_2 |  | vc  |
| config.registry.DB.key_3 |  | *i6IYS3iu6gL2UJSLgtDE5NijMq80JdaWt3QiZoTwt5sY6AwCqlP2MD95zUqFK2o0  |
| config.registry.key_EvaluationExpiryDate |  | AQD+yggAAACUD6VwO6F5aUQAAACQogM3VwNAH5FGdMkXmq2pEcaWKYzUQfk+uhMR27VMzNtNSbV7rP8Fym+Er6K9EwIophEWMohhnK21wPQfK/E7VR15Pg==  |
| config.task.minCompletedLifetime |  | 60  |
| config.vdt.severity | Verbosity level of distributed tracing | none  |
| config.vmacore.cacheProperties |  | true  |
| config.vmacore.ssl.fips |  | false  |
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
| config.vpxd.odbc.dsn |  | VMware VirtualCenter  |
| config.vpxd.rhttpproxy.httpport |  | 80  |
| config.vpxd.rhttpproxy.httpsport |  | 443  |
| config.vpxd.secureSoapPort |  | 8089  |
| config.vpxd.soapPort |  | 8085  |
| config.vpxd.ssl.CAPath |  | /etc/ssl/certs  |
| config.vpxd.sso.admin.uri |  | https://vcsa.williamlam.com/sso-adminserver/sdk/vsphere.local  |
| config.vpxd.sso.default.admin |  | Administrator@vsphere.local  |
| config.vpxd.sso.default.isGroup |  | false  |
| config.vpxd.sso.groupcheck.uri |  | https://vcsa.williamlam.com/sso-adminserver/sdk/vsphere.local  |
| config.vpxd.sso.solutionUser.certificate |  | /etc/vmware-vpx/ssl/vcsoluser.crt  |
| config.vpxd.sso.solutionUser.name |  | vpxd-0a73847a-2fc9-49d6-b088-4cce3062e55c@vsphere.local  |
| config.vpxd.sso.solutionUser.privateKey |  | /etc/vmware-vpx/ssl/vcsoluser.key  |
| config.vpxd.sso.sts.uri |  | https://vcsa.williamlam.com/sts/STSService/vsphere.local  |
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
| etc.issue | /etc/issue | VMware vCenter Server Appliance 7.0.1.00000  |
| etc.motd | /etc/motd |   |
| event.batchsize | Batch size in cleanup events procedure | 2000  |
| event.maxAge | Maximum event age | 30  |
| event.maxAgeEnabled | Enable event cleanup | True  |
| instance.id | Instance ID | 3  |
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
| logger.[SSO][SsoWrapper] |  | info  |
| logger.Alarm |  | info  |
| logger.alarmMo |  | info  |
| logger.AlarmXAction |  | info  |
| logger.App |  | info  |
| logger.AssetPropertiesUpdater |  | info  |
| logger.AssignHwHostInfo |  | info  |
| logger.AsyncVmomiInvoker |  | info  |
| logger.Attestation |  | info  |
| logger.Auth_win32 |  | info  |
| logger.Authorize |  | info  |
| logger.AuthorizeManager |  | info  |
| logger.Authz |  | info  |
| logger.AuthzStorageProvider |  | info  |
| logger.BackupRestore |  | info  |
| logger.bufferedClientRequest |  | info  |
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
| logger.ClusterHealthPerspectives |  | info  |
| logger.cnxmgrLogger |  | info  |
| logger.componentManagerUtil |  | info  |
| logger.ComputePolicyClient |  | info  |
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
| logger.CryptoManagerAWS |  | info  |
| logger.CryptoManagerGCP |  | info  |
| logger.CryptoManagerKmipWrapper |  | info  |
| logger.CryptUtil |  | info  |
| logger.CustomizationSpecsSvc |  | info  |
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
| logger.DeltaMigrationManager |  | info  |
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
| logger.EsxAgentManagerService |  | info  |
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
| logger.HostHealthPerspectives |  | info  |
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
| logger.maintReqLogger |  | info  |
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
| logger.MoEVCMgr |  | info  |
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
| logger.SOAP-100 |  | info  |
| logger.SOAP-101 |  | info  |
| logger.SOAP-102 |  | info  |
| logger.SOAP-103 |  | info  |
| logger.SOAP-104 |  | info  |
| logger.SOAP-105 |  | info  |
| logger.SOAP-106 |  | info  |
| logger.SOAP-107 |  | info  |
| logger.SOAP-108 |  | info  |
| logger.SOAP-109 |  | info  |
| logger.SOAP-11 |  | info  |
| logger.SOAP-110 |  | info  |
| logger.SOAP-111 |  | info  |
| logger.SOAP-112 |  | info  |
| logger.SOAP-113 |  | info  |
| logger.SOAP-114 |  | info  |
| logger.SOAP-115 |  | info  |
| logger.SOAP-116 |  | info  |
| logger.SOAP-117 |  | info  |
| logger.SOAP-118 |  | info  |
| logger.SOAP-119 |  | info  |
| logger.SOAP-12 |  | info  |
| logger.SOAP-120 |  | info  |
| logger.SOAP-121 |  | info  |
| logger.SOAP-122 |  | info  |
| logger.SOAP-123 |  | info  |
| logger.SOAP-124 |  | info  |
| logger.SOAP-125 |  | info  |
| logger.SOAP-126 |  | info  |
| logger.SOAP-127 |  | info  |
| logger.SOAP-128 |  | info  |
| logger.SOAP-129 |  | info  |
| logger.SOAP-13 |  | info  |
| logger.SOAP-130 |  | info  |
| logger.SOAP-131 |  | info  |
| logger.SOAP-132 |  | info  |
| logger.SOAP-133 |  | info  |
| logger.SOAP-134 |  | info  |
| logger.SOAP-135 |  | info  |
| logger.SOAP-136 |  | info  |
| logger.SOAP-137 |  | info  |
| logger.SOAP-138 |  | info  |
| logger.SOAP-139 |  | info  |
| logger.SOAP-14 |  | info  |
| logger.SOAP-140 |  | info  |
| logger.SOAP-141 |  | info  |
| logger.SOAP-142 |  | info  |
| logger.SOAP-143 |  | info  |
| logger.SOAP-144 |  | info  |
| logger.SOAP-145 |  | info  |
| logger.SOAP-146 |  | info  |
| logger.SOAP-147 |  | info  |
| logger.SOAP-148 |  | info  |
| logger.SOAP-149 |  | info  |
| logger.SOAP-15 |  | info  |
| logger.SOAP-150 |  | info  |
| logger.SOAP-151 |  | info  |
| logger.SOAP-152 |  | info  |
| logger.SOAP-153 |  | info  |
| logger.SOAP-154 |  | info  |
| logger.SOAP-155 |  | info  |
| logger.SOAP-156 |  | info  |
| logger.SOAP-157 |  | info  |
| logger.SOAP-158 |  | info  |
| logger.SOAP-159 |  | info  |
| logger.SOAP-16 |  | info  |
| logger.SOAP-160 |  | info  |
| logger.SOAP-161 |  | info  |
| logger.SOAP-162 |  | info  |
| logger.SOAP-163 |  | info  |
| logger.SOAP-164 |  | info  |
| logger.SOAP-165 |  | info  |
| logger.SOAP-166 |  | info  |
| logger.SOAP-167 |  | info  |
| logger.SOAP-168 |  | info  |
| logger.SOAP-169 |  | info  |
| logger.SOAP-17 |  | info  |
| logger.SOAP-170 |  | info  |
| logger.SOAP-171 |  | info  |
| logger.SOAP-172 |  | info  |
| logger.SOAP-173 |  | info  |
| logger.SOAP-174 |  | info  |
| logger.SOAP-175 |  | info  |
| logger.SOAP-176 |  | info  |
| logger.SOAP-177 |  | info  |
| logger.SOAP-178 |  | info  |
| logger.SOAP-179 |  | info  |
| logger.SOAP-18 |  | info  |
| logger.SOAP-180 |  | info  |
| logger.SOAP-181 |  | info  |
| logger.SOAP-182 |  | info  |
| logger.SOAP-183 |  | info  |
| logger.SOAP-184 |  | info  |
| logger.SOAP-185 |  | info  |
| logger.SOAP-186 |  | info  |
| logger.SOAP-187 |  | info  |
| logger.SOAP-188 |  | info  |
| logger.SOAP-189 |  | info  |
| logger.SOAP-19 |  | info  |
| logger.SOAP-190 |  | info  |
| logger.SOAP-191 |  | info  |
| logger.SOAP-192 |  | info  |
| logger.SOAP-193 |  | info  |
| logger.SOAP-194 |  | info  |
| logger.SOAP-195 |  | info  |
| logger.SOAP-196 |  | info  |
| logger.SOAP-197 |  | info  |
| logger.SOAP-198 |  | info  |
| logger.SOAP-199 |  | info  |
| logger.SOAP-2 |  | info  |
| logger.SOAP-20 |  | info  |
| logger.SOAP-200 |  | info  |
| logger.SOAP-201 |  | info  |
| logger.SOAP-202 |  | info  |
| logger.SOAP-203 |  | info  |
| logger.SOAP-204 |  | info  |
| logger.SOAP-205 |  | info  |
| logger.SOAP-206 |  | info  |
| logger.SOAP-207 |  | info  |
| logger.SOAP-208 |  | info  |
| logger.SOAP-209 |  | info  |
| logger.SOAP-21 |  | info  |
| logger.SOAP-210 |  | info  |
| logger.SOAP-211 |  | info  |
| logger.SOAP-212 |  | info  |
| logger.SOAP-213 |  | info  |
| logger.SOAP-214 |  | info  |
| logger.SOAP-215 |  | info  |
| logger.SOAP-216 |  | info  |
| logger.SOAP-217 |  | info  |
| logger.SOAP-218 |  | info  |
| logger.SOAP-219 |  | info  |
| logger.SOAP-22 |  | info  |
| logger.SOAP-220 |  | info  |
| logger.SOAP-221 |  | info  |
| logger.SOAP-222 |  | info  |
| logger.SOAP-223 |  | info  |
| logger.SOAP-224 |  | info  |
| logger.SOAP-225 |  | info  |
| logger.SOAP-226 |  | info  |
| logger.SOAP-227 |  | info  |
| logger.SOAP-228 |  | info  |
| logger.SOAP-229 |  | info  |
| logger.SOAP-23 |  | info  |
| logger.SOAP-230 |  | info  |
| logger.SOAP-231 |  | info  |
| logger.SOAP-232 |  | info  |
| logger.SOAP-233 |  | info  |
| logger.SOAP-234 |  | info  |
| logger.SOAP-235 |  | info  |
| logger.SOAP-236 |  | info  |
| logger.SOAP-237 |  | info  |
| logger.SOAP-238 |  | info  |
| logger.SOAP-239 |  | info  |
| logger.SOAP-24 |  | info  |
| logger.SOAP-240 |  | info  |
| logger.SOAP-241 |  | info  |
| logger.SOAP-242 |  | info  |
| logger.SOAP-243 |  | info  |
| logger.SOAP-244 |  | info  |
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
| logger.SOAP-71 |  | info  |
| logger.SOAP-72 |  | info  |
| logger.SOAP-73 |  | info  |
| logger.SOAP-74 |  | info  |
| logger.SOAP-75 |  | info  |
| logger.SOAP-76 |  | info  |
| logger.SOAP-77 |  | info  |
| logger.SOAP-78 |  | info  |
| logger.SOAP-79 |  | info  |
| logger.SOAP-8 |  | info  |
| logger.SOAP-80 |  | info  |
| logger.SOAP-81 |  | info  |
| logger.SOAP-82 |  | info  |
| logger.SOAP-83 |  | info  |
| logger.SOAP-84 |  | info  |
| logger.SOAP-85 |  | info  |
| logger.SOAP-86 |  | info  |
| logger.SOAP-87 |  | info  |
| logger.SOAP-88 |  | info  |
| logger.SOAP-89 |  | info  |
| logger.SOAP-9 |  | info  |
| logger.SOAP-90 |  | info  |
| logger.SOAP-91 |  | info  |
| logger.SOAP-92 |  | info  |
| logger.SOAP-93 |  | info  |
| logger.SOAP-94 |  | info  |
| logger.SOAP-95 |  | info  |
| logger.SOAP-96 |  | info  |
| logger.SOAP-97 |  | info  |
| logger.SOAP-98 |  | info  |
| logger.SOAP-99 |  | info  |
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
| logger.StorageQueryManager |  | info  |
| logger.stressOption |  | info  |
| logger.SupportMgr |  | info  |
| logger.svcUtils |  | info  |
| logger.sysCommandAdapter |  | info  |
| logger.Tagging |  | info  |
| logger.tagMgr |  | info  |
| logger.Task |  | info  |
| logger.TaskInfo |  | info  |
| logger.TechPreviewManager |  | info  |
| logger.telemetry-stage.vcenter-all.vpxd.drs.7_0u1.instance.ph-vpxd-6669931c-9351-4bf5-9baf-0e76f69693de |  | info  |
| logger.telemetry.vcenter-all.vpxd.drs.7_0u1.instance.ph-vpxd-6669931c-9351-4bf5-9baf-0e76f69693de |  | info  |
| logger.telemetry.vcs.api.vmodl1.7_0.instance.ph-vpxd-6669931c-9351-4bf5-9baf-0e76f69693de |  | info  |
| logger.TenantManager |  | info  |
| logger.ThreadPool |  | info  |
| logger.TopnMetadata |  | info  |
| logger.Translator |  | info  |
| logger.TrustedInfrastructure.HostConfig |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Attestation.Os.Esx.BaseImages |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Attestation.ServiceStatus |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Attestation.Tpm.CaCertificates |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Attestation.Tpm.EndorsementKeys |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Attestation.Tpm.Settings |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.ConsumerPrincipals |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.Providers |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.Providers.ClientCertificates |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.Providers.Credential |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.Providers.CurrentPeerCertificates |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.Providers.TrustedPeerCertificates |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.ProvidersClientCertificates.Csr |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityClusters.Kms.ServiceStatus |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityVc.Attestation |  | info  |
| logger.TrustedInfrastructure.TrustAuthorityVc.Kms |  | info  |
| logger.TrustedInfrastructure.VapiLocalizer |  | info  |
| logger.TrustedInfrastructure.WorkloadClusters.Attestation.Services |  | info  |
| logger.TrustedInfrastructure.WorkloadClusters.Attestation.ServicesAppliedConfig |  | info  |
| logger.TrustedInfrastructure.WorkloadClusters.Kms.Services |  | info  |
| logger.TrustedInfrastructure.WorkloadClusters.Kms.ServicesAppliedConfig |  | info  |
| logger.TrustedInfrastructure.WorkloadClusters.ServicesAppliedConfig |  | info  |
| logger.TrustedInfrastructure.WorkloadVc.Attestation.Services |  | info  |
| logger.TrustedInfrastructure.WorkloadVc.Kms.Services |  | info  |
| logger.TxnMgr |  | info  |
| logger.Url_win32 |  | info  |
| logger.User |  | info  |
| logger.UtilEx |  | info  |
| logger.VapiAuthzFilter |  | info  |
| logger.VapiEndpoint |  | info  |
| logger.VapiEndpoint.HTTPService |  | info  |
| logger.VapiEndpoint.HTTPService.HttpConnection |  | info  |
| logger.VapiLocalizer |  | info  |
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
| logger.VCDlfDownloader |  | info  |
| logger.VchaServiceClientAdapter |  | info  |
| logger.VcQueryService |  | info  |
| logger.VdbOpJournal |  | info  |
| logger.ViewManager |  | info  |
| logger.VimVapiSamlHokHandler |  | info  |
| logger.VimVapiSessionHandler |  | info  |
| logger.VimVapiSessionLeaseFilter |  | info  |
| logger.VimVapiSessionSvc |  | info  |
| logger.VimVapiUserPassHandler |  | info  |
| logger.virtualDiskMgr |  | info  |
| logger.Vmacore::Xml::Security |  | info  |
| logger.VmCheck |  | info  |
| logger.vmconfig |  | info  |
| logger.VmCustomizationSvc |  | info  |
| logger.VmCustomizer |  | info  |
| logger.vmft |  | info  |
| logger.vmguest |  | info  |
| logger.vmMonitor |  | info  |
| logger.vmmoVm |  | info  |
| logger.Vmomi |  | info  |
| logger.VMOMI |  | info  |
| logger.VMOMI-FSS |  | info  |
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
| logger.Vmprov |  | info  |
| logger.VmProv |  | info  |
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
| logger.VpxaServices |  | info  |
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
| logger.VpxdHostConnection |  | info  |
| logger.vpxdUtil |  | info  |
| logger.VpxdVapiTasksSvc |  | info  |
| logger.vpxdVdb |  | info  |
| logger.VpxdVlf |  | info  |
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
| logger.VslmService |  | info  |
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
| logger.WorkQueue.vpxd.authorization |  | info  |
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
| VirtualCenter.HostBiosUuid | VirtualCenter Host Bios Uuid | 420e5f99-6cc2-a340-ab5b-b75bcaed57d6  |
| VirtualCenter.InstanceName | Instance name | vcsa.williamlam.com  |
| VirtualCenter.ManagedIP | vCenter management IP address |   |
| VirtualCenter.MaxDBConnection | Maximum database connections | 50  |
| VirtualCenter.VimApiUrl | VIM API URL | https://vcsa.williamlam.com:443/sdk  |
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
| vpxd.cluster.roboMMEnabled | Enable DRS MM evacuations with appropriate ROBO license | True  |
| vpxd.event.burstFilter.compressToDb | Enable burst filter on the database | True  |
| vpxd.event.burstFilter.compressToSyslog | Enable burst filter on the syslog stream | False  |
| vpxd.event.syslog.enabled | Enable syslog streaming | True  |
| vpxd.hostkey.newIfMissing | Generate a new host key if the host key is not available | True  |
| vpxd.httpClientIdleTimeout | Http Client Pool Idle Timeout | 900  |
| vpxd.KMS.compatCheckInterval | KMS compatibility cache update interval (in minutes) | 5  |
| vpxd.KMS.status | KMS status check interval (in minutes) | 5  |
| vpxd.kmscert.threshold | KMS Certificate Management Threshold (in days) | 30  |
| vpxd.license.data | License data | AQD+yggAAACUD6VwO6F5aUQAAACQogM3VwNAH5FGdMkXmq2pEcaWKYzUQfk+uhMR27VMzNtNSbV7rP8Fym+Er6K9EwIophEWMohhnK21wPQfK/E7VR15Pg==  |
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
| vrdma.uuid |  | 52 e1 47 ba 1e 1d 0f f0-47 c1 df 41 6b c2 46 95  |
| WebService.Ports.http | HTTP port number | 80  |
| WebService.Ports.https | HTTPS port number | 443  |
| wwn.instance.id | WWN instance | 0  |

