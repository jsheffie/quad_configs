TURTLE MODE!!!!

Otherwise known as dshot commands.

I watched JB's vid on how to set this up.
https://www.youtube.com/watch?v=3LL2caB3r88

DSHOT commands: ( there are currently two of them )
   - beeper
   - flip over after crash ( turtle mode )

DSHOT -> BLHELI_S ( almost all blheli_s esc's support this feature )
      -> BLHELI_32 all esc's support this feature.

1: FC Support: you need to be running betaflight 3.2.0 RC5 or greater. ( I was running 3.1.7 forever )
2: BLHELI Support: flash esc's with firmware that supports for this feature.
3: Setup betaflight.
   1: modes: beeper
   2: modes: flip_over_after_crash


Usage:
  1: disarm quad
  2: enable turtle mode
  3: arm quad ( nothing happens )
  4: move alerion right -n- left.



My BF Setup things:
# diff
# Betaflight / BETAFLIGHTF3 3.1.7 Apr  3 2017 / 21:43:25 (e1c4b5c)
name jeffield

map TAER1234
serial 2 2048 115200 57600 0 115200
aux 0 0 0 900 1400
aux 1 28 0 900 1200
aux 2 4 0 900 1400
aux 3 13 1 900 1300
set min_throttle = 1045
set motor_pwm_protocol = MULTISHOT
set yaw_motor_direction = -1
set osd_vbat_pos = 2081
set osd_flytimer_pos = 2090
set osd_ontimer_pos = 2517
set osd_flymode_pos = 364
set osd_horizon_pos = 200
set osd_craft_name_pos = 2497
profile 0

rateprofile 0
rateprofile 0

set rc_rate = 139
set rc_rate_yaw = 139
set rc_expo = 35
set rc_yaw_expo = 35
set roll_srate = 78
set pitch_srate = 78
set yaw_srate = 78
