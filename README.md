# 에코와트 ECOWATT 에너지 절감 계산기

가전제품의 소비전력과 사용시간만 입력하면 한 달 전기 절감량·절감 금액·탄소 감축량을 계산해 주는 무료 교육용 웹 도구입니다.

- 사이트: https://ecowatt.coalab.co.kr
- 구성: 단일 `index.html` (HTML + CSS + JavaScript, 빌드 과정 없음)
- 기능: 에너지 절감 / 탄소발자국 / 한 달 기록(브라우저 저장) / 기온 조회(Open-Meteo, 키 불필요)
- 개인정보: 입력값과 기록은 이용자의 브라우저에만 저장됩니다.

※ 결과는 교육용 추정치이며 실제 전기요금(기본요금·누진제·세금)과 다를 수 있습니다.

## 배포
Netlify 정적 호스팅(빌드 명령 없음, 게시 폴더는 루트). 커스텀 도메인 `ecowatt.coalab.co.kr`은 Cloudflare DNS의 CNAME(DNS only)으로 연결되어 있습니다. 현재는 Netlify Drop 방식 배포라, 수정 후에는 Netlify에 다시 업로드해야 반영됩니다.

## 사진 출처
Photo by Sian Wynn-Jones on Unsplash

## 만든 곳
COALAB 코아랩
