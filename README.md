# groupware-automation

한비로 그룹웨어 결재 문서(기안품의서 등)를 Claude in Chrome으로 작성·임시저장하기 위한 저장소. 지금은 해외 RMA(일본 JBS 등) 신품 교체 기안을 건 단위로 관리한다. 클라우드 세션과 Chrome(그룹웨어) 세션이 이 repo의 `case.yaml` 상태값을 보고 작업을 이어받는다.

- 규칙: [CLAUDE.md](CLAUDE.md)
- 진행 중인 건: [index.md](index.md)
- 템플릿: `templates/`

- CS 기록(RMA 대장)은 `ericwon1891-arch/linkflow-nvr`의 `cs` 브랜치(`rma.md`, `customers/<업체>/rma/<RMA 번호>.md`)에 있다. 이 저장소에는 사내 결재 문서만 둔다.
