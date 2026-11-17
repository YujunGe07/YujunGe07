# Yujun (Amy) Ge

**Embodied AI, robot learning, and systems that make experiments repeatable.**

Computer Science at **Stanford University** · Research Assistant, **ILIAD Lab / SAIL**

Incoming **Software Development Engineer Intern at Amazon**, Summer 2027

[Email](mailto:yujunge@stanford.edu) · [LinkedIn](https://www.linkedin.com/in/yujun-ge/) · [Explore my code](https://github.com/YujunGe07?tab=repositories)

I build across the loop from **perception to action to evaluation**: extracting motion from video, connecting agents to simulators, and making their behavior measurable. My work spans multimodal learning, dexterous manipulation, world models, and agents that recover when a workflow breaks.

## What I am working on

| Area | Work |
| --- | --- |
| **Robot learning** | Multimodal learning and generalization across physical platforms, environments, and tasks at Stanford's ILIAD Lab. |
| **World models and simulation** | Shared environment, sensor, and rollout interfaces across FlyBody, MuJoCo, CARLA, and Unreal Engine as a founding AI engineer at Common Origin. |
| **Reliable experiments** | Structured logs, validation, automated evaluation, and failure recovery for simulation and agent workflows. |

Previously: embodied AI engineering at **AtomBite**, browser agents at **Kairos UGC**, and anomaly detection at **Haurlan**. Those roles involved demonstration capture and manipulation pipelines, persistent browser simulations, and model evaluation with synthetic data.

## Selected builds

### [Human to Humanoid Motion](https://github.com/YujunGe07/human-to-humanoid-motion)

**Camera keypoints into robot joint states.** A standalone vision and robotics prototype with YOLO pose estimation, confidence checks, joint-limit clamping, a custom humanoid URDF, and ROS 2 / RViz visualization. Includes a desktop preview that runs without ROS.

`Python` · `YOLO` · `OpenCV` · `ROS 2` · `URDF`

### [Molecular Identity to Visual Wiring](https://github.com/YujunGe07/common-origin-techical-challenge)

**Can gene expression help predict neural connectivity?** An independent public-data challenge project joining Drosophila expression and connectome data across **17 neuron types and 272 directed pairs**. Ridge regression is evaluated against simple baselines on held-out pairs and held-out neuron types, with results and limitations committed alongside the pipeline.

`Python` · `Computational neuroscience` · `Ridge regression` · `Generalization`

### [BERT Embedding Compression](https://github.com/YujunGe07/bert-embedding-compression)

**How much of an embedding do we need to keep?** Preliminary experiments on PCA compression and transfer across data distributions. The initial AG News run retained **83.4% classification accuracy at 128 dimensions**, compared with **83.0% at 768 dimensions**. Separate PCA-fit/classifier-train splits and category-shift tests examine how robust that result is.

`PyTorch` · `Transformers` · `PCA` · `Representation learning`

### [AI-Driven Tennis Coaching](https://github.com/YujunGe07/AI-Driven-Tennis-Coaching)

**Find a professional stroke to compare with your own.** ViViT video embeddings and nearest-neighbor retrieval for tennis video comparison, accompanied by the research paper. The study examines how court appearance, clip duration, and camera angle affect matching.

`ViViT` · `Video retrieval` · `Computer vision`

### [URTC Scheduling Portal](https://github.com/YujunGe07/urtc-registration)

**Software around the research community.** Separate presenter and organizer workflows, server-side scheduling checks, booking conflict handling, and calendar exports. An isolated presenter demo is available in the [portal](https://yujunge07.github.io/urtc-registration/).

`TypeScript` · `React` · `Supabase` · `GitHub Actions`

More projects: [ECG signal analysis](https://github.com/YujunGe07/ECG-Signal-Analysis) · [Assistive communication](https://github.com/YujunGe07/V1_AI_ML_AAC) · [Prediction-market matching engine](https://github.com/YujunGe07/haurlan-lite)

## Research and recognition

- **Regeneron Science Talent Search Scholar.**
- **Independent author of an IEEE publication presented at MIT URTC 2025**, receiving the **4th Place Best Paper Award**.
- **First author of an IEEE publication on AI-driven tennis coaching.**

## Tools I work with

| | |
| --- | --- |
| **Learning and perception** | Python, PyTorch, TensorFlow, Hugging Face, scikit-learn, multimodal models, computer vision |
| **Robotics and simulation** | MuJoCo, CARLA, Unreal Engine, FlyBody, ManiSkill3, SAPIEN, LeRobot, ROS 2, URDF, FK/IK |
| **Agents and engineering** | Playwright, Docker, tool orchestration, automated evaluation, structured logging, TCP/JSON |
| **Applications and data** | Java, JavaScript, TypeScript, SQL, Flask, PostgreSQL, Elasticsearch, Git, CI/CD |

I am especially interested in how learned systems behave when the camera, environment, task, or embodiment changes, and how to build the infrastructure to investigate that reliably.
