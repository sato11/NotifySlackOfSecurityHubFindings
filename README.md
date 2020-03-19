# NotifySlackOfSecurityHubFindings

[AWS Security Hub](https://aws.amazon.com/jp/security-hub/)で検知された内容をCloudWatchルールで監視してSNSトピックに通知する。  
SNSトピックをさらに[AWS Chatbot](https://aws.amazon.com/jp/chatbot/)でSlackに通知しているが、これについては2020年3月時点でCloudFormationがサポートしていないため、手動で設定している。
