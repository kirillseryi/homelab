# HomeLab

A collection of `compose.yaml` files that I'm using at my homelab.

## Table of Contents

- [HomeLab](#homelab)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [List of services](#list-of-services)
  - [Contributors](#contributors)
  - [License](#license)
  - [Badges](#badges)
  - [GitHub Repository](#github-repository)

## Installation

Make sure that you already have both **Docker** and **Docker-Compose** installed.

## Usage

Copy either whole repository or a separate service folder, which contains `compose.yaml` file and, optionally, some additional configuration files.  
Don't forget to create and populate an `.env` file if you see that any environment variables are mentioned in `compose.yaml` (it usually looks like `${something}`).  
After copying the files just run `docker-compose up -d` command in a directory with `compose.yaml` file and let the magic begin.

> ⚠️ All services are configured to run on a separate network. Take that into account if you're going to run any of them separately.

## List of services

| Service name                                            | Port                                   |
| :------------------------------------------------------ | :------------------------------------- |
| [Airflow](./airflow-compose/)                           | `8080`                                 |
| [Arrs](./arrs-compose/)                                 | see `compose.yaml` file content        |
| [Budibase](./budibase-compose/)                         | `10000`                                |
| [Change detection](./changedetection-compose/)          | `5000`                                 |
| [Code server](./code-server-compose/)                   | `8493`                                 |
| [Homepage](./homepage-compose/)                         | `55201`                                |
| [Karakeep](./karakeep-compose/)                         | `3000`                                 |
| [Metabase](./metabase-compose/)                         | `15923`                                |
| [Minio](./minio-compose/)                               | `9001`                                 |
| [n8n](./n8n-compose/)                                   | `5678`                                 |
| [Newt](./newt-compose/)                                 |                                        |
| [Omni tools](./omni-tools-compose/)                     | `21020`                                |
| [Pinchflat](./pinchflat-compose/)                       | `8945`                                 |
| [Plex](./plex-compose/)                                 | `32400`                                |
| [Postgres](./postgres-compose/)                         | PostgreSQL: `27743`<br>Adminer: `27744`|
| [Sabnzbd](./sabnzbd-compose/)                           | `8080`                                 |
| [Stirling PDF](./stirling-pdf-compose/)                 | `19838`                                |
| [Streamlit ChatGPT](./streamlit-chatgpt-clone-compose/) | `8501`                                 |
| [VPN Project](./vpnproject-compose/)                    | Qbittorrent: `8090`                    |
| [Watchtower](./watchtower-compose/)                     |                                        |

## Contributors

- [kirillseryi](https://github.com/kirillseryi).

## License

This project is licensed under the MIT License License - see the [LICENSE](LICENSE) file for details.

## Badges

[![GitHub stars](https://img.shields.io/github/stars/HomeLab)](https://github.com/kirillseryi/HomeLab/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HomeLab)](https://github.com/kirillseryi/HomeLab/network/members)
[![GitHub issues](https://img.shields.io/github/issues/HomeLab)](https://github.com/kirillseryi/HomeLab/issues)
[![GitHub license](https://img.shields.io/github/license/HomeLab)](https://github.com/kirillseryi/HomeLab/blob/master/LICENSE)

## GitHub Repository

[Link to GitHub repository](https://github.com/kirillseryi/HomeLab)
