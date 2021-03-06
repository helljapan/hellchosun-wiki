[헬조선 위키 원문 창고](https://chosun.cf/wiki/)
===================

이 git 저장소는 헬조선 위키의 원본 텍스트 보관 창고입니다. 헬조선을 종합적으로 정리하는 위키로서 기능하게 될 곳입니다. 다만 별도의 이미지 등은 다양한 외부 소스를 활용해주셔야 합니다.

[Imgur](https://imgur.com)나 git을 잘 다루시는 분의 경우 [Wiki용 바이너리 창고](https://github.com/hellchosun/hellchosun-bins)에 이미지/오디오 파일 등을 Push 하시면 확인 후 승인해 드립니다.


# 장점


## 왜 git을 원본 소스 저장에 사용하나요?

체계적으로 설계가 가능합니다. 대표적인 예로 기존의 미디어위키와는 달리 폴더 구조를 그대로 차용하여 문서를 설계할 수 있습니다. 이러한 구조는 검색의 용이성에도 도움이 됩니다. 예를 들면 문서 주소가 https://chosun.cf/wiki/생활/교통/대중교통/지옥철 (이때 github에 저장되는 실제 물리적 파일명은 '지옥철.wiki' 가 되어야 합니다) 이런식의 주소 구조도 가능하게 됩니다. 추후 예제 문서와 실제 서비스되는 페이지를 안내할 예정입니다.


## 정확한 사후 검수를 통하여 업데이트가 가능합니다.

기존의 위키는 수시로 일어나는 반달 현상과 내용 훼손 등이 일어날 여지가 있었지만, 이 방식은 사후에 티켓을 포함한 패치셋이라고 불리는 문서 변형 요청서를 작성하고 중간 관리자 그룹이 이를 승인할 때 합병(Merged)되는 방식이므로 비이성적인 편집을 전송하더라도 적용이 불가능하게 됩니다.


## 언제든지 공개되어있습니다.

위키 텍스트 전체를 언제든지 바로 내려받을 수 있습니다. 이러한 상황에서도 저작권은 기여자에게 속합니다. 하지만 공중에 공개되는 본 사이트의 특성상 작성자분들께서는 사이트에 복제, 수정할 수 있는 전 세계적 라이선스를 서비스에 제공한다고 전제합니다.


# 단점

## 미디어위키 문법을 익히셔야 합니다.

미디어위키은 간단하지만 기본적인 문서 포맷을 갖춰지게 해주는 강력한 기능을 가지고 있습니다. 다음은 미디어위키 문법에 대한 설명들이 모여있는 문서입니다. 미디어위키과 함께 HTML 코드를 함께 넣으셔도 됩니다. 직접적 보안위협이 없는한 대부분 승인됩니다.

링크는 현재는 HTML 포맷으로 [[생활/교통/대중교통/지옥철]] 처럼 작성하시면 됩니다.


## 기여하는 법이 조금 어렵고 최종 적용에 약간의 시간이 걸립니다.

git을 기본적으로 사용하시고 다양한 명령어를 사용하실 줄 아는 분이시면 금방 하실 수 있지만, 명령어에 대한 충분한 배경지식이 없으신 분들은 처음에 어려움을 느끼실 수 있습니다. 최종 승인은 현재는 사람이 해야 하지만, 추후에는 봇을 만들어 문장 패턴 분석 후 문제 없을시 자동 merge 되는 방법을 고민중입니다.


# 참여/기여하는 법

[헬조선 위키 프로젝트에 기여하는 방법](https://github.com/hellchosun/hellchosun-wiki/blob/master/CONTRIBUTING.markdown) 문서에 상세하게 사용법을 적어두었습니다.


# 주의

변경 승인 이후 결과에 최종 반영되기까지는 최대 6시간 정도 소요됩니다.

관리자를 모집하고 있습니다. http://ask.fm/hellchosun 에 Github 아이디를 보내주세요.

입력하시는 파일의 확장자는 md로 미디어위키 & 도쿠위키 & HTML 형식으로 입력이 가능합니다.

