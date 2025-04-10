---
category: Aviation
created_at: 2025-03-01 19:17:41-05:00
modified_at: 2025-04-08T14:13:33-04:00
status: Active
tags:
  - aviation
  - classnotes
title: Aviation Formulas
topic:
  - Reference
  - Planning
type: Resource
program: PPL
---

# Aviation Formulas
[[🏠 Homepage]]
- [[ATPL Formulas.pdf]]
## Formula for Density Altitude

The density altitude (DA) is given by:

$$
DA = PA + \left( 120 \times (OAT - ISA_{temp}) \right)
$$

where:

$$
PA = (29.92 - \text{Altimeter Setting}) \times 1000 + \text{Field Elevation}
$$

$$
ISA_{temp} = 15 - \left(2 \times \frac{\text{Field Elevation}}{1000} \right)
$$

---
## Flight Time Calculation
$$
\text{Time} = \frac{\text{Distance}}{\text{Groundspeed}}
$$
## Fuel Required
$$
\text{Fuel Required} = \text{Fuel Burn Rate} \times \text{Time (hours)}
$$


## Crosswind Component Calculation

To find the crosswind component for Runway 36 with a wind direction of 320º at 12 knots, use the formula:

$$
X_w = V \times \sin(\theta)
$$

Where:
- \( X_w \) = Crosswind component (knots)
- \( V \) = Wind speed (knots)
- \( \theta \) = Angle between wind direction and runway heading

#### **Step 1: Find Wind Angle**
$$
\theta = | 320º - 360º |
$$
$$
\theta = 40º
$$

#### **Step 2: Calculate Crosswind Component**
$$
X_w = 12 \times \sin(40º)
$$
$$
X_w \approx 12 \times 0.6428
$$
$$
X_w \approx 7.71 \text{ knots}
$$

Thus, the crosswind component is **approximately 7.7 knots**.

## Groundspeed Calculation

To determine the planned groundspeed when flying a true course of 130º with a true airspeed of 112 knots and winds aloft from 250º at 15 knots, use the formula:

#### **Formula for Groundspeed**
$$
GS = TAS \pm \text{Headwind Component}
$$

Where:
- \( GS \) = Groundspeed (knots)
- \( TAS \) = True Airspeed (knots)
- \( HW \) = Headwind (negative) or Tailwind (positive) component (knots)

The headwind component is calculated as:

$$
HW = V_w \times \cos(\theta)
$$

#### **Step 1: Find Wind Angle**
$$
\theta = | 250º - 130º |
$$
$$
\theta = 120º
$$

#### **Step 2: Calculate Headwind Component**
$$
HW = 15 \times \cos(120º)
$$
$$
HW \approx 15 \times (-0.5)
$$
$$
HW \approx -7.5 \text{ knots} \quad (\text{Headwind})
$$

#### **Step 3: Compute Groundspeed**
$$
GS = 112 + (-7.5)
$$
$$
GS \approx 104.5 \text{ knots}
$$

Thus, the **planned groundspeed is approximately 104.5 knots**.