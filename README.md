# SAP-BC
BC contents

## ERP 
Enterprise Resource Planning : 영업활동 ~ 해당 제품의 생산/출하 및 판매를 걸쳐 회계에 반영되기까지의 일련의 Business Process를 관리하는 시스템

### ERP process
1. MM : 1)구매를 요청하면, 2)해당되는 구매 오더를 넣고 3)구매 자재를 입고시킨 후 4)해당 송장을 만든다.
2. PP : 1)생산오더를 내면, 2)MM에서 구매 자재 입고 내역을 가져와 원자재 출고를 진행한 뒤, 3) 생산 실적 처리를 입력 후 4)생산된 품목을 입고한다.
3. SD : 1)생산되어 입고된 품목에 대한 판매 오더를 내면 2)출하를 진행한 뒤 3)해당 송장을 발행한다.
4. FI : 1)판매 송장을 기준으로 외상매출 전표를 작성한다. 2)해당 과정에서 비용이 얼마나 나왔는지 입력 한다(임금/급여, 일반비, 복리후생비, 자재 매입금 등)
5. CO : 1)매출과 비용을 비교하여 수익성 분석을 진행 한 뒤, 2)제조원가를 끌어내고, 3)손익을 비교한다.


### SAP Version history
* 1992년 7월 6일 공식 발매
* NetWeaver : SAP의 기술적 기반 - ERP 시스템은 NetWeaver위에 위치
* ECC : Erp Central Component - ERP와 같은 용어라 이해하면 편함.
[Basis Functionality] : SAP_BASIS 버전
[Remark] : ERP 버전
