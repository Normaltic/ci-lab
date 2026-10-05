# ci-lab

semantic-release 기반 배포 파이프라인의 concurrency 동작 실험장.

- `stage`(rc) / `main` 브랜치에서 semantic-release 를 실제로 실행한다
- 검증 job 은 `sleep`, 빌드·배포는 `echo` stub
- 시나리오는 `stage`/`main` 에 `fix:` 커밋을 push 해서 재현한다

secret: `SEMANTIC_RELEASE_GITHUB_TOKEN` — 이 레포 Contents/Issues/Pull requests RW PAT.
릴리즈 커밋이 다른 workflow 를 깨우려면 GITHUB_TOKEN 이 아니어야 한다.

변수(선택): `STUB_SCALE`(sleep 배수, 기본 1), `FAIL_VERIFY`(true 면 검증 실패)
