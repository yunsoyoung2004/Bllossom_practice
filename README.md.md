# Bllossom 8B Fine-Tuning & Gradio Demo Notebooks

이 저장소는 Llama 3 기반의 Bllossom-8B 한국어 모델을 활용하여 다양한 목적의 파인튜닝 및 데모를 위한 Jupyter 노트북들로 구성되어 있습니다. 각 노트북에 대한 설명은 아래와 같습니다.

## 📁 노트북 설명

### 1. `Bllossom_8B_koAlpaca_fine_tuning.ipynb`
- **설명**: koAlpaca 스타일의 데이터셋을 기반으로 Bllossom-8B 모델을 파인튜닝하는 과정을 담고 있습니다.
- **주요 내용**: 데이터 로딩, LoRA 적용, Trainer 설정 및 파인튜닝 실행.

### 2. `Llama_3_Bllossom_8B_gradio.ipynb`
- **설명**: 파인튜닝된 Bllossom-8B 모델을 Gradio 인터페이스를 통해 실시간 데모 형태로 실행하는 코드입니다.
- **주요 내용**: 모델 로딩, 사용자 입력에 따른 예측 응답 생성, Gradio UI 생성.

### 3. `Tutorial_for_Bllossom_8B.ipynb`
- **설명**: Bllossom-8B 모델을 처음 사용하는 사람들을 위한 튜토리얼 노트북입니다.
- **주요 내용**: 모델 불러오기, 간단한 인퍼런스 테스트 및 토크나이저 활용법 안내.

### 4. `tutorial_SFT_LLM_(lora)_fine_tuning.ipynb`
- **설명**: SFT(Supervised Fine-Tuning) 방식과 LoRA를 활용하여 LLM을 파인튜닝하는 전체 워크플로우를 설명한 튜토리얼입니다.
- **주요 내용**: 데이터 전처리, LoRA 구성, Trainer 세팅, 결과 저장까지 전체 파이프라인 포함.


