# emergency_logistics
Emergency μ-Logistics: Fleet management and Route Optimization for Drones
## Inspiration
There have been several pandemics in the past, but surely, this is the first time we are fighting it with the help of technology. The virus mainly spreads through droplet infection, and it is quite likely that a patient might infect others on his way to the test center. Soon, the health care systems and test centers will be overwhelmed with patients. Swab based, and a method called loop-mediated isothermal amplification (LAMP) based COVID tests are conducted at home, and are expected to hit the market soon. The patient can be remote, symptomatically-treated and admitted to the hospital only if necessary. This can reduce the average hospitalization time, avoid the risk of spreading the virus and accommodate more patients at the hospital who need intensive care. There is a strong need for a logistics system that is very versatile, low cost, easy to deploy and quick for small payloads. (less than 1000 gms).

**Yes, the drones!**

We as a team would like to propose a micro logistics system, that is, highly time and cost-optimized, and can be built out of direct contributions from the public community.

## What it does
Drones are very familiar to the hobbyist community. With a low-cost computer, a GPS, and telemetry radio, the drone can be made autonomous. This is where we, as a community get together to contribute technologically to fight a pandemic. The public community around a given area can lend their drones. With additional low-cost hardware, they will be made autonomous and will be able to communicate with our platform. It is fairly easy to keep track of a few drones manually but the complexity increases exponentially even with a few ten's of them. There is where our platform comes in to picture. The following aspects are considered in optimizing this multi-dimensional problem:

- **Keep track drone telemetry and health (battery level, range, current location)**

- **Generate optimal routes based on multiple pick-ups and drop points.**

- **Assign drones to optimal routes. (considering battery levels and payload capacity)**

- **Improve drone utilization.** 

- **Fully automate the process.**

## How we built it
The platform is built using Python and OR-tools.

**Please check out these links!**
- https://youtu.be/G2rj6jamp5o
- Demo: https://drive.google.com/open?id=1gvZxFsP9uATlZZFntsrMpgzLIiaKgoAV
- Demo page: https://bhatramya.github.io/emergency_logistics/
