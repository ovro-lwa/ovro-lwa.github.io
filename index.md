# OVRO-LWA Software

## Web Apps

Set up ssh tunnels to use web apps (ssh server/port tunnel shown in parentheses).

Operations and M&C apps:

[Web UI](http://localhost:9090) (webserveruiservice:9090) |
[Grafana](http://localhost:3000) (grafana:3000) |
[System Health Dashboard](http://localhost:5006/LWA_dashboard) (lxdlwacr:5006) |
[Low-Freq Sky](http://localhost:8081) (lwacalimhead:8081) |

Admin or defunct apps:

[MAAS](http://localhost:5240) (lxdlwamaas:5240) |
[Antenna Mapping](http://127.0.0.1:5007/?hip.load_uri=%22.%22&hip.filters=%5B%5D&hip.color_by=%22antnum%22&hip.PARALLEL_PLOT.order=%5B%22antnum%22%2C%22pola_fee%22%2C%22polb_fee%22%2C%22arx_address%22%2C%22pola_arx_channel%22%2C%22polb_arx_channel%22%2C%22snap2_hostname%22%2C%22pola_digitizer_channel%22%2C%22polb_digitizer_channel%22%5D) (lxdlwacr:5007) (table of mapping in System Health Dashboard) |
[LWASNAP](http://greghell.github.io/LWASNAP/) |


## Documentation

[mnc_python](https://ovro-lwa.github.io/mnc_python) |
[lwa-antpos](https://ovro-lwa.github.io/lwa-antpos) |
