# 한성자동차 메르세데스-벤츠 김성한 홈페이지

## GitHub Pages 배포
1. ZIP 압축을 풉니다.
2. 저장소 최상위에 `index.html`, `assets` 폴더, `robots.txt`, `sitemap.xml`이 보이도록 전체 파일을 업로드합니다.
3. GitHub 저장소의 **Settings → Pages**에서 `Deploy from a branch`, `main`, `/(root)`를 선택하고 저장합니다.
4. `https://계정명.github.io/`에서 확인합니다.

## 담당자 정보 수정
- 전화번호/담당자 이름: `index.html`에서 `김성한`, `010-8630-0210` 검색 후 수정
- 상담 폼: 현재는 제출 버튼을 누르면 고객 기기의 문자 앱에 상담 내용이 채워집니다. 고객이 문자 앱에서 직접 전송해야 합니다.
- 카카오톡 링크: 링크가 준비되면 헤더나 상담 영역에 카카오톡 버튼을 추가할 수 있습니다.

## 사진 교체
- 메인 배경 및 차량 이미지는 `assets/css/style.css`의 `.hero-bg`, `.img-sedan`, `.img-suv` 등 `background-image` URL을 변경하면 됩니다.
- 담당자 사진은 `assets/images/consultant.jpg`를 넣고 `.photo-placeholder` 스타일을 실제 사진 배경으로 바꾸면 됩니다.
- 현재 사용된 차량 사진은 디자인용 외부 이미지이며, 실제 판매 차량의 정확한 이미지·트림을 나타내지 않을 수 있습니다.

## 수정이 필요한 부분
- `robots.txt`, `sitemap.xml`의 `YOUR-GITHUB-USERNAME`을 실제 GitHub Pages 주소로 변경하세요.
- 공식 딜러/브랜드 제휴를 오인하게 하는 표현은 사용하지 말고, 전시장·직함·브랜드 로고 사용은 소속사 가이드와 승인을 확인하세요.
- 프로모션, 가격, 재고, 금융 조건은 확정된 최신 자료만 반영하세요.
