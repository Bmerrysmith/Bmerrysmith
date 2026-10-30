# Benjamin Merryman-Smith

Software engineering student at Florida Gulf Coast University. I build computer vision pipelines and agent memory systems, with a focus on reliable data, controlled experiments, and clear evaluation.

## Selected work

### [AgriNav Perception](https://github.com/Bmerrysmith/agrinav-perception)

Rice and weed perception for an autonomous paddy tractor. I led object detection and plant discrimination for this senior engineering project.

- Built dataset conversion and integrity checks, detector training, and COCO evaluation in an installable Python package.
- Found a split-manifest mismatch affecting 940 files and added checks that verify the emitted dataset against its manifest.
- Used matched baseline experiments to identify where standard models outperformed the custom architecture.

**Python · PyTorch · computer vision · data validation · ML evaluation**

[Explore the code](https://github.com/Bmerrysmith/agrinav-perception/tree/main/src/agrinav) · [Read the baseline findings](https://github.com/Bmerrysmith/agrinav-perception/blob/main/docs/baselines.md)

### [GIM Agent Memory](https://github.com/Bmerrysmith/gim-agent-memory)

Research infrastructure for studying what agents should retain under a fixed persistent-memory budget.

- Implemented evidence-linked memory records, deterministic serialization, exact vector retrieval, and storage-budget enforcement.
- Built a seeded workshop environment, correctness tests, and reproducible engineering comparisons.
- Kept preliminary workshop results separate from the central research hypothesis, which remains untested.

**Python · agent systems · vector retrieval · reproducible experiments**

[Run the demo](https://github.com/Bmerrysmith/gim-agent-memory#quick-start) · [Review the implementation](https://github.com/Bmerrysmith/gim-agent-memory/tree/main/src/gim)

### [Senior project case study](https://github.com/Bmerrysmith/Senior-Project-Portfolio/tree/benjamin-merryman-smith)

A detailed account of my AgriNav contribution: dataset reconstruction, silent training failures, evaluation design, and the control experiments that changed the project direction. The repository includes other students' portfolios on separate branches; this link goes to my work.

## How I work

I use dataset checks, tests, and controlled baselines to find out whether a result is real before building on it. My repositories distinguish implemented features, measured findings, and open research questions.
