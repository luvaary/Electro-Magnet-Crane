# Desktop Electromagnet Crane — Science Talent Search Build Guide

---

## Overview

This model crane demonstrates two core principles of electromagnetism and mechanical
engineering: (1) that a current-carrying coil wrapped around an iron core creates a
temporary magnet strong enough to lift small ferrous objects, and (2) that a rotating
bearing can distribute a load through a full 360° arc. When the circuit is closed by
pressing the momentary switch, current from a 9 V battery flows through the coil
windings, magnetising the iron core. Releasing the switch breaks the current, collapsing
the field and dropping the load — exactly like a full-scale scrapyard crane.

The Lazy Susan bearing replaces a fixed joint at the base of the upright column. Because
the upper assembly (column + boom + electromagnet) sits on the rotating inner ring of
the bearing, the entire crane can be turned by hand to any angle without disturbing the
base or wiring.

---

## Materials and Components

| Item | Specification | Qty |
|---|---|---|
| MDF or plywood base plate | 280 mm × 280 mm × 12 mm | 1 |
| Lazy Susan bearing (square) | 100 mm × 100 mm, steel, rated ≥ 5 kg | 1 |
| Aluminium square tube (upright) | 20 mm × 20 mm × 1.5 mm wall, cut to 370 mm | 1 |
| Aluminium flat bar (boom) | 20 mm × 3 mm, cut to 200 mm | 1 |
| Plastic/nylon pulley | 20 mm wheel diameter, M4 axle | 1 |
| Steel wire or monofilament cable | 0.5 mm diameter, 600 mm length | 1 |
| Iron bolt (core) | M10 × 50 mm hex-head | 1 |
| Enamelled copper wire (magnet wire) | 0.3 mm diameter, ~15 m | 1 reel |
| 9 V battery + snap connector | Standard PP3 / 6LR61 | 1 |
| Momentary push-button switch | SPST normally-open, rated ≥ 500 mA | 1 |
| M4 machine screws + nuts | Stainless, 10 mm | 8 |
| M10 nut + washers | For clamping coil | 2 |
| Heatshrink or electrical tape | General insulation | 1 m |
| Small L-brackets | Aluminium, 25 mm | 4 |
| Epoxy adhesive | Two-part structural | 1 pair |

---

## Suggested Dimensions

| Component | Dimension |
|---|---|
| Base plate | 280 mm × 280 mm × 12 mm |
| Upright column height | 370 mm above base top |
| Boom length (from column centre) | 195 mm |
| Boom cross-section | 20 mm × 3 mm flat bar |
| Electromagnet coil outer diameter | ~36 mm |
| Coil length | ~45 mm |
| Iron core (M10 bolt) | 50 mm length |
| Cable free length (fully lowered) | ~140 mm |
| Lazy Susan bearing footprint | 100 mm × 100 mm |

---

## Assembly Steps

