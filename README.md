# OpenDigger Panel

A lightweight, single-file dashboard for visualizing open source project metrics powered by [OpenDigger](https://www.open-digger.cn/).

## Features

- **OpenRank & Activity Trend** - Time series charts with monthly/quarterly/yearly granularity
- **Stars, Contributors, Issues, Code Changes** - Key project health indicators
- **Health Score** - Weighted composite score (OpenRank + Activity + Bus Factor + New Contributors + Issue Close Rate)
- **Multi-Repo Compare** - Compare up to 6 repositories side by side
- **GitHub / Gitee** - Supports both platforms

## Live Demo

https://hnwyllmm.github.io/opendigger-panel/

## Usage

Open `opendigger-dashboard.html` directly in a browser, or serve it via any static HTTP server:

```bash
python3 -m http.server 8080
# Then visit http://localhost:8080
```

## Data Source

All data is sourced from [OpenDigger](https://www.open-digger.cn/), a free open source analytics platform. No authentication required.

## License

[MIT](./LICENSE)
