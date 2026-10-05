---
layout: page
title: About
---

I am a C++ engineer focused on performance: algorithm engineering, parallel and
distributed
computing, and GPU programming. I like working close to the hardware: profiling
the hot path,
choosing the data layout, and checking with measurements whether an optimisation
really holds up.

I studied for my M.Sc. in Computer Science at the Karlsruhe Institute of
Technology (KIT) from 2022
to 2026. The thesis and all coursework are completed, and I took my last exam in
September 2026;
its result and the degree certificate are still pending. I am looking for a
full-time position in high-performance C++ (low
latency, HPC and GPU, or performance-critical product software) and am available
now.

**Technical focus:** C++ (C++11 to C++20, templates and metaprogramming), CUDA,
MPI, Python ·
Linux, CMake, Git · profiling, multithreading, cache-aware data structures,
parallel and
distributed algorithms.

## How it started

C++ was my first programming language. I taught myself in middle school from the
book *Grundkurs
C++* by Jürgen Wolf, and it has stayed my main language ever since.

My first formal training came at the Berufskolleg Technik in Siegen (2015 –
2018), where I
qualified as a state-certified information technology assistant and earned the
Fachhochschulreife:
programming fundamentals, computer systems and networking. Alongside school I
joined the junior
studies programme of the University of Siegen (2016 – 2017) and attended
computer science
lectures there, among them Software Engineering I and Linear Algebra for
Computer Scientists.

## Industry

All my industry work so far was part-time, as a working student alongside school
and university.

### pmdtechnologies · Siegen · 2017 – 2022

pmd develops 3D time-of-flight depth sensors. I started with an internship in
the summer of 2017:
an NSIS installer for one of the main products and smaller C++ tickets across
the code base, with
Jira, Bitbucket and Jenkins as the team's toolchain. I stayed on as a working
student for almost
five years, alongside school and my bachelor's. Most of that work was C++11 with
Qt and OpenGL: I
re-implemented the raw-data viewer in C++/Qt and worked on the 3D visualisation.
For Android I
wrapped the native C++ sensor framework in a Java library (JNI) and built a 3D
viewer on the
Camera2 API. This is where C++ turned from a hobby into a professional tool for
me.

### Vector Informatik · Karlsruhe · 2023 – 2026

At Vector I worked in the medical-devices department, on an implementation of
IEEE 11073 SDC, the
standard for networked communication between medical devices. My first tasks
there were outside
C++; over time I moved into the C++20 part of the stack. I implemented parsers
for the SDC message
family and template-metaprogramming abstractions that check rules of the message
model at compile
time, so that a whole class of errors cannot reach a running device. In this
domain the constraint
is certifiable correctness rather than raw speed, and it taught me to be precise
about what code
guarantees and what a test actually shows.

## Research

### Lattice Boltzmann Methods group · H-BRS · 2022 – 2024

My bachelor's thesis led me to [lettuce](https://github.com/lettucecfd/lettuce),
an open-source,
PyTorch-based framework for GPU-accelerated Lattice Boltzmann simulations of
fluid flows, and I
kept working on it as a student research assistant (three contracts, 16 months
in total, remote
from Karlsruhe). I replaced generic PyTorch operations with custom CUDA kernels
and wrote a
hardware-aware code generator that JIT-compiles kernels for the configuration at
hand. The
generated kernels reached up to 46× the throughput of the PyTorch baseline.

### Lattice Boltzmann Research Group · KIT · 2022 – 2023

In my first year at KIT I also worked on the C++ computational engine of the
Lattice Boltzmann
Research Group, profiling its hot kernels and optimising them.

### Master's thesis: KaSpan · KIT · 2025 – 2026

In Prof. Peter Sanders' Algorithm Engineering group I built KaSpan, a
distributed algorithm for
strongly connected components in C++ and MPI, and evaluated it on the HoreKa
supercomputer with up
to 8,208 cores against the existing distributed solvers. The full story, with
plots, is in the
[post on KaSpan]({% post_url 2026-10-05-kaspan %}); the code is on
[GitHub](https://github.com/rawbby/KaSpan).

## Education

### M.Sc. Computer Science · Karlsruhe Institute of Technology · 2022 – 2026

I specialised in parallel computing and algorithm engineering. The courses I
enjoyed most were the
ones closest to how fast code really runs: Parallel Algorithms, Advanced Data
Structures, Text
Indexing and Algorithm Engineering, plus the lab on efficient parallel C++. A
highlight outside
that focus was the practical challenge in Formal Systems: a generator for SAT
encodings, written
in Java, and my submission was the best of the course. The master's thesis on
KaSpan was graded
1.3. My last exam was in September 2026; until its result is in, the overall
grade is provisional:
1.5 (German scale, 1.0 = best). Because I worked about 20
hours a week throughout, the degree took longer than the standard two years.

Outside the lectures I was active in the student council (student counselling
and interviews for
the master's admission), in the student union's festival committee and in the
programme committee
of the AKK cultural centre.

### B.Sc. Computer Science · University of Siegen · 2018 – 2022

My specialisation was visual computing. For my bachelor's thesis, *Efficient
CUDA and C++
Implementation of Fluid Dynamics Simulations in a PyTorch-Based Open-Source
Framework* (grade 1.0),
I brought CUDA and C++ into lettuce, which was the start of my research work on
GPU performance.

## Contact

- Email: [info@robert-fritsch.de](mailto:info@robert-fritsch.de)
- GitHub: [github.com/rawbby](https://github.com/rawbby)
-
LinkedIn: [linkedin.com/in/robert-andreas-fritsch](https://www.linkedin.com/in/robert-andreas-fritsch)
