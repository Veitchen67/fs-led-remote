# FS-LED Remote

Web Bluetooth remote for the "FS-LED" board (PSoC 62S2 + CYW43439, CY8CKIT-062S2-AI).

Open https://veitchen67.github.io/fs-led-remote/ in Chrome on Android
(Bluetooth and location on), tap **Connect to FS-LED**, then **Toggle LED mode**.

- Shows the current LED mode (BLE notifications of the "Mode" characteristic).
- "Toggle LED mode" writes `0x01` to the "Command" characteristic = same as pressing
  the user button on the board.

`index.html` is a copy of `webapp/index.html` from the (private) firmware project.
