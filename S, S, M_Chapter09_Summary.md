# 9. Thre Three-dimensional Field : Depth and Volume(3차원 영역 : 깊이와 부피)
이 장에서는 z 축, 그래픽 깊이 계수, 렌즈의 깊이 특성 및 입체 투영의 네 가지 특정 3 차원 필드 영역을 살펴 본다.

## _1. Z축_
3 차원 모델에서는 깊이를 나타내는 z 축이 추가된다.
놀랍게도 환상적인 3차원(깊이)은 영화, 특히 비디오에서 가장 유연한 화면 차원임을 입증한다.

## _2. 그래픽 깊이 요소_

### 겹치는 평면들
가장 직접적인 그래픽 깊이 신호는 겹치는 평면이다. 한 물체가 다른 물체에 의해 부분적으로 가려진 것을 볼 때, 
당신은 덮고있는 물체가 부분적으로 가려진 물체 앞에 있어야한다는 것을 알고 있다.

### 상대적 크기
물체의 크기를 알고 있거나 상황에 맞는 단서 (예 : 다른 알려진 물체)로 물체의 크기를 추측 할 수 있다면 
화면 이미지의 상대적인 크기로 물체가 카메라에서 얼마나 멀리 떨어져 있는지 알 수 있습니다.

### 평면에서의 높이
모순되는 거리 신호가 분명하지 않고 카메라가지면과 평행하게 촬영한다고 가정하면 사람과 물체가 사진 영역에서 더 높이 올라 갈수록 점점 더 멀어지는 것으로 인식된다. 
이 거리 신호는 수평선에 도달 할 때까지만 작동한다.

### 직선적 원근법
선형 원근법에서 모든 물체는 멀어질수록 점차 작아 보이고 평행선은 멀리서 수렴하며 수직선과 수평선은 관찰자 (카메라)로부터 멀어 질수록 더 붐비게된다.

_강제된 원근법_ : 우리는 이미지 크기와 수렴을 해석하는 경향이 있기 때문에 상대적인 거리가있는 선을 사용하면 평행선이 "더 빨리" 수렴되도록 하여 
(더 쉽게) 거리의 느낌을 생성하고 먼 물체를 일반적으로 인식하는 것보다 작게 보이게 만들 수 있다.

### 공중 원근법
우리는 멀리있는 물체보다 우리와 가까운 물체를 더 선명하게 볼 수 있는데, 이를 공중 원근이라고 한다.

## _3. 렌즈의 심도 특성_
렌즈의 광학적 특성은 비디오 또는 영화 화면에서 3 차원의 환상을 크게 향상 시키거나 방해 할 수 있다.

### 평면 겹치기 : 넓은 앵글 렌즈
광각 렌즈는 협각 렌즈만큼 겹치는 평면에 의존하지 않지만 표시하는 것을 피할 수 없다.

### 평면 겹치기 : 좁은 앵글 렌즈
협각 렌즈는 광각 렌즈와는 반대로 물체가 실제보다 z 축을 따라 더 가깝게 보이게 한다.

### 상대적 크기 : 넓은 앵글 렌즈
광각 렌즈는 상대적인 크기를 크게 과장한다.

### 상대적 크기 : 좁은 앵글 렌즈
같은 장면을 협각 렌즈로 촬영하면 두 배가 훨씬 더 가까워 보입니다.

### 직선적 원근법 : 광각 렌즈
광각 렌즈는 평행선의 수렴을 가속화합니다. 즉, 일반적으로 볼 때보다 더 빨리 수렴하는 것처럼 보이므로 물체나 건물이 늘어나는듯한 착각을 준다. z 축 공간은 길쭉하게 표시된다.

### 직선적 원근법 : 협각 렌즈
반대로 협각 렌즈는 평행선의 정상적인 수렴을 억제하므로 선형 원근법을 통해 깊이의 환상을 줄인다.

### 공중 원근법으로 작업하기
필드의 깊이 (초점에 표시되는 z 축을 따라있는 영역)를 조작하고 선택적 초점을 사용하여 즉, z 축을 따라 특정 영역에만 초점을 맞추면 항공 원근을 얻을 수 있습니다.

_공중 원근법-광각 렌즈_ : 광각 렌즈는 큰 피사계 심도를 생성하기 때문에 공중 원근을 덜 강조한다.

_공중 원근법-협각 렌즈_ : 협각 렌즈는 피사계 심도가 얕아서 공중 원근을 강조한다.

_선택적 집중_ : 선택적 포커스 기술을 사용하면 포커스를 맞출 z축의 정확한 부분(평면)을 선택할 수 있으며, 포커스의 바로 앞이나 뒤에 있는 영역이 포커스를 벗어난다.

_선반 집중_ : 랙 초점 효과에는 z 축의 한 위치에서 다른 위치로 초점을 변경하는 것이 포함된다.

## _4. 3D 입체적 영사_
입체 디스플레이는 방금 살펴본 3 차원의 표준 표현과 기술적으로나 미학적으로 다르다.

### 입체적 3D vs 표준 3D : 기술적 차이
표준 3D와 입체 3D의 기본적인 기술적 차이점은 표준 3D는 사건의 단일 렌즈 또는 외눈 보기를 기반으로 하고 입체 3D는 이중 렌즈 또는 양눈 보기를 기반으로 한다는 것이다.

### 입체적 3D vs 표준 3D : 미학적 차이
이 장의 시작 부분에서 언급했듯이 비디오 및 영화의 표준 1 렌즈 투영의 시뮬레이션 된 3D 공간과 2 렌즈 입체 3D 투영 사이의 주요 미학적 차이는 투영된 이벤트의 z 축을 인식하는 방법이다.
