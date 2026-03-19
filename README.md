# OVPN-Configs-scraper

OVPN-Configs-scraper is a Node.js tool that automatically collects free OpenVPN configuration files from various public sources. It streamlines the retrieval, organization, and updating of these configs for quick use.

## Features
- Automated scraping of public VPN server lists.
- Generation of ready-to-use `.ovpn` files.
- IP address caching and duplicate management.
- Export of configurations to a dedicated folder.

> [!IMPORTANT]
> To deploy your own version, you can use the following section.
> PLEASE DO NOT FORK, OUR VERSIONS WILL DIFFER ANYWAYS.
> 
>  ## Prerequisites
>  - Node.js >= 20
>  - npm
>
>  ## Installation
>  ```bash
>  git clone https://github.com/your-username/OVPN-Configs-scraper.git
>  cd OVPN-Configs-scraper
>  npm install
>  ```
>
>  ## Build 
>  Before running the app, you need to build the TypeScript source files:
>  ```bash
>  npm run build
>  ```
>  This will compile the TypeScript code into JavaScript in the `dist/` directory.
> 
>  ## Usage
>  To run the scraper and update the configuration files:
>  ```bash
>  npm start
>  ```

> [!TIP]
> The generated `.ovpn` files can be found in the `data/configs/` folder.

## Download VPN Configurations
You can directly download the generated configuration files:

- [Go to the configs/ folder](./data/configs/)

Or download individually:

### Japan
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 49.129.176.235 | Japan | BIGLOBE Inc. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/49.129.176.235.ovpn) |
| 118.106.208.237 | Japan | Chubu Telecommunications Company, Inc. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/118.106.208.237.ovpn) |
| 118.154.9.31 | Japan | DION (KDDI CORPORATION) | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/118.154.9.31.ovpn) |
| 119.173.41.175 | Japan | JCOM Co., Ltd. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/119.173.41.175.ovpn) |
| 106.153.16.152 | Japan | Kddi Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/106.153.16.152.ovpn) |
| 219.100.37.190 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.190.ovpn) |
| 219.100.37.21 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.21.ovpn) |
| 219.100.37.194 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.194.ovpn) |
| 219.100.37.9 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.9.ovpn) |
| 219.100.37.89 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.89.ovpn) |
| 219.100.37.191 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.191.ovpn) |
| 219.100.37.175 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.175.ovpn) |
| 219.100.37.198 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.198.ovpn) |
| 219.100.37.64 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.64.ovpn) |
| 219.100.37.180 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.180.ovpn) |
| 110.67.166.58 | Japan | Sony Network Communications Inc | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/110.67.166.58.ovpn) |
| 58.87.159.114 | Japan | Sony Network Communications Inc | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/58.87.159.114.ovpn) |
| 131.147.203.90 | Japan | Sony Network Communications Inc. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/131.147.203.90.ovpn) |


### South Korea
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 61.96.71.28 | South Korea | CCS | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/61.96.71.28.ovpn) |
| 221.167.26.145 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/221.167.26.145.ovpn) |
| 59.26.33.152 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/59.26.33.152.ovpn) |
| 14.37.134.238 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/14.37.134.238.ovpn) |
| 169.212.0.150 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/169.212.0.150.ovpn) |
| 125.134.140.215 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/125.134.140.215.ovpn) |
| 14.34.3.130 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/14.34.3.130.ovpn) |
| 210.204.209.200 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/210.204.209.200.ovpn) |
| 118.130.207.150 | South Korea | LG DACOM Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/118.130.207.150.ovpn) |
| 182.226.193.203 | South Korea | LG POWERCOMM | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/182.226.193.203.ovpn) |
| 1.229.239.249 | South Korea | SK Broadband Co Ltd | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/1.229.239.249.ovpn) |
| 116.121.181.6 | South Korea | SK Broadband Co Ltd | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/116.121.181.6.ovpn) |
| 211.108.98.234 | South Korea | SK Broadband Co Ltd | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/211.108.98.234.ovpn) |


### Thailand
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 184.22.223.79 | Thailand | AIS-Fibre | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/184.22.223.79.ovpn) |


### United States
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 47.229.3.127 | United States | Charter Communications | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/47.229.3.127.ovpn) |
| 72.199.208.164 | United States | Cox Communications Inc. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/72.199.208.164.ovpn) |
| 47.188.213.188 | United States | Frontier Communications Solutions | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/47.188.213.188.ovpn) |


### Vietnam
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 183.91.4.152 | Vietnam | CMC Telecom Infrastructure Company | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/183.91.4.152.ovpn) |
| 113.22.36.1 | Vietnam | FPT Telecom Company | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/113.22.36.1.ovpn) |
| 42.119.192.226 | Vietnam | FPT Telecom Company | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/42.119.192.226.ovpn) |

> **Tip**: For the full list, check the `data/configs/` folder after running the scraper.


## Contributing
Contributions are welcome! Feel free to open an issue or a pull request.

## License
MIT

