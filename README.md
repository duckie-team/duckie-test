## duckie-quack-test-coverage-deploy

[duckie-quack-quack](https://github.com/sungbinland/duckie-quack-quack)의 테스트 커버리지에 변동이 생기면 자동으로 푸시되고 커버리지 리포트가 깃허브 페이지로 배포됩니다.

배포 주소: [quack-test.duckie.team](https://quack-test.duckie.team)

---

#### 자동 배포

[duckie-quack-quack](https://github.com/sungbinland/duckie-quack-quack)에 `test` 와 `deploy` label 이 붙은 PR 이 올라오면 [Android CI](https://github.com/sungbinland/duckie-quack-quack/blob/develop/.github/workflows/android-ci.yml) 과정을 거치면서 이 저장소로 [Kover](https://github.com/Kotlin/kotlinx-kover)에 의해 생성된 테스트 커버리지 HTML 리포트가 자동 푸시됩니다. 이후 푸시된 파일들을 기준으로 깃허브 페이지 빌드가 시작됩니다.