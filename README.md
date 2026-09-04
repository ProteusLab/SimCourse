# CPU & OS simulation Elective Course

Course website: <https://proteuslab.github.io/SimCourse/>

## What is the course about?

Сourse repository is dedicated to CPU and OS simulation in third bachelor semester at MIPT.

All teaching materials used during the semester are [here](simcourse-site/slides/).

## Demo Code

You can find [simulator library](lib/) and [test generation script](test/) here.

During the course we consistently improve our toy model of the simulator.

1. [Naive Interpreter](naive_interpreter/sim.cc)
2. [JIT translator](jit_translator/sim.cc)

## Usage

From the root of source directory configure:

```bash
mkdir -p build/
cmake -B build -S . -DCMAKE_BUILD_TYPE=Release
```

Then run build:

```bash
cmake --build build/ -j<nproc>
```
