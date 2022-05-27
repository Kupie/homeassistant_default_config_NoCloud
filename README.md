# homeassistant_default_config_NoCloud
a mod of the "default_config" integration for Home Assistant, minus the "Cloud" portion

## Installation:

#### wget the files after SSH-ing into your home assistant container and put them into <config_dir>/custom_components/default_config_nocloud:
```
mkdir -p /config/custom_components/default_config_nocloud
cd /config/custom_components/default_config_nocloud
wget https://raw.githubusercontent.com/Kupie/homeassistant_default_config_NoCloud/main/__init__.py
wget https://raw.githubusercontent.com/Kupie/homeassistant_default_config_NoCloud/main/__init__.py
```

#### Modify configuration.yaml to have "default_config_nocloud:" instead of "default_config:" like so:
```
# Loads default set of integrations. Do not remove.
#default_config:
default_config_nocloud:
```

#### Restart Home Assistant and you should no longer have cloud integrations loaded.

