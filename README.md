# LAB3 FPGA 응용 실습

정현재 · 2023440127

7개 실험의 RTL, 테스트벤치, 핀 제약, 시뮬레이션 설정과 실험 보고서 및 증빙 자료를 정리한 저장소입니다.

## 보고서

- [실험 전 보고서](<report/pre/LAB3 실험전 보고서.pdf>)
- [실험 후 보고서](<report/post/LAB3 실험후 보고서.pdf>)

## 실험별 자료

| 실험 | 소스 | VS Code 자료 | Vivado 자료 | 보드 영상 |
|---|---|---|---|---|
| 1. LED PWM | [소스](<lab3_19_led_pwm/>) | [자료](<evidence/vscode/experiment01/>) | [자료](<evidence/vivado/experiment01/>) | [영상](<evidence/board/videos/실험1 보드 영상.mp4>) |
| 2. RGB PWM | [소스](<lab3_20_rgb_pwm/>) | [자료](<evidence/vscode/experiment02/>) | [자료](<evidence/vivado/experiment02/>) | [영상](<evidence/board/videos/실험2 보드 영상.mp4>) |
| 3. 피에조 | [소스](<lab3_21_piezo/>) | [자료](<evidence/vscode/experiment03/>) | [자료](<evidence/vivado/experiment03/>) | [영상](<evidence/board/videos/실험3 보드 영상.mp4>) |
| 4. 스텝 모터 | [소스](<lab3_22_stepper/>) | [자료](<evidence/vscode/experiment04/>) | [자료](<evidence/vivado/experiment04/>) | [영상](<evidence/board/videos/실험4 보드 영상.mp4>) |
| 5. MMSS Clock | [소스](<lab3_23_mmss_clock/>) | [자료](<evidence/vscode/experiment05/>) | [자료](<evidence/vivado/experiment05/>) | [영상](<evidence/board/videos/실험5 보드 영상.mp4>) |
| 6. 문자 LCD | [소스](<lab3_24_character_lcd/>) | [자료](<evidence/vscode/experiment06/>) | [자료](<evidence/vivado/experiment06/>) | [영상](<evidence/board/videos/실험6 보드 영상.mp4>) |
| 7. UART Echo | [소스](<lab3_25_uart_echo/>) | [자료](<evidence/vscode/experiment07/>) | [자료](<evidence/vivado/experiment07/>) | [영상](<evidence/board/videos/실험7 보드 영상.mp4>) |

각 소스 폴더의 `src`는 RTL, `sim`은 테스트벤치, `constraints`는 XDC이며, `simulation.json`은 시뮬레이션 설정입니다.

VS Code 자료에는 각 실험의 전체 파형과 기본 PASS 로그 캡처만 포함되어 있습니다.

## 보드 시연

조교에게 시연한 항목은 **실험 7: UART Echo**입니다. A, Z, 줄바꿈 입력에 대한 보드 사진과 입력 화면을 보관했습니다.

- [실험7 보드 사진(A)](<evidence/board/photos/실험7 보드 사진(A).png>)
- [실험7 보드 사진(Z)](<evidence/board/photos/실험7 보드 사진(Z).png>)
- [실험7 보드 사진(줄바꿈)](<evidence/board/photos/실험7 보드 사진(줄바꿈).png>)
- [실험7 입력 사진(A)](<evidence/board/photos/실험7 입력 사진(A).png>)
- [실험7 입력 사진(Z)](<evidence/board/photos/실험7 입력 사진(Z).png>)
- [실험7 입력 사진(줄바꿈)](<evidence/board/photos/실험7 입력 사진(줄바꿈).png>)

- [기타 캡처](<evidence/other/>)

## 저장소와 제출 버전

- 저장소: https://github.com/Jeong719/ECE2_Lab3
- 최종 제출 커밋 해시는 보고서와 자료를 업로드한 뒤 확인합니다.

## 자료 구성

실험 코드는 저장소에 이미 업로드되어 있으므로 이번 업로드 폴더에는 보고서와 증빙 자료를 포함했습니다. 위 소스 링크는 기존 저장소의 실험 폴더를 가리킵니다. report, evidence와 이 README.md를 기존 저장소의 최상위에 추가합니다.
증빙 파일은 기존 자료를 복사한 것이며, 이 정리 작업에서 회로 시험이나 시연을 새로 수행한 것은 아닙니다.
영상 미리보기가 지원되지 않으면 다운로드하여 재생합니다.
