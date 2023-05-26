# i3 config for ubuntu

## Packages required

- spotifyctl
- pulseaudio
- install the spotify bar app: https://github.com/rpieja/i3spotifystatus
- optional: blueman, thunar

## Things to modify

- i3status: change the pulse device to yours:

```bash
$ pacmd list-sinks | grep name:
  name: <alsa_output.pci-0000_00_14.2.analog-stereo>
```
- lock screen: move the `lock` script in `.config/scripts/`

## Inspo

- man i3status
- [Theme](https://draculatheme.com/i3)
- [Good Tutorial](https://itsfoss.com/i3-customization/)
