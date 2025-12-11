# DeepFakeDetection
This repository provides a curated collection of research papers, datasets, benchmarks, and tools related to DeepFake detection. It serves as a comprehensive resource hub for researchers and practitioners interested in exploring state-of-the-art methods and emerging trends in DeepFake analysis and detection.

## 📊DeepFake Datasets Overview

| Dataset | Year | Size | Manipulations | Description | Link |
|---------|------|-------|----------------|-------------|-------|
| **FaceForensics++** | 2019 | 1.9M frames | FaceSwap, DeepFake | Benchmark containing pristine and manipulated videos | [Dataset](#) |
| **Celeb-DF v2** | 2020 | 5,639 videos | DF, FS | High-quality, realistic DeepFake videos | [Dataset](#) |
| **DFDC** | 2020 | 100K+ videos | Multiple | Large-scale dataset from Facebook challenge | [Dataset](#) |
| **UADFV** | 2018 | 49 videos | DeepFake v1 | Early DeepFake detection dataset | [Dataset](#) |
| **DeeperForensics 1.0** | 2020 | 60,000 videos | Real-world distortions | Realistic conditions & perturbations | [Dataset](#) |
| **KoDF (Korean DeepFake Dataset)** | 2021 | 625K clips | Multiple | High-quality Asian face dataset | [Dataset](#) |
| **WildDeepFake (WDF)** | 2021 | 3,509 videos | Internet-scraped | Real-world DeepFake videos collected from the web | [Dataset](#) |
| **ASVspoof 2019/2021** | 2019/21 | Audio | Voice cloning | Dataset for audio spoofing & voice DeepFakes | [Dataset](#) |

## Concepts
1. Detecting Artificial Images via Vanishing-Point Geometry \
   powerful clue for spotting AI-generated is through geometry of the scene and not the pixels.

  Real photographs follow strict perspective rules because they originate from a single camera viewpoint. One of these rules is the presence of a dominant vanishing point, where parallel lines in the world appear to meet.

  AI-generated images, however, often fail this test. Instead of aligning toward one shared vanishing point, different parts of the scene may drift toward multiple, inconsistent convergence  points.

  Why? Because generative models assemble scenes in segments, and they don’t always maintain a unified 3D perspective across the entire frame.

  These subtle geometric inconsistencies create a reliable signal: even when the image looks perfect, the perspective may quietly reveal it’s generated.
2. ss
