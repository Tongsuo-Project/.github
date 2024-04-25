铜锁密码学开源社区
===============

铜锁是一个开源社区，其中包含有多个密码学相关项目，主要分成如下几大类：
1. 铜锁标准版：一个提供现代密码学算法和安全通信协议的开源基础密码库，为存储、网络、密钥管理、隐私计算等诸多业务场景提供底层的密码学基础能力，实现数据在传输、使用、存储等过程中的私密性、完整性和可认证性，为数据生命周期中的隐私和安全提供保护能力。
2. RustyVault：一个现代的secrets管理系统，可以兼容Hashicorp Vault，提供安全存储、身份认证、密码学算法计算（签名、验签、加密、解密等）、公有云身份体系对接、PKI/CA等能力
3. 迷你锁：一个以提供轻量级密码学算法和安全通信协议为核心的嵌入式密码学算法库，具有体积小、占用资源少的特点
4. 其他周边支持类项目：包括多语言适配层、各类工具等

具体如下：

* RustyVault: RustyVault代码仓库
* rust-tongsuo: 铜锁标准版的Rust语言封装
* Tongsuo: 铜锁密码库标准版代码仓库
* docs: 铜锁密码库标准版的文档仓库
* tongsuo-mini: 迷你锁代码仓库
* wrk: 支持国密的wrk版本
* curl: 支持国密的curl版本
* tongsuo-java-sdk: 铜锁的Java语言封装
* tongsuo-python-sdk: 铜锁的Python语言封装
* tongsuo-go-sdk: 铜锁的Go语言封装
* php-src: 铜锁的PHP语言封装
* tongsuo-benchmark: 铜锁性能测试网站的代码
* proxy-tongsuo: Envoy适配铜锁

废弃和归档仓库：
* python-crypto: 废弃的铜锁的Python语言封装
* tongsuo-doc：弃用，改为使用docs仓库，本仓库归档
