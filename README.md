<br />
<p align="center">
  <h3 align="center">Go-amino</h3>

Core library for aphelion and SDK. Used for base ledger working and state transitions.

<b>Halt Status:</b> In-production: Libonomy Mainnet

</p>

## Getting Started

Follow the instructions below to run the project locally.

## Prerequisites

Make sure you have the following installed:

- **GO**

  Install GO from:

  ```sh
  https://go.dev/doc/install
  ```

  ⚠️ **Supported GO version:** `1.12`


## Installation

1. **Clone the repository**

2. **Navigate to the project directory**

3. **Install dependencies**

```sh
go mod tidy
```

### To make the build
```sh
make install
```

### For starting the build
```sh
./BUILD_NAME
```

Once started, the amino serialization can be seen. This is a sub-module and mainly used inside cusp-sdk for serialization of transactions.

```
Copyright © 2025 — Libonomy
```