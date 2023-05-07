
# Cloud Run Quick Demo - 1 (컨테이너 이미지로부터 Cloud Run 프로비저닝 하기)


# Cloud Run Quick Demo - 2 (소스코드로부터 Cloud Run 프로비저닝 하기, Feat. Cloud Build)
1. 소스 코드 clone
```
git clone https://github.com/kiwonl/hello-cloudrun-go && cd hello-cloudrun-go
```

2. "Cloud Build" 로 소스코드 빌드 및 저장소 푸시
```
PROEJCT_ID=[YOUR-PROJECT-ID]
gcloud builds submit -t gcr.io/${PROEJCT_ID}/hello-cloudrun-go .
gcloud container images list
```

3. "Continuously deploy new revision from a source repository" 를 통해 저장소 연동 후 배포


# Cloud Run Quick Demo - 3 (2에서 사용한 소스코드 수정 후 재배포 확인)

# Cloud Run Quick Demo - 4 (Cloud Deploy 를 사용해 여러 환경 배포)
```

```







