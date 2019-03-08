
<html>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<head>
<title>mysql简介</title>
<head>
<body>
<h1>MySql(关系型数据库管理系统)</h1>
<ol>
<div>MySQL是一个关系型数据库管理系统，由瑞典MySQL AB 公司开发，目前属于 Oracle 旗下产品。MySQL 是最流行的关系型数据库管理系统之一，在 WEB 应用方面，MySQL是最好的 RDBMS (Relational Database Management System，关系数据库管理系统) 应用软件。</div>
<div>MySQL是一种关系数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。</div>
<div>MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL 作为网站数据库。</div>
<div>由于其社区版的性能卓越，搭配 PHP 和 Apache 可组成良好的开发环境。</div>
</ol>
<br>
<br>
<h2>应用环境</h2>
<ol>

<div>与其他的大型数据库例如 Oracle、DB2、SQL Server等相比，MySQL 自有它的不足之处，但是这丝毫也没有减少它受欢迎的程度。对于一般的个人使用者和中小型企业来说，MySQL提供的功能已经绰绰有余，而且由于 MySQL是开放源码软件，因此可以大大降低总体拥有成本。</div>

<div>Linux作为操作系统，Apache 或Nginx作为 Web 服务器，MySQL 作为数据库，PHP/Perl/Python作为服务器端脚本解释器。由于这四个软件都是免费或开放源码软件（FLOSS)，因此使用这种方式不用花一分钱（除开人工成本）就可以建立起一个稳定、免费的网站系统，被业界称为“LAMP“或“LNMP”组合。</div>
<br>

<div style='width: 1000px;display:none;word-break: break-all;word-wrap: break-word;'>==mahuaBegin==c499c5f76e48a7ac91eae2ce2527ceae029bacc5c88507901cb194269b253f1518419e9adc65ba095f5b59ff30b1cca821c90b159136c0c252a70dcd413fb784ef344b3abb77a1d2f4924c4828eb207c757d1b3b9b403fa299a01d2d57b2bae4ea982f906e1affb806a0083c84cf5ebab61f978681bbb5495ed53b0bec47bd88bad4d2820431b3715b7e283e59b442ef0d3132761334f0b8d94e5120bd0577cd03dfaa21da0b124aeb785af4a8a0e22fef19ce703b91717e6f23667255a692893137879966f20139b2c4fa8d27973e088bb2990d808b1fc9494ad7dd4476bbbe3be3c9312edf36f2eae45a77e5b66198c089039a65586eda1e6013be41b6b3c2efea9b487d93b7e7262b9438eeb4388702ac8a8b6b9577f36d01e994be49a250ae9573cd784da8eb64ec3dfc5a87d01dc94b94de86fa1f8aa635bf2c0af6d94ce5c67d15924655124fae7955408510317a416d24ef2567237df9983ee8a1b21384ab276a8015f5e7241dc6a2eb7627491e465654adf10e3f514b5c1219a437f368a3c0564d345b86b3948d56c63883e51d8a632a793e9e59f13c4736e0ec7a0b6e17d3f5e4a62efb0beec506303a778a27f12e88e04e3dc4478443f99b5646118428ab7bafc70c965ff05540762063f0af13fcab1676ad552b61552117aa06e6512cc8897c33f79fc6c17308d428eb0d4fff99f61752e3aae979a8aa59bde62fa79f00e5435dde38916f6272f2604296a1ab59aeed2853f774f344286f54055d7ca7a848071344c22a0083cf1d31f662==mahuaEnd==</ol>



<h2>系统特性</h2>
<ol>
<div>1．使用 C和 C++编写，并使用了多种编译器进行测试，保证了源代码的可移植性。</div>
<div>2．支持 AIX、FreeBSD、HP-UX、Linux、Mac OS、NovellNetware、OpenBSD、OS/2 Wrap、Solaris、Windows等多种操作系统。</div>
<div>3．为多种编程语言提供了 API。这些编程语言包括 C、C++、Python、Java、Perl、PHP、Eiffel、Ruby,.NET和 Tcl 等。</div>
<div>4．支持多线程，充分利用 CPU 资源。</div>
<div>5．优化的 SQL查询算法，有效地提高查询速度。</div>
<div>6．既能够作为一个单独的应用程序应用在客户端服务器网络环境中，也能够作为一个库而嵌入到其他的软件中。</div>
<div>7．提供多语言支持，常见的编码如中文的 GB 2312、BIG5，日文的 Shift_JIS等都可以用作数据表名和数据列名。</div>
<div>8．提供 TCP/IP、ODBC 和 JDBC等多种数据库连接途径。</div>
<div>9．提供用于管理、检查、优化数据库操作的管理工具。</div>
<div>10．支持大型的数据库。可以处理拥有上千万条记录的大型数据库。</div>
<div>11．支持多种存储引擎。</div>
<div>12.MySQL 是开源的，所以你不需要支付额外的费用。</div>
<div>13.MySQL 使用标准的 SQL数据语言形式。</div>
<div>14.MySQL 对 PHP 有很好的支持，PHP是比较流行的 Web 开发语言。</div>
<div>15.MySQL是可以定制的，采用了 GPL协议，你可以修改源码来开发自己的 MySQL 系统。</div>
<div>16.在线 DDL/更改功能，数据架构支持动态应用程序和开发人员灵活性（5.6新增）</div>
<div>17.复制全局事务标识，可支持自我修复式集群（5.6新增）</div>
<div>18.复制无崩溃从机，可提高可用性（5.6新增）</div>
<div>19.复制多线程从机，可提高性能（5.6新增）</div>
<div>20.3倍更快的性能（5.7  新增）</div>
<div>21.新的优化器（5.7新增）</div>
<div>22.原生JSON支持（5.7新增）</div>
<div>23.多源复制（5.7新增）</div>
<div>24.GIS的空间扩展 （5.7新增）</div>
</ol>
</body>
</html>
