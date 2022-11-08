# Update NEW realease Erigon [v2.29.0](https://github.com/ledgerwatch/erigon/releases/tag/v2.29.0) + lighthouse [v3.2.1](https://github.com/sigp/lighthouse/tree/v3.2.1)
![Copy of Copy of Copy of Staking is live](https://user-images.githubusercontent.com/90826754/200572250-6746122b-2dc4-4825-807c-4142ce2cef12.png)

- officail Github page Erigon [here](https://github.com/ledgerwatch/erigon)
- officail Github page lighthouse [here](https://github.com/sigp/lighthouse)

*NOTE!: use one of the scripts bellow: 1.for the first installation or 2.for update to the new version*

## 1. Installation Erigon v2.29.0 + lighthouse v3.2.1
```
wget -O erigon.sh https://raw.githubusercontent.com/papadritta/erigon_lighthouse/main/erigon.sh && chmod +x erigon.sh && ./erigon.sh
```
## 2. Update to Erigon v2.29.0 + lighthouse v3.2.1
>works only if you use installation script above with different version of Erigon & Lighthouse
```
wget -O erigon.v2.29.0.sh https://raw.githubusercontent.com/papadritta/erigon_v2.29.0/main/erigon.v2.29.0.sh && chmod +x erigon.v2.29.0.sh && ./erigon.v2.29.0.sh
```
## 3. Check status & logs
- Erigon
```
sudo systemctl status erigon
sudo journalctl -fu erigon
```
- Lighthouse
```
sudo systemctl status lighthousebeacon
sudo journalctl -fu lighthousebeacon
```
ALL DONE!
