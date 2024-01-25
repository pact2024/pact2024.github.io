---
title:        Workshops/Tutorials Program
description:  PACT 2023 Workshops/Tutorials Program
id:           workshops
layout:       page_sidebar
show_sidebar: true
---

# Tutorials/Workshops Program

* [Program](#program)
* [Abstracts](#abstracts)

## Program

### Saturday, October 21, 2023

<table class="table table-striped">
	<thead>
		<th>
			Time
		</th>
		<th>
			What
		</th>
		<th>
			Where
		</th>
	</thead>
	<tr>
		<td>
			half day
		</td>
		<td>
			<a href="/images/PACT2023_AI_Workshop_Agenda.pdf">
				Workshop: AI Acceleration
			</a>
		</td>
		<td>
			Room Turin
		</td>
	</tr>
	<tr>
		<td>
			full day
		</td>
		<td>
			<a href="https://go-nhr.de/CLPE">
				Tutorial: Core-Level Performance Engineering
			</a>
		</td>
		<td>
			Room Wien
		</td>
	</tr>
</table>

### Sunday, October 22, 2023

<table class="table table-striped">
	<thead>
		<th>
			Time
		</th>
		<th>
			What
		</th>
		<th>
			Where
		</th>
	</thead>
	<tr>
		<td>
			half day
		</td>
		<td>
			<a href="https://groups.csail.mit.edu/commit/mlsh/">
				Workshop: Machine Learning for Software Hardware Co-Design (MLSH'23)
			</a>
		</td>
		<td>
			Room Turin
		</td>
	</tr>
	<tr>
		<td>
			full day
		</td>
		<td>
			<a href="https://hpc.pnl.gov/SODA/tutorials/2023/PACT.html">Tutorial: SODA Synthesizer: Accelerating Data Science Applications with an end-to-end Silicon Compiler</a>
		</td>
		<td>
			Room Wien
		</td>
	</tr>
</table>

## Abstracts

#### [Workshop: AI Acceleration](/images/PACT2023_AI_Workshop_Agenda.pdf) (Saturday)

AI acceleration workshop aims to delve into the latest advancements in AI acceleration techniques and technologies
exploring cutting-edge solutions designed to enhance the speed, efficiency, and scalability of AI algorithms and
models. Key topics of discussion will include hardware acceleration, open platforms for AI, AI benchmarks and
emerging AI hardware architectures. The workshop on AI acceleration provides a venue for the international
researchers and industry community to share ideas and techniques to accelerate AI workloads.


#### [Workshop: Machine Learning for Software Hardware Co-Design (MLSH'23)](https://groups.csail.mit.edu/commit/mlsh) (Sunday)

As Machine Learning (ML) continues to permeate all areas of computing, software system designers and software stack developers are adopting ML solutions and designs to solve challenging problems presented in their areas; especially in areas like optimization and hardware design. ML is increasingly being used to solve a diverse set of problems such as the design of cost models, code optimization heuristics, efficient search space exploration, automatic optimization, and program synthesis. Designing accurate machine learning models, feature engineering, verification, and validation of obtained results and selecting and curating representative training data are all examples of challenging but important problems in this area that are actively being explored by a large community of researchers in industry and academia. This workshop provides a great venue for the international research community to share ideas and techniques to apply machine learning to system challenges with a focus on the software stack and hardware. 


#### [Tutorial: Core-Level Performance Engineering](https://go-nhr.de/CLPE) (Saturday)

While many developers and researchers put a lot of effort into optimizing large-scale parallelism, they often neglect the importance of an efficient serial code. Even worse, slow serial code tends to scale very well, hiding the fact that resources are wasted because no definite hardware performance limit (“bottleneck”) is exhausted. This tutorial conveys the required knowledge to develop a thorough understanding of the interactions between software and hardware on the level of a single CPU core and the lowest memory hierarchy level (the L1 cache). We introduce general out-of-order core architectures and their typical performance bottlenecks using modern x86-64 (Intel Ice Lake) and ARM (Fujitsu A64FX) processors as examples. We then go into detail about x86 and AArch64 assembly code, specifically including vectorization (SIMD), pipeline utilization, critical paths, throughput prediction, and loop-carried dependencies. We also demonstrate performance analysis and performance engineering using the Open-Source Architecture Code Analyzer (OSACA) in combination with a dedicated instance of the well-known Compiler Explorer. Various hands-on exercises will allow attendees to make their own experiments and measurements and identify in-core performance bottlenecks and optimize code. Furthermore, we show real-life use cases and performance studies to emphasize how profitable in-core performance engineering can be.

For more information, course materials, and the schedule, see [https://go-nhr.de/CLPE]().


#### [Tutorial: SODA Synthesizer: Accelerating Data Science Applications with an end-to-end Silicon Compiler](https://hpc.pnl.gov/SODA/tutorials/2023/PACT.html) (Sunday)

Data Science applications (machine learning, graph analytics) are among the main drivers for the renewed interests in designing domain specific accelerators, both for reconfigurable devices (Field Programmable Gate Arrays) and Application-Specific Integrated Circuits (ASICs).
Today, the availability of new high-level synthesis (HLS) tools to generate accelerators starting from high-level specifications provides easier access to FPGAs or ASICs and preserves programmer productivity. However, the conventional HLS flow typically starts from languages such as C, C++, or OpenCL, heavily annotated with information to guide the hardware generation, still leaving a significant gap with respect to the (Python based) data science frameworks.
This tutorial will discuss HLS to accelerate data science on FPGAs or ASICs, highlighting key methodologies, trends, advantages, benefits, but also gaps that still need to be closed.
The tutorial will provide a hands-on experience of the SOftware Defined Accelerators (SODA) Synthesizer, a toolchain composed of SODA-OPT, an opensource front-end and optimizer that interface with productive programming data science frameworks in Python, and Bambu, the most advanced open-source HLS tool available, able to generate optimized accelerators for data-intensive kernels.
