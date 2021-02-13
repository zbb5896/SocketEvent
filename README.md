# FlatBread
高并发的Socket基础库 带有解决粘包的简单协议 优势在于简单的结构和内存的高度重用省去浪费的开销

基础TCP通信库
包含的能力
1. 因发送效能过快导致的丢包重发(未实现)
2. 因服务端短暂崩溃客户端可缓存下发送的所有包 服务端再度上线后继续处理
3. 优秀的性能 {低结构化} {客户端 服务端独立化} {流的分片处理}
4. 此框架为基础TCP比较可靠的脚手架 因结构简单 理解方便 所以更可在基础上扩展
5. 内部已有基础封包 也可直接使用
