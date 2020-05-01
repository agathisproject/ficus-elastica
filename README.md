<p align="center"> <img src="workflow-HighLevel.svg"> </p>

- The *projects high-level workflow* should be consistent with the diagram above.

- The **project**, usually identified by its doc set hosted in a distinct GitHub repository, provides the overall framework for the workflow.

- A **project** can be seeded through an **idea** that is grown into a design **specification** finalized by an **implementation** supporting the manufacturing, releasing or assembling of an **end-product**.

- A **project** can, as well, branch of another project and become a distinct entity. Such branching is recommended only at the at the end of idea, specification or implementation phases.

- The **implementations** are bounded by the design **specifications** and are documented as source code, CAD files and supporting information required to build and use **end-product**.

- An **end-product** can be:
  - a hardware piece-part
  - a hardware assembly made of piece-parts and (sub)assemblies
  - a software binary file installed on a hardware piece-part or assembly

- The **end-product** is validated against its specifications and system specifications.

- To avoid resource wasting mistakes, frequent work testing against the up-stream design specifications is mandated.


<p align="center"> <img src="workflow-LowLevel.svg"> </p>

- Every *low level workflow* phase, such as **idea, specification or implementation**
should be consistent with the diagram above.

- The work in the repository should happen only in the git branch named *work*.

- The allowed operations on the *master* branch are the *git branch* at the beginning of the work phase and the *git merge* at the end of it.

- Most of the creative work happens during the commits before the *pull request*.

- Most of the corrective work happens between the *pull request* and is done to resolve/close all issues open during the review.

- The work is finalized with a voting followed by a *git merge* if approved.


