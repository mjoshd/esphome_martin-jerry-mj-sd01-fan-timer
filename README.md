# Martin Jerry Dimmer MJ-SD01 -> Exhaust Fan Timer

#### Info:

Offers 10, 20, 30, and 60 minute timers as well as an always-on mode.

Uses the LEDs to display time selection and turns off LEDs as remaining time decreases.

|Always-on|60m|30m|20m|10m||
|:---:|:---:|:---:|:---:|:---:|:---:|
|X|||||led 5|
||X||||led 4|
||X|X|||led 3|
||X|X|X||led 2|
|X|X|X|X|X|led 1|

<br>

While off, pressing any button will turn on power and start a 10 minute timer.

|Button|Tap while off|Tap while on|Long press while off or on|
|:---:|:---:|:---:|:---:|
|up|10m timer|increase timer|always-on/timer disabled**|
|down|10m timer|decrease timer|30 minute timer|
|power|10m timer|power-off||

Turning on from Home Assistant will start a 10 minute timer.

** The always-on mode can also be enabled by pressing the up/increase-timer button again after reaching the 60m setting. While always-on is enabled, pressing either the down/decrease-timer button or the power button will exit the always-on mode.

<br>

#### Device:

<img src="martin-jerry-mj-sd01-dimmer.jpg" alt="Martin Jerry Dimmer MJ-SD01" width="480" />


#### Links:

[1-pack (Amazon)](https://www.amazon.com/gp/product/B07FXYSVR1/ref=as_li_tl?ie=UTF8&tag=mjoshd-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B07FXYSVR1&linkId=9f97b952ef335b2d3f82b207eb8a27f1)

[2-pack (Amazon)](https://www.amazon.com/gp/product/B07HJSJ6VG/ref=as_li_tl?ie=UTF8&tag=mjoshd-20&camp=1789&creative=9325&linkCode=as2&creativeASIN=B07HJSJ6VG&linkId=66a66a0d5f5648cb25820c7cff62e0aa)

<br>

## Warning!!

**Only use this for low-power/energy-efficient fans! DO NOT connect this device to a heater, ever!**

*Be 100% certain that the connected load will not exceed the switch's limited power handling capabilities!*

Power handling capabilities can be found on the [Martin Jerry MJ-SD01 support page](https://www.martinjerry.com/sd01support) under the "Specifications:" section.

<br>

### Disclaimer

:warning: **DANGER OF ELECTROCUTION** :warning:

These devices are not toys. They use Mains AC so there is a danger of electrocution if not installed properly. If you don't know how to install it, please call an electrician. Remember: _**SAFETY FIRST**_. It is not worth to risk yourself, your family and your home if you don't know exactly what you are doing. Never try to connect a wire to flash a device while it is connected to MAINS AC.

We don't take any responsibility nor liability for using this software nor for the installation or any tips, advice, videos, etc. given by any member of this site or any related site.

```
Disclaimer borrowed from Tasmota github page.
```
