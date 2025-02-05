---
title: SP Config
order: 6
---

# SP Config

This section gives you a complete config of SP.

```toml
AppID = ''
Server = []
GRPCAddress = ''

[SpDB]
User = ''
Passwd = ''
Address = ''
Database = ''
ConnMaxLifetime = 0
ConnMaxIdleTime = 0
MaxIdleConns = 0
MaxOpenConns = 0

[BsDB]
User = ''
Passwd = ''
Address = ''
Database = ''
ConnMaxLifetime = 0
ConnMaxIdleTime = 0
MaxIdleConns = 0
MaxOpenConns = 0

[BsDBBackup]
User = ''
Passwd = ''
Address = ''
Database = ''
ConnMaxLifetime = 0
ConnMaxIdleTime = 0
MaxIdleConns = 0
MaxOpenConns = 0

[PieceStore]
Shards = 0

[PieceStore.Store]
Storage = ''
BucketURL = ''
MaxRetries = 0
MinRetryDelay = 0
TLSInsecureSkipVerify = false
IAMType = ''

[Chain]
ChainID = ''
ChainAddress = []
GasLimit = 0

[SpAccount]
SpOperatorAddress = ''
OperatorPrivateKey = ''
FundingPrivateKey = ''
SealPrivateKey = ''
ApprovalPrivateKey = ''
GcPrivateKey = ''

[Endpoint]
ApproverEndpoint = ''
ManagerEndpoint = ''
DownloaderEndpoint = ''
ReceiverEndpoint = ''
MetadataEndpoint = ''
UploaderEndpoint = ''
P2PEndpoint = ''
SignerEndpoint = ''
AuthenticatorEndpoint = ''

[Approval]
BucketApprovalTimeoutHeight = 0
ObjectApprovalTimeoutHeight = 0
ReplicatePieceTimeoutHeight = 0

[Bucket]
AccountBucketNumber = 0
FreeQuotaPerBucket = 0
MaxListReadQuotaNumber = 0
MaxPayloadSize = 0

[Gateway]
DomainName = ''
HTTPAddress = ''

[Executor]
MaxExecuteNumber = 0
AskTaskInterval = 0
AskReplicateApprovalTimeout = 0
AskReplicateApprovalExFactor = 0.0
ListenSealTimeoutHeight = 0
ListenSealRetryTimeout = 0
MaxListenSealRetry = 0

[P2P]
P2PPrivateKey = ''
P2PAddress = ''
P2PAntAddress = ''
P2PBootstrap = []
P2PPingPeriod = 0

[Parallel]
GlobalCreateBucketApprovalParallel = 0
GlobalCreateObjectApprovalParallel = 0
GlobalMaxUploadingParallel = 0
GlobalUploadObjectParallel = 0
GlobalReplicatePieceParallel = 0
GlobalSealObjectParallel = 0
GlobalReceiveObjectParallel = 0
GlobalGCObjectParallel = 0
GlobalGCZombieParallel = 0
GlobalGCMetaParallel = 0
GlobalDownloadObjectTaskCacheSize = 0
GlobalChallengePieceTaskCacheSize = 0
GlobalBatchGcObjectTimeInterval = 0
GlobalGcObjectBlockInterval = 0
GlobalGcObjectSafeBlockDistance = 0
GlobalSyncConsensusInfoInterval = 0
UploadObjectParallelPerNode = 0
ReceivePieceParallelPerNode = 0
DownloadObjectParallelPerNode = 0
ChallengePieceParallelPerNode = 0
AskReplicateApprovalParallelPerNode = 0
QuerySPParallelPerNode = 0
DiscontinueBucketEnabled = false
DiscontinueBucketTimeInterval = 0
DiscontinueBucketKeepAliveDays = 0

[Task]
UploadTaskSpeed = 0
DownloadTaskSpeed = 0
ReplicateTaskSpeed = 0
ReceiveTaskSpeed = 0
SealObjectTaskTimeout = 0
GcObjectTaskTimeout = 0
GcZombieTaskTimeout = 0
GcMetaTaskTimeout = 0
SealObjectTaskRetry = 0
ReplicateTaskRetry = 0
ReceiveConfirmTaskRetry = 0
GcObjectTaskRetry = 0
GcZombieTaskRetry = 0
GcMetaTaskRetry = 0

[Monitor]
DisableMetrics = false
DisablePProf = false
MetricsHTTPAddress = ''
PProfHTTPAddress = ''

[Rcmgr]
DisableRcmgr = false

[Log]
Level = ''
Path = ''

[Metadata]
IsMasterDB = false
BsDBSwitchCheckIntervalSec = 0

[BlockSyncer]
Modules = []
Dsn = ''
DsnSwitched = ''
Workers = 0
EnableDualDB = false

[APIRateLimiter]
PathPattern = []
HostPattern = []
APILimits = []

[APIRateLimiter.IPLimitCfg]
On = false
RateLimit = 0
RatePeriod = ''

[Manager]
EnableLoadTask = false
```
