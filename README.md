# DSH Operit Plugins

Operit-compatible tool plugins for the DeepSeek Harness (DSH) mobile agent platform.

## Plugins

| File | Description |
|---|---|
| `time.js` | Current time helper |
| `system_tools.js` | System operations: settings management, app install/uninstall & launch, notifications, location, device info, Intent/broadcast execution |
| `extended_file_tools.js` | Extended file operations |
| `extended_http_tools.js` | Extended HTTP helpers |

Each file is self-contained, embeds its own metadata (name, display name, description, tool schema) in a header comment, and can be loaded directly as an Operit / DSH plugin.

## License

MIT
