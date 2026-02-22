The Franklin Construct is a modular personal mobility platform that targets controlled,
low-altitude hovering and assisted propulsion without fixed infrastructure. It is not a maglev train
derivative, not a ducted-fan aircraft, and not a novelty toy. It is an electromagnetic suspension
and propulsion system designed to operate over unprepared surfaces using a combination of
passive and active magnetic strategies, with an optional surface-conditioning layer to improve
coupling repeatability.

1.2 Core Architecture Statement
The current design is a hybrid electromagnetic architecture:
-Passive permanent-magnet arrays provide a strong baseline magnetic field (B-bias)
without continuous power draw. This reduces the burden on active systems.
-Actively driven resonant coils provide stabilization, thrust vectoring, braking, and
dynamic gap control. These coils are driven by a high-efficiency inverter using a
PLL-tracked, ZVS-capable topology.
The passive field establishes a foundation. The active system rides on top of it -- modulating,
correcting, vectoring, and braking. Neither component alone claims to provide full rider-scale lift;
together, they form a force budget that is validated incrementally.

1.3 "Mist Track" Framing (No Magic)
A temporary surface-conditioning layer ("mist track") is used to improve repeatability of
magnetic/electromagnetic coupling on arbitrary terrain. This layer is not assumed to behave as
an ideal conductor or ideal magnetic track. Instead, it is treated as a controllable, time-limited
surface modifier whose properties are explicitly measured and used by the control system to
adapt lift and stability in real time.
Key properties that must be characterized:
-Sheet resistance (Ohm/sq): measured via 4-point probe or calibrated proxy
-Uniformity: measured across a grid (>= 9 points over defined area), reported as mean,
standard deviation, and percent variance
-Persistence window: time interval after deposition during which film properties remain
within defined thresholds, measured under stated ambient conditions and surface type
The mist track is not assumed to "biodegrade into nothing."
The carrier fluid may be biodegradable; particulate fate and exposure controls are addressed in the safety plan (Section
7) and the Ethics & Environmental Handling Plan (Appendix G). Deposition is engineered to
minimize airborne risk.

1.4 Program Structure
The project is structured around staged validation. The first technical milestone is not "full rider
hover."
It is:
A measured and repeatable force-vs-gap curve over representative surfaces
Defined thermal limits observed and logged
Stable closed-loop gap control demonstrated on a rig
Once these are validated, the design scales by increasing active area, optimizing magnetic
circuit geometry, and improving surface conditioning uniformity. Each scaling step is itself a
gated milestone with pass/fail criteria and required artifacts.
This structure means the document reads as a validation program, not a product
announcement. Every section that follows is designed to support this approach: claims are
conditional, numbers are tied to test conditions, and progress is earned through....
