# report suricata rule 
## 과제
snort(suricata) rule 파일을 제작하여 특정 사이트 트래픽을 탐지하여라.

## 상세
- test.rules 파일에 20개의 사이트를 탐지하는 룰을 만든다.
- 이후 fast.log를 확인하면서 20개의 사이트가 제대로 탐지되는지 확인을 해 본다(rules 파일내의 모든 sid가 fast.log파일에 로그로 남아야 한다).
- 평문 통신(HTTP)이 이루어 지는 사이트 뿐만 아니라 TLS 통신(HTTPS)을 하는 사이트에 대한 탐지를 구현해 본다.

## 기타
- git에는 rules 파일과 fast.log 파일을 올릴 것.
- 메일에는 코드 파일을 첨부하지 말고 git 주소만 알려줄 것.

## 추가
- fast_pattern 이해 및 적용  
https://suricata.readthedocs.io/en/suricata-6.0.0/rules/fast-pattern-explained.html
