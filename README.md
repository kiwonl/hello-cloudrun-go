Cloud Build 를 사용하여 소스코드로 부터 컨테이너 이미지 빌드 후 저장소(Container Registry)에 저장
+ Artifact Registry 사용을 권장하나 간단할 설명을 위해 Container Registry 를 사용
```
$PROEJCT_ID==[YOUR-PROJECT-ID]
$gcloud builds submit -t gcr.io/${PROEJCT_ID}/hello-cloudrun-go .
```

+ Container Registry 에 저장된 컨테이너 이미지 확인
```
$gcloud container images list
NAME
gcr.io/kwlee-app-eco-sandbox/hello-cloudrun-go
```
