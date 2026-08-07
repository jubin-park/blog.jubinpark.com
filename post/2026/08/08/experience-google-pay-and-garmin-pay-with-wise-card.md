대한민국에서는 비주류인, 구글 픽셀 휴대폰을 들고 생활한다는 건 다소 불편한 일입니다. 사서 고생할 정도로요.
구글 픽셀 1세대가 나온지도 벌써 10년이 지났지만, 국내에 정식 발매가 된 적은 한 번도 없습니다.
또한 국내에서 픽셀로 통신을 하려면, VoLTE 패치를 불가피하게 해야 하는 상황에 부딪힙니다.
감사하게도 국내 구글 픽셀 커뮤니티에서는 꾸준히 해결책이 발굴되고, 또 공유되고 있습니다.

예전부터 저는 픽셀 폰으로 물건을 현장 결제하고 싶은 로망이 있었습니다. 삼성 갤럭시 폰 패밀리 입장에서는 케이크 한 조각 먹는 수준의 난도죠. [**삼성월렛**](https://play.google.com/store/apps/details?id=com.samsung.android.spay&hl=ko)(前 삼성페이)라는 막강하고 편리한 앱이 있으니까요.
굳이 쉬운 길 놔두고 힘든 길을 가고 싶은건 왜일까요? 답은 '성공하면 기분이 짜릿할 것 같아서' 입니다.

2023년, 대한민국에 애플페이가 정식 도입된 이래로 NFC 방식의 [EMV Contactless](https://www.emvco.com/emv-technologies/emv-contactless-chip/) 결제가 보편화되고 있습니다. 물론 컨택리스 결제를 지원하는 카드 단말기에 한해서만 사용이 가능하지만요. 그 와중에 제 눈을 반짝이게 하는 정보를 발견했습니다.

위키피디아에 의하면, 애플페이와 구글페이는 동일한 컨택리스 결제를 사용한다고 합니다.

> Apple Pay on iPhones and Google Pay on Android mobile phones are common forms of contactless payments used.
  https://en.wikipedia.org/wiki/Contactless_payment

이런 애플페이의 수혜(?)에 힘입어, 문득 구글페이와 가민페이의 사용 경험을 하고 싶어졌습니다.
조사를 해보니, 구글페이는 국내용 카드의 등록이 불가능 하다고 합니다. 가민페이의 상황도 마찬가지였습니다.

그러나 영국의 [Wise](https://en.wikipedia.org/wiki/Wise_(company)) 카드가 이 문제를 해결할 수 있었습니다. 조사 중 폴란드의 [ZEN 닷컴](https://en.wikipedia.org/wiki/ZEN.com) 카드사도 덩달아 언급되곤 하는데, 지금 시점에선 발급하기 까다로워졌나 봅니다.

# Wise 카드
[Wise](https://play.google.com/store/apps/details?id=com.transferwise.android) 앱을 설치하고 비실물 카드를 하나 만들었습니다. **20 파운드**를 자신의 Wise 계좌에 넣으면 발급 신청이 가능합니다. 다행히도 신청 비용이 들진 않았습니다. 하지만 결제할 때마다 수수료는 들지만요. 신청 방법은 구글에 검색하면 정보를 얻을 수 있습니다.

# 가민페이
가민 시계를 사용하는 분들은 아시겠지만, 시계 설정을 위해서는 **[Garmin Connect** ](https://play.google.com/store/apps/details?id=com.garmin.android.apps.connectmobile)앱이 필요합니다.
그 앱의 **Settings** - **Wallet & Garmin Pay** 라는 메뉴에서 카드를 등록할 수 있습니다.
참고로 태국의 [래빗 카드](https://en.wikipedia.org/wiki/Rabbit_Card)라는 것도 등록할 수 있더군요. 그건 잘 모르겠고, 제 Wise 카드를 등록했습니다.

그러면 결제 비밀번호 4자리를 새로 만들라고 합니다. 시계에서 결제 기능을 사용하기 전 입력하는 패스코드입니다. 결제 때마다 항상 입력하는 건 아니고, 시간이 어느 정도 지나야만 패스코드 입력 창이 다시 나타납니다. 그 시간 주기는 모르겠어요.

편의점에 들어갑니다. 미리 가민 시계로 결제 준비를 마칩니다. 간식을 카운터에 들고 갑니다. '이게 정말 될까?' 하면서 괜히 긴장이 됩니다. 혹여나 실패할까 2차 결제 수단도 미리 준비합니다. 기대감과 함께 시계를 찬 손목을 단말기에 올립니다.

마침내 3100원 첫 결제에 성공했습니다. 가격 1.64 파운드, 수수료 0.01 파운드가 발생했습니다. 1 파운드 = 1905.83원인 시점에 결제가 됐네요.

# 구글페이
[**Google Wallet**](https://play.google.com/store/apps/details?id=com.google.android.apps.walletnfcrel)앱을 설치하는 것부터가 관건이었습니다.
사용하는 계정 프로필의 지역이 대한민국이라 lock에 걸린 것인지, 설치가 아예 불가능합니다.
Play Store에서 일본 프로필 구글 계정으로 전환했더니 설치할 수 있었습니다.

이후 구글 월렛을 실행해서 Wise 카드 등록을 시도했습니다. 폰의 부트로더가 Unlock 상태여서 등록에 계속 실패하고 맙니다. 3단계의 Play Integrity가 일부 깨져서 사용이 불가능한 상태였습니다.

사실은 순정 상태(부트로더가 잠긴 상태)여야만 구글페이를 정상적으로 이용할 수 있습니다. 하지만 부트로더를 다시 lock 하면 휴대폰의 모든 데이터가 초기화됩니다. 그건 죽어도 싫어서 대신 루팅을 했습니다. 성가시지만 VoLTE 패치 하신 분들은 자주 하시는 경험일 것입니다.

이후 구글페이 한 번 써보려고 이렇게까지 해야하나 허무감이 느껴지기 시작합니다. 하지만 제 호기심은 해소되어야만 했습니다. 여러 개의 Apatch 패치 모듈을 설치해야 했는데 꽤 복잡했습니다. 저는 이 [가이드](https://xdaforums.com/t/updated-01-29-2026-guide-get-strong-integrity-on-android-16-fix-banking-apps-revolut-google-wallet-apatch-method.4753805/)를 따라하면서 (일부 outdated 내용이 있지만) 우여곡절 끝에 Play 무결성 3단계를 모두 통과하는 데 성공합니다.

1. ✅ MEETS_DEVICE_INTEGRITY
2. ✅ MEETS_BASIC_INTEGRITY
3. ✅ MEETS_STRONG_INTEGRITY

성공적으로 구글월렛의 카드 등록도 성공했습니다. 이후 루팅을 감지해서 뻗어버리는 어플들 때문에 루팅을 해제했습니다. 이 상태로 편의점에 결제하러 갔습니다.

결제가 잘 됐습니다.

별 거 아닐 수도 있겠지만, 이런 희소성 있는 사용자 경험을 하니 괜히 기분이 좋습니다. 구글 폰이나 구글페이가 국내에 도입이 될 지는.. 앞으로도 미지수라고 생각하고요. EMV 컨택리스 단말기가 앞으로도 다양한 매장에 많이 확대되고 보편화되기를 기원하며, 이만 글을 마칩니다.

고마워요 애플페이!