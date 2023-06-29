# DDNS - UPNP

Scripts to automate DDNS with dynu and UPNP.

## Dependencies

- POSIX Shell :  Busybox, bash, dash, ...
- Curl
- MiniUPnPc

## Help

dynu

    Usage: dynu ...
    
    Manage DNS bindings in `www.dynu.com`. Please set the token
    with DYNU_API_KEY or /etc/tokens/dynu.
    
    ... show                       : Show configuration.
    ... public-ip                  : Get public IP address.
    ... domain-ls                  : List domains.
    ... domain-id  DOMAIN          : Get domain's ID.
    ... domain-set DOMAIN [IPADDR] : Assign IP address to domain.

update-ddns

    Usage: update-ddns
    
    Read DDNS information from "/etc/ddns" and update DDNS
    if needed. Tokens are read from "/etc/tokens/dynu".

update-upnp

    Usage: update-upnp
    
    Read DDNS information from "/etc/upnp".

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
