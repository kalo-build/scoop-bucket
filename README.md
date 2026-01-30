# Scoop Bucket for Kalo

This is the official Scoop bucket for [Kalo CLI](https://github.com/kalo-build/kalo-cli).

## Installation

```powershell
# Add the bucket (one-time setup)
scoop bucket add kalo https://github.com/kalo-build/scoop-bucket

# Install
scoop install kalo
```

## Update

```powershell
scoop update kalo
```

## Uninstall

```powershell
scoop uninstall kalo
scoop bucket rm kalo  # optional
```

## Available Apps

| App | Description |
|-----|-------------|
| `kalo` | Kalo CLI - Plugin-based code generation and database management |

## About Kalo

Kalo CLI is a modern tool for running atomically composable specification (Morphe, OpenAPI, ...) compilation plugins using WebAssembly (WASM). It enables seamless compilation of schemas across different formats through a flexible plugin system.

Learn more at [github.com/kalo-build/kalo-cli](https://github.com/kalo-build/kalo-cli)
