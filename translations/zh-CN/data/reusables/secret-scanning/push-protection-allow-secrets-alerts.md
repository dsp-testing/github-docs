当您允许推送密钥时，将在“Security（安全）”选项卡中创建警报。 {% data variables.product.prodname_dotcom %} closes the alert and doesn't send a notification if you specify that the secret is a false positive or used only in tests. If you specify that the secret is real and that you will fix it later, {% data variables.product.prodname_dotcom %} keeps the security alert open and sends notifications to the author of the commit, as well as to repository administrators. 更多信息请参阅“[管理来自密码扫描的警报](/code-security/secret-scanning/managing-alerts-from-secret-scanning)”。