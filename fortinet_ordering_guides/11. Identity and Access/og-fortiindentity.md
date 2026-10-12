# og-fortiindentity

Ordering Guide
FortiIdentity Cloud
(formerly FortiToken Cloud)
Available as Software-as-a-Service (SaaS)
FortiIdentity Cloud (FIC) is a powerful Identity and Access Management cloud service
that offers broad functionality to help you protect your resources from being accessed
by anyone except authenticated and authorized users. FortiIdentity Cloud provides
strong security without sacrificing user productivity and can be easily managed from the
cloud. Key features and benefits of FortiIdentity Cloud include:
Local IdP
Local IdP for federating SAML and OIDC applications on a standalone basis or use in
addition to other external IdPs.
IdP Proxy
Proxy one or more downstream SAML or OIDC Service Providers to one or more
upstream SAML or OIDC Identity Providers
Centrally Managed Authentication and Authorization
Centralized configuration and management for authentication/authorization policies, MFA
and Adaptive Authentication
Native Integration with Fortinet products
Out-of-the box integration with FortiGate, FortiAuthenticator and other Fortinet products
Simplified Admin and Deployment
Modern, intuitive web interface
No Extra Hardware or Software Required
No changes in security policies or ACLs are required. FortiToken Mobile OTP Tokens
included
Easy Provisioning and Scaling
SaaS scalability, daily usage reports, email notifications of subscription expiration, and
flexible renewal methods

FortiIdentity Cloud (formerly FortiToken Cloud) Ordering Guide
FUNCTIONAL AREA FEATURE
Identity Provider
IdP Proxy
SAML/OAuth2/OIDC
IdP Proxy
Secure Application Access and Single Sign-On (SSO)
RADIUS/802.1X
Fortinet SSO
LDAP Sync
SCIM Provisioning
Mobile OTP (FTM)
FortiToken OTP hard tokens (FTK)1
FIDO Passwordless2
MFA Adaptive Authentication
Email OTP
SMS OTP3
LDAP Auth Proxy
Admin Portal
Portals
End User Self Service Portal
1 FTK hard tokens require separate purchase
2 FTK410 FIDO2 (device bound credentials) is separate purchase (or bring your own FIDO authenticator)
3 SMS credits included with FIC subscription. Additional SMS credits can be purchased separately
FortiIdentity Cloud Use Cases
Identity Provider
Use FIC as for a local user directory on its own or to augment existing IdPs
Identity Provider Proxy
Proxy multiple downstream SAML SPs and OIDC RPs to multiple upstream SAML IdPs and OIDC Providers
Microsoft Entra External Authentication Methods (EAM) Provider
Use FIC MFA instead of MS MFA
Secure Access to Applications
Define who, what, when, where and how users are allowed access . Support for SAML, OIDC, OAuth, RADIUS, FSSO
Multi-Factor/Passwordless Authentication
Supports various MFA methods including Mobile OTP, SMS and email OTP, hardware tokens, and anti-phishing FIDO2 passkeys
Adaptive Authentication
Configure access based on login context
Order Information
SOLUTION BUNDLE FORTIIDENTITY CLOUD
25 – 499 users FC1-10-IDCLD-445-02-DD
Cloud-based IAM 500 - 1999 users FC2-10-IDCLD-445-02-DD
*Minimum order quantity is 25 2000 – 9999 users FC3-10-IDCLD-445-02-DD
10,000 or more users FC4-10-IDCLD-445-02-DD
2500 SMS credits FIC-SMS-2500
Additional SMS 10000 SMS credits FIC-SMS-10K
25000 SMS credits FIC-SMS-25K
2


**Table 2.1**

| FUNCTIONAL AREA | FEATURE |
| --- | --- |


**Table 2.2**

| SOLUTION BUNDLE | FORTIIDENTITY CLOUD |
| --- | --- |


**Table 2.3**

|  |  |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |

