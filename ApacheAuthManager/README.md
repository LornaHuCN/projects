This is a project based on PHP to set Apache authorization settings.
1. htpasswd

2. Authentication and Authorization

. Authentication type - AuthType
  - mod_auth_basic
  - mod_auth_digest
. Authentication provider - AuthBasicProvider and AuthDigestProvider directive
  - mod_authn_anon
  - mod_authn_dbd
  - mod_authn_dbm
  - mod_authn_file
  - mod_authnz_ldap
. Authorization - Require directive
  - mod_authnz_ldap
  - mod_authz_dbm
  - mod_authz_groupfile
  - mod_authz_host
  - mod_authz_owner
  - mod_authz_user
. Other modules
  - mod_authn_alias


3. External Modules 
mod_auth_cas.i686 : Apache 2.0/2.2 compliant module that supports the CASv1 and CASv2 protocols
mod_auth_kerb.i686 : Kerberos authentication module for HTTP
mod_auth_mellon.i686 : A SAML 2.0 authentication module for the Apache Httpd Server
mod_auth_ntlm_winbind.i686 : NTLM authentication for the Apache web server using winbind daemon
mod_auth_token.i686 : Token based URI access module for Apache
mod_auth_xradius.i686 : Apache module that provides authentication against RADIUS Servers
mod_authnz_external.i686 : An Apache module used for authentication
mod_authnz_pam.i686 : PAM authorization checker and PAM Basic Authentication provider
pwauth.i686 : External plugin for mod_authnz_external authenticator

