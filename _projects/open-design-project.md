---
layout: project
title: Open Design Project (Adjustable Netting Post)
description: Telescoping trellis post for efficient insect netting management during vineyard harvest
technologies: 
image: /assets/images/vine_v2.png
---

## Table of Contents

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)
---

# Client Pitch

**Team:** FABulous engineers who make lanternflies DI  
**Clients:** Cornell CALS Extension / E&J Gallo Winery / National Grape

### Problem Statement

Research has shown that over-the-row insect netting can reduce SLF population by up to 99.8%. This netting has a 6×1.8mm mesh and must be secured on the bottom and sides of the row. This solution is not perfect, however. The netting must be removed before harvest and reapplied after. Not only is this process labor-intensive, it leaves the grape plants unprotected before and during harvest. It must also be noted that pesticides cannot be used for a certain interval before harvest. There are other styles of netting — such as side netting — which allow hand-harvesting without complete removal of the netting. However, side netting is not as effective at protecting against SLF in comparison to over-the-row netting.

### Impact

Despite its potential effectiveness at protecting grape vines, very fine mesh has seen limited use. Large-scale vineyards are unable to efficiently use small-scale, drape-over-the-vine nets because of the significant time and labor required in installation and removal. If this process is made more efficient, more vineyards could use this fine mesh to prevent lanternflies from accessing the vines.

### Proposed Direction

**Concept: Adjustable Netting Post**

**What it is:** The Adjustable Netting Post is a method of efficiently raising and lowering over-the-row insect netting during harvest. It is a telescoping post which can extend roughly 4 feet, allowing for over-the-row netting to be raised before harvest.

**How it would be used:** Each modified trellis post is extendable. Over-the-row netting is then installed over the trellis. When the vines are ready for harvest, workers can extend the poles nearest to them, raising the netting. They can then harvest grapes and lower the Adjustable Netting Posts behind them.

**Why it's better than the status quo:**
- Eliminates need to fully uninstall and reinstall SLF nets before and after harvest
- Eliminates period of vulnerability to SLF damage while nets are down
- Can eventually be adapted to work for machine harvesting as well

**End-of-semester proof-of-concept:** Full-sized telescoping post + net and demonstrated functionality.

### Key Risks / Unknowns

**Tangle Risk** — Nets can tangle in the vines or on the post itself, damaging vines and increasing difficulty of operation. *Test:* Trials removing the nets from various bushes.

**Ground-Net Gap** — Attaching the net to the bottom of the post may create a gap between the net and the ground, lowering the system's effectiveness. *Test:* Minimize gap + do research.

**Post Accessibility** — Inability to easily access the posts for raising/lowering would defeat the system's purpose of saving labor. *Test:* Measure time required to raise/lower post.

### Questions for the Client

1. How often do you use hand harvesting (as opposed to using harvesters)?  
   *Decision affected:* Focus on hand harvesting in our design.
2. At what height on the vines do your variety of grapes grow?  
   *Decision affected:* Height post needs to extend to.
3. If you utilize netting, what is your typical process for installation/removal?  
   *Decision affected:* Overall design direction.

### References

