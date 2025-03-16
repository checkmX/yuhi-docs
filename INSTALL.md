# Yuhi installation

## Requirements

- **iPhone 7** or other device compatible with checkm8.

- Computer with Linux.

- **Downloaded files** from the Releases section in this repo:

- `Yuhi.bin`

- `Pongo.bin`

- `loader` (will be available in GitHub releases).

- Installed **palera1n**.

---

## 1. Transferring the device to DFU

### For iPhone 7:

1. Turn off the device.

2. Wait **10 seconds** until the phone turns off completely.

3. Press the **down volume button + lock button** and hold **10 seconds**.

4. Release the screen lock button, but continue to hold the **volume button down** until a notification about the connected USB device appears on the computer (**about 5-10 seconds**).

---

## 2. Launch PongoOS

Execute the command:

palera1n -vpk [path to Pongo.bin]

## 3. Launch Yuhi

Execute the command:

printf '/send [path to Yuhi.bin]\nbootm\n' | sudo [path to loader]

## 4. Open Telnet connection

Execute the command:

telnet 172.16.42.1

