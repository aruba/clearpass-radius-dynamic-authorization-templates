# RADIUS Dynamic Authorization Templates for ClearPass
RADIUS Dynamic Authorization templates (Disconnect and CoA)

Right Click > Save Link/Target As

Import under Policy Manager > Administration > Dictionaries > RADIUS Dynamic Authorization Templates


## Aruba

### AOS-CX Edge with CPPM 6.8 and earlier
> NOTE: These templates and enforcement profiles are only for use on CPPM 6.8.X and earlier.

First, download (right click, Save Link/Target As) and import the latest Aruba RADIUS dictionary > (CPPM: Administration » Dictionaries » RADIUS):
* [Aruba RADIUS Dictionary v2019-02](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/aruba/radius-dict_aruba-14823_v2019-02.xml)

Next, download (right click, Save Link/Target As) the following RADIUS Dynamic Authorization templates and add them to CPPM (Administration » Dictionaries » RADIUS Dynamic Authorization Templates):
* [Disconnect Template](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/aruba/radius-da_template_aoscx_disconnect_legacy.xml)
* [Change User Role Template](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/aruba/radius-da_template_aoscx_coa_change-user-role_legacy.xml)
* [Bounce Port Template](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/aruba/radius-da_template_aoscx_coa_bounce-port_legacy.xml)

Download (right click, Save Link/Target As) and import the pre-built enforcement profiles for Disconnect and Port Bounce (CPPM: Configuration » Enforcement » Profiles):
* [Disconnect Enforcement Profile](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/aruba/radius-da_enf-prof_aoscx_disconnect_legacy.xml)
* [Bounce Port Profile](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/aruba/radius-da_enf-prof_aoscx_coa_bounce-port_legacy.xml)

## Meraki
[Disconnect Message](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/meraki/radius-da-template_meraki_disconnect-message.xml)
> NOTE: You must have the [Meraki RADIUS dictionary](https://github.com/aruba/clearpass-radius-dynamic-authorization-templates/raw/master/meraki/radius-dictionary_meraki.xml) installed.

