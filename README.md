# Linux Bash Notifications

```bash
  notify-send "Hello World"
  notify-send "Title" "Message"
  notify-send -t 3000 "My message" "This is my message"
  notify-send -t 1000 "My message" "This is my message"
  notify-send --icon=phone -t 5000 "My message" "This is my message"
  notify-send --icon=audio-input-microphone -t 5000 "My Message" "This is my message"
  notify-send --icon=/usr/share/icons/Yaru/scalable/status/printer-error-symbolic.svg -t 5000 "My Message" "This is my message"
  notify-send --icon=/usr/share/icons/Adwaita/scalable/devices/audio-headphones-symbolic.svg -t 5000 "My Message" "This is my message"
```

```bash
  man notify-send
```

### Grab `*.svg` files

```bash
  find /usr/share/icons -iname "*.svg"
```
