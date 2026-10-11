# 安全问题报告

发现账号隔离、确认链接泄漏或其他可利用漏洞时，请在[仓库 Security → Advisories](https://github.com/zhoujingkai14-a11y/mingdan/security/advisories)选择“Report a vulnerability”提交私密报告。报告中尽量使用虚构数据和最小复现。

请勿在公开 Issue 中粘贴 API Key、密码、恢复密钥、客户确认码、真实消息或数据库。普通使用问题可以通过[问题模板](https://github.com/zhoujingkai14-a11y/mingdan/issues/new/choose)提交脱敏复现。

配置只放在服务端环境变量或本机 `.env`；Git 忽略不是加密。泄露的真实 Key 应先在供应商处撤销或轮换，再处理 Git 历史；删除当前文件不能撤销已经公开的密钥。

仓库私密漏洞报告、可用的密钥扫描与推送保护会在本次迁移时核对启用。扫描覆盖范围不能证明代码不存在全部机密或漏洞。

本项目提供本地发布检查与 CI，不构成完整渗透测试。尚未承诺安全报告响应时间或长期安全维护期限。
