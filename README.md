# 模块配置调度框架（GO）
## 背景
1. 本框架提供模块化、配置化的流程编排能力，基于 Go 语言编写
2. 设计灵感：gin 框架源码、日常工作总结
3. 由我设计的第一版功能已在某一线互联网公司线上真实应用，并带来很好的收益
    1. 实现了业务配置化，在真实业务场景下，直接减少了 90% 技术人力投入
    2. 鉴于历史包袱的原因，一些想法不能直接应用到线上，故本框架除了提供基础功能外，将会承接自己的一些思考和规划，希望做到更加抽象，更加通用化

