+++
title = "소개"
chapter = true
weight = 10
pre = "<b>1. </b>"
+++

이번 Lab에서는 과거 자전거 대여 수 데이터를 가지고 Amazon Forecast를 활용하여 시계열 예측 모델을 만들어 봅니다.

## 준비사항
* AWS 계정: AWS IAM, S3, SageMaker 자원을 생성할 수 있는 권한이 필요합니다. 
* AWS Region: SageMaker는 지원되는 region은 [AWS Regional Product Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/) 에서 확인하실 수 있습니다. 이번 실습은 `N. Virginia (us-east-1)` region 에서 실행 합니다. 
* Browser: 최신 버전의 Chrome, Firefox를 사용하세요.

### 주의 사항
Notebook 안의 Cell에서 코드 실행후 결과 값이 나오는 데는 수 초가 걸립니다. 훈련 Job을 실행하는 경우 수 분이 걸릴 수도 있습니다.  실습 완료 후에는 아래 가이드에 따라  생성된 자원을 꼭 종료/삭제해 주세요. 

## Contact Us
AWS 서비스에 관한 질문은 AWS Support나 담당 AM을 통해서 문의해 주시고 본 워크샵의 발표자료에 관한 질문 사항은 아래의 email 링크를 통해 문의해 주시면 감사하겠습니다.

<center>{{% button href="mailto:ml-tfc-kr@amazon.com" icon="far fa-envelope" %}}Email us{{% /button %}}</center>

© 2019 Amazon Web Services, Inc. 또는 자회사,

All rights reserved.