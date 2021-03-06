# Resource rewritepolicylabel

Spec for **rewritepolicylabel** resource - [citrix documentation page](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/12.0/configuration/rewrite/rewritepolicylabel/rewritepolicylabel/)

- [Identifier](#identifier)
- [Operations](#operations)
- [Fields](#fields)

## Identifier

Identifier : labelname

## Operations

| Name | Method | Url |
|----|----|----|
| List | GET | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel` |
| Get | GET | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel/<name>` |
| Delete | DELETE | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel/<name>` |
| Update | PUT | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel` |
| Add | POST | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel` |
| Enable | POST | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel?action=enable` |
| Disable | POST | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel?action=disable` |
| Rename | POST | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel?action=rename` |
| Unset | POST | `http://<netscaler-ip-address>/nitro/v1/config/rewritepolicylabel?action=unset` |

## Fields

| Name | Update | Type |
|----|----|----|
| labelname | No | string |
| comment | No | string |
| transform | No | http_req, http_res, othertcp_req, othertcp_res, url, text, clientless_vpn_req, clientless_vpn_res, sipudp_req, sipudp_res, siptcp_req, siptcp_res, diameter_req, diameter_res, radius_req, radius_res, dns_req, dns_res |

