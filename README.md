# TempMessage

A simple plugin for Equicord/Vencord that lets you send messages that automatically delete thyself after a set duration.

## Preview

![TempMessage preview](preview.gif)

## Installation

1. Clone the repo into your `userplugins` directory:
   ```
   git clone https://github.com/Sighyu/TempMessage.git
   ```
2. Navigate to the root Equicord/Vencord folder and run `pnpm build`.
4. Restart Discord with **Ctrl+R**.
5. Enable **TempMessage** in Settings → Plugins.

## Usage

Use the `/temp` slash command in any channel:

```
/temp message:<your message> duration:<time>
```

### Duration Format

| Unit | Symbol | Example |
|------|--------|---------|
| Seconds | `s` | `30s` |
| Minutes | `m` | `5m` |
| Hours | `h` | `2h` |
| Days | `d` | `1d` |
| Weeks | `w` | `4w` |
| Months | `M` | `1M` |


(no one will ever use weeks or months 💀)

Minimum duration is **1 second**.

## Example

```
/temp message:this message will delete in 10 min duration:10m
```

Sends the message and deletes it after 10 minutes.

