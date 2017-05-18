DB2 9.5 数据服务器
============================================
Information as Service
-支持和查询结构化,半结构化和非结构化数据
-集成数据
-提供实体解析,数据管理,联邦和内容管理
-运行时分析
============================================
  DB2 具有公共代码库
***********************
*         DB2         *
* database services   *
*     Common code     *------------------90%
***********************
*OS interface software*
***********************
*     OS-specific     *
*     Unique code     *------------------10%
***********************
*  Operating system   *
*   Hewlett Packard   *
*        Linux        *
*         Sun         *
*         AIX         *
*  Microsoft Windows  *
***********************
(SQL API 95% 公共)
(公共的Web服务框架)
============================================
============================================
db2 catalog tcpip node node_npb remote 134.96.164.150 server 50000
db2 catalog database zjdw as zjdw_npb at node node_npb
db2 terminate
150 --- 正式库
============================================
db2 catalog tcpip node node_115 remote 134.96.33.115 server 50012
db2 catalog database zjdw as zjdw_115 at node node_115
db2 terminate
115 --- 测试库
============================================
db2 catalog tcpip node node_117 remote 134.96.33.117 server 50012
db2 catalog database zjdw as zjdw_117 at node node_117
db2 terminate
117 --- 调度服务器,查看作业情况
============================================
db2 catalog tcpip node node_158 remote 134.96.164.158 server 50000
db2 catalog database zjdw as zjdw_158 at node node_158
db2 terminate
158 --- 正式库
============================================
