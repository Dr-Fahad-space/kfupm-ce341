# Chapter 3: Characteristics of Driver, Pedestrian, Vehicle & Road

**Highway Transportation System Components**

Instructor: Dr. Fahad Alqahtani

> **Note:** Coming Soon - Tuesday in class

## Learning Objectives

By the end of this chapter, it should be possible to:

- **Remember:** list the four components of the highway transportation system; define key terms (visual acuity, peripheral vision, PIEV, superelevation, side friction, SSD, PSD).
- **Understand:** explain why driver and pedestrian limitations must be reflected in design criteria and why variability drives the use of percentiles.
- **Apply:** compute braking distance, stopping sight distance, and minimum curve radius using standard design equations (with correct units and grade sign conventions).
- **Analyze:** distinguish static, kinematic, and dynamic vehicle characteristics and connect each to specific roadway design elements (e.g., lane width, ramp length, curve design).
- **Evaluate:** interpret how changes in grade, friction, superelevation, or perception-reaction time change safety margins.

---

## Chapter Introduction

Highway transportation systems look simple on the surface—people drive along roads in vehicles—but the system's performance and safety depend on several interacting components. This chapter organizes the highway mode of transportation into four core components: **the driver**, **the pedestrian**, **the vehicle**, and **the road**.

A key theme is **variability**. Drivers differ in perception, decision-making, and reaction. Pedestrians vary in walking speed and attention. Vehicles vary in size, weight, acceleration, and braking. Roads vary in alignment, grade, surface condition, and sight distance. Because traffic engineering is not an exact science, design commonly uses **percentile-based criteria** (for example, 85th or 95th percentile capabilities) to cover most users under most conditions.

## 3.1 Introduction: Four components of the highway system

*Required Bloom level: Remember + Understand*

The highway transportation system consists of four interacting components:

- **Driver:** perceives information (signs, vehicles, pedestrians), makes decisions, and executes control (steer, brake, accelerate).
- **Pedestrian:** shares space at crossings and along road edges; has different speed, perception, and vulnerability than vehicle users.
- **Vehicle:** provides mobility but imposes geometric and physical constraints (size, turning path, acceleration and braking limits).
- **Road:** the infrastructure that must provide adequate geometry, surface condition, and sight distance for expected operating speeds.

## 3.2 Driver characteristics

*Required Bloom level: Understand*

Driver skill and perceptual abilities (seeing, hearing, evaluating, and reacting) vary widely and can degrade with alcohol, fatigue, medication side effects, or time of day. For design, engineers typically select criteria aligned with a high percentile capability (often the 85th or 95th percentile).

### 3.2.1 Visual reception

*Required Bloom level: Understand + Apply*

Vision is the primary sensory input for driving. Important eye characteristics include **visual acuity**, **peripheral vision**, **color vision**, **glare vision and recovery**, and **depth perception**. Visual acuity is commonly described using Snellen fractions.

Peripheral vision allows a driver to detect objects outside the narrow cone of clearest vision. The peripheral cone can be very wide (up to about 160°) but effectively narrows as speed increases.

### 3.2.2 Hearing reception

*Required Bloom level: Understand*

Hearing is typically secondary for driving tasks, but it matters for detecting warning sounds (especially from emergency vehicles).

### 3.2.3 Perception–reaction (PIEV) process

*Required Bloom level: Understand + Apply*

The response to a roadway stimulus can be divided into four sub-processes:

1. **Perception:** noticing the object/control device
2. **Identification:** recognizing what it is
3. **Emotion (decision):** choosing an action
4. **Volition / reaction:** executing the action

The total time is commonly called **perception–reaction time**. Typical values range from about **1.2 to 3.0 s**, and design often uses **2.5 s**.

### Key Vocabulary - Driver Characteristics

- **Visual acuity:** ability to see fine detail; commonly described using the Snellen fraction (e.g., 6/6).
- **Peripheral vision:** ability to detect objects outside the cone of clearest vision; generally narrows as speed increases.
- **PIEV / perception–reaction process:** Perception, Identification, Emotion, Volition—the sub-processes that determine response time.
- **Perception–reaction time (t):** elapsed time from noticing a stimulus to completing the initial response.

## 3.3 Pedestrian characteristics

*Required Bloom level: Understand + Apply*

Pedestrians share many relevant characteristics with drivers (vision and hearing), but their **walking behavior** is additionally critical for traffic control design.

A commonly used walking speed from the Highway Capacity Manual is about **1.22 m/s**, and it is often reduced to about **0.9 m/s** when the proportion of elderly pedestrians exceeds approximately 20%.

> **Example: Pedestrian Clearance Time**
> 
> For an 18 m crosswalk:
> - **t = 18 / 1.22 ≈ 14.8 s** (typical)
> - **t = 18 / 0.9 = 20.0 s** (elderly)

