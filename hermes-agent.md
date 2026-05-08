````md
# 📁 Hermes Configuration & Data Locations

All your files are stored in `~/.hermes/`:

| Type | Path |
|---|---|
| **Settings** | `/home/ubuntu/.hermes/config.yaml` |
| **API Keys** | `/home/ubuntu/.hermes/.env` |
| **Data** | `/home/ubuntu/.hermes/cron/`, `sessions/`, `logs/` |

---

# 📝 Editing Your Configuration

## Setup Commands

```bash
hermes setup
````

Re-run the full setup wizard.

```bash
hermes setup model
```

Change model/provider.

```bash
hermes setup terminal
```

Change terminal backend.

```bash
hermes setup gateway
```

Configure messaging.

```bash
hermes setup tools
```

Configure tool providers.

---

## Configuration Commands

```bash
hermes config
```

View current settings.

```bash
hermes config edit
```

Open config in your editor.

```bash
hermes config set <key> <value>
```

Set a specific configuration value.

---

## Edit Files Directly

```bash
nano /home/ubuntu/.hermes/config.yaml
nano /home/ubuntu/.hermes/.env
```

---

# 🚀 Ready to Go

```bash
hermes
```

Start chatting.

```bash
hermes gateway
```

Start the messaging gateway.

```bash
hermes doctor
```

Check for issues.

```
```
