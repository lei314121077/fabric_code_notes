# Fabric 1.0源代码笔记

## ■ Fabric 1.0源代码笔记 之 Fabric源码篇

*本文基于Fabric v1.0.4版本代码。*
* [Fabric 1.0源代码笔记 之 Peer](code/peer/README.md)
	* [peer根命令入口及加载子命令](code/peer/peer_main.md)
	* [peer node start命令实现](code/peer/peer_node_start.md)
	* [peer channel命令及子命令实现](code/peer/peer_channel.md)
	* [peer chaincode命令及子命令实现](code/peer/peer_chaincode.md)
	* [EndorserClient（Endorser客户端）](code/peer/EndorserClient.md)
	* [BroadcastClient（Broadcast客户端）](code/peer/BroadcastClient.md)
	* [DeliverClient（Deliver客户端）](code/peer/DeliverClient.md)
	* [EndorserServer（Endorser服务端）](code/peer/EndorserServer.md)
* [Fabric 1.0源代码笔记 之 Orderer](code/orderer/README.md)
	* [orderer start命令实现](code/orderer/orderer_start.md)
	* [localconfig（Orderer配置文件定义）](code/orderer/localconfig.md)
	* [ledger（Orderer Ledger）](code/orderer/orderer_ledger.md)
	* [BroadcastServer（Broadcast服务端）](code/orderer/BroadcastServer.md)
	* [multichain（多链支持包）](code/orderer/multichain.md)
* [Fabric 1.0源代码笔记 之 flogging（Fabric日志系统）](code/flogging/README.md)
* [Fabric 1.0源代码笔记 之 BCCSP（区块链加密服务提供者）](code/bccsp/README.md)
* [Fabric 1.0源代码笔记 之 MSP（成员关系服务提供者）](code/msp/README.md)
* [Fabric 1.0源代码笔记 之 LevelDB（KV数据库）](code/leveldb/README.md)
* [Fabric 1.0源代码笔记 之 blockfile（区块文件存储）](code/blockfile/README.md)
* [Fabric 1.0源代码笔记 之 Tx（Transaction 交易）](code/tx/README.md)
	* [RWSet（读写集）](code/tx/rwset.md)
* [Fabric 1.0源代码笔记 之 putils（protos/utils工具包）](code/putils/README.md)
* [Fabric 1.0源代码笔记 之 Ledger（账本）](code/ledger/README.md)
	* [idStore（ledgerID数据库）](code/ledger/idstore.md)
	* [blkstorage（block文件存储）](code/ledger/blkstorage.md)
	* [statedb（状态数据库）](code/ledger/statedb.md)
	* [historydb（历史数据库）](code/ledger/historydb.md)
* [Fabric 1.0源代码笔记 之 events（事件服务）](code/events/README.md)
* [Fabric 1.0源代码笔记 之 gossip（流言算法）](code/gossip/README.md)
* [Fabric 1.0源代码笔记 之 scc（系统链码）](code/scc/README.md)
	* [cscc（通道相关）](code/scc/cscc.md)
	* [escc（背书相关）](code/scc/escc.md)
	* [lscc（链码相关）](code/scc/lscc.md)
	* [qscc（账本查询相关）](code/scc/qscc.md)
	* [vscc（策略校验相关）](code/scc/vscc.md)
* [Fabric 1.0源代码笔记 之 Proposal（提案）](code/proposal/README.md)
* [Fabric 1.0源代码笔记 之 policy（背书策略）](code/policy/README.md)
* [Fabric 1.0源代码笔记 之 Chaincode（链码）](code/chaincode/README.md)
	* [ChaincodeSupport（链码支持服务端）](code/chaincode/ChaincodeSupport.md)
* [Fabric 1.0源代码笔记 之 consenter（共识插件）](code/consenter/README.md)
	* [filter（过滤器）](code/consenter/filter.md)
* [Fabric 1.0源代码笔记 之 cryptogen（生成组织关系和身份证书）](code/cryptogen/README.md)
* [Fabric 1.0源代码笔记 之 configtx（配置交易）](code/configtx/README.md)
	* [configtxgen（生成通道配置）](code/configtx/configtxgen.md)
	* [genesis（系统通道创世区块）](code/configtx/genesis.md)
	* [ChannelConfig（通道配置）](code/configtx/ChannelConfig.md)

## ■ Fabric 1.0源代码笔记 之 附录篇
	
* [Fabric 1.0源代码笔记 之 附录-ECDSA（椭圆曲线数字签名算法）](annex/ecdsa.md)
* [Fabric 1.0源代码笔记 之 附录-简称表](annex/abbreviation.md)
* [Fabric 1.0源代码笔记 之 附录-Fabric使用的第三方包](annex/third_party_packages.md)
* [Fabric 1.0源代码笔记 之 附录-Fabric 1.0.4 go代码量统计](annex/codestats.md)
* [Fabric 1.0源代码笔记 之 附录-关键数据结构（图）](annex/datastructure.md)
* [Fabric 1.0源代码笔记 之 附录-关键流程图（图）](annex/flowchart.md)
* [Fabric 1.0源代码笔记 之 附录-gRPC（Fabric中注册的gRPC Service）](annex/grpc.md)

