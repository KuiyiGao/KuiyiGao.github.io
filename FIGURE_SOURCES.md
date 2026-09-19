# Figure sources

These are original paper figures and saved project outputs. Images were extracted or cropped without changing plotted values or labels. This website update did not rerun the experiments.

## Published papers

The two papers below list Wenxuan Wang as first author. His GitHub profile is [Jarviswang94](https://github.com/Jarviswang94). Kuiyi Gao is the third listed author of MMSafeAware and the second listed author of Chain-of-Jailbreak.

- `figs/mmsafeaware-table1.png`: Table 1, page 3 of [Wang et al., ACL 2025](https://aclanthology.org/2025.acl-long.832/). Comparison of input modalities and safety-scenario coverage. Cropped from the [official PDF](https://aclanthology.org/2025.acl-long.832.pdf), rectangle (68, 67, 527, 317) in PDF points, 216 DPI.
- `figs/mmsafeaware-figure3.png`: Figure 3, page 12 of the same paper. Reported accuracy across unsafe and benign scenarios. Plot crop (66, 99, 530, 306), 216 DPI.
- `figs/coj-figure3.png`: Figure 3, page 6 of [Wang et al., Findings of ACL 2025](https://aclanthology.org/2025.findings-acl.571/). Reported jailbreak success rates across scenarios and services. Cropped from the [official PDF](https://aclanthology.org/2025.findings-acl.571.pdf), rectangle (66, 252, 530, 393), 216 DPI.
- `figs/coj-figure4.png`: Figure 4, page 7 of the same paper. Reported jailbreak success rates by editing-step count. Plot crop (306, 167, 529, 318), 216 DPI.

All four paper crops are attributed to Wang et al. (2025) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Only the crop boundaries changed; the original figure labels and data are retained. The website captions summarize the figures separately from their original paper captions.

Repository artifacts were also checked at fixed snapshots:

- [MMSafetyAwareness result table](https://github.com/Jarviswang94/MMSafetyAwareness/blob/500b595c82dfe73d5695bc994d9882a306d2aa1c/paper/result.png), commit `500b595c82dfe73d5695bc994d9882a306d2aa1c`.
- [Chain-of-Jailbreak result table](https://github.com/Jarviswang94/Chain-of-Jailbreak/blob/15b4942f0e5d9606836d6d6199cdd831eab36de3/paper/result1.jpg), commit `15b4942f0e5d9606836d6d6199cdd831eab36de3`.

These repository files are linked for source comparison. The figures hosted here use the final ACL papers; the repository result tables were not assumed to be identical to those final versions.

## Course projects

- `figs/memslot-saliency.png`: Original PNG embedded in cell 6 (zero-based) of [MemSlot_Report.ipynb](https://github.com/KuiyiGao/Distorted-OCR-Compression/blob/b48f11cf7cdc05d194aa6bd33ec15369d654dfc1/notebooks/MemSlot_Report.ipynb). Saved course-project output, extracted without modification.
- `figs/poetry-samples.jpg`: Two archived FLUX image grids from Kuiyi Gao's ENGE3940 project (2025), arranged with labels. The selected examples are illustrative and do not establish a measured difference between literary movements.

## Workflow diagrams

The eight `*-workflow*.svg` files are new schematic summaries, drawn for this portfolio from the published study descriptions and existing course-project workflows. They are not original paper figures or experimental results.

- MMSafeAware: image–text pair → model safety judgment → accuracy on unsafe and benign subsets.
- Chain-of-Jailbreak: image-editing session outputs → safety assessment → comparison across models and scenarios. This is an evaluation overview.
- MemSlot: contract features → memory-slot saliency → selection/rendering → OCR-decoded text → separate QA reader. End-to-end QA evaluation is unfinished.
- Poetry: poem excerpts → FLUX / Stable Diffusion images → CLIP-based variation → group comparisons. The displayed images and analysis are archived outputs.

`figs/poetry-imagist-output.jpg` is the original Imagist FLUX grid from the ENGE3940 archive, used as a smaller homepage preview. It is included in the full poetry image gallery.
