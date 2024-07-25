# KimpTracker API Documnetation
해당 레포지토리는 [swagger-github-pages](https://github.com/peter-evans/swagger-github-pages)를 템플릿으로 사용해 KimpTracker Open API 를 [Swagger UI](https://github.com/swagger-api/swagger-ui) 로 문서화한 레포지토리입니다.

## Github Pages
깃허브 페이지를 통해 무료 호스팅되었습니다. 다음의 링크를 통해 API 문서를 확인할 수 있습니다.
- https://jhj0517.github.io/kimptracker-swagger-ui/

## API Overview
[업비트](https://docs.upbit.com/reference/%EC%A0%84%EC%B2%B4-%EA%B3%84%EC%A2%8C-%EC%A1%B0%ED%9A%8C), [바이낸스](https://binance-docs.github.io/apidocs/spot/en/#introduction)로부터 코인 데이터를, [FXRateAPI](https://fxratesapi.com/)를 통해 환율 데이터를 조회하여 김치 프리미엄을 계산합니다. <br>

각 데이터는 AWS EC2 인스턴스에서 Open API 가 허용하는 한도 내에서 최대한 짧은 인터벌로 갱신됩니다. <br>

REST API 는 AWS Lambda 와 AWS API Gateway 서비스로 구성하였습니다.

