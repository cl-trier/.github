# GPU Access for Students: Free and Affordable Options

This overview focuses on GPU resources suitable for student assignments, term papers, and small machine-learning projects, including fine-tuning and LoRA experiments. Research-computing options with lengthy application processes are included but marked accordingly.

## Overview

| Service | Cost | Best for | Limitations |
|---|---|---|---|
| [Google Colab](https://colab.research.google.com) | Free tier; paid plans available | Notebooks, prototyping, small fine-tuning jobs | Limited GPU availability, session duration, and compute quotas |
| [Kaggle Notebooks](https://www.kaggle.com/code) | Free | Small experiments, baseline models, fine-tuning | Weekly GPU quotas, session limits, and variable availability |
| [Modal](https://modal.com) | Free Starter credits subject to current terms | Python scripts, LoRA, automated GPU jobs | Credits and resource limits apply |
| ash — Student GPU server, University of Trier | Free; access on request | Experiments that outgrow Google Colab | Shared and not sufficient for all students at once; availability not guaranteed; limited disk space |
| [KISSKI LLM Service](https://kisski.gwdg.de) | Potentially free through eligible academic projects | GPU-based LLM training and inference | Application or project approval may be required; individual student access is not guaranteed |
| [Vast.ai](https://vast.ai) | Pay-as-you-go; prices vary by provider. Free student access via its education program | Budget GPU instances and batch experiments | Reliability, availability, and hardware quality vary |
| [RunPod](https://www.runpod.io) | Pay-as-you-go; selected GPUs from around $0.27/hour | Fine-tuning with dedicated GPUs and longer jobs | Storage may cost extra; GPU prices and availability vary |
| [Elwetritsch](https://hpc.rz.rptu.de) — RPTU Kaiserslautern-Landau | Academic computing resource; check access conditions | Larger ML experiments and HPC workloads | Application and approval may take a considerable amount of time |
| [Mogon](https://hpc.uni-mainz.de) — Johannes Gutenberg University Mainz | Academic computing resource; check access conditions | HPC and GPU computing | Application and approval may take a considerable amount of time |

## Notes on individual services

### Free and easy-to-access options

- **[Google Colab](https://colab.research.google.com):** A convenient starting point for notebook-based experiments. Since its GPU capacity was insufficient for some workloads, it may be best suited to prototyping and debugging.
- **[Kaggle](https://www.kaggle.com/code):** A useful free alternative for small datasets, baseline models, and limited GPU experiments.
- **[Modal](https://modal.com):** Particularly interesting for Python-based workloads that need a GPU only while a job is running. Check the current free-credit allowance and academic eligibility before relying on it.

### Academic computing resources

- **ash (136.199.93.84):** The student GPU server of the University of Trier, with 1 × NVIDIA Tesla V100 (32 GB VRAM) and 6 × NVIDIA GeForce RTX 2080 Ti (11 GB VRAM each); CUDA 13.0. The server is shared and not sufficient for all students at once, so try Google Colab first and use ash only if Colab is not enough. Availability and sufficient capacity cannot be guaranteed, and disk space is limited. To get access, contact Iftakharul Islam at [s2ifisla@uni-trier.de](mailto:s2ifisla@uni-trier.de).
- **[KISSKI](https://kisski.gwdg.de):** Offers AI infrastructure and services through academic and other eligible projects. Students should ask whether access is possible through their university or supervising department.
- **[Elwetritsch](https://hpc.rz.rptu.de):** The RPTU's computing infrastructure may be suitable for larger workloads. Allow sufficient lead time for access approval.
- **[Mogon](https://hpc.uni-mainz.de):** Mainz's HPC infrastructure is another potential option for GPU-intensive academic work. Check current eligibility and application procedures well in advance.

For both Elwetritsch and Mogon, access for students working on individual term papers is not guaranteed; confirm the requirements with the respective computing centre.

### Paid GPU clouds

- **[RunPod](https://www.runpod.io):** A practical option when a dedicated GPU with 24 GB VRAM is needed. For 10–40 hours of GPU time, a rough budget might be around $3–$36 in compute costs, depending on the GPU and hourly rate.
- **[Vast.ai](https://vast.ai):** Also offers free access for students through its education program ([vast.ai/education](https://vast.ai/education)). Worth comparing with RunPod for cheaper instances. Check persistent storage, interruption policies, and provider reliability before starting a long-running job.

Prices and free-tier quotas can change, so verify current terms before starting a project.

## Recommended order for students

1. Start with Google Colab or Kaggle for prototyping and small experiments.
2. If Colab is not enough, ask for access to ash; it is shared, so availability is not guaranteed and disk space is limited.
3. Try Modal for GPU jobs that can run as scripts rather than interactive notebooks.
4. Use RunPod or Vast.ai when you need more predictable capacity or 24 GB of VRAM.
5. Apply to KISSKI, Elwetritsch, or Mogon early if your project requires substantial compute and you have enough time for the application process.

For a student with a budget of €20–50 per month and approximately 10–40 GPU hours, a combination of free notebooks and occasional pay-as-you-go GPU rental is a practical starting point.
