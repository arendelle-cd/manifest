# 🚀 Kubernetes 기반 애플리케이션 배포 및 운영 전략 (Canary 배포, HPA)

이 저장소는 **Kubernetes 기반 애플리케이션 배포 및 운영 전략 설계** 의 일부로, Canary 배포와 HPA 관련 코드가 포함되어 있습니다.  
시스템 안정성, 고가용성을 확보하고 운영 효율성을 높이기 위해 설계 및 구축한 기능들을 담고 있습니다.

---

## 📌 기능
- **Canary 배포**: 트래픽 일부를 새로운 버전으로 점진적으로 전환
- **Horizontal Pod Autoscaler (HPA)**: CPU/메모리 기준 자동 스케일링

## 🛠 기술 스택
- **Container / Orchestration**: Kubernetes, Docker  
- **Auto Scaling**: HPA (Horizontal Pod Autoscaler)  
- **Traffic Management**: NGINX Ingress Controller (Canary Routing)

## 🎬 시연 영상

[![시연 영상 썸네일](https://img.youtube.com/vi/_TVC69Qdzdg/0.jpg)](https://youtu.be/_TVC69Qdzdg?si=dJmyHUrNjE2ARqS7)  
**영상 설명:** Canary 트래픽 분배 과정을 시각적으로 보여줍니다.
