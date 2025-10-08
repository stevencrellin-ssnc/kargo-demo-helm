# Kargo Demo - Helm Charts Repository

This repository contains Helm charts for the Kargo demo:

- `guestbook/` - Simple guestbook application
- `hello-world/` - Simple hello-world application

## Usage

```bash
helm install guestbook ./guestbook
helm install hello-world ./hello-world
```

## Kargo Integration

This repository is watched by Kargo Warehouses that create Freight whenever changes are committed.
