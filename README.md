# Cortex3D

**Tagline:** *“Perception, simulation, control — a 3D engine built from scratch.”*

---

## Overview

Cortex3D is a **3D and physics engine** designed as a personal engineering dojo.  
It is meant to teach and demonstrate:

- 3D rendering (software or GPU)  
- Physics of rigid bodies (integration, collision, response)  
- Modular system architecture (math → scene → render → physics → I/O)  
- Simulations that can be extended to embedded systems or robotics  

It’s not just a project — it’s a hands-on way to learn core engineering principles.

---

## Features

- Math library: vectors, matrices, quaternions  
- Scene graph: entities, transforms, parent-child hierarchy  
- Rendering: triangle rasterizer, z-buffer, basic shading  
- Physics: gravity, collisions, semi-implicit integration  
- Camera: free navigation with quaternions  
- Model loading: simple OBJ support  
- Debugging: bounding boxes, normals, forces  
- Future: GPU acceleration, AI, IoT communication  

---

## Project Structure

Cortex3D/
├─ core/          # math, types, utilities
├─ render/        # software rasterizer, shaders
├─ scene/         # scene graph, transforms
├─ physics/       # integrators, collisions, solvers
├─ io/            # loaders, input handling
├─ tools/         # debugging, visualization, tests
├─ examples/      # sample scenes
└─ README.md

---

## Roadmap / What To Do Next

### Phase A — Foundations
- [ ] Implement math library: Vec3, Mat4, Quaternion  
- [ ] Minimal triangle rasterizer  
- [ ] 3D → viewport projection  
- [ ] Display simple shapes (cube, pyramid)

### Phase B — Rendering & Scene
- [ ] Camera with quaternion-based navigation  
- [ ] Basic shading (Lambert, Phong)  
- [ ] Simple OBJ loader  
- [ ] Basic culling/optimization

### Phase C — Physics
- [ ] Particle system with semi-implicit integration  
- [ ] Rigid bodies: AABB / simple collisions  
- [ ] Broadphase → narrowphase collision detection  
- [ ] Impulse solver for friction/restitution

### Phase D — Advanced / Polish
- [ ] GJK + EPA for complex collisions  
- [ ] Sequential impulse solver for constraints  
- [ ] BVH / octree for acceleration  
- [ ] Optional GPU rendering + visual debugging  

> You can check off each item as you implement it — this makes the README a living roadmap.

---

## How to Use / Goals

- Start **software-first**: get triangles on screen, particles moving  
- Keep each module testable and visible: positions, velocities, collisions  
- Document decisions and results here or in `/tools`  
- Aim for modularity: later modules (AI, embedded sensors, networked simulation) can plug in easily  

---

## Why Cortex3D?

Cortex3D is your personal **engineering dojo**:

- Every triangle rendered, every collision resolved, every quaternion calculated teaches you **core skills**.  
- Provides a visible, impressive demonstration of mastery.  
- Can later extend to drones, robotics, or embedded high-tech applications.  

---

## Notes for Myself

- Use this README to check **what to implement next**  
- Keep it public-facing but actionable  
- Update as features are added or ideas evolve  
- Always visualize: triangles, collisions, debug info  
- Test each step before moving on  

---

Cortex3D is **learning by doing at the highest level** — challenging, concrete, and visually satisfying.