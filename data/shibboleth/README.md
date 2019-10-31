# Shibboleth Assets

## Shibboleth IdP
Configuration for development IdP instances

[Example usage](https://github.com/jhu-sheridan-libraries/jhuda-docker-idp/blob/master/Dockerfile) within a `Dockerfile` for the JHU Data Archive:
```
COPY --from=jhuda/assets:latest /data/shibboleth/jhuda/shibboleth-idp/conf /opt/shibboleth-idp/conf
COPY --from=jhuda/assets:latest /data/shibboleth/jhuda/shibboleth-idp/metadata /opt/shibboleth-idp/metadata
```

* [JHU Data Archive Shibboleth IdP configuration](jhuda/)
* [PASS JHU Shibboleth IdP configuration](pass/jhu)
* [Harvard Shibbloleth IdP configuration](pass/harvard)