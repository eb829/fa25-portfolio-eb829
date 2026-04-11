---
layout: project
title: Combatting Spotted Lanternfly Design Project
description: CAD and Manufacturing Project - Team 003 / E&J Gallo Winery
technologies: [Autodesk Fusion, Laser Cutting, 3D Printing, Prototyping, Testing]
image: /assets/images/old-radio.jpg
---

<div style="border:1px solid #ddd; border-radius:10px; padding:1rem 1.25rem; margin:1rem 0 1.5rem 0; background:#fafafa;">
  <h2 style="margin-top:0;">Project Navigation</h2>
  <p style="margin-bottom:0.5rem;">Use the links below to jump directly to each portfolio milestone.</p>
  <ul style="margin-bottom:0;">
    <li><a href="#client-pitch">Client Pitch</a></li>
    <li><a href="#functional-prototype">Functional Prototype</a></li>
  </ul>
</div>

<div style="margin-top:2rem;"></div>

---
### This page documents the evolution of my Spotted Lanternfly (SLF) trap, from the original problem framing to the first functional prototype.
---
## <a id="client-pitch"></a>Client Pitch
### Problem statement
Vineyards across the United States are plagued by spotted lantern fly infestations, which, according to the Cornell Chronicle can cause up to $8.8 million in damages per vineyard over 3 years of infestation due to vine death, reduced fruit quality, and product contamination. There is currently no available mechanical system that draws the SLFs on or near grapevines during the harvest window away from vines and concentrates them into a controlled location where they can be removed or contained.
### Proposed direction
Scent and Visual Cue SLF Trap:
A cylindrical trap with holes funneling inward just large enough for an SLF to fly in that uses the scent of a Tree of Heaven and is mounted on a tall, slender silhouette to attract the SLF. This would hold a liquid to inhibit SLF flight and drown them. 
### Intended Impact
Our traps are adjustable and allow for the collection and **management of SLF's** without the harmful use for pesticides. It passively attracts and kills SLFs and get them off the crop for harvest. Additionally, it requires little human effort once set in place, making it **labor efficient**.
## <a id="functional-prototype"></a>Functional Prototype
The purpose of this prototype was to test the **mechanical feasibility** of the trap architecture before we manufacture with real materials. Rather than proving final trapping performance, this iteration focused on whether the main subsystems could be fabricated, assembled, and operated as intended. Appart from this, we wanted to confirm thaht the measurements were physically reasonable.
## Prototype Overview

The functional prototype consists of the following main subsystems:

- **Box housing** made from laser-cut wooden plates
- **drawer** for user access
- **wooden funnel**
- **extendable poll** made to adapt to be put in different location

## Initial Sketches
Overall trap sketch

![Overall Sketch](/assets/images/Overallsketch.png)

Extendable Pole sketch
![Overall Sketch](/assets/images/Extendable-Pole-sketch.png)
Funnel Opening Sketch
## Prototype Design Documentation

### Box Housing
Description: Outer housing of the trap which contains the drawer and trap funnel as well as interfaces with the extendable post
Fabrication: Use bandsaw to cut wood to size, then glue sides together to form box
### Drawer
Description: a drawer on a set of rails at the bottom of the trap to catch the SLF and store the trap liquid 
Fabrication: glue 2 strips of wood cut to size onto the inside of the box, make the box for the drawer out of wood and cut a slit with a ledge at the bottom of the slit on either side of the drawer such that it slides into the container easily 
### Trap Funnel 
Fabrication: Used the bandsaw to cut flaps out of wood and used the bandsaw to cut a notch in the back of each for a rubber band/string to sit in. Drilled a hole in each flap with a hand drill. Used pliers to cut the wire and bent it into a circle. Ziptied each flap to the ring.
### Extendable Post
Description: two horseshoe shaped poles, where the smaller one fits into the bigger one, with holes drilled into the sides such that a rod can fit through respective holes and make the length adjustable 
Fabrication: sawed wood to desired width and length with the bandsaw, drilled holes (1cm diameter) every 2 inches in 2 out of 3 wooden parts of the same length, glued to strips of wood in a horseshoe shape, with the strips of wood with holes facing each other, for the inner and the outer part of the pole


## What Was Tested

This prototype focused on testing three main features:

1. **Funnel mechanism**
2. **Drawer**
3. **Extendable Pole**

---
## Test 1: Drawer Weight Capacity

The drawer is designed to hold captured SLFs and allow for easy removal. This test assesses whether the drawer can successfully support the maximum expected load of SLFs, including a safety factor.

