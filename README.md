# MDA Research Kubernetes Link Directory

Content credit to Yiyang Niu ([yniu2@mdanderson.org](mailto:yniu2@mdanderson.org)) & Yang Zhang ([yzhang45@mdanderson.org](mailto:yzhang45@mdanderson.org)).

Organized by Xinrui Li ([xli37@mdanderson.org](mailto:xli37@mdanderson.org)).

This page is a link organization index only. It is not a tutorial. Each link includes what it is for and when to use it.

## How to Use This Page
- Start with the three links in Critical Links (Must Read).
- Use Account and Access links to request accounts and config support.
- Use Setup and Operations links for specific tasks.

Contact for kubeconfig and templates: [EDI-Kubernetes-Admin@mdanderson.org](mailto:EDI-Kubernetes-Admin@mdanderson.org)

## Critical Links (Must Read)

| Link | What It Is About | When to Use | Access Note |
| --- | --- | --- | --- |
| [Kubernetes Orientation README](https://github.mdanderson.org/yzhang45/Kubernetes-Orientation/blob/main/README.md) | Primary orientation and initial setup context for MDA Kubernetes users. | Read first before any setup or job submission. | Internal GitHub access required. |
| [Kubernetes Q&A README](https://github.mdanderson.org/EDI-Research-Kubernetes/Kubernetes_QA/blob/main/README.md) | Operational Q&A, common errors, troubleshooting, and task-specific guidance. | Use during day-to-day operation and troubleshooting. | Internal GitHub access required. |
| [Kubernetes Seminar PowerPoint By Yiyang Niu](https://mdandersonorg-my.sharepoint.com/:p:/r/personal/xli37_mdanderson_org/_layouts/15/Doc.aspx?sourcedoc=%7B77743AA8-EDDD-4BDD-B126-69B65947CD02%7D&file=251111_BCB%26BS_kubernetes_server_seminar%20-%20Copy.pptx&action=edit&mobileredirect=true&DefaultItemOpen=1) | Presentation with key Kubernetes suggestions and server usage recommendations. | Use for overview and context before deep diving into docs. | SharePoint and MDA account access required. |

## Account and Access Links

| Link | What It Is About | When to Use |
| --- | --- | --- |
| [MDA HPC Portal](https://hpcweb.mdanderson.edu/) | Main entry point for HPC resources, policies, and account processes. | Use for official HPC information and request navigation. |
| [Seadragon Account Request](https://hpcweb.mdanderson.edu/request_account.html) | Account request page for Seadragon access. | Use before trying to submit Kubernetes jobs from Seadragon. |
| [EDI-Kubernetes-Admin@mdanderson.org](mailto:EDI-Kubernetes-Admin@mdanderson.org) | Team contact for kubeconfig file and job template provisioning. | Email when you need Kubernetes configuration and storage mapping setup. |

## Training and Orientation Materials

| Link | What It Is About | When to Use |
| --- | --- | --- |
| [Kubernetes User Setup.docx](https://mdandersonorg-my.sharepoint.com/personal/yzhang45_mdanderson_org/_layouts/15/guestaccess.aspx?share=EXs4wrqjoT5Dk2gsXkkPr34BtAMwtwJfXm0sX-HQJ56cUw&e=F8xpAN) | Written setup walkthrough and supporting notes. | Use when you want a document-style setup reference. |
| [Kubernetes User Setup.mp4](https://mdandersonorg-my.sharepoint.com/personal/yzhang45_mdanderson_org/_layouts/15/guestaccess.aspx?share=EdnlAB0lmnNDuCuNplCmln0BTAMZe93I3r13vRekn9wUzA&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=5BShJF) | Video version of user setup flow. | Use if you prefer a visual walkthrough. |
| [K8s Orientation Introduction v3.mp4](https://mdandersonorg-my.sharepoint.com/personal/yzhang45_mdanderson_org/_layouts/15/guestaccess.aspx?guestaccesstoken=zLbWXT3Yw%2Fmjz91BSCE6RkdbD7DOQ2B5GOVXt54dFOw%3D&docid=2_10225cb0526084f6a959537b8d51dd848&rev=1&e=OmrYTI) | Orientation video with Kubernetes context and usage guidance. | Use as an overview before detailed setup. |
| [Kubernetes Orientation.pdf](https://mdandersonorg-my.sharepoint.com/personal/yzhang45_mdanderson_org/_layouts/15/guestaccess.aspx?guestaccesstoken=9mi83qXhtEKx1XvmHf7kWkuQJ%2fLVWoTMG7Mdxk%2f5D0U%3d&docid=2_05da03f0fefd344bfbc962430fbcaeeae&rev=1&e=OmrYTI) | PDF orientation material for offline reading. | Use when you need a printable/static reference. |

## Setup and Workflow Links

| Link | What It Is About | When to Use |
| --- | --- | --- |
| [MDA JupyterHub Portal](http://hpcexhaproxy.mdanderson.edu/jupyter/) | Interactive Kubernetes environment for notebooks and development workloads. | Use for interactive development and testing. |
| [MDAJupyterHub README](https://github.mdanderson.org/yzhang45/MDAJupyterHub/blob/main/README.md) | Detailed JupyterHub usage notes and environment guidance. | Use when configuring or troubleshooting JupyterHub usage. |
| [BuildDockerImage README](https://github.mdanderson.org/yzhang45/BuildDockerImage/blob/main/README.md) | How to build Docker images for Kubernetes workloads. | Use when your dependencies are not covered by standard images. |
| [VSCode_JupyterHub README](https://github.mdanderson.org/EDI-Research-Kubernetes/VSCode_JupyterHub/blob/main/README.md) | Remote VS Code workflow integrated with Kubernetes and JupyterHub usage. | Use when developing remotely in VS Code. |
| [Alternative Python Management](https://github.mdanderson.org/EDI-Research-Kubernetes/PythonManagement/blob/main/Alternative%20Methods%20to%20Anaconda%20for%20Python%20Management.md) | Methods for Python package/environment management without Anaconda. | Use when you need lighter or alternative environment management. |
| [ShareStorage supplementalGroups](https://github.mdanderson.org/EDI-Research-Kubernetes/ShareStorage#using-supplementalgroups-in-kubernetes) | How to access multiple network storage mounts using supplemental groups. | Use when one container needs access to multiple storage group permissions. |
| [OpenLens Release v6.5.2-366](https://github.com/MuhammedKalkan/OpenLens/releases/tag/v6.5.2-366) | OpenLens download for Kubernetes UI management and log viewing. | Use if you prefer UI-based Kubernetes management instead of only CLI. |

## Operations and Monitoring Links

| Link | What It Is About | When to Use |
| --- | --- | --- |
| [Kubernetes Nodes Dashboard](https://hpcexhaproxy.mdanderson.edu/kubernetes/nodes/) | Cluster-wide node/resource visibility. | Use to check available node and hardware status. |
| [Kubernetes Users Dashboard](https://hpcexhaproxy.mdanderson.edu/kubernetes/users/) | User-facing dashboard for workloads and metrics history. | Use to review running jobs and historical CPU/GPU/RAM usage. |
| [Research High-Performance Computing](https://mdandersonorg.sharepoint.com/sites/information-services/SitePages/Research-High-Performance-Computing.aspx) | Institutional HPC resource overview and platform information. | Use for official infrastructure and resource context. |
| [HPC Resources at MD Anderson](https://mdandersonorg.sharepoint.com/sites/information-services/SitePages/Research-High-Performance-Computing.aspx#resources-at-md-anderson) | Direct section showing available resources. | Use when confirming cluster capacity and hardware availability. |

## Official Technical Reference

| Link | What It Is About | When to Use |
| --- | --- | --- |
| [Kubernetes Job Controller Docs](https://kubernetes.io/docs/concepts/workloads/controllers/job/) | Official Kubernetes documentation for batch Job resources. | Use for YAML schema, parallelism, completions, and controller behavior details. |
