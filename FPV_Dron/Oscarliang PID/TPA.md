TPA
TPA stands for Throttle PID Attenuation.
https://oscarliang.com/pid-filter-tuning-blackbox/

6. Niższy TPA

Na karcie strojenia PID ustaw punkt przerwania TPA z 1350 na 1750, aby uniknąć problemów z maskowaniem oscylacji TPA przy niskiej/średniej przepustnicy podczas strojenia. Dostrój TPA na końcu, jeśli problemy z oscylacjami występują przy wysokiej przepustnicy, ale generalnie minimalizowałbym użycie TPA, kiedy tylko jest to możliwe.


To fine tune TPA, perform a throttle sweep and check the frequency vs. throttle heatmap. If you get oscillations above a certain throttle level, in which case TPA can help.

In the latest Betaflight it only attenuates D gain above certain throttle level (which is usually the cause of the oscillations). In the older Betaflight it attenuates both P and D, if you want you can bring this back by typing in CLI: set tpa_mode = PD.

Normally I prefer to set throttle value in TPA as high as possible, so D gain is more constant across a wider throttle range. Make sure to set the throttle value a little lower than the position where the D term related oscillations start to show up. For example, if oscillation starts around 1800 throttle, I would do something like this: TPA = 0.75, 1750.