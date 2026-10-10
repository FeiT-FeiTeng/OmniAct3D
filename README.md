<div align="center">

<h2>OmniAct3D: Leveraging Foundation Geometry and<br>Evidence-Grounded Reasoning for Panoramic 3D Detection</h2>

<p>
  Runtong&nbsp;Wu <b>&middot;</b>
  Fei&nbsp;Teng <b>&middot;</b>
  Di&nbsp;Wen <b>&middot;</b>
  Guoqiang&nbsp;Zhao <b>&middot;</b>
  Kunyu&nbsp;Peng <b>&middot;</b>
  Kailun&nbsp;Yang
</p>

<p><a href="https://arxiv.org/pdf/2610.03015">Paper</a></p>

<p>🛠️ 👷 🚀</p>
<p>🔥 Code release is in preparation. 🔥</p>

</div>

### Update

- **2026.10.10** Demo video added and project repository initialized.
- **2026.10.02** The [arXiv paper](https://arxiv.org/abs/2610.03015) is released.

### TODO List

- [x] Paper and demo video.
- [ ] Source code release.
- [ ] Model checkpoints.
- [ ] Installation and inference instructions.

### Demo Video

https://github.com/user-attachments/assets/68d906c2-2e27-4e91-be7b-b7d4e690d059

### Abstract

OmniAct3D brings foundation-model-based 3D detection to 360° equirectangular panoramas. Its three components address spherical geometry, object-level evidence, and local appearance: ERGA-Ray adapts geometry features, VARC refines 3D hypotheses through evidence-grounded actions, and AGHE estimates heading from higher-resolution object crops. The framework preserves transferable foundation-model priors while adapting them to panoramic perception. Experiments report gains of 2.96 NDS points on Spheriverse over the previous best detector and 24.87 mAP points on PanoMMOcc over the unadapted foundation-model baseline. VARC also retains 95–98% of same-configuration mAP when paired with target-specific geometry adaptation.

### Method

- **ERGA-Ray — ERP-Ray Geometry Adapter:** spherical rays and panoramic periodicity.
- **VARC — Visual-Action Reasoning Chain:** panoramic evidence guides structured 3D refinement.
- **AGHE — Appearance-Guided Heading Expert:** higher-resolution object regions support heading estimation.

See the [paper](https://arxiv.org/pdf/2610.03015) for the full abstract, architecture, and experimental details.
