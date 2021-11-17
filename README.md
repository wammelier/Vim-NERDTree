# Vim-NERDTree
## WSL 정복하기

<h3> MAC Iterm Terminal 을 이용한 vim 사용</h3>

개발을 하면서 GUI 를 쓸것인지 CLI 를 쓸것인지 고민을 한적이 있다.
확실히 편의성에선 GUI가 정답인거 같고 간지느 CLI라고 생각으 했다.
그리고 대부분의 개발자들도 GUI를 사용하는 개발자가 현저히 많기 때문에 나 또하 GUI를 이용하는 횟수가 점점 늘어갔다.

어느순간.. 금융권 프로젝트르 하면서 어쩔수 없이 vi 를 사용하는 횟수가 늘어나고 심지어 나느 지금 git도 cli를 이용하여 커밋 푸쉬르 진행하고 있다.
그러다보니 어느순간 gui로 하는 방법보다 cli로 이용하는게 보기 편해졌고 점점 cli가 더 많은 기능과 어떤 시스템을 이해는데 있어서 더 유리하다는 사실을 깨우쳤다.
물론 개발자마다 자신의 취향을 선택하는것에 대해 어떤것을 사용하라고 강조할 권리느 그 누구도 가지고 있지 않다고 생각한다.

<h3> 어떤 툴으 이용할 것 인가?</h3>
사실 나는 텍스트 에디터르 메모장, 노션 이렇게 두개 이외에 다른것에 손을 잘 대지 않앗다.. 그이유느 솔직히 귀찮기도 하고 어렸을때부터 난 메모장으 좋아했....
하지만 일을하다보며 불가피하게 노가다르 해야하 상황이 생긴다 예를들어볼까?
<b>
String abc;
String cde;
Stirng edf;
</b>
자 이런 문구가 있고 우리가 만약 String --> Integer 를 바꾸는 작업을 해야할때 솔직히 3개밖에 안되는 저 문구르 바꾸는데 얼마나 걸리려니 싶다.
근데 만약 몇백개 단위로 존재한다면..? 컨트로 + c , + v를 반복할것인가?... 이래서 텍스트 에디터가 필요하다..
솔직히 vsCode 도 정말 잘 만든 에디터라고 생각하기 때문ㅇ 자신에게 맞느 wsl을 선택하여 사용하길 바란다.
하지마 나는 vim plugin nerdTree를 선택했다.

<h3>NERDTree 란?</h3>
리눅스를 쓰다보면 vi 나 vim을 간혹 사용하게 되는데 마우스를 잡기 귀찮아 하는 나에겐 정말 vim은 최고의 에디터인거 같다.. 하지만 vim 을 좀더 확장해서 쓰고 싶은 마음에
vim 플러그인을 주벼 지인에게 추천받았고 너드트리가 정말 좋다는 추천을 받았기에 손가락에 익숙해지도로 연습중이다..

<h3>NERDTree 설치</h3>