### Success Criteria

The drawer should:

- support a load of **12 kg** with a safety factor applied,
- be closed **20 times** under that load without difficulty,
- and show no visible damage after repeated use.

### Outcome

The drawer prototype was tested with loads up to **6 kg** — approximately half of the target load — to account for anticipated differences in material strength between the prototype and final design. The structure supported this load successfully, though the handle design requires improvement to reliably sustain higher forces during repeated pushing and pulling cycles.

The drawer was also able to be reused **50 times without visible damage**, confirming the durability of the overall structure. These results suggest the core design is sound, but handle reinforcement will be a priority in the next iteration.

---

## Test 2: Drawer Sliding on Rails

The drawer slides along rails to allow practical access to the captured SLFs. This test assesses whether the drawer mechanism operates smoothly under repeated use.

### Success Criteria

The drawer should:
- slide on and off the rails without resistance,
- and complete **50 open-and-close cycles** without getting stuck.

### Outcome

Under a **3 kg load**, the drawer opened and closed smoothly for **15 consecutive cycles** without jamming, demonstrating that the sliding mechanism functions effectively. While the full 50-cycle target was not reached in this prototype test, the results indicate that the rail mechanism is reliable under load. Further testing at higher cycle counts and with a reinforced handle will be conducted in the next iteration.

---

## Test 3: Pole Height Adjustment

The trap is mounted on an adjustable pole that can be repositioned within the vineyard. This test assesses the durability and practicality of the pole adjustment mechanism.

### Success Criteria

The pole mechanism should:

- adjust smoothly up and down,
- and withstand **50 adjustment cycles** without sustaining damage.

### Outcome

The extendable pole mechanism passed all tests. The pole was successfully raised and lowered **50 times** without any visible damage or slippage, and the position-setting pin could be engaged and released with minimal force, confirming smooth and practical operation. Additionally, the pole showed no visible deformation when the trap was loaded with **6 kg**, demonstrating sufficient structural integrity for real-world use. These results indicate that the pole mechanism is well-designed and requires only minimal refinement before the next iteration. 

---

## Test 4: Flap Range of Motion and Default Position

The flaps are constrained so they cannot move past vertical, keeping the funnel opening small enough to prevent SLFs from escaping. This test assesses whether the range of motion can be user-configured and whether the flaps reliably return to their default position.

### Success Criteria

The flaps should:

- be constrained so they cannot move past the vertical position,
- return to their original default diameter opening after a fly passes through,
- complete this reset **30 times** consistently,
- and allow the user to set both the range of motion and the default resting position.

### Outcome

The funnel mechanism was tested using a fly model on a string to simulate SLF entry and attempted escape. Under ideal conditions — with flaps properly spaced, correctly oriented, and no string interference — the fly model fell through the funnel with minimal force and could not be pulled back out, confirming that the one-way trapping concept works as intended.

However, under non-ideal conditions such as improper flap spacing, twisted flaps, or a caught string, the trap either prevented the model from entering or failed to retain it. This highlights that consistent flap positioning is critical to trap performance.

As a result, **spacers will be added to the flap ring** in the next prototype to maintain proper flap spacing and orientation, reducing the likelihood of failure due to misalignment.

---

## What the Prototype Showed
This functional prototype showed that:

- the drawer mechanism can support significant loads without structural failure,
- the rail sliding system operates smoothly and without jamming,
- the extendable pole can be adjusted reliably and bear the trap's full weight,
- and the funnel flap concept successfully traps a fly model under ideal conditions.

At the same time, the prototype revealed important design issues:

- the drawer handle requires reinforcement to withstand higher forces,
- the funnel flaps need spacers to maintain consistent spacing and orientation,
- and flap performance is sensitive to assembly quality, requiring a more foolproof mounting solution.
Even though the prototype did not fully satisfy every success criterion, it was valuable because it confirmed the viability of our core mechanisms while exposing specific integration and durability issues that were not apparent from the concept design alone.
---

## Next Iteration

The next prototype should focus on:

---
## End-of-Semester Demonstration
For the end-of-semester exhibition, we will demonstrate the **flap range of motion and default position criterion** with a live demonstration of a fly model passing through the funnel flaps and the flaps returning to their default position, showing that the one-way trapping mechanism prevents escape.

---


## Supporting Documentation

[View full design documentation PDF]({{ "/assets/ODP5PDF.pdf" | relative_url }})

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}

