FPVCHAT: ( 2017.07.05 )
not sure if this is hardware issue, or software issue.... ( is this i-term windup?) https://youtu.be/U2BJSuDS0Ls?t=23s
I think my next step is to put a cap on the FC ( I am running a unify-pro and if I bump it to 500mw I get pulsing lines... so I just run it at 200mw and ran 15 packs through it yesterday with no issues ) 
I am running betaflight 3.1.7 and PT1 and gyro notch 1 and 2 are off ... in fact here is my config https://github.com/jsheffie/quad_configs/blob/master/flight_controller/bff3_board/corgette/corgette1.config
Every time I start to get some self-confidence in this hobby/sport I get smacked-down... into the top of a tree no-less with crazy shit like this.
Note: all motor bolts were tight...  ( I am softmounting motors and fc ) ... lets see... motors... are the lumenier 2206/2300 and the esc's are Lumenier 30A blheli 2-4s ( running 4s 1300)... multishot. I am hoping the FC cap is the way to go... any help is much appreciated.

Changes:
 - checked receiver wireing, visually ... good.
 - FC cpu was at 35% ... turned off accel and now down to 25%
 - turned back on the PT1 filtering i.e. gyro notch1 back to 400 and gyro notch 2 back to 200
### - changed the esc protocol from multishot -> dshot
   ( note: should have re-set the esc's ... betaflight -> motors -> switch -> full throttle -> plug in battery -> pull throttle all the way down)
- props off
- power on
- shake the living fuck out of it, and listen for tunes
- reflash esc's
- re-calibrate esc's ( w/ multishot )
n if all of that fails... gona try dshot.

- Think I fixed the above issue
  - re-flashed to the latest version of the firmware and ran multishot on it ( note the last 2 releases of the firmware say dshot in the name 
so I skiped thme before ) 
  - re-calibrated esc's in betaflight.

Note: also noted wavy lines in video at 500mw output power.

