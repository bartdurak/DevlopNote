Dynamic Idle
Dynamic Idle improves stability, enhances propwash handling, and reduces the chance of ESC desync. It increases motor speed when the throttle is at zero, improving control authority and responsiveness at low throttle inputs. Other benefits include sharper flip and roll stops, more responsive in low throttle and more effective braking.

When Dynamic Idle is set, Static Motor Idle (in %)  in the Motors tab is disengaged.

To setup Dynamic Idle, you need to

Enable bi-directional DShot in the Motor Tab (if you already have RPM filter enabled, you are all set)
Enter a suitable Idle RPM value in the PID Tuning page (e.g., 20 to 40 for 5″ drones).
The recommended Idle RPM value depends on propeller size and pitch. Smaller and lower pitch propellers generally require higher values. Adjust the value higher in windy conditions to counteract instability.

Prop Sizes	High Pitch Props	Low Pitch Props
31mm/1.2″	84	167
40mm/1.6″	62	124
2″	50	100
2.5″	40	80
3″	33	66
3.5″	28	57
4″	25	50
5″	20	40
6″	16	33
7″	14	28
8″	12	25
10″	10	20
Considerations for Dynamic Idle:
![[Pasted image 20241102151829.png]]