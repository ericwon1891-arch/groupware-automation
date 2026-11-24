# [기안 초안] {{distributor_ko}} RMA 불량 {{product_ko}}({{model}}) {{qty}}대 신품 교체의 건

> {{id}} · 작성 {{today}} · `[ ]`는 채워야 할 칸. 영업재고(영업샘플) 처리라 비용(단가·금액·발송비)은 적지 않는다.

| 항목 | 내용 |
|---|---|
| 기안부서 | 해외영업 |
| 기안자 | 원창민(Eric) |
| 기안일 | {{draft_date or "[  ]"}} |
| 제목 | {{distributor_ko}} RMA 불량 {{product_ko}}({{model}}) {{qty}}대 신품 교체의 건 |

## 1. 목적
{{distributor_desc}}를 통해 RMA 접수된 {{product_ko}}({{model}}) {{qty}}대가 {{result}}으로 확인되었고, {{reason_short}} 보증기간 내 무상 신품 교체를 진행하고자 합니다.

## 2. 경위
{{#timeline}}- {{date}}: {{event}}
{{/timeline}}

## 3. 대상
| No. | 모델 | S/N | 고객 증상 | 점검 결과 | 보증 | 처리 |
|---|---|---|---|---|---|---|
{{#items}}| {{no}} | {{model}} | {{sn}} | {{symptom}} | {{result}} | {{warranty}} | {{action}} |
{{/items}}

## 4. 신품 교체 사유
{{#reasons}}- {{.}}
{{/reasons}}

## 5. 출고 계획
- 교체용 신품: 영업재고(영업샘플)로 처리
- 출고 방법: {{ship_options}}
- 회수 불량품 {{qty}}대: 당사 보관(불량 분석·폐기는 생산/품질팀 판단)

## 6. 첨부
{{#attachments}}{{no}}. {{desc}}
{{/attachments}}

이상과 같이 기안하오니 검토 후 재가하여 주시기 바랍니다.
