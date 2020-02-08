# Virtualbox 세팅

<br/><br/>


# Tmux 세팅

## Tmux 실행 방법
tmux 입력해서 실행.<br/>
prefix 키를 누른 다음 키보드에서 손을 떼고, 그 다음에 bind 키를 누른다.<br/>
<br/><br/>

## Tmux 설정 변경 (.tmux.conf 파일 변경 후 적용.)
=> git의 /sample/.tmux.conf 파일 참조. (기본으로 세팅해도 됨. 현재 tmux2.8 버전에서 설정해서 사용 중..) <br/>
<br/>

### prefix 키를 Ctrl + b에서 Ctrl + c로 변경
<pre>
set -g prefix C-c
unbind C-b
unbind C-a
</pre>
원래는 prefix 키가 Ctrl + b인데 Ctrl + c로 바꿔줌. (키보드 위치가 넘 멀어서..)<br/>
<br/><br/>

# Tmux 명령

### Ctrl + c, 스페이스
분할된 창(pane)을 동일한 크기로 변경하거나 계속 누르면 다른 창 분할 모드로 바꿔줌..<br/>

### Ctrl + c, r
tmux가 실행되고 있을 때, .tmux.conf 파일 수정 후 바로 적용해 줌.<br/>

### Ctrl + c, ,
창 이름 변경.<br/>

