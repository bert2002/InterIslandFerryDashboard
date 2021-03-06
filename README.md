# Inter Island Ferry Dashboard

A dashboard for Inter Island Ferries in Hong Kong.

# How to access

Open a browser and enter following internet address.

https://bert2002.github.io/InterIslandFerryDashboard/

# Parameters

You can change the behavior of the website by adding parameters to the url. The following parameters are available:

| Parameter | Default | Allowed | Description |
|-----------|---------|---------|-------------|
| ferry| PengChauToCentral |  | Defines which ferry schedule to be shown. This can be a comma separated list |
| instagram | pengchau | | Show images based on the tag |
| maxferry | 3 | 1..100 | Show next X ferries |
| sunrise | 0 | 1 | Show sunrise and sundown time |
| wind | 1 | 0 | Show wind speed |
| temperature | 1 | 0 | Show temperature |
| humidity | 0 | 1 | Show humidity |

## Example

1. Show Peng Chau to Discovery Bay ferry and instagram images tagged with discoverybayhk.

https://bert2002.github.io/InterIslandFerryDashboard/?&ferry=PengChauToDiscoveryBay&instagram=discoverybayhk

2. Show additionally wind and humidity

https://bert2002.github.io/InterIslandFerryDashboard/?&wind=1&humidity=1

3. Show multiple ferry schedules

https://bert2002.github.io/InterIslandFerryDashboard/?&ferry=PengChauToCentral,PengChauToDiscoveryBay

`Note:` Up to 4 schedules can be shown.

# Ferry Schedules

* Peng Chau to Central (PengChauToCentral)
* Peng Chau to DiscoveryBay (PengChauToDiscoveryBay)

* Central to Peng Chau (CentralToPengChau)

# Screenshot

![Example](https://raw.githubusercontent.com/bert2002/InterIslandFerryDashboard/master/screenshot/screenshot.png)

# Plugins

WIP
