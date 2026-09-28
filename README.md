# 안녕하세요, 손정찬입니다 👋

백엔드와 클라우드 인프라를 중심으로 개발합니다.  
Java · Spring 기반 서비스를 만들고, Go · Terraform · Kubernetes를 활용하며 오픈소스에 기여하고 있습니다.

## Featured Projects

### [KeyWe — 원격 키오스크 주문 서비스](https://github.com/jungchanSon/-keywe)

키오스크 사용이 어려운 이용자를 위해, 가족이 스마트폰으로 원격 주문을 도울 수 있는 서비스입니다.

- **주요 구성**: 회원·주문·뱅킹·정산 등으로 나눈 마이크로서비스와 Kubernetes 배포 구성
- **기여 내용**: 뱅킹·정산 서비스 개발, 뱅킹 낙관적 락 적용, Kafka 이벤트 연동 및 Helm 차트 구성
- **기술**: Java · Spring Boot · Kafka · MySQL · Docker · Kubernetes · Helm

### [Convi — Git 협업 자동화 도구](https://github.com/jungchanSon/-convi)

커밋 메시지 생성, 커밋 컨벤션 설정, GitLab MR 리뷰를 지원하는 개발자 도구입니다.

- **주요 구성**: IntelliJ·VS Code용 Commit Buddy, 컨벤션을 만드는 Lint Buddy, AI 리뷰를 제공하는 Review Buddy
- **기여 내용**: Commit Buddy의 OpenAI 연동, `.convirc` 기반 커밋 추천, Lint Buddy 웹 UI와 사용 가이드 개발
- **기술**: Kotlin · TypeScript · Next.js · Python · GitLab CI/CD

## Open Source

### [Naver Cloud Terraform Provider](https://github.com/NaverCloudPlatform/terraform-provider-ncloud)

**Merged PRs: 12** · 2023–2024

- **리소스 확장**: MySQL 리소스, Hadoop 리소스·데이터 소스 및 상품 조회 데이터 소스 추가 — [#340](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/340), [#390](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/390), [#413](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/413) · **Merged**
- **구조 개선**: VPC Peering 리소스·데이터 소스를 Terraform Plugin Framework로 전환 — [#367](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/367) · **Merged**
- **안정성 개선**: Auto Scaling 정책 삭제 및 네트워크 인터페이스 갱신 시 발생하는 panic 수정 — [#346](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/346), [#352](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/352), [#328](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pull/328) · **Merged**

[전체 기여 PR 보기 →](https://github.com/NaverCloudPlatform/terraform-provider-ncloud/pulls?q=is%3Apr+author%3AjungchanSon)

### [LitmusChaos](https://github.com/litmuschaos)

- **오류 처리 개선**: FileHandler가 오류 응답 후 실행을 중단하도록 수정 — [litmus #5530](https://github.com/litmuschaos/litmus/pull/5530) · **Merged**
- **실험 상태 검사 개선**: Managed Node Group의 EC2 대기 검사에서 `stopped` 상태를 허용하는 수정 제안 — [litmus-go #799](https://github.com/litmuschaos/litmus-go/pull/799) · **Open**

<sub>PR 상태 확인: 2026-09-20</sub>

---

<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/jungchanSon" width="600" alt="jungchanSon의 GitAnimals 농장" />
</a>
