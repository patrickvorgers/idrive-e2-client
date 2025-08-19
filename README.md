# idrive-e2-client

[![PyPI version](https://img.shields.io/pypi/v/idrive-e2-client.svg)](https://pypi.org/project/idrive-e2-client/)
[![Python versions](https://img.shields.io/pypi/pyversions/idrive-e2-client.svg)](https://pypi.org/project/idrive-e2-client/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Async Python client for the  
[IDrive e2 Get Region Endpoint API](https://www.idrive.com/s3-storage-e2/guides/get_region_endpoint).  

This library provides a small, typed wrapper around the IDrive e2 region lookup call:

- 🔑 Fetch the correct **endpoint URL** for an access key  
- 🚦 Handle invalid credentials and network errors with clean exceptions  
- ⚡ Async-first design, built on `aiohttp`  

It is lightweight, minimal, and used by the [Home Assistant](https://www.home-assistant.io/) backup integration for IDrive e2.

---

## Install

```bash
pip install idrive-e2-client
