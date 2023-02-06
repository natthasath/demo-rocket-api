# 🎉 DEMO Rocket API

Rocket API is a fast and simple web framework for building and deploying REST APIs in Rust programming language, providing a flexible and expressive platform for delivering robust and scalable web services.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### ⚓ Developer Tool

- rustup
- cargo

### 🚀 Setup

```shell
cargo init
cargo add rocket@0.5.0-rc.2 --features json
cargo add serde --features derive
cargo add chrono --features serde
cargo add uuid --features v4
cargo install cargo-watch
```

### 🏆 Run

```shell
cargo watch -q -c -w src/ -x run
```