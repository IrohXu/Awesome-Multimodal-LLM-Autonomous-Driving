# Multimodal Large Language Models for Autonomous Driving (WACV 2024 LLVM-AD)

## Datasets

The table is inspired by Comparison and stats in DriveLM

| Dataset  |    Base Dataset    |    Language Form    |   Perspectives  |   Scale      |  Release?  |
|:---------:|:-------------:|:-------------:|:------:|:--------------------------------------------:|:----------:|
| [BDD-X 2018](https://github.com/JinkyuKimUCB/explainable-deep-driving)  |  [BDD](https://bdd-data.berkeley.edu/)  | Description | Planning Description & Justification    | 8M frames, 20k text strings   |**:heavy_check_mark:**|
| [HAD HRI Advice 2019](https://usa.honda-ri.com/had)  |  [HDD](https://usa.honda-ri.com/hdd)  | Advice | Goal-oriented & stimulus-driven advice | 5,675 video clips, 45k text strings   |**:heavy_check_mark:**|
| [Talk2Car 2019](https://github.com/talk2car/Talk2Car)   |      [nuScenes](https://www.nuscenes.org/)    | Description |  Goal Point Description | 30k frames, 10k text strings | **:heavy_check_mark:**|
| [SUTD-TrafficQA 2021](https://github.com/sutdcv/SUTD-TrafficQA)   |      -    | QA |  QA | 10k frames 62k text strings | **:heavy_check_mark:**|
| [DRAMA 2022](https://usa.honda-ri.com/drama)   |  - | Description |  QA + Captions | 18k frames, 100k text strings | **:heavy_check_mark:**|
| [nuScenes-QA 2023](https://arxiv.org/abs/2305.14836)   |   [nuScenes](https://www.nuscenes.org/)  | QA |  Perception Result     | 30k frames, 460k generated QA pairs| **:heavy_check_mark:** |
| [DriveLM 2023](https://github.com/OpenDriveLab/DriveLM) | [nuScenes](https://www.nuscenes.org/) | QA + Scene Description | Perception, Prediction and Planning with Logic | 30k frames, 360k annotated QA pairs |**:heavy_check_mark:** |
| [MAPLM 2023](https://github.com/LLVM-AD/MAPLM) | [THMA](https://dl.acm.org/doi/10.1609/aaai.v37i13.26848) | **:boom: QA + Scene Description** | **:boom:Perception, Prediction and HD Map Annotation** | 100k+ frames, 900k+ annotated Scene Description + QA pairs | **:heavy_check_mark:** |

## Awesome Papers

### MLLM for Perception

| Model  |    Year     |    LLM    |   Param  |    Modalities      |  Learning   |   Workflow  |
|:---------:|:-------------:|:-------------:|:------:|:--------------------------------------------:|:----------:|
| Driving with LLMs |  2023  | LLaMA-7b  |  7B   |  numeric+language   | FT | Propose a object-level multimodal LLM that merges vectroized numeric modalities with a pre-trained LLM. |

### MLLM for Planning & Control




## Papers Accept in WACV 2024 LLVM-AD    

### Long Paper     

TBD

### Tech Report (Short Paper)       

TBD

## Citation    

If the survey and our workshop inspire you, please cite our work:    

```
@article{wacv2024multimodalllm,
  title={Multi-Modal Large Language Models for Autonomous Driving},
  author={WACV 2024 LLVM-AD Organization Committee},
  journal={WACV 2024 Workshop},
  year={2024}
}
```