## 3.4 Vehicle characteristics

*Required Bloom level: Analyze*

Vehicle characteristics are organized into: **static** (size and weight), **kinematic** (speed/acceleration/distance), and **dynamic** (forces).

### 3.4.1 Static characteristics: size and weight

*Required Bloom level: Analyze*

The size of the design vehicle affects lane width, shoulder width, parking bay dimensions, and vertical curve length. Vehicle axle loads influence pavement thickness.

### 3.4.2 Kinematic characteristics: acceleration as a function of speed

*Required Bloom level: Apply*

A common model relates acceleration to current speed: **du/dt = α − βu**

### 3.4.3 Dynamic characteristics: resistances, power, braking, and curve design

*Required Bloom level: Apply + Evaluate*

Resistive forces include: air resistance, grade resistance, rolling resistance, and curve resistance.

### 3.4.4 Braking distance

*Required Bloom level: Apply*

The braking distance formula incorporating grade effects:

$$D_b = (u_1^2 - u_2^2) / [254 (a/g ± G)]$$

Use **+** for uphill, **−** for downhill. G is decimal grade (3% = 0.03).

### 3.4.5 Minimum radius of a circular curve

*Required Bloom level: Apply*

Curve design balances lateral acceleration using superelevation and side friction:

$$R = u^2 / [127(e + f_s)]$$

Where:
- u = speed (km/h)
- e = superelevation (decimal)
- f_s = side friction factor

> **Example: Minimum Curve Radius**
> 
> For u = 80 km/h, e = 0.08, f_s = 0.15:
> $$R = 80² / [127(0.08 + 0.15)] = 6400 / 29.21 ≈ 219 \text{ m}$$

## 3.5 Road characteristics: sight distance

*Required Bloom level: Understand + Apply*

**Sight distance** is the length of roadway a driver can see ahead. Two major types are: **Stopping sight distance (SSD)** and **Passing sight distance (PSD)**.

### 3.5.1 Stopping sight distance (SSD)

*Required Bloom level: Apply*

SSD is the sum of: (1) distance traveled during perception–reaction time, and (2) braking distance.

$$SSD = 0.278ut + (u_1^2 - u_2^2) / [254(a/g ± G)]$$

- First term: distance during perception-reaction (u in km/h, t in seconds)
- Second term: braking distance

> **Example: Stopping Sight Distance**
> 
> For u = 90 km/h, t = 2.5 s, level grade, a/g = 0.35:
> - SSD = 0.278 × 90 × 2.5 + 90² / (254 × 0.35)
> - SSD = 62.55 + 91.11 = **153.7 m (≈ 154 m)**

### 3.5.2 Passing sight distance (PSD)

*Required Bloom level: Understand*

PSD is the minimum sight distance required on a two-lane, two-way highway to allow a driver to complete a passing maneuver safely.

---

## Practice Problems

### Problem 1 — Bloom's Level: Remember

**Question:** List the four main components of the highway transportation system.

**Answer:** The driver, the pedestrian, the vehicle, and the road.

### Problem 2 — Bloom's Level: Understand

**Question:** Why are 85th or 95th percentile values commonly used in design criteria?

**Answer:** Because driver abilities vary; higher percentiles cover most users and reduce chance of exceeding human performance.

### Problem 3 — Bloom's Level: Understand

**Question:** Name the four sub-processes of the PIEV process.

**Answer:** Perception, Identification, Emotion (decision), and Volition (reaction).

### Problem 4 — Bloom's Level: Apply

**Question:** A 15 m crosswalk: compute clearance time at 1.22 m/s and 0.9 m/s.

**Answer:**
- t = 15/1.22 ≈ 12.3 s
- t = 15/0.9 = 16.7 s

### Problem 5 — Bloom's Level: Apply

**Question:** Using a/g = 0.35, decelerate from 100 km/h to 60 km/h on level grade. Find braking distance.

**Answer:** 
$$D_b = (10000 - 3600)/(254 × 0.35) = 6400/88.9 ≈ 72 \text{ m}$$

### Problem 6 — Bloom's Level: Apply

**Question:** Compute SSD for u = 80 km/h, t = 2.5 s, level grade, a/g = 0.35.

**Answer:**
$$SSD = (0.278 × 80 × 2.5) + 80²/(254 × 0.35) = 55.6 + 72.0 = 127.6 \text{ m (≈ 128 m)}$$

### Problem 7 — Bloom's Level: Apply

**Question:** For u = 70 km/h, e = 0.06, f_s = 0.14, compute minimum curve radius.

**Answer:**
$$R = 70² / [127(0.06 + 0.14)] = 4900 / 25.4 ≈ 193 \text{ m}$$