**Step 1 — Prepare the base.**
Cut MDF or plywood to 280 × 280 mm. Sand all edges smooth. Mark the centre point. Drill
four pilot holes matching the outer ring bolt pattern of the Lazy Susan bearing (consult
your bearing's datasheet — typically a 75 mm square bolt circle for a 100 mm bearing).

**Step 2 — Mount the Lazy Susan bearing.**
Bolt the outer (fixed) ring of the bearing to the top face of the base plate using M4
bolts through the pre-drilled holes. Apply a small drop of thread-lock. The inner
(rotating) ring faces upward and will carry the crane structure.

**Step 3 — Fabricate the column foot block.**
Cut a 68 × 50 × 20 mm block from scrap timber or MDF. This block bridges the inner ring
of the bearing to the base of the aluminium upright. Bolt it through the inner ring bolt
circle. Apply epoxy under the block for additional shear resistance once alignment is
confirmed.

**Step 4 — Mount the upright column.**
Cut the 20 × 20 mm aluminium square tube to 370 mm. Attach two small L-brackets at the
bottom face of the column. Bolt these through the column foot block so the upright stands
perfectly vertical (use a small spirit level). Apply epoxy at the joint line for rigidity.

**Step 5 — Fabricate and attach the boom.**
Cut the 20 × 3 mm aluminium flat bar to 195 mm. Drill an M4 hole at the tip (20 mm from
the far end) for the pulley axle. Drill two matching holes at the inner end for attachment
to the top of the upright. Bolt the boom horizontally to the column top. The boom should
project outward from the column centre to a tip approximately 195 mm away.

**Step 6 — Mount the pulley.**
Thread the M4 axle bolt through the hole at the boom tip and fit the 20 mm plastic pulley
with washers on each side. Tighten the nut firmly — the pulley must spin freely but have
no lateral play.

**Step 7 — Wind the electromagnet coil.**
Thread the M10 bolt through a pre-drilled hole in a small plywood cheek plate (one on
each end of the coil form, 38 mm diameter). Leave 150 mm of wire free as a lead. Wind
~400 turns of 0.3 mm enamelled wire in tight layers, keeping each layer even. Leave
another 150 mm free at the end. Secure the winding with two wraps of heatshrink. The
completed coil should measure roughly 36 mm in diameter and 45 mm long. Resistance should
be approximately 8–15 Ω.

**Step 8 — Attach the electromagnet.**
Thread the steel cable through the pulley and tie a small wire loop at the bottom end.
Hook this loop over the head of the M10 bolt (the top of the electromagnet). The magnet
should hang vertically, with the flat core face pointing downward.

**Step 9 — Route the wiring.**
Run the two coil leads up the cable (secure with small zip-ties every 50 mm), over the
pulley, back along the top edge of the boom (use adhesive cable clips), and down the front
face of the upright column. At the base, connect the positive lead through the momentary
switch, then to the positive terminal of the 9 V battery snap connector. Connect the
negative lead directly to the negative terminal. Mount the switch to the column face at a
comfortable operating height (around 490 mm from base top — approximately 120 mm above
the base plate).

**Step 10 — Final check and test.**
Confirm all joints are firm. Rotate the upper assembly on the bearing through a full 360°
— there should be no binding. Press the switch and hold a small steel washer (or paper
clip) beneath the magnet face. It should attract and hold. Release the switch — the object
drops. If lift is weak, check wire insulation on the coil leads for nicks (shorts reduce
current) and confirm battery voltage.

---

## How the Lazy Susan Bearing Is Installed — and Why It Matters

The Lazy Susan bearing consists of two flat steel rings separated by a circular ball race.
The outer ring is fixed (bolted to the base plate). The inner ring rotates freely on the
balls and carries all the weight above it.

In this crane, the inner ring is bolted to the column foot block, which in turn supports
the entire upright, boom, and electromagnet assembly. Because the wiring runs down the
outside of the column and is long enough to allow a full sweep, the crane can rotate
through 360° without any mechanical stop. This allows the operator to pick up an object
from one position and swing the crane to deposit it at another — mimicking the real-world
function of a slewing crane.

Without the bearing, the crane would require a fixed pivot and could only demonstrate
lifting in a single direction — losing the rotation functionality entirely.

> **Assumed specification:** A 100 mm square steel Lazy Susan bearing rated for 5 kg is
> more than sufficient for the ~250 g upper assembly. This assumption is explicitly noted
> as an educational choice; heavier bearings may be substituted.

---

## How the Electromagnet Is Mounted and Powered

The electromagnet hangs from the steel lifting cable via the head of the M10 bolt that
forms its iron core. The coil windings surround this core. When DC current passes through
the windings, the core becomes magnetised and the flat bottom face of the bolt head acts
as the pickup face.

**Power source:** 9 V battery (PP3). This is a deliberate choice for classroom safety —
below the threshold that presents any shock hazard, while supplying enough current through
an 8–15 Ω coil to generate a usable magnetic field. At 9 V across 10 Ω, approximately
0.9 A flows, which is adequate to lift small iron objects (washers, bolts, small nuts) up
to roughly 50–80 g depending on coil quality and core contact.

The switch is wired in series on the positive line. Using a momentary (normally-open)
switch means the magnet is only energised while the button is held — intentional and safe.

---

## Wiring Overview

```
(+) Battery → Switch → Coil lead A
(−) Battery → Coil lead B
```

Both leads travel from the base up the column face, along the boom top edge, and down the
cable to the coil terminals. Keep lead pairs twisted together along straight runs to
minimise any electromagnetic interference with the coil field itself. Insulate all
stripped ends with heatshrink. Polarity for the electromagnet is not critical (the core
magnetises regardless of current direction), but maintaining consistent polarity is good
practice.

---

## Safety Notes

- The 9 V supply presents no shock risk under normal handling.
- Do not run the electromagnet continuously for more than 2–3 minutes at a stretch — the
  coil will warm up. This is normal; allow it to cool before the next demonstration.
- Ensure all bolted joints are firmly tightened before lifting any object; the bearing
  inner ring must be secure before the crane is operated.
- Keep the lift cable taut — a slack cable can slip the pulley groove.
- Do not attempt to lift objects heavier than 80 g; the 9 V supply and small core are not
  rated for heavier loads and may overheat.
- Sand and paint any exposed raw MDF edges to prevent moisture absorption over time.

---

## Size Check — Confirming the 0.4 m Limit

| Dimension | Value | Within 0.4 m? |
|---|---|---|
| Total height (base bottom to boom top) | ≈ 0.382 m | ✓ Yes |
| Base footprint width | 0.280 m | ✓ Yes |
| Base footprint depth | 0.280 m | ✓ Yes |
| Maximum horizontal reach (column centre to magnet) | ≈ 0.215 m | ✓ Yes |

All four critical dimensions are comfortably within the 0.4 m constraint. The most
relevant single dimension — total standing height — is approximately 0.38 m. The base
footprint fits within a 28 cm square, suitable for any standard desk or display table.

---

## Using the Diagram in a Science Talent Search Display

The SVG diagram is designed to be printed at A3 size (420 × 297 mm) or displayed on a
screen without loss of resolution, as it is a vector file. For a display board, mount a
printed copy at eye level beside the physical model. Use the labeled callouts to guide
judges through each component as you explain: start at the base and Lazy Susan bearing,
trace the upright to the boom, follow the wiring path to the electromagnet, and
demonstrate the 360° rotation in real time. The diagram also serves as your schematic
reference in the written report; cite it in the methods section as
"Figure 1 — Annotated crane schematic."
