### References:
- **Video title:** The State of Julia (In 2022) with Jeff Bezanson | JuliaCon 2022
- **Video Link:** https://youtu.be/N4h46_TCmGc

### Contents
An overview of the state of Julia in 2022.

00:00 Welcome
00:13 Opening of the talk
00:50 Compiler Update
00:59 New language features
01:25 New: `const` fields in structs 
01:39 New: `@atomic` for multithreaded programming
02:28 New: Type declarations on global variables
02:33 New: N-d array syntax `[A;;; B]`
02:38 New: Property destructuring `(; a, b) = x`
02:52 New: Slurping in any position `first, xs..., last=x`
03:04 New: `try...catch...else`
03:15 Compiler internal improvements (quick overview)
03:39 Strip debug info, metadata, IR
04:18 Early finalization insertion
04:38 Inductive range check elimination
05:07 Separate LLVM/codegen from runtime
06:31 StaticCompiler.jl
08:21 Precompile improvements
10:05 Effect analysis: new toys `Base.infer_effects`
11:50 Effect analysis: more optimizations
12:45 Effect analysis: faster compilation
14:22 Inlining improvements
14:38 Ongoing: Diffractor.jl (Automatic Differentiation)
14:53 Ongoing: Compiler plugins
15:12 Ongoing: Parallel compilation
15:33 Ongoing: Better static compilation support; Caching native code?
15:40 Ongoing: Separate compilation?
16:04 Threading Roadmap
16:55 Threading: Foreign threads calling multithreaded Julia runtime
18:13 Threading: Interactive thread pool
19:08 GC
19:24 GC: performance tuning
19:53 GC: new flag `--heap-size-hint`
20:18 GC: parallel marking
20:38 GC: parallel sweeping
20:52 GC: Exploring MMTk integration
21:25 GPU support is growing
21:48 Profiling: New allocation profiler
22:08 Profiling: Thread & Task aware CPU Profiling
22:14 Profiling: Profile already-running code
22:37 Profiling: Package Load Timing
22:51 Pkg: `status` now shows upgradability
23:11 Pkg: Automatically install missing packages
24:37 Pkg: Number of registered packages reached 8000
25:12 How long is taking us between releases
26:53 "Why We Use Julia, 10 Years Later"
27:37 Q&A: Is 2.0 coming after 1.9? When/What can we expect from 2.0?


### links to JuliaCon 2022 talks
Precompile improvements https://youtu.be/GnsONc9DYg0&t=664

GC: parallel marking (Diogo Netto) https://youtu.be/Ks0p6PQyIPs
GC: parallel sweeping (Christine Flood) https://youtu.be/YkcQYJIoaq8
GC: Exploring MMTk integration (Eduardo Souza) https://youtu.be/2ekwjy60tR0

GPU support is growing:
oneAPI.jl https://youtu.be/-n5VMbEQLa4
Metal.jl https://youtu.be/IARikXzRU7s

New allocation profiler https://youtu.be/BFvpwC8hEWQ

"Why We Use Julia, 10 Years Later" https://julialang.org/blog/2022/02/10years/ 
