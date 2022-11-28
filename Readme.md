# 브랜드페이 PHP 샘플

토스페이먼츠 브랜드페이 PHP 샘플입니다. [Docs](https://docs.tosspayments.com/guides/brandpay/overview)내 기본연동(quickstart), 위젯연동(widget)을 기본으로 합니다.


## 시작하기 


```sh
├── common
│   ├── var.php // 사전 세팅 (API KEY 등)
│   └── confirm-payment.php // 결제승인(https://docs.tosspayments.com/reference/brandpay#결제-승인)
│   └── callback-auth.php   // 인증(https://docs.tosspayments.com/guides/brandpay/auth)
│
├── static
│   ├── image
│   └── css
│
├── quickstart // 기본연동
└── widget // 위젯 연동
```