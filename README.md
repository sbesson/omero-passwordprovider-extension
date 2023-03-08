OMERO password provider extension
---------------------------------

Requirements
============

 * OMERO.server 5.6

Configuration
=============

The no-op password provider can be activated by setting
`omero.security.password_provider`:

    omero config set \
        omero.security.password_provider chainedPasswordProviderNoop

References
==========

* https://omero.readthedocs.io/en/stable/developers/Server/PasswordProvider.html
