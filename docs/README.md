# 🚀 기능 요구 사항
### 기본적으로 1부터 9까지 서로 다른 수로 이루어진 3자리의 수를 맞추는 게임이다.

## 기능 구현 목록
1. 1~9 사이의 숫자를 3개를 중복되지 않게 무작위로 뽑아 수를 정한다.
2. 게임 시작 시 "숫자 야구 게임을 시작합니다" 출력 (1회만)
3. 곧바로 "숫자를 입력해주세요 : " 입력을 띄운다
4. 입력된 값이 숫자가 아니거나, 길이가 3이 아니면 "잘못된 값을 입력했습니다 올바른 값을 입력해주세요." 출력
5. 입력된 값을 볼이 몇개인지, 스트라이크가 몇 개인지 출력
6. 스트라이크의 값이 3이 아닐 땐 3번을 반복한다.
7. 만약 스트라이크의 값이 3이면 "3개의 숫자를 모두 맞히셨습니다! 게임 종료" 출력
8. 그리고 "게임을 새로 시작하려면 1, 종료하려면 2를 입력하세요." 출력하고 입력 대기를 받는다
9. 이 또한 1이나 2가 아니면 "잘못된 값을 입력했습니다 올바른 값을 입력해주세요." 출력
10. 1면 2번을 제외하고 1번부터 9번까지 반복한다.
11. 2면 "게임을 종료합니다." 출력 및 프로그램 종료