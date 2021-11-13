تهدیدهای امنیتی API
==================
از متدو لوژی رتبه بندی تهدید اوسپ برای تحلیل تهدید ها استفاده شده است .

The [OWASP Risk Rating Methodology][1] was used to do the risk analysis.

  در جدول زیر اصطلاحات مرتبط با امتیاز ریسک به صورت خلاصه اشاره شده است .

The table below summarizes the terminology associated with the risk score.

| عوامل تهدید | قابلیت بهره برداری | شیوع ضعف | قابلیت تشخیص ضعف | تاثیر فنی | تاثیر کسب و کار |
| :-: | :-: | :-: | :-: | :-: | :-: |
| API خاص | آسان: **3** | گسترده **3** | آسان **3** | شدید **3** | خاص کسب و کار |
| API خاص | متوسط: **2** | مرسوم **2** | متوسط **2** | در حد متوسط **2** | خاص کسب و کار |
| API خاص | سخت: **1** | سخت **1** | سخت **1** | جزئی **1** | خاص کسب و کار |

**توجه**: این رویکرد احتمال عامل تهدید را در نظر نمی گیرد. همچنین هیچ یک از جزئیات فنی مختلف مرتبط با برنامه خاص شما را در نظر نمی گیرد.
هر یک از این عوامل می تواند به طور قابل توجهی بر احتمال کلی مهاجم برای یافتن و سوء استفاده از یک آسیب پذیری خاص تأثیر بگذارد.
این رتبه‌بندی تأثیر واقعی بر کسب‌وکار شما را در نظر نمی‌گیرد. سازمان شما باید تصمیم بگیرد که سازمان با توجه به فرهنگ، صنعت و محیط نظارتی شما، چه میزان خطر امنیتی ناشی از برنامه ها و API ها را می پذیرد. هدف OWASP API Security Top 10 انجام این تحلیل ریسک برای شما نیست.

## منابع

### OWASP

* [OWASP Risk Rating Methodology][1]
* [Article on Threat/Risk Modeling][2]

### خارجی

* [ISO 31000: Risk Management Std][3]
* [ISO 27001: ISMS][4]
* [NIST Cyber Framework (US)][5]
* [ASD Strategic Mitigations (AU)][6]
* [NIST CVSS 3.0][7]
* [Microsoft Threat Modeling Tool][8]

[1]: https://www.owasp.org/index.php/OWASP_Risk_Rating_Methodology
[2]: https://www.owasp.org/index.php/Threat_Risk_Modeling
[3]: https://www.iso.org/iso-31000-risk-management.html
[4]: https://www.iso.org/isoiec-27001-information-security.html
[5]: https://www.nist.gov/cyberframework
[6]: https://www.asd.gov.au/infosec/mitigationstrategies.htm
[7]: https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator
[8]: https://www.microsoft.com/en-us/download/details.aspx?id=49168
