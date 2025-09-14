# cross_chain
##合约设计（MyOFT.sol）
继承 LayerZero 的 OFTV2 合约，该合约已实现跨链代币转移的核心逻辑
自定义 crossChainTransfer 函数，简化跨链转账调用
构造函数初始化代币信息、LayerZero 端点和初始供应
