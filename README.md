# homebridge-sensibo-ac
[Homebridge](https://github.com/nfarina/homebridge) plugin for Sensibo Sky - Smart AC Control

Complies with ```Service.HeaterCooler``` (AC)

`min node version required: 10.17`<br>
`min homebridge version required 0.4.0`

check with:
`node -v` & `homebridge -V`
<br>and update if needed

# Installation

1. Install homebridge using: `sudo npm install -g homebridge`
2. Install this plugin using: `sudo npm install -g homebridge-sensibo-ac`
3. Update your configuration file. See `sample-config.json` in this repository for a sample.

**install from git (latest version): `sudo npm install -g https://github.com/nitaybz/homebridge-tado-ac.git`


## Config file

#### Easy config:
```
"platforms": [
    {
        "platform": "SensiboAC",
        "apiKey": "*************"
    }
]
```

#### Advanced config:
```
"platforms": [
    {
        "platform": "SensiboAC",
        "apiKey": "*************",
        "disableFan": false,
        "disableDry": false,
        "enableSyncButton": true,
        "debug": true
    }
]
```