FortiIdentity Cloud (formerly FortiToken Cloud) Ordering Guide
License Limits
• Seat license based on number of users
• Applications limit is calculated as number of users licensed / 10 with a lower limit of 5.
• User Source limit is calculated as number of users licensed / 10 with a lower limit of 5.
For example, if a customer buys 100 FIC seats (100 users), they will be allowed up to 10 applications and 10 user sources.
In another case, if a customer buys a 25 user license, they can have up to 5 applications and 5 user sources.
The application limit includes Web, Management, SCIM, SSO and End user portals.
• Realm limit
• If the user license is less than or equal to 500, realm limit will be the same as the user quota.
• Else it will be 500 + (User quota) / 10.
For example, a 1000 user license will have a realm limit of 1000 / 10 + 500 = 600.
Licensing for accounts with FortiSASE licenses
FIC licensing entitlements differ depending on whether there is a single IdP/user source or multiple IdPs/user sources.
FortiIdentity Cloud provides special entitlements for user limits and authentication capabilities for accounts with FortiSASE
licenses.
Accounts with FortiSASE license and no FIC license
Accounts with FortiSASE licenses without an FIC license are entitled to an FIC tenant with a passthrough user limit equal to
twice the number of licensed SASE users. Unlike local users configured in the FIC local user source and remote users that are
imported into FIC from a remote IdP, Passthrough users are temporary users where FIC acts as a pure IdP proxy to a remote IdP
for FortiSASE SAML applications.
For example, if you have a 50-user FortiSASE license, your FIC user limit will be 100 passthrough users. The doubling of user
quota is to account for churn in the remote IdP.
Passthrough users are treated as temporary users in FortiIdentity Cloud. Any passthrough user that has been inactive for 30
consecutive days is automatically deleted by FortiIdentity cloud. Upon deletion, the associated user quota becomes available for
future passthrough users.
With only a FortiSASE license associated with the account, FortiSASE SSO applications can have only one IdP user source
corresponding to a single upstream remote IdP.
LICENSE FIC LOCAL AND REMOTE USER LIMIT FIC PASSTHROUGH USERS
FortiSASE only 3 (free 3 user license with any valid support contract) 2000
FortiSASE + FIC Up to 103 (20 plus free 3 users with any valid support contract) Up to 2000
Accounts with both FortiSASE and FIC Licenses
Accounts with a FortiSASE license along with a paid FIC license can add multiple IdP user sources for FortiSASE SSO
applications. Each passthrough user will only be counted as 0.05 user towards the user limit.
As an example, take a customer with a 1000 user SASE license and a 100-user FIC license.
If the customer configures 53 local plus remote users, the quota left for passthrough users is (103-53) x 20 = 1000.
Frequently Asked Questions
See the FortiIdentity Cloud FAQs.
www.fortinet.com
Copyright © 2026 Fortinet, Inc. All rights reserved. Fortinet®, FortiGate®, FortiCare® and FortiGuard®, and certain other marks are registered trademarks of Fortinet, Inc., and other Fortinet names herein may also be registered and/or common law trademarks of Fortinet. All other product or
company names may be trademarks of their respective owners. Performance and other metrics contained herein were attained in internal lab tests under ideal conditions, and actual performance and other results may vary. Network variables, different network environments and other condi-
tions may affect performance results. Nothing herein represents any binding commitment by Fortinet, and Fortinet disclaims all warranties, whether express or implied, except to the extent Fortinet enters a binding written contract, signed by Fortinet’s SVP Legal and above, with a purchaser
that expressly warrants that the identified product will perform according to certain expressly-identified performance metrics and, in such event, only the specific performance metrics expressly identified in such binding written contract shall be binding on Fortinet. For absolute clarity, any
such warranty will be limited to performance in the same ideal conditions as in Fortinet’s internal lab tests. Fortinet disclaims in full any covenants, representations, and guarantees pursuant hereto, whether express or implied. Fortinet reserves the right to change, modify, transfer, or otherwise
revise this publication without notice, and the most current version of the publication shall be applicable.
FIC-OG-R2-20261001


**Table 3.1**

| LICENSE | FIC LOCAL AND REMOTE USER LIMIT | FIC PASSTHROUGH USERS |
| --- | --- | --- |
