## CUDA 설치 및 복구

딥러닝 연구를 진행하기 이전 그래픽카드를 구매하셨다면 CUDA를 설치해주셔야 합니다.

### **CUDA를 설치하지 않으셨다면 그래픽카드를 구매하시고 사용하지 않는 것과 같습니다.**

필자의 환경에서 여러번 시행착오를 통해 겪었던 내용을 정리 및 공유합니다. 

컴퓨팅 환경이 조금 다르거나 가상환경 오류로 인한 재설치가 필요하신 상태이시더라도 해당 문서를 참고하시어 설치를 진행하신다면 시행착오로 발생하는 시간을 덜 수 있습니다. 

다음 노션 페이지를 접속하시어 해당하시는 상황에 맞춰 페이지 이동 부탁드립니다.

감사합니다.

[노션 페이지 이동](https://earthy-cave-bb0.notion.site/CUDA-_-e60752805b1945dbaa0cfb7dc6cf6ff7)

#### 필자의 설치 환경

- Window10 64-bit
- Python 3.7
- NVIDIA GeForce RTX 3060 / ZOTAC / 12GB
- CUDA Toolkit 11.1 (pytorch 사용을 위함)

- cuDNN v8.1.1.33 for CUDA Version 11.2
- NVIDIA GPU drivers 461.72 notebook