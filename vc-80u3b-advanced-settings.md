# vCenter Server 8.0 Update 3b Build 24262322 Advanced Settings

Total: 894

| Name | Description | Value |
|---|---|---|
| ads.maxFetch | Maximum users to retrieve | 5000  |
| ads.maxFetchEnabled | Enable user retrieve limits | True  |
| ads.timeout | User retrieve timeout | 60  |
| alarms.version | Default alarm upgrade version | -1  |
| alarms.versionEx | Default alarm extended version | 111.0.60  |
| client.timeout.long | Long operation client timeout | 120  |
| client.timeout.normal | Client timeout | 30  |
| client.VerifySSLCertificates | Verify SSL certificates | True  |
| config.alarms.vim.version |  | vim.version.v8_0_3_0  |
| config.drs.kvstore.local |  | False  |
| config.license.client.lsNotificationsSyncSeconds |  | 30  |
| config.license.client.oldServerLsNotificationsSyncSeconds |  | 600  |
| config.log.compressOnRoll |  | true  |
| config.log.level |  | info  |
| config.log.maxFileNum |  | 30  |
| config.log.maxFileSize |  | 52428800  |
| config.log.outputToConsole |  | false  |
| config.log.outputToFiles |  | true  |
| config.registry.key_EvaluationExpiryDate |  | AQD+yggAAADSz4WGxjtU4UQAAAARZRfw8Q1vSMQHdZF1f/GHYqx5mTeouuBHz0vl6Z4B/VaZv0La0eMcB7sTK0ajTqeCpFfPlrNPy0jX+1DrsTxgCf1/YA==  |
| config.task.minCompletedLifetime |  | 60  |
| config.vdt.severity | Verbosity level of distributed tracing | info  |
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
| config.vpxd.hgw.UseHttp2 | Enable HTTP/2 for ESXi connections | false  |
| config.vpxd.hostGateway.enabled |  | true  |
| config.vpxd.hostGateway.gatewaySource |  | ComponentManager  |
| config.vpxd.hostnameUrl |  | w4-pcld-245-151.eng.vmware.com  |
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
| config.vpxd.sso.admin.uri |  | https://w4-pcld-245-151.eng.vmware.com/sso-adminserver/sdk/vsphere.local  |
| config.vpxd.sso.default.admin |  | Administrator@vsphere.local  |
| config.vpxd.sso.default.isGroup |  | false  |
| config.vpxd.sso.groupcheck.uri |  | https://w4-pcld-245-151.eng.vmware.com/sso-adminserver/sdk/vsphere.local  |
| config.vpxd.sso.solutionUser.certificate |  | /etc/vmware-vpx/ssl/vcsoluser.crt  |
| config.vpxd.sso.solutionUser.name |  | vpxd-8f372b9c-3487-473d-82e6-c1f96dfe84ad@vsphere.local  |
| config.vpxd.sso.solutionUser.privateKey |  | /etc/vmware-vpx/ssl/vcsoluser.key  |
| config.vpxd.sso.sts.uri |  | https://w4-pcld-245-151.eng.vmware.com/sts/STSService/vsphere.local  |
| config.vpxd.support.scriptDirectory |  | /usr/lib/vmware-vpx  |
| config.vpxd.vcha.drsAntiAffinity |  | true  |
| config.vpxd.vecs.storeName |  | vpxd  |
| config.vpxd.vsan.dynmgr.enable |  | true  |
| config.vpxd.vsan.hostaffinity.enable |  | false  |
| config.vpxd.vsan.witness.vlcm.supported.vendors.models |  | Amazon EC2<!>Amazon EC2 m5.xlarge<<!>>  |
| config.vpxd.vsan.xvc.stretchedcluster.enable |  | false  |
| config.workflow.port |  | WORKFLOW_PORT  |
| DBProc.Log.Buffer | DB procedures log buffer | 5000  |
| DBProc.Log.Debug.Info |  | ON  |
| DBProc.Log.Event.Purge |  | 10  |
| DBProc.Log.Stats.Purge |  | 10  |
| DBProc.Log.Topn.Purge |  | 5000  |
| etc.issue | /etc/issue | VMware vCenter Server Appliance 8.0.3.00200  |
| etc.motd | /etc/motd |   |
| event.batchsize | Batch size in cleanup events procedure | 2000  |
| event.maxAge | Maximum event age | 30  |
| event.maxAgeEnabled | Enable event cleanup | True  |
| instance.id | Instance ID | 62  |
| LicenseServer.matchHostToVirtualCenter | Match host license server to vCenter | True  |
| log.level | Logging level | info  |
| logger.[SSO][DomainIdNormalizer] |  | info  |
| logger.ActivationToSoapProxy |  | info  |
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
| logger.AuthTokenFactory |  | info  |
| logger.Authz |  | info  |
| logger.AuthzStorageProvider |  | info  |
| logger.BackupRestore |  | info  |
| logger.bufferedClientRequest |  | info  |
| logger.CatalogSyncManager |  | info  |
| logger.cdrsPlmt |  | info  |
| logger.certmgrLogger |  | info  |
| logger.certRequestHandler |  | info  |
| logger.CertsCache |  | info  |
| logger.certUtils |  | info  |
| logger.changeTag |  | info  |
| logger.checkswapPlacementInfo |  | info  |
| logger.ClientAdapterBase |  | info  |
| logger.ClientPreload |  | info  |
| logger.ClientUpgrader |  | info  |
| logger.clusterCache |  | info  |
| logger.clusterChecker |  | info  |
| logger.ClusterHealthPerspectives |  | info  |
| logger.clustersvcLogger |  | info  |
| logger.clusterWorkflowMgr |  | info  |
| logger.cnxmgrLogger |  | info  |
| logger.componentManagerUtil |  | info  |
| logger.ComputeResEventMgr |  | info  |
| logger.ComputeResLock |  | info  |
| logger.ConfigIssue |  | info  |
| logger.ConfigOptionDescsSvc |  | info  |
| logger.ConfigOptionsSvc |  | info  |
| logger.ConfigTargetsSvc |  | info  |
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
| logger.Default.StatsRegistry(00007f5dd40c5ef0) |  | info  |
| logger.DeltaMigrationManager |  | info  |
| logger.doImpersonate |  | info  |
| logger.drmLogger |  | info  |
| logger.drsExec |  | info  |
| logger.DvpgSender |  | info  |
| logger.DvsCore |  | info  |
| logger.DvsHostMethodDispatcher |  | info  |
| logger.dvsKeeper |  | info  |
| logger.DvsLock |  | info  |
| logger.DvsStateRecovery |  | info  |
| logger.DvsUtils |  | info  |
| logger.dynamicMethodValidator |  | info  |
| logger.edrsStatsProvider(00007f5dc83dba40) |  | info  |
| logger.emmStatsProvider(00007f5dc83eb540) |  | info  |
| logger.Entropyd |  | info  |
| logger.EnvBrowserApiResolver |  | info  |
| logger.EnvoyHostGateway |  | info  |
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
| logger.firewallrulesets |  | info  |
| logger.FirewallRulesets |  | info  |
| logger.foldersvcLogger |  | info  |
| logger.ftUtils |  | info  |
| logger.GuestName |  | info  |
| logger.guestops |  | info  |
| logger.halhost |  | info  |
| logger.Handle checker |  | info  |
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
| logger.HTTP |  | info  |
| logger.HTTP server |  | info  |
| logger.HTTP server /folder |  | info  |
| logger.HTTP session map |  | info  |
| logger.HTTP.HTTPService |  | info  |
| logger.HTTP.HTTPService.HttpConnection |  | info  |
| logger.Http2ClientSession-3 |  | info  |
| logger.Http2ServerSession-1 |  | info  |
| logger.Http2ServerSession-2 |  | info  |
| logger.Http2ServerSession-3 |  | info  |
| logger.Http2ServerSession-4 |  | info  |
| logger.HttpConnectionPool-000000 |  | info  |
| logger.HttpConnectionPool-000001 |  | info  |
| logger.HttpNfcBridgeHandler |  | info  |
| logger.HttpNfcTicket |  | info  |
| logger.HTTPS |  | info  |
| logger.HTTPS.HTTPService |  | info  |
| logger.HTTPS.HTTPService.HttpConnection |  | info  |
| logger.HttpsTransactionFactory |  | info  |
| logger.HttpSvc |  | info  |
| logger.HttpSvc.HTTPService |  | info  |
| logger.HttpSvc.HTTPService.HttpConnection |  | info  |
| logger.httpUtil |  | info  |
| logger.infraUpdateHa |  | info  |
| logger.InternalSvc |  | info  |
| logger.InternalVapiRequestHandler |  | info  |
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
| logger.IO.Connection |  | info  |
| logger.IO.Http |  | info  |
| logger.Iofilter |  | info  |
| logger.IpAllocator |  | info  |
| logger.ipfix |  | info  |
| logger.journal |  | info  |
| logger.journalIO |  | quiet  |
| logger.KeyProvider |  | info  |
| logger.lacp |  | info  |
| logger.License:Util:TaskScheduler:LicenseServiceClientCachedImpl:SyncTask |  | info  |
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
| logger.LocalVapiAuthzFilter |  | info  |
| logger.LocalVapiSamlHokHandler |  | info  |
| logger.LocalVapiSessionHandler |  | info  |
| logger.LocalVapiSessionLeaseFilter |  | info  |
| logger.Lock |  | info  |
| logger.LogBundler |  | info  |
| logger.LSClient |  | info  |
| logger.LsNotificationsRetriever |  | info  |
| logger.lunUtil |  | info  |
| logger.Mail_win32 |  | info  |
| logger.Main |  | info  |
| logger.maintReqLogger |  | info  |
| logger.Memory checker |  | info  |
| logger.MemoryAlertPublisher |  | info  |
| logger.mergeOp |  | info  |
| logger.MethodValidator |  | info  |
| logger.MoA8sCluster |  | info  |
| logger.MoA8sHost |  | info  |
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
| logger.networksvcLogger |  | info  |
| logger.NfcLib |  | info  |
| logger.NfcMgr |  | info  |
| logger.NfcServiceProxy |  | info  |
| logger.NfcTicketsHelper |  | info  |
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
| logger.phonehomesvcLogger |  | info  |
| logger.PortSender |  | info  |
| logger.PriorityInfo.16 |  | info  |
| logger.PriorityInfo.4 |  | info  |
| logger.PriorityInfo.8 |  | info  |
| logger.PrivilegeCheck |  | info  |
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
| logger.Req@ehp/1.0 |  | info  |
| logger.Req@ehp/7.0.0.0 |  | info  |
| logger.Req@ehp/7.0.2.0 |  | info  |
| logger.Req@infra/1.0 |  | info  |
| logger.Req@internalehp/1.0 |  | info  |
| logger.Req@internalehp/7... |  | info  |
| logger.Req@internalinfra... |  | info  |
| logger.Req@internalnfc/1.0 |  | info  |
| logger.Req@internalnfc/2.0 |  | info  |
| logger.Req@internalnfc/3.0 |  | info  |
| logger.Req@internalnfc/6... |  | info  |
| logger.Req@internalnfc/6.0 |  | info  |
| logger.Req@internalnfc/6.5 |  | info  |
| logger.Req@internalnfc/6.7 |  | info  |
| logger.Req@internalnfc/7... |  | info  |
| logger.Req@internalvcint... |  | info  |
| logger.Req@internalvim25... |  | info  |
| logger.Req@internalvpxd3... |  | info  |
| logger.Req@internalvsan/... |  | info  |
| logger.Req@internalvsan/6.6 |  | info  |
| logger.Req@internalvsan/6.7 |  | info  |
| logger.Req@internalvsan/7.0 |  | info  |
| logger.Req@internalvsan/7.1 |  | info  |
| logger.Req@internalvsan/7.2 |  | info  |
| logger.Req@internalvsan/7.3 |  | info  |
| logger.Req@internalvsan/7.4 |  | info  |
| logger.Req@nfc/1.0 |  | info  |
| logger.Req@nfc/2.0 |  | info  |
| logger.Req@nfc/3.0 |  | info  |
| logger.Req@nfc/6.0 |  | info  |
| logger.Req@nfc/6.5 |  | info  |
| logger.Req@nfc/6.7 |  | info  |
| logger.Req@nfc/6.7.1 |  | info  |
| logger.Req@nfc/6.7.2 |  | info  |
| logger.Req@nfc/7.0.0.0 |  | info  |
| logger.Req@nfc/7.0.1.0 |  | info  |
| logger.Req@nfc/7.0.2.1 |  | info  |
| logger.Req@nfc/7.0.3.0 |  | info  |
| logger.Req@nfc/7.0.3.2 |  | info  |
| logger.Req@vcint/7.0.2.0 |  | info  |
| logger.Req@vcint/7.0.2.1 |  | info  |
| logger.Req@vcint/7.0.3.0 |  | info  |
| logger.Req@vcint/7.0.3.1 |  | info  |
| logger.Req@vcint/7.0.3.2 |  | info  |
| logger.Req@vcint/8.0.0.0 |  | info  |
| logger.Req@vcint/8.0.0.1 |  | info  |
| logger.Req@vcint/8.0.0.2 |  | info  |
| logger.Req@vcint/8.0.1.0 |  | info  |
| logger.Req@vcint/8.0.2.0 |  | info  |
| logger.Req@vcint/8.0.3.0 |  | info  |
| logger.Req@vim25/2.5u2 |  | info  |
| logger.Req@vim25/4.0 |  | info  |
| logger.Req@vim25/4.1 |  | info  |
| logger.Req@vim25/5.0 |  | info  |
| logger.Req@vim25/5.1 |  | info  |
| logger.Req@vim25/5.5 |  | info  |
| logger.Req@vim25/6.0 |  | info  |
| logger.Req@vim25/6.5 |  | info  |
| logger.Req@vim25/6.7 |  | info  |
| logger.Req@vim25/6.7.1 |  | info  |
| logger.Req@vim25/6.7.2 |  | info  |
| logger.Req@vim25/6.7.3 |  | info  |
| logger.Req@vim25/6.8.7 |  | info  |
| logger.Req@vim25/6.9.1 |  | info  |
| logger.Req@vim25/7.0.0.0 |  | info  |
| logger.Req@vim25/7.0.0.2 |  | info  |
| logger.Req@vim25/7.0.1.0 |  | info  |
| logger.Req@vim25/7.0.1.1 |  | info  |
| logger.Req@vim25/7.0.2.0 |  | info  |
| logger.Req@vim25/7.0.2.1 |  | info  |
| logger.Req@vim25/7.0.3.0 |  | info  |
| logger.Req@vim25/7.0.3.1 |  | info  |
| logger.Req@vim25/7.0.3.2 |  | info  |
| logger.Req@vim25/8.0.0.0 |  | info  |
| logger.Req@vim25/8.0.0.1 |  | info  |
| logger.Req@vim25/8.0.0.2 |  | info  |
| logger.Req@vim25/8.0.1.0 |  | info  |
| logger.Req@vim25/8.0.2.0 |  | info  |
| logger.Req@vim25/8.0.3.0 |  | info  |
| logger.Req@vpxd3/1.0 |  | info  |
| logger.Req@vpxd3/2.0 |  | info  |
| logger.Req@vpxd3/3.0 |  | info  |
| logger.Req@vpxd3/4.0 |  | info  |
| logger.Req@vpxd3/5.5 |  | info  |
| logger.Req@vpxd3/6.0 |  | info  |
| logger.Req@vpxd3/6.5 |  | info  |
| logger.Req@vpxd3/6.7 |  | info  |
| logger.Req@vpxd3/6.7.1 |  | info  |
| logger.Req@vpxd3/6.7.2 |  | info  |
| logger.Req@vpxd3/6.8.7 |  | info  |
| logger.Req@vpxd3/6.9.1 |  | info  |
| logger.Req@vpxd3/7.0.0.0 |  | info  |
| logger.Req@vpxd3/7.0.0.2 |  | info  |
| logger.Req@vpxd3/7.0.1.0 |  | info  |
| logger.Req@vpxd3/7.0.1.1 |  | info  |
| logger.Req@vpxd3/7.0.2.0 |  | info  |
| logger.Req@vpxd3/7.0.2.1 |  | info  |
| logger.Req@vpxd3/7.0.3.0 |  | info  |
| logger.Req@vpxd3/7.0.3.1 |  | info  |
| logger.Req@vpxd3/7.0.3.2 |  | info  |
| logger.Req@vpxd3/8.0.0.0 |  | info  |
| logger.Req@vpxd3/8.0.0.1 |  | info  |
| logger.Req@vpxd3/8.0.0.2 |  | info  |
| logger.Req@vpxd3/8.0.1.0 |  | info  |
| logger.Req@vpxd3/8.0.2.0 |  | info  |
| logger.Req@vpxd3/8.0.3.0 |  | info  |
| logger.Req@vsan/6.6 |  | info  |
| logger.Req@vsan/6.6.1 |  | info  |
| logger.Req@vsan/6.6.2 |  | info  |
| logger.Req@vsan/6.7 |  | info  |
| logger.Req@vsan/6.7.0 |  | info  |
| logger.Req@vsan/6.8.7 |  | info  |
| logger.Req@vsan/7.0 |  | info  |
| logger.Req@vsan/7.1 |  | info  |
| logger.Req@vsan/7.2 |  | info  |
| logger.Req@vsan/7.3 |  | info  |
| logger.Req@vsan/7.4 |  | info  |
| logger.Req@vsan/8.0.0.1 |  | info  |
| logger.Req@vsan/8.0.0.2 |  | info  |
| logger.Req@vsan/8.0.0.3 |  | info  |
| logger.Req@vsan/8.0.0.4 |  | info  |
| logger.Req@vsan/dev.version |  | info  |
| logger.Req@vsan/reserved |  | info  |
| logger.Req@vsan/VMC M5 |  | info  |
| logger.Req@vsan/vSAN 6.7U1 |  | info  |
| logger.Req@vsan/vSAN 6.7U3 |  | info  |
| logger.Req@vsan/vSAN 7.0U1 |  | info  |
| logger.Req@vsan/vSAN 7.0U2 |  | info  |
| logger.Req@vsan/vSAN 7.0U3 |  | info  |
| logger.ResMgr |  | info  |
| logger.ResourceMgr |  | info  |
| logger.ResourcePlanningMgr |  | info  |
| logger.ResPoolTree |  | info  |
| logger.ScheduledTimer |  | info  |
| logger.sdrsLogger |  | info  |
| logger.secondaryVmCreator |  | info  |
| logger.Service |  | info  |
| logger.ServiceAccount |  | info  |
| logger.ServiceMgrImpl |  | info  |
| logger.session pool |  | info  |
| logger.SessionCounter |  | info  |
| logger.SessionPropertiesFilter |  | info  |
| logger.sessionsSvcLogger |  | info  |
| logger.SgxHostRegistration.Impl |  | info  |
| logger.SimpleCommandImpl |  | info  |
| logger.sms |  | info  |
| logger.Snmp |  | info  |
| logger.SOAP |  | info  |
| logger.ssoCertificate |  | info  |
| logger.SsoClient |  | info  |
| logger.SsoWrapper |  | info  |
| logger.SsoWrapper.AdminAdapter |  | info  |
| logger.SsoWrapper.DomainIdNormalizer |  | info  |
| logger.SsoWrapper.DomainMappingsSvc |  | info  |
| logger.SsoWrapper.GroupcheckAdapter |  | info  |
| logger.SsoWrapper.LookupService |  | info  |
| logger.SsoWrapper.SamlTokenFactory |  | info  |
| logger.SsoWrapper.SsoAdminFacade |  | info  |
| logger.SsoWrapper.SsoCertificateManager |  | info  |
| logger.SSPI |  | info  |
| logger.StateLock |  | info  |
| logger.Stats |  | info  |
| logger.StatsAggregator |  | info  |
| logger.StatsCollector |  | info  |
| logger.StatsFilter |  | info  |
| logger.StatsMetadata |  | info  |
| logger.StatsRegistry |  | info  |
| logger.StatsRegistry.Cooked.Counters |  | info  |
| logger.StatsRegistry.QueriesSvc |  | info  |
| logger.StorageQueryManager |  | info  |
| logger.stressOption |  | info  |
| logger.SupportMgr |  | info  |
| logger.svcUtils |  | info  |
| logger.sysCommandAdapter |  | info  |
| logger.SystemStatsProvider(00007f5dc83eb290) |  | info  |
| logger.systemSvcLogger |  | info  |
| logger.Tagging |  | info  |
| logger.tagMgr |  | info  |
| logger.Task |  | info  |
| logger.TaskInfo |  | info  |
| logger.TechPreviewManager |  | info  |
| logger.telemetry-stage.hashmode-v1.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry-stage.vcenter-all.vpxd.drs.7_0u1.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry-stage.vcenter-all.vpxd.hdcs.7_0u2.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry-stage.vcenter-all.vpxd.vclscrx.8_0u3.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry-stage.vpxd.perfmanager.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry-stage.vSphere.vpxd.switchOps.provisioning.7.0.1.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.datasets-vapi.v1.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.guest_os_cust.7_0_1.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.srm.vlr.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vcenter-all.vpxd.drs.7_0u1.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vcenter-all.vpxd.hdcs.7_0u2.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vcenter-all.vpxd.vclscrx.8_0u3.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vcs.api.vmodl1.7_0.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.VDDK.8_0_2.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vpxd.perfmanager.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vSphere.vpxd.monterey.phase1-0.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vSphere.vpxd.monterey.vds.phase1-0.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vSphere.vpxd.nfcSov.8.0.0.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.telemetry.vtpm_8.0.instance.ph-vpxd-b772a303-b43a-45d1-89e7-669f62fd47dd |  | info  |
| logger.TenantManager |  | info  |
| logger.ThreadPool |  | info  |
| logger.TopnMetadata |  | info  |
| logger.transcoder |  | info  |
| logger.Translator |  | info  |
| logger.TrustedInfrastructure.HostConfig |  | info  |
| logger.TrustedInfrastructure.Hosts.Hardware.Tpm.Eventlog |  | info  |
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
| logger.TrustedInfraTpm |  | info  |
| logger.TrustedInfraTpmEk |  | info  |
| logger.TxnMgr |  | info  |
| logger.Url_win32 |  | info  |
| logger.User |  | info  |
| logger.UserCache |  | info  |
| logger.UserDirectorySso |  | info  |
| logger.UtilEx |  | info  |
| logger.VapiAuthzFilter |  | info  |
| logger.VapiClientWrappers |  | info  |
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
| logger.VchaServiceClientAdapter |  | info  |
| logger.VcQueryService |  | info  |
| logger.VdbOpJournal |  | info  |
| logger.ViewManager |  | info  |
| logger.ViJsonAdapter |  | info  |
| logger.ViJsonEndpoint |  | info  |
| logger.ViJsonToSoapProxy |  | info  |
| logger.Vimsvc.VcCgiServiceManager |  | info  |
| logger.VimVapiOpIdExtractFilter |  | info  |
| logger.VimVapiSamlBearerHandler |  | info  |
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
| logger.VmDataSetsSvc |  | info  |
| logger.vmft |  | info  |
| logger.vmguest |  | info  |
| logger.VmLogLevelSvc |  | info  |
| logger.vmMonitor |  | info  |
| logger.vmmoVm |  | info  |
| logger.VMOMI |  | info  |
| logger.Vmomi |  | info  |
| logger.VMOMI-FSS |  | info  |
| logger.vmomi.soapStub[0] |  | info  |
| logger.vmomi.soapStub[1] |  | info  |
| logger.vmomi.soapStub[10] |  | info  |
| logger.vmomi.soapStub[11] |  | info  |
| logger.vmomi.soapStub[12] |  | info  |
| logger.vmomi.soapStub[14] |  | info  |
| logger.vmomi.soapStub[15] |  | info  |
| logger.vmomi.soapStub[3] |  | info  |
| logger.vmomi.soapStub[4] |  | info  |
| logger.vmomi.soapStub[41] |  | info  |
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
| logger.Vpxd.FdChecker |  | info  |
| logger.Vpxd.MemChecker |  | info  |
| logger.vpxDas |  | info  |
| logger.vpxdCgiServiceManager |  | info  |
| logger.VpxdHostConnection |  | info  |
| logger.VpxdHttpExportKpHandler |  | info  |
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
| logger.VsanVcMgmtCnx |  | info  |
| logger.VslmService |  | info  |
| logger.vspan |  | info  |
| logger.vTContainerMappingsImpl |  | info  |
| logger.vTContainersImpl |  | info  |
| logger.VTpmManager |  | info  |
| logger.vumOp |  | info  |
| logger.VvolInfoMgr |  | info  |
| logger.VvolVasaMgr |  | info  |
| logger.Webserver |  | info  |
| logger.workloadStatsProvider(00007f5dc83dbde0) |  | info  |
| logger.WorkQueue.authz.cache.persister.queue |  | info  |
| logger.WorkQueue.HostProfile |  | info  |
| logger.WorkQueue.vmacoreDefaultIOCompletionQueue |  | info  |
| logger.WorkQueue.vmacoreDefaultIOQueue |  | info  |
| logger.WorkQueue.vmacoreDefaultLongTaskQueue |  | info  |
| logger.WorkQueue.Vpxd.alarms.notification.queue |  | info  |
| logger.WorkQueue.Vpxd.alarms.persister.queue |  | info  |
| logger.WorkQueue.vpxd.authorization |  | info  |
| logger.WorkQueue.vpxd.cluster.deplmode.queue |  | info  |
| logger.WorkQueue.Vpxd.disabledMethods.queue |  | info  |
| logger.WorkQueue.vpxd.event.persister.queue |  | info  |
| logger.WorkQueue.vpxd.event.process.queue |  | info  |
| logger.WorkQueue.vpxd.events.burstfilter |  | info  |
| logger.WorkQueue.vpxd.ovfconsumers.queue |  | info  |
| logger.WorkQueue.vpxd.privilegecheck.queue |  | info  |
| logger.WorkQueue.vpxd.stats.persister.queue |  | info  |
| logger.WorkQueue.vpxd.statsregistry.queue |  | info  |
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
| vgpu.hotmigrate.enabled | vGPU hot migration | True  |
| VirtualCenter.AutoManagedIPV4 | Automatically discovered vCenter management IPv4 address |   |
| VirtualCenter.AutoManagedIPV6 | Automatically discovered vCenter management IPv6 address |   |
| VirtualCenter.DataCollector.ConsentData | Configuration of the Customer Experience Improvement Program | null  |
| VirtualCenter.DataCollector.Enabled | Deprecated. See: VirtualCenter.DataCollector.ConsentData | False  |
| VirtualCenter.DataCollector.Schedule | Customer experience improvement program data collection schedule |   |
| VirtualCenter.FQDN | vCenter FQDN | w4-pcld-245-151.eng.vmware.com  |
| VirtualCenter.HostBiosUuid | VirtualCenter Host Bios Uuid | 420ef5d6-8749-33a6-b000-dcb6bcd60f44  |
| VirtualCenter.InstanceName | Instance name | w4-pcld-245-151.eng.vmware.com  |
| VirtualCenter.ManagedIP | vCenter management IP address |   |
| VirtualCenter.MaxDBConnection | Maximum database connections | 50  |
| VirtualCenter.VimApiUrl | VIM API URL | https://w4-pcld-245-151.eng.vmware.com:443/sdk  |
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
| vpxd.clone.tpmProvisionPolicy | Default TPM provision policy | copy  |
| vpxd.cluster.roboMMEnabled | Enable DRS MM evacuations with appropriate ROBO license | True  |
| vpxd.CryptoManager.skpAllowedRoles | Roles are allowed to create Standard Key Provider |   |
| vpxd.dvx.locale.cleanupInterval | DVX locale files cleanup interval | 720  |
| vpxd.event.burstFilter.compressToDb | Enable burst filter on the database | True  |
| vpxd.event.burstFilter.compressToSyslog | Enable burst filter on the syslog stream | False  |
| vpxd.event.syslog.enabled | Enable syslog streaming | True  |
| vpxd.hostkey.newIfMissing | Generate a new host key if the host key is not available | True  |
| vpxd.httpClientIdleTimeout | Http Client Pool Idle Timeout | 900  |
| vpxd.KMS.backupCheckInterval | Key provider backup check interval (in hours) | 24  |
| vpxd.KMS.compatCheckInterval | Key provider compatibility cache update interval (in minutes) | 5  |
| vpxd.KMS.exportTokenExpiry | Key provider export token expiry (in minutes) | 5  |
| vpxd.KMS.remediationInterval | Key provider remediation interval (in minutes) | 5  |
| vpxd.KMS.status | Key provider status check interval (in minutes) | 5  |
| vpxd.kmscert.threshold | KMS Certificate Management Threshold (in days) | 30  |
| vpxd.license.data | License data | AQD+yggAAADSz4WGxjtU4UQAAAARZRfw8Q1vSMQHdZF1f/GHYqx5mTeouuBHz0vl6Z4B/VaZv0La0eMcB7sTK0ajTqeCpFfPlrNPy0jX+1DrsTxgCf1/YA==  |
| vpxd.license.ForceDownloadDLF | Force Download DLF | False  |
| vpxd.locale | Server locale |   |
| vpxd.motd | Global message |   |
| vpxd.npivWwnGeneration.portWwnNumber | Generation port WWN number | 4  |
| vpxd.npivWwnGeneration.singleNodeWwn | Generation single node WWN | True  |
| vpxd.ticketing.thumbprintTypes |  | sha1  |
| vpxd.usageStats.duration | Usage statistics duration | 1209600  |
| vpxd.usageStats.level | Usage statistics level | 0  |
| vpxd.usageStats.persist | Save usage statistics to the database | True  |
| vpxd.vdb.space.errorPercent | The used database space that triggers an error event | 95  |
| vpxd.vdb.space.warningPercent | The used database space that triggers a warning event | 80  |
| vpxd.vod.persist | Save usage statistics to a file | True  |
| vpxd.webscriptLauncher.enabled | Enable webscript launcher page | True  |
| vrdma.uuid |  | 52 36 05 7f 94 e1 8a c2-c4 28 91 2d c7 82 13 5d  |
| WebService.Ports.http | HTTP port number | 80  |
| WebService.Ports.https | HTTPS port number | 443  |
| wwn.instance.id | WWN instance | 0  |
