## [pytorch tutorial](https://pytorch.org/tutorials/beginner/basics/intro.html)

pytorch tutorial을 실습한 파일들입니다.

- 0_quickstart.ipynb
  - PyTorch를 사용하여 FashionMNIST 데이터셋으로 간단한 신경망 모델을 만들고 학습하는 과정을 다룬다
  - 데이터셋을 내려받고 DataLoader로 데이터를 로딩하며, 신경망 모델을 정의하고 학습하는 방법
  - 학습한 모델을 저장하고 불러오는 방법

- 1_Tensors.ipynb
  - PyTorch의 텐서 생성, 속성 및 연산에 대한 내용
  - 코드에서는 텐서를 생성하는 다양한 방법과 텐서의 속성(크기, 데이터 유형, 저장 장치)을 확인하는 방법과 텐서 간의 연산과 슬라이싱을 다룬다.
  - NumPy 배열과의 상호 운용성과 텐서와 NumPy 배열 간 데이터 공유의 특징을 설명

- 2_Dataset%20Dataloaders.ipynb
  - PyTorch의 데이터셋과 데이터로더(DataLoader)를 사용하여 데이터를 불러오고 훈련 준비를 하는 방법을 설명
  - FashionMNIST 데이터셋을 사용하여 데이터를 로드하고 시각화하며, 사용자 정의 데이터셋 클래스를 생성하는 방법 실습
  -  데이터로더를 사용하여 데이터를 미니배치로 묶어주고 반복하면서 모델 훈련에 사용할 수 있는 형태로 데이터를 처리하는 방법 실습

- 3_Transformers.ipynb
  - torchvision의 ToTensor 변환을 사용하여 이미지를 텐서로 변환하고, Lambda 변환을 사용하여 사용자 정의 람다 함수를 적용하여 라벨을 원핫 인코딩으로 변환하는 방법을 설명
  - ToTensor 변환은 이미지를 [0, 1] 범위로 스케일링하여 텐서로 변환하며, Lambda 변환은 사용자가 지정한 람다 함수를 사용하여 데이터 변환을 수행한다

- 4_Build%20The%20Neural%20Network.ipynb
  - PyTorch의 nn.Module을 사용하여 신경망 모델을 정의하고, 다양한 레이어 및 연산을 살펴보며 모델의 구조와 매개변수를 출력하는 방법을 설명한다.
  - 모델은 nn.Sequential로 레이어를 순차적으로 쌓아 구성할 수 있으며, nn.Linear는 선형 변환을 수행하고 nn.ReLU는 활성화 함수로 사용된다.
  - 모델의 매개변수 정보를 출력하고, 요약 정보를 통해 모델의 구조와 매개변수 개수를 확인하며, 매개변수의 gradient 정보을 확인하는 방법을 실습

- 5_Automatic%20Differenctiation%20With%20Torch%20AutoGrad.ipynb
  - PyTorch의 autograd에 대해 알아보기
  - PyTorch의 autograd는 미분 가능한 연산을 추적하여 연산 그래프를 생성하고 역전파를 통해 그래디언트를 자동으로 계산하는 기능을 제공한다.
  - requires_grad=True를 설정하면 해당 텐서의 그래디언트를 계산하고 연산 그래프를 생성하고 이 그래프는 순전파에서 연산을 계산하고 동시에 그래디언트 함수를 유지하여 역전파 시 각 텐서의 .grad_fn을 통해 변화도를 계산하고 이를 누적하여 전파한다.

- 6_Optimizing Model Parameters
  - PyTorch를 사용하여 모델을 훈련하고 평가하는 과정
  - 데이터 로더, 손실 함수, 최적화 기법 등을 사용하여 훈련 루프와 검증 루프를 구성하고, 모델의 가중치를 최적화하여 성능을 개선한다.
  -  FashionMNIST 데이터셋을 사용하여 모델을 훈련하고 평가하는 예시를 실습한다.

- 7_Save and Load the Model
  - PyTorch에서 모델 가중치와 모델 구조를 저장하고 불러오는 방법
  - 모델의 가중치는 `state_dict()`를 사용하여 저장하고 불러올 수 있으며, 모델 구조와 가중치를 함께 저장하기 위해 `torch.save()`와 `torch.load()`를 사용할 수 있다.





위 내용들을 정리하여 [블로그](https://leejeahyuk.github.io/categories/#pytorch)에 올려 두었습니다.

