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
| 115.179.206.241 | Japan | ARTERIA Networks Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/115.179.206.241.ovpn) |
| 113.154.67.10 | Japan | DION (KDDI CORPORATION) | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/113.154.67.10.ovpn) |
| 111.106.171.215 | Japan | Kddi Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/111.106.171.215.ovpn) |
| 118.156.137.250 | Japan | Kddi Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/118.156.137.250.ovpn) |
| 220.153.62.215 | Japan | Kintetsu Cable Network Co., Ltd. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/220.153.62.215.ovpn) |
| 220.254.220.117 | Japan | Naganoken Kyodou Densan Co.Ltd. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/220.254.220.117.ovpn) |
| 180.57.87.157 | Japan | NTT Communications Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/180.57.87.157.ovpn) |
| 153.192.201.62 | Japan | NTT Communications Corporation | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/153.192.201.62.ovpn) |
| 110.163.129.171 | Japan | NTT DOCOMO, INC. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/110.163.129.171.ovpn) |
| 60.108.251.162 | Japan | SoftBank Corp. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/60.108.251.162.ovpn) |
| 60.151.213.105 | Japan | SoftBank Corp. | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/60.151.213.105.ovpn) |
| 219.100.37.64 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.64.ovpn) |
| 219.100.37.224 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.224.ovpn) |
| 219.100.37.124 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.124.ovpn) |
| 219.100.37.117 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.117.ovpn) |
| 219.100.37.56 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.56.ovpn) |
| 219.100.37.102 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.102.ovpn) |
| 219.100.37.182 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.182.ovpn) |
| 219.100.37.192 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.192.ovpn) |
| 219.100.37.162 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.162.ovpn) |
| 219.100.37.3 | Japan | SoftEther | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/219.100.37.3.ovpn) |
| 118.240.3.52 | Japan | Sony Network Communications Inc | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/118.240.3.52.ovpn) |
| 110.67.14.151 | Japan | Sony Network Communications Inc | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/110.67.14.151.ovpn) |


### South Korea
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 114.199.13.90 | South Korea | Green Cable Television Station | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/114.199.13.90.ovpn) |
| 221.155.188.2 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/221.155.188.2.ovpn) |
| 210.100.131.144 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/210.100.131.144.ovpn) |
| 119.200.143.121 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/119.200.143.121.ovpn) |
| 121.130.211.67 | South Korea | Korea Telecom | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/121.130.211.67.ovpn) |
| 182.213.78.216 | South Korea | LG POWERCOMM | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/182.213.78.216.ovpn) |
| 125.191.219.154 | South Korea | LG POWERCOMM | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/125.191.219.154.ovpn) |
| 116.43.160.131 | South Korea | LG POWERCOMM | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/116.43.160.131.ovpn) |
| 1.224.195.110 | South Korea | SK Broadband Co Ltd | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/1.224.195.110.ovpn) |


### Thailand
| IP | Country | ISP | Provider | Config |
|---|---|---|---|---|
| 27.130.119.129 | Thailand | Triple T Broadband Public Company Limited | VPNGate | [Download](https://raw.githubusercontent.com/fox3000foxy/OVPN-Configs-scraper/refs/heads/main/data/configs/27.130.119.129.ovpn) |

> **Tip**: For the full list, check the `data/configs/` folder after running the scraper.


## Contributing
Contributions are welcome! Feel free to open an issue or a pull request.

## License
MIT

