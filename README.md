# ROFI-MOJI

Use your [rofi](https://davedavenport.github.io/rofi/) launcher to
select from different ASCII<sup>1</sup> emoji and let `xdotool` type them for you.


### Screenshot

![Screenshot](/rofi-moji.png?raw=true)

### Installation

Copy `rofi-moj` to your `$PATH` and just add it to your regular Rofi
call:

```
rofi -modi 'window,ssh,run,emoji:rofi-moji'
```
---
[1] `ASCII`: **A**rti**s**an **C**ode (for) **I**rony **I**nterchange
