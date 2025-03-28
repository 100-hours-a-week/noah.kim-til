# AI workflow
- 사전 학습 모델을 이용하여 이미지 분류 테스트 수행했습니다.
- 원하는 테스트에 적합하도록 Fine Tuning을 진행했습니다.
- AI 관련 concept들을 이해하며 모델들의 학습 성과를 설명하도록 노력했습니다.

1. 서론
- 이미지 분류는 다양한 산업에서 핵심 기술로 활용됨.
- 본 연구는 VGG16, ResNet50, ResNet18 모델을 비교해 채소 이미지 데이터셋 분류 성능을 평가하는 것이 목적임.

2. 관련 연구
- VGG16: 단순하고 깊은 구조, 3x3 필터 사용. 기울기 소실 문제 존재.
- 기울기 소실: 깊은 신경망에서 역전파 시 기울기가 점점 작아지는 문제.
- ResNet: 잔차 연결(Shortcut)로 기울기 소실 해결. ResNet50은 Bottleneck 구조 사용.

3. 실험 방법
- 데이터셋: 채소 이미지 21,000장, 15개 클래스, 224x224 크기, 학습/검증/테스트 = 70/15/15.

4. 실험 결과 및 분석
- ResNet50:
    - 훈련 정확도 98.6%, 테스트 정확도 91.37%.
    - 과적합 조짐 있음. 검증 손실 증가 구간 존재.

- VGG16:
    - 훈련 정확도 92.94%, 테스트 정확도 91.37%.
    - 안정적인 수렴, ResNet50과 유사한 성능.

- ResNet18:
    - 훈련·검증·테스트 정확도 모두 99.93%.
    - Loss 거의 0에 수렴. 데이터셋이 너무 쉬운 가능성 제기됨.

6. 결론
- 연구 목표 달성: 모델 비교 및 성능 분석 성공적으로 수행.

- 성능 요약: 모든 모델이 90% 이상 정확도 기록. ResNet18이 가장 높지만 데이터셋 한계 고려 필요.
- 추가 연구: 다양한 데이터셋, 최신 모델(EfficientNet 등), 하이퍼파라미터 최적화 등 확장 예정.

7. 실습 코드
- [vgg16.ipynb](https://github.com/100-hours-a-week/noah.kim-til/blob/main/vgg16.ipynb)
- [resnet50.ipynb](https://github.com/100-hours-a-week/noah.kim-til/blob/main/resnet50.ipynb)
- [resnt18.py](https://github.com/100-hours-a-week/noah.kim-til/blob/main/resnet18.ipynb)

# til-template

## 오늘 내가 배운 것들(Today I Learned)

### [2월 1주차] : void 인강 정리 (js 응용) & 웹개발 프로젝트 실습

25.02.03 [실행 컨텍스트 & this 바인딩 분석](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-03.md)

25.02.04 [numpy, pandas](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-04.md)

25.02.05 [numpy, pandas(2)](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-05.md)

25.02.06 [numpy, pandas(마무리)](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-06.md)

25.02.07 [풀스택 프로젝트 따라해보기](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-07.md)

25.02.08 [풀스택 프로젝트 따라해보기2](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-08.md)

25.02.09 [풀스택 프로젝트 따라해보기3](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-09.md)

### [2월 2주차] : 웹개발 프로젝트 실습 

25.02.10 [풀스택 프로젝트 따라해보기4](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-10.md)

25.02.11 [크램폴린 특강](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-11.md)

25.02.12 [데이터 시각화 matplotlib](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-12.md)

25.02.13 [데이터 시각화 matplotlib2](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-13.md)

25.02.14 [책 읽기-시작! AWS](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-14.md)

25.02.15 [Alex 수학 강의 & 네이버 현직자 특강](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-15.md)

25.02.16 [코드 리팩토링: 인자가 많은 메서드 개선 방법 알아보기](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-16.md)

25.02.17 [API & 크롤링 관련 이모저모](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-17.md)

25.02.18 [Feign 코드 분석과 서버 성능 개선 방법 알아보기](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-18.md)

25.02.19 [null 반환 지양 이유와 개선 방법](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Feb/2025-02-19.md)

25.02.20 ~ 25.03.02 [아이디어톤 & 해커톤](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-02.md)

25.03.03 [AI 서버 EC2 인스턴스에 배포한 뒤, http 메서드로 테스트](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-03.md)

25.03.04 [사전 훈련 모델 활용](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-04.md)

25.03.05 [model max token 이슈 해결 & 캐싱](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-05.md)

25.03.06 [캐싱 & api 응답 조정](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-06.md)

25.03.07 [커넥팅 데이: 특강 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-07.md)

25.03.08 [밥팟 ai 파트 고도화](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-08.md)

25.03.09 [springboot+mybatis+mysql: 1~9 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-09.md)

25.03.10 [springboot+mybatis+mysql: 10~20 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-10.md)

25.03.11 [코테 공부 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-11.md)

25.03.12 [코테 공부 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-12.md)

25.03.13 [코테 공부 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-13.md)

25.03.14 [코테 공부 정리](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-14.md)

25.03.15 [유사도 검색 고도화를 위한 추가 크롤링 탐색](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-15.md)

25.03.16 [챗봇 제미나이 api로 변경 방안 탐색](https://github.com/100-hours-a-week/noah.kim-til/blob/main/Mar/2025-03-16.md)