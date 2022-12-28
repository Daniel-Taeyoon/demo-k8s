# Kubernetes Guide
- minikube 설치 후 minikube start로 실행해야 명령어 동작 가능.
- "deployment.yml" 파일 역할은?
  -> 디플로이먼트는 파드와 레플리카에 대한 선언적 업데이트를 제공한다.

### File Structure
- eks-sample-(deployment, service) / iam_policy.json : EKS 실습파일
  - 참고 : https://docs.aws.amazon.com/ko_kr/eks/latest/userguide/sample-deployment.html
- k8s-(deployment, service, ingress) : Local 실습파일.
  - 참고 : https://kubernetes.io/ko/docs/concepts/workloads/controllers/deployment/