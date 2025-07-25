![UserBlaze TrustMesh Vault](https://pub-a300c5959c894a1dbb0d6842da5577b1.r2.dev/userblaze-trustmesh-vault-github-banner.jpg)

# UserBlaze TrustMesh Vault

**TrustMesh Vault** is the customer-hosted component that powers UserBlaze’s TrustMesh architecture. It acts as the trust boundary between internal systems and UserBlaze’s Cloud service, ensuring that **no personally identifiable information (PII) ever leaves customer infrastructure**.

TrustMesh Vault maps sensitive customer identifiers (like names, emails, etc.) to anonymized UUIDs, stores these mappings locally, and uses them to transform third-party data (e.g., from Mixpanel, Zendesk) before sending anonymized data to UserBlaze.

---

> [!NOTE]
> **Managed Implementation**: UserBlaze Cloud provides a fully-managed implementation of TrustMesh. If you don't want to run TrustMesh Vault yourself, you can simply use our [Cloud service](https://app.userblaze.com/sign-up).

---

## Key Capabilities

* 🔐 **PII-to-UUID Mapping**: Maps identifiers to UUIDs for eventual de-anonymized correlation on customer-controlled devices.
* 🧱 **Zero Trust Data Relay**: Anonymizes and transmits only sanitized data to the UserBlaze backend.
* 🛠️ **Customer-Operated by Design**: Deployed and managed by your team on your infrastructure.
* 🧩 **Source Connectors**: Integrates with tools like Mixpanel, Zendesk, Amplitude, etc.
* 🗃️ **Local Mapping Store**: Securely retains identity mappings; never syncs sensitive data outside your network.

By deploying TrustMesh Vault, enterprise customers can unlock the full power of UserBlaze without compromising on data privacy, residency, or compliance mandates.


