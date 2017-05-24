I had this issue...
on throttle punches the quad would sometimes 
'Drop a wing'
Basically I would flip upside down... like some motor stopped spinning momentairly.
This did not happen all the time, and appeard to happen after several packs of flying
( seemed that warmed up hw would induce the behavior more readily )

I tried many things to fix the issue.

- First I thought the issue was a prop striking the top-mounted battery.
  - rebuilt quad from xhover -> xhover-lx to give more prop clearance
  - later mounted the battery on the bottom to re-verify there was not a prop strike situation.

- My motors Cobra 2204/2300 were a big long in the tooth... I thought I might have
an sticky bearing.
  - bought new motors ( Brother Hobby Returners/ 2206/2300)
    - this did not fix the issue... but I noticed shorter flight times ( with RaceCraft 5051's and much easier to punch out and float.)

Final Theory of issue:
 - esc / fc syncing issues. ( Running RotorGeeks RG20 1st generation )
   https://docs.google.com/document/d/1Vzx0GOiOd8FpSVPJjsDBqIWdzaWQaSt4fslR2xnTT_w/edit?usp=sharing

 - Steps to fix:
   - Update the ESC firmware 14.1 -> 14.85 
     - use multishot vice oneshot125

   - I want zero gravity mode so I am also going to update from 
     bf 3.1.6 -> Latest ( )