name: title-layout
layout: true
class: center, middle, title
---
name: basic-layout
layout: true
class: left, top
---
name: title
template: title-layout
# Senior Thesis PDRR
.footnote[Vijay Thakkar, Prof. Rich West]
???
SLIDE 0: Title

---
name: thesis-statement
template: title-layout
### Design a proof of concept system that allows for Android OS to be emulated on x86 hardware to serve as a host for low criticality (infotainment) processing in the presence of a high criticality sister guest. 
???
SLIDE 1: Thesis Statement
- Infrastructure for heterogenous mixed criticality compute for the cars of the future

---
name: requirements
template: basic-layout
### Requirements
- Provide low latency read-write access to buffer between two guest OSes
- No interference with the high criticality processing of ROTS
- 
???
SLIDE 3: Thesis Statement
- Infrastructure for heterogenous mixed criticality compute for the cars of the future


---
name: deliverables
template: basic-layout
### Deliverables
- Android guest kernel module for reading shared memory access
- Linux guest kernel module to write to shared memory
- Linux host kernel module that sets up the shared memory
- A running demo on actual hardware
- Possible implementation with Quest and Quest-V
???
SLIDE 4: Thesis Statement
- Infrastructure for heterogenous mixed criticality compute for the cars of the future
