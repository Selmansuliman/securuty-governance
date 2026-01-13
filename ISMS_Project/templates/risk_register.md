# Risk Register – نموذج افتراضي مُعبأ (وفق NIST SP 800-30)

هذا النموذج يمثل **Risk Register عملي** مع أمثلة افتراضية، مناسب لبيئات **Enterprise / SOC / PKI / Cloud**، ويُستخدم مباشرة في العروض التنفيذية والتدقيق.

---

## 1. معلومات عامة
- **Organization:** Example Corp
- **Assessment Scope:** Identity, SOC, PKI, Cloud
- **Methodology:** NIST SP 800-30 (Qualitative / Semi-Quantitative)
- **Risk Rating Scale:** Low / Moderate / High

---

## 2. Risk Register Table

| Risk ID | Asset | Threat Source | Threat Event | Vulnerability | Existing Controls | Likelihood | Impact | Risk Level | Risk Owner | Treatment Option | Residual Risk | Status |
|--------|-------|---------------|--------------|---------------|-------------------|------------|--------|------------|------------|------------------|---------------|--------|
| R-01 | Active Directory | External Attacker | Credential compromise via phishing | Weak MFA enforcement for admins | MFA for users, password policy | High | High | High | CISO | Mitigate: Enforce MFA + PAM | Moderate | Open |

| R-02 | Cloud Admin Accounts | Insider (Malicious) | Abuse of excessive privileges | Over-privileged IAM roles | IAM RBAC, logging | Moderate | High | High | Head of Cloud | Mitigate: Least Privilege + JIT | Moderate | In Progress |

| R-03 | SOC SIEM Platform | Process Failure | Delayed detection of attack | Poor use-case coverage | SIEM deployed, basic alerts | Moderate | Moderate | Moderate | SOC Manager | Mitigate: Tune use cases | Low | Open |

| R-04 | Root CA Private Key | Advanced Threat Actor | Key compromise | Insufficient ceremony oversight | HSM, dual control | Low | Very High | High | PKI Manager | Avoid: Strengthen ceremonies | Low | Open |

| R-05 | Endpoint Fleet | Ransomware Group | Malware execution | Unpatched endpoints | EDR, AV | High | Moderate | High | IT Security | Mitigate: Patch management | Moderate | Open |

| R-06 | Third-Party Vendor | Supply Chain | Breach via vendor access | Weak third-party security review | NDA, access restriction | Moderate | High | High | Vendor Mgmt | Transfer: Contractual clauses | Moderate | Open |

| R-07 | Audit Logs | Insider (Negligent) | Log tampering | Logs not immutable | Central logging | Low | High | Moderate | Security Ops | Mitigate: WORM storage | Low | Closed |

---

## 3. شرح مختصر للحقول (للإدارة)

- **Asset:** الأصل المتأثر بالمخاطر
- **Threat Source:** مصدر التهديد (خارجي، داخلي، تقني)
- **Threat Event:** السيناريو المحتمل
- **Vulnerability:** نقطة الضعف المستغلة
- **Existing Controls:** الضوابط الحالية
- **Likelihood:** احتمالية الحدوث (Low/Moderate/High)
- **Impact:** التأثير في حال التحقق
- **Risk Level:** ناتج Likelihood × Impact
- **Risk Owner:** المسؤول التنفيذي
- **Treatment Option:** Mitigate / Accept / Transfer / Avoid
- **Residual Risk:** المخاطر بعد المعالجة
- **Status:** حالة التنفيذ

---

## 4. ملاحظات مهنية مهمة

- لا يُسمح بـ Risk بدون **Owner واضح**
- Impact يُقاس بناءً على **أسوأ تأثير معقول**
- High Impact + Low Likelihood ≠ Risk منخفض
- المخاطر الحرجة يجب رفعها للإدارة العليا

---

## 5. استخدامات هذا السجل

- تقارير CISO
- لجان المخاطر
- ISO 27001 / ETSI / NIST audits
- التخطيط الاستراتيجي للميزانية

---

**End of Sample Risk Register**

