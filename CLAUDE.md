# gate

doobystudio.com 대문(루트 도메인) 정적 사이트. 블로그는 별도 레포 `dooby135/dooby135.github.io` (blog.doobystudio.com).

## Build and run

빌드 단계 없음. 로컬 확인:

```bash
python3 -m http.server 8000
```

## Conventions

- GitHub Pages가 main 브랜치 루트를 그대로 서빙한다. `.nojekyll`로 Jekyll 처리를 끈다.
- dooby135 계정 레포: remote는 `git@github-dooby135:dooby135/gate.git`, 로컬 git identity는 dooby135.
