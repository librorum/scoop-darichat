# scoop-darichat

[다리챗](https://darichat.com) 윈도우 데스크톱 앱을 Scoop 으로 설치한다.

```powershell
scoop bucket add darichat https://github.com/librorum/scoop-darichat
scoop install darichat/darichat
```

- 데스크톱 앱은 스스로 업데이트한다.
- 매니페스트는 다리챗 `pnpm run release:app` 이 새 버전·sha256 으로 갱신한다.
