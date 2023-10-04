# FWS API Gateway

The `fws-api-gateway` serves as the entry point for all Flood Warning System API requests. It utilizes Nginx to efficiently route incoming requests to the correct internal service.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Configuration](#configuration)
- [Logging](#logging)
- [Contributing](#contributing)
- [License](#license)

## Overview

As the main gateway, this service is critical in directing traffic, handling load balancing, and ensuring that requests reach their intended destinations such as authentication, information retrieval, or data fetching components of the FWS.

## Prerequisites

- Docker
- Docker Compose (optional)

## Setup

1. Clone the repository:
```bash
git clone [repository-url]