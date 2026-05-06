---
layout: project
title: MAE 2250 ODP Project
description: Targeted Oviposition Control for Spotted Lanternflies
technologies: [CAD, 3D Printing, Prototype Testing, Fluid Delivery, Product Design]
image:
imagealt:
---

## Project Overview

<nav class="milestone-toc" aria-label="MAE 2250 milestone table of contents">
  <a href="#client-pitch">Client Pitch</a>
  <a href="#functional-prototype">Functional Prototype</a>
  <a href="#client-report">Client Report</a>
</nav>

This project focuses on developing a targeted and scalable solution to reduce the spread of spotted lanternflies by addressing the root cause of reinfestation: uncontrolled egg-laying behavior. Rather than attempting to eliminate adult populations directly, our approach introduces localized "no-lay zones" that discourage oviposition in sensitive areas such as vineyards, equipment zones, and high-value agricultural regions.

To achieve this, we designed and prototyped a distributed repellent system consisting of compact, battery-powered devices that emit a controlled spray of an essential oil-water mixture. These devices are intended to be deployed in a network across vulnerable areas, creating overlapping zones of deterrence that redirect lanternflies away from protected spaces and toward more manageable locations. This strategy allows for more efficient monitoring and removal of egg masses while reducing the labor associated with widespread manual inspection.

The project integrates mechanical design, fluid delivery, and environmental considerations to balance effectiveness, safety, and ease of use. Our prototype demonstrates the feasibility of maintaining a consistent repellent concentration, achieving meaningful spatial coverage, and operating reliably in a modular format suitable for field deployment. Overall, this system represents a shift from reactive control methods to a more proactive and targeted approach for managing spotted lanternfly populations.

## <span id="client-pitch">Client Pitch</span>

[Open the Client Pitch PDF]({{ "/assets/pdfs/client-pitch.pdf" | relative_url }})

<iframe class="pdf-embed" src="{{ "/assets/pdfs/client-pitch.pdf" | relative_url }}" title="Client Pitch PDF"></iframe>

### Context and Problem

The client pitch defined the core problem as uncontrolled SLF oviposition. Existing approaches often focus on reducing adult density in vineyards, but they do not directly address egg masses that remain in the environment and later hatch. Since each egg mass can contain roughly 30 to 50 eggs, scattered egg laying creates a compounding infestation problem.

### Proposed Direction

The proposed concept was an essential-oil aerosol repellent module that emits short bursts of oils such as tea tree, peppermint, or lavender before and during the oviposition period. Multiple devices would be installed near sensitive vineyard areas from July through December, spaced roughly 10 to 25 feet apart. The goal would be to create local no-lay zones and redirect egg laying toward controlled areas where egg masses could be monitored and destroyed.

### Key Risks and Client Questions

The main risks were environmental variability and population redistribution. Wind, rain, and outdoor conditions could change aerosol drift and concentration, while redirecting SLF could increase density in nearby untreated areas if deployment is not planned carefully. The client questions focused on where egg masses are most commonly found, when deployment should begin before oviposition, and whether there are restrictions on chemical compounds or odors near grape production areas.

## <span id="functional-prototype">Functional Prototype</span>

[Open the Functional Prototype PDF]({{ "/assets/pdfs/functional-prototype.pdf" | relative_url }})

<iframe class="pdf-embed" src="{{ "/assets/pdfs/functional-prototype.pdf" | relative_url }}" title="Functional Prototype PDF"></iframe>

### Prototype Design

The functional prototype demonstrated the mechanical and fluid-handling portions of the concept. The design included a 3D printed base and motor compartment, a micro N20 DC gear motor, a 3D printed bottle holder and outer shell, a 32 oz HDPE bottle, a bearing support, a McMaster-Carr ball bearing, and a 12V submersible pump.

### Testing

The prototype was tested through four main checks:

- Component fit testing confirmed that the assembly showed the intended placement of the main parts, though the purchased bottle did not fit the printed component and required a future design adjustment.
- Pump function testing showed that the selected pump could not self-prime, which made it unsuitable for an autonomous on-off system.
- Mixing efficiency testing used food coloring to confirm that the motor-driven chamber could mix the liquid uniformly in a short period of time.
- Rotational speed testing measured 15 rotations in 5.24 seconds, corresponding to about 170 RPM.

### Success Criteria

The prototype was evaluated by stability, mixing, and liquid transport. The target was for the assembled bottle, motor, shell, and supports to remain stable for at least 30 seconds while running; for the fluid to become visually uniform within 30 seconds; and for the pump to move 50 mL of liquid from the bottle to the nozzle in under one minute.

## <span id="client-report">Client Report</span>

[Open the Client Report PDF]({{ "/assets/pdfs/client-report.pdf" | relative_url }})

<iframe class="pdf-embed" src="{{ "/assets/pdfs/client-report.pdf" | relative_url }}" title="Client Report PDF"></iframe>

### Proposed Solution

The final client report presented a battery-powered, distributed repellent device for field deployment in vineyards. The system uses a rotating reservoir, fluid delivery mechanism, and spray distribution component inside a compact housing. The prototype is designed to discourage SLF from laying eggs in sensitive areas and to make egg-mass monitoring and removal more targeted.

### How It Works and How It Is Used

At the center of the device is a 950 mL reservoir mounted in a coaxial cylinder system. A DC motor rotates the reservoir at approximately 142 RPM to keep the essential-oil and water mixture homogeneous. A diaphragm pump moves the fluid from the reservoir to the nozzle, and the spray system distributes the solution in a 360-degree pattern. The nozzle can operate in mist or stream mode, giving flexibility between coverage area and fluid consumption.

The device is powered by a 12V battery pack housed in the base. The base includes stake holes for field stability, while the reservoir can be refilled through a top-mounted funnel and the battery pack can be removed for recharging. In practice, multiple devices would be placed around vineyard perimeters, equipment zones, and previously infested regions to create a distributed deterrent network.

### Testing Results

Testing compared three nozzle configurations using effective range, mixture homogeneity, and application cycles per bottle. The mixing mechanism maintained a stable oil-water mixture across spray velocities, and the number of use cycles per fill was similar across modes. The stream setting performed best, reaching a 4.5 foot radius and about 63.62 square feet of coverage, which was substantially greater than the hybrid and mist settings.

### Conclusion and Recommended Next Steps

The recommended implementation begins in high-risk areas such as vineyard perimeters and previously infested regions, with devices placed several meters apart to create slightly overlapping deterrence zones. Effectiveness should be monitored throughout the September to November oviposition stage, and device placement or spray mode should be adjusted based on environmental conditions and SLF activity.

This device is not intended to kill SLF directly. Instead, it is meant to localize current and future populations so existing egg removal methods can be applied more effectively before eggs hatch in spring. Next steps include integrating the design with existing vineyard irrigation infrastructure, using a concentrated stock solution that mixes with clean water on demand, and adding aerosol sensing so the system can adapt to changing outdoor conditions.
