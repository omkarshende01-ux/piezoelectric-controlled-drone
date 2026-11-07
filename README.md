# Piezoelectric-Controlled Drone

**A multirotor whose thrust is adjusted by changing propeller-blade camber — not just motor speed.**
Aerospace senior design capstone, Fall 2026–present — Rutgers University, six-person team.
My role: structures subteam and team secretary.

## The idea

Conventional multirotors vary thrust by changing motor speed. This concept bonds macro
fiber composite (MFC) piezoelectric patches to the propeller blades: apply voltage, the
patch strains, the blade camber changes, and the aerodynamic coefficients and blade
loading change — so thrust can be adjusted quickly and finely, before motor speed has
changed significantly. The effect still has to be verified on a thrust stand.

## What I did

- SolidWorks rotor assemblies, including the blade-pocket geometry where the MFC patch
  sits — the bond line that transfers actuation into camber change
- Composite manufacturing trade-offs and rotor load analysis; the assembly has to carry
  the patch without creating a weak blade section
- Propulsion sizing and eCalc studies: early motor/prop combinations did not give enough
  thrust-to-weight margin, so we compared motors, propellers, and coaxial arrangements
  to reach the current baseline
- Simplified rotor support using aluminum U-brackets to reduce complexity
- Worked the rotating-interface problem: wires attached directly to a spinning propeller
  can twist or need slip rings, so the revised concept rotates the electronics with the
  hub and investigates wireless transfer across the rotating interface
- Composite vacuum-bagging practice (flat plate, then curved surfaces) and early
  ESC / flight-controller integration
- Team-secretary coordination across the structures, propulsion, and controls work

## Key numbers (modeled — not yet measured)

| Metric | Value |
| --- | --- |
| Vehicle mass estimate (component-based) | 4.03 kg |
| Modeled thrust-to-weight ratio | 2.1 |
| Modeled trailing-edge displacement | 0.40 mm |
| Motor / controller | Hobbywing Platinum motor + Platinum Pro 60A ESC |
| Propeller | 20x10 two-blade carbon fiber |

## Status

Capstone in progress. The thrust-to-weight ratio and blade deflection above are
analytical / model-based results. Piezoelectric thrust enhancement has NOT yet been
experimentally demonstrated. Next steps: KDec motor test stand to verify control with
the flight transmitter, then piezo actuation on the blade, then both together.
