# Hi강리가족 · HiClass 링크 허브

직접 데이터를 넣지 않고 **[하이클래스 HiClass](https://www.hiclass.net/main/home)** 메뉴 URL로 바로 이동하는 정적 페이지입니다. **LIU**·**LIA**(최근 게시글·알림장), 공통(급식·하이톡) 주소는 `index.html`에서 수정하면 됩니다. UI는 벤토·글래스·메시 배경·스태거 진입 등을 반영했고 `prefers-reduced-motion`을 존중합니다.

## 사용 방법

- `index.html`을 브라우저로 열면 됩니다.
- 아이별로 **다른 URL**이 생기면 `index.html` 안 각 카드의 `href`만 수정하면 됩니다.

## 로컬에서 미리보기

```powershell
# 저장소를 클론한 폴더로 이동한 뒤
python -m http.server 5500
```

브라우저에서 `http://127.0.0.1:5500/` 접속.

## 배포

저장소 **Settings → Pages** 에서 빌드 소스를 **GitHub Actions** 로 두면, `main` 푸시 시 자동 배포됩니다.

- 사이트 주소: `https://junpa82-black.github.io/uahanhiclass/`
