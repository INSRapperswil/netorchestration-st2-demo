# netorchestration-st2-demo

## Requirements

- Install pack [NAPALM](https://github.com/StackStorm-Exchange/stackstorm-napalm)
- Configure NAPALM `/opt/stackstorm/configs/netbox.yaml`
- Install pack [NETBOX](https://github.com/StackStorm-Exchange/stackstorm-netbox)
- Configure NETBOX `/opt/stackstorm/configs/netbox.yaml`

- Network devices
  - Enable restconf
  - Configure MPLS-L3VPN
  - Setup netbox

## Installation

- Install this pack
- Configure username and password for restconf `/opt/stackstorm/configs/netorchestration-st2-demo`


## Workflows

- Create VLAN
- Create VRF
- Create SVI

## Rules

- Webhook create vlan
- Webhook create vrf
- Webhook create svi
