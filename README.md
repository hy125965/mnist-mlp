# mnist-mlp
머신러닝 입문 10주차 — MNIST 손글씨 숫자 MLP (PyTorch)

## 실행 방법
```
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python mnist_mlp.py
```
## 결과
- 3 에폭, hidden 128: 테스트 정확도 0.961 (CPU 13초)
- 5 에폭, hidden 256: 테스트 정확도 0.97x

## 파일
- `mnist_mlp.py` — 학습 스크립트
- `requirements.txt` — 필요한 패키지
