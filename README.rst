===========================
openvpn-certificate-manager
===========================

Currently **WIP**.

This project is suppose to be simple Django application to manage OpenVPN configs and certificates.

Idea
----

**Users**

1. User gain access via IDP (currently Azure AD - SAML).
2. Create an OpenVPN Certificate / Config, protected by passphrase.
3. Download and use it.

Config is created only one-time, in case user lose the configuration, user is forced to create new config.
User can also revoke their own config.

**Administrator**

* List all users and all configs (active or inactive)
* Deactivate any user config