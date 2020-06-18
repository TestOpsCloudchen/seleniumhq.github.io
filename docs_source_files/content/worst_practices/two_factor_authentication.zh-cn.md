---
title: "双因素认证"
weight: 1
---

{{% notice info %}}
<i class="fas fa-language"></i> Page being translated from 
English to Chinese. Do you speak Chinese? Help us to translate
it by sending us pull requests!
{{% /notice %}}

双因素认证缩写为 2FA 提供了一种一次性认证模式One Time Password(OTP)被大量使用在
移动应用的认证上例如：“谷歌认证器”，“微软认证器”等等，或者短信密码、电子邮件确认链接。
这些都是Selenium稳定自动化中长期的巨大阻碍。虽然也有一些方法可以自动化这类流程，但是
对于Selenium的自动化测试来说也引入了不安全的因素，所以最好考虑绕过2FA在自动化过程中。

这里有一些选项可以绕过2FA检查：
* 在测试环境中禁止对特定用户的 2FA 校验，这样你就可以使用这些账户进行自动化测试。
* 在测试环境中禁止 2FA 校验
* 针对特定IP地址区域进行2FA的校验。这样我们可以将测试设备的IP地址归于白名单内。