- Leach, Heather & Mariani, Tom & Centinari, Michela & Urban, Julie. (2023). Evaluating integrated pest management tactics for spotted lanternfly management in vineyards. *Pest Management Science*, 79. [doi:10.1002/ps.7528](https://doi.org/10.1002/ps.7528)
- [Spotted Lanternfly Management in Vineyards — Penn State Extension](https://extension.psu.edu/spotted-lanternfly-management-in-vineyards)
- [Cornell Research on SLF Netting — Facebook Video](https://www.facebook.com/Cornell/videos/cornell-research-led-by-gavin-sacks-is-helping-ej-gallo-winery-in-modesto-califo/1700985444195723/)

---

# Functional Prototype

**Group R2**

### Purpose

The functional prototype tests the core telescoping mechanism of the Adjustable Netting Post. The goal was to validate that the pole can extend and retract smoothly, lock securely at full height, and require a reasonable amount of force to operate — all critical requirements for vineyard use.

### Bill of Materials

| Name | Description | Specs | Fabrication Details |
|------|-------------|-------|---------------------|
| Outer Tube | Cardboard tube from McMaster package | OD: 106mm, ID: 104mm, Length: 1.96m | Cut a 54″ slot ~1″ thick; cut a J at the top; cut hole in back for handle; attach pulley |
| Inner Tube | Cardboard tube from McMaster package | OD: 81mm, ID: 79mm, Length: 1.96m | Cut 2 holes opposite each other for handle to pass through at bottom |
| Pulley | 3D-printed PLA pulley for lifting & locking mechanism (outer casing, side supports, center axis, pulley wheel) | ~60×60mm, pulley diameter ~20mm | Side supports epoxied to outer tube; screw attaches center axis to outer tube |
| Rope | Nylon thread for pulley (scavenged) | Arbitrary length (≥190cm) | Tie to handle, slide through pulley |
| Handle | Wooden handle for raising & lowering | 95×81mm rectangle + 105×20mm handle | Slides through outer tube hole into inner tube; thick section fits inner tube slots; thin section sticks out through slot |

### Moving Components Sketches

<img src="{{ "/assets/images/moving_components_sketch.png" | relative_url }}" width="80%" alt="Moving Components Sketch">

### Initial CAD

**Extended and locked into place:**

<img src="{{ "/assets/images/extended_pole_cad.png" | relative_url }}" width="80%" alt="Extended and Locked CAD">

**Unextended:**

<img src="{{ "/assets/images/unextended_pole_cad.png" | relative_url }}" width="80%" alt="Unextended CAD">

### Assembly Documentation

**Step 1: Attach pulley body/wheel to top of base tube**

Install the pulley pin with a screw. Place on the wheel and epoxy the pulley body to the outer tube.

<img src="{{ "/assets/images/assembly_1a.png" | relative_url }}" width="80%" alt="Assembly Step 1 — Pulley installation">

&emsp;&emsp; &emsp; &emsp; Pulley Pin  &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; Wheel &emsp; &emsp; &emsp;&emsp; &emsp; &emsp; &emsp;&emsp;&emsp;&emsp;&emsp; &emsp; Pulley Body

**Step 2: Slide inner tube into base tube**

Align the inner tube handle slot with the outer tube pin channel.

<img src="{{ "/assets/images/assembly_2a.png" | relative_url }}" width="80%" alt="Outer Tube — Pin channel shown">

&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; Outer tube

**Step 3: Insert pin handle through the outer tube into the inner tube**

The thick section sits inside the inner tube while the thin handle section protrudes through the slot.

<img src="{{ "/assets/images/assembly_3a_2.png" | relative_url }}" width="80%" alt="Pin Handle Slot">
&emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; &emsp; Inner tube with handle slot shown

<img src="{{ "/assets/images/assembly_3a_1.png" | relative_url }}" width="40%" alt="Pin Handle">
<img src="{{ "/assets/images/assembly_3b.png" | relative_url }}" width="40%" alt="Pin handle inserted — end result">

 &emsp;&emsp; &emsp; &emsp;&emsp; &emsp; &emsp; &emsp; &emsp; Pin &emsp; &emsp; &emsp; &emsp; &emsp;&emsp; &emsp; &emsp; &emsp; &emsp;&emsp; &emsp; &emsp; &emsp; &emsp; handle inserted correctly


**Step 4: Tie rope around pin handle, run through mounted pulley**

Thread the nylon rope from the handle up and over the pulley at the top of the outer tube.

<img src="{{ "/assets/images/assembly_4a.png" | relative_url }}" width="40%" alt="Rope and pulley setup">
<img src="{{ "/assets/images/assembly_4b.png" | relative_url }}" width="40%" alt="Pulley close-up with rope threaded">

&emsp;&emsp; &emsp;&emsp;&emsp; &emsp;&emsp;&emsp; &emsp;&emsp;&emsp; &emsp; Nylon Rope &emsp;&emsp; &emsp;&emsp;&emsp; &emsp;&emsp;&emsp; &emsp;&emsp;&emsp; &emsp; Tied around handle

**Step 5: Check that the pole can extend**

Verify smooth extension by pulling the rope or pushing the handle upward.

<img src="{{ "/assets/images/assembly_5a.png" | relative_url }}" width="40%" alt="Pole extended">

### Test Documentation

#### Tube Deflection Test
*Testing alignment between the two tubes to prevent damage from torquing.*

- **Description:** Inner tube is fully extended using the pin mechanism. The angle between the inner tube and vertical is measured to quantify deflection from ideal vertical orientation.
- **Result:** Tube deflected 3.5°.
- **Conclusion:** This test is of limited use in its current form. Spacers between the inner and base tubes were intended to stabilize the inner tube, but the first spacers had too-small tolerances and a second set could not be manufactured in time. The inner tube therefore has much more play than it would with spacers. This test will be repeated once spacers are fabricated.

#### Lifting Force Test
*Testing the pin/handle mechanism and pulley mechanism for required force to extend the pole.*

- **Description:** Using a force gauge, the force required to lift the pin handle was recorded across several scenarios — both with the pulley and by lifting the pole directly from the pin handle. Scenarios included holding the inner tube stationary at an intermediate height, recording the force to start moving the inner tube, and extending the pole from minimum to maximum height in under two seconds. Ten trials of the third scenario were conducted and averaged.
- **Results:**

| Scenario | Pin Handle &emsp; | Pulley |
|----------|-----------|--------|
| Holding force | 4.9 N | 12.8 N |
| Lifting force (to start moving) | 18.6 N | 14.7 N |
| Avg. max force during full extension &emsp;| 35.3 N | 32.5 N |

&nbsp;  
Both methods required very low perceived effort.

- **Conclusion:** Results are lower than expected, which is encouraging. The final prototype will use heavier PVC pipe (2.4 kg vs. 1.3 kg cardboard), so forces are expected to scale by approximately 1.85×. Research shows that the optimum pull strength for repeated tasks is roughly ⅓ of maximum pull strength (~130 N threshold). Current forces are well below this limit, and can be further reduced with lubrication between tubes and bearings for the pulley.

#### Pin Locking Test
*Testing the pin/handle locking mechanism for quick extension and locking time.*

- **Description:** Slot the pin handle into the J-slot to fully extend the rod. The rod must stay securely extended without additional support and must not suffer visible damage. The time to lift the handle and slot it into the lock was measured 5 times.
- **Result:** The pole extended and remained in place without outside support. No visible damage was found after deconstruction. Average time to raise and lock: **3.48 seconds**.
- **Conclusion:** The J-slot locking mechanism is sufficient to bear the weight of the pole. PVC tubes (2.4 kg) will increase the force, but PVC is significantly stronger than cardboard, so durability should not be an issue. Slotting the handle into the lock took slightly longer than desired; a wider initial J-slot opening could reduce the need for precise alignment.

#### Pulley Wrap Locking Test
*Testing the pulley wrap locking mechanism for quick extension and locking time.*

- **Description:** Using the pulley, extend the pole to full height, then wrap the rope around the pole so it remains fully extended without support. Measure time to fully secure the pole and check for damage.
- **Result:** The pole extended easily with the pulley system. No visible damage. Four wraps of rope were needed for sufficient friction. Average time to lift and wrap: **10.98 seconds**.
- **Conclusion:** Initial lifting took only 1–2 seconds; most time was spent wrapping the string at an awkwardly high position. Future designs can improve lock time by including a knob to wrap the rope around or a small spike on the pulling end of the rope to insert into the ground.

### Success Criteria Summary

| Criterion | Threshold &emsp;| Result | Status |
|-----------|-----------|--------|--------|
| Pull force to actuate | < 130 N | Both methods well under 130 N &emsp;| **PASS** |
| Locking time | < 5 s | Pin: 3.48 s / Pulley: 10.98 s | Pin: **PASS** / Pulley: **FAIL** |
| Deflection off vertical &emsp; | < 1° | 3.5° | **FAIL** |

**Next steps:** Address deflection with tighter tolerancing and spacers. Improve pulley locking time with a rope knob or ground spike. Transition from cardboard to PVC tubes for the next prototype.

# Client Report



## Context and Problem Statement:
Vineyards face significant harm from spotted lanternflies (SLF), because grape vines are one of the primary plants on which SLF feed. This feeding damages the vines and causes significant declines in grape yield. Pesticides are a conventional method to protect vines, but they cannot be used up to a week before harvest. Additionally, grape harvest season aligns with peak SLF activity, making it the period of greatest grapevine vulnerability throughout the year. 
Research has shown that over-the-row insect netting can reduce SLF population on grape vines by up to 99.8%. The tested netting has a 6x1.8mm mesh and must be secured on the bottom and sides of the row. This solution is imperfect, however. The netting must be removed before harvest and reapplied after, which is a labor-intensive process that leaves the grape plants unprotected for significant periods of time. Other styles of netting, such as side netting, allow hand-harvesting without a complete removal process. However, side netting is not as effective at protecting against SLF compared to over-the-row netting. We wanted to create something that leverages the effectiveness of fine mesh netting, but decreases the extensive labour required from the netting replacement process.
##Final Prototype and Application:
	Our solution is a system of telescoping trellis line posts. These posts are spaced along the trellis, sitting below the insect netting. When harvest time comes, users can raise each post using the lifting rope. The netting is lifted by the extending post, allowing the grapes to be accessed beneath. After harvesting, the posts are collapsed, lowering the netting back over the vines. 
## Conclusion and Recommendation:
	We recommend that our prototype be tested with real vines and netting to determine its feasibility. Our post performed well in testing, extending and collapsing with relative ease. However, the forces caused by netting snagging on vines is a significant unknown. Furthermore, we do not know how easily netting will re-drape over the rows when the poles are collapsed. 
	Our pole is designed to reduce the labor involved in removing and applying insect netting. It must work easily both in the lab and in the field. We do not yet know if our pole solution is more or less laborious than applying netting the conventional way. This must be determined before pursuing our solution further. 
## Testing and Results:
	Three primary tests were conducted: an extension deflection test, a lifting force test, and an extension and locking time test.
For the lifting force test, the goal was less than one degree of deflection, and we measured 0.2 degrees. This deflection level means our design enables precise translational alignment of poles and prevents unnecessary shear forces on our 3D prints. 
	We then conducted a lifting force test. Industrial labor standards suggest that the average person can lift 40kg on a 5/16 in rope (the diameter we are using) but for repeated movements it is suggested that someone not pull more than ⅓ of their maximum pull strength. Based on these recommendations, our goal was a maximum pull force of 130N (13.3kg). The hold force required was 4.9N (0.5kg), the minimum lifting force required was 91.1N (9.3kg), and the max force average during a lift was 124.4N (12.7kg). This means our design will not cause undue fatigue on workers operating our extendable poles.
	Our mechanism is designed to save manual labor and time so it is imperative that it can be extended and locked quickly. Therefore, for our extension and locking time test, we set a goal of 5 seconds for the total time, and measured an average of 1.8s for extension and 2.1s for locking (3.9s total). With the aid of devices, a zip tie can be attached or removed in about 3 seconds. If zipties are placed every foot, and poles are placed every ten feet, then using the extendable pole system is 14.6 times faster than traditional methods. Our testing doesn't account for the additional time to take the net off the vines and roll it up, so time savings could be even greater.
## Prototype and Testing Details:
### Testing Methods (Results listed above):
Extension Deflection Test: The tube deflection test consists of fully extending and tieing off the inner tube then measuring the angle of the inner tube from vertical to determine deflection from ideal orientation. This test was created to evaluate the tolerancing between the inner tube, outer tube, and their sliders. Lower deflection indicates more accurate tolerancing and less shear forces on the 3D printed sliders.
Lifting Force test: The lifting force test consists of using a force gauge to measure several different lifting forces. The first measurement is a hold test where we record the force required to hold the inner tube stationary at an intermediate height (not locked at the top or resting on the bottom). In the second scenario we record the force required to start moving the inner tube upwards. In the third scenario, we extend the pole upwards in a smooth motion. We record the max force during this time. Ten trials of the third scenario were conducted and averaged. This test was created to evaluate whether lifting many poles would be strenuous on grape harvesters.
Extension and Locking Test: The extension and locking time test consists of measuring the time it takes to fully extend and secure the pole in place and averaged over 10 trials.
Component List and Bill of Materials:


### Assembly process
Press fit the Dowel pin through the Top cap
Use ½’’ length ¼-20 screws and bolts to secure the cleat into place 
Press fit all of the components except the base connector and top PVC pipe together as shown by the green arrows above.
Use ½’’ length ¼-20 screws and bolts to secure top cap, top t-connector, and inner tube slider 
Tie a stopper knot into the lifting rope, run it through the bottom hole in the inner PVC pipe and through the opening in the top cap.
Insert the inner PVC pipe into the Outer PVC pipe 
Press fit the base connector and the top PVC pipe as shown by the green arrows
Use ½’’ length ¼-20 screws and bolts to secure the top PVC pipe and base connector into place 


# References:
Das, B., & Wang, Y. (2004). Isometric Pull-Push Strengths in Workspace: 1. Strength Profiles. International Journal of Occupational Safety and Ergonomics, 10(1), 43–58. https://doi.org/10.1080/10803548.2004.11076594
Leach, Heather & Mariani, Tom & Centinari, Michela & Urban, Julie. (2023). Evaluating integrated pest management tactics for spotted lanternfly management in vineyards. Pest Management Science. 79. 10.1002/ps.7528.
https://treetools.co.nz/Blog/How_much_force_can_you_apply_with_one_hand_200N_apparently?srsltid=AfmBOors1cu2TwxJdQpEdWvJQ7eJ697kaamFAnxtD69cgdBPZzqzGOAy

