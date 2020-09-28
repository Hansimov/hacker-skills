# 重点漏洞列表

## 链接

* OWASP Top Ten Web Application Security Risks
  * [https://owasp.org/www-project-top-ten/](https://owasp.org/www-project-top-ten/)
* CWE - CWE List Version 4.2 
  * [https://cwe.mitre.org/data/index.html](https://cwe.mitre.org/data/index.html)
* The HackerOne Top 10 Most Impactful and Rewarded Vulnerability Types \| HackerOne 
  * [https://www.hackerone.com/blog/hackerone-top-10-most-impactful-and-rewarded-vulnerability-types](https://www.hackerone.com/blog/hackerone-top-10-most-impactful-and-rewarded-vulnerability-types)
* Top 10 Most Impactful and Rewarded Vulnerability Types \| HackerOne 
  * [https://www.hackerone.com/top-10-vulnerabilities](https://www.hackerone.com/top-10-vulnerabilities)

## Hackerone 报告笔记

**关键词：SSRF、XSS、信息泄露、注入**

* 云上安全日益重要：组织争前恐后使用混合的和云上环境，因此 SSRF 将会稳定繁荣；信息泄露仍将常见，始终在赏金漏洞前列。
* 企业看重权限提升、SSRF 和 IDOR：尽管报告的绝对数量并非最多，但是这三者累计赏金最多。
* Hackerone 十大漏洞仅有 4 种在 OWASP Top 10 上：XSS、信息泄露、注入；而在 OWASP 排名第 4 的 XXE 在 Hackerone 排名 15。
* 在 XSS 之上的 企业逻辑错误、代码注入以及更多：XSS 依旧最常见的漏洞类型。不过，一些数量少价格高的漏洞类型，比如企业逻辑错误和代码注入等，表明这些漏洞在多样化的攻击面上的影响。

> 表格：不同漏洞类型的数量比例

| 类型 / 领域 | 互联网 & 在线服务 | 计算机软件 | 电信行业 | 媒体 & 娱乐 |
| :--- | :--- | :--- | :--- | :--- |
| **XSS** | 30% | 29% | 31% | 37% |
| **不恰当的验证** | 18% | 24% | 17% | 18% |
| **信息泄露** | 23% | 18% | 25% | 19% |
| 权限提升 | 5% | 7% | 5% | 4% |
| SQL 注入 | 3% | 1% | 2% | 3% |
| 代码注入 | 2% | 2% | 3% | 2% |
| SSRF | 1% | 1% | 1% | 1% |
| IDOR | 2% | 2% | 0% | 2% |
| 不恰当的访问控制 | 4% | 4% | 3% | 4% |
| **CSRF** | 12% | 11% | 14% | 10% |



