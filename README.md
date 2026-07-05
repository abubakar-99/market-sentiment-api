# market-sentiment-api

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python) ![License](https://img.shields.io/badge/License-MIT-green) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Aggregates Twitter and Reddit sentiment per ticker via NLP.

## Overview

This tool provides a production-ready implementation focused on performance, security, and developer experience. Built with modern best practices and designed for real-world deployment.

## Features

- **High performance** — optimized for low latency and high throughput
- **Production ready** — proper error handling, logging, and observability
- **Well tested** — unit and integration tests included
- **Easy to deploy** — Docker support out of the box

## Installation

```bash
git clone https://github.com/abubakar-99/market-sentiment-api
cd market-sentiment-api
pip install -r requirements.txt
```

## Usage

```bash
python src/main.py --help
```

## Architecture

```
market-sentiment-api/
├── src/
│   ├── main.py
│   ├── core/
│   └── utils/
├── tests/
├── docs/
├── Dockerfile
└── README.md
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

[MIT](LICENSE)
