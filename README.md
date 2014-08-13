소개
====

한국어를 입력하면 로마자로 변환해주는 Java 라이브러리. 국립국어원 로마자 표기법을 기반으로 구현되었고 많은 부분이 커버 가능하지만 한국어의 특성상 단어별 사전 데이터가 존재하지 않으면 100% 구현이 어렵기 때문에 완벽하지는 않다.

온라인 데모
====

http://unply.com/@/koreanRomanizer/

메서드 요약
====

<table>
  <tr>
    <td>void</td>
    <td>setCapitalizeOnFirstLetter(boolean capitalizeOnFirstLetter)</td>
    <td>true로 설정하면 공백으로 구분된 각 단어의 첫 글자를 대문자로 출력한다 (기본값: true)
  </tr>
  <tr>
    <td>void
    <td>setUseHyphenWhenVowelConfused(boolean useHyphenWhenVowelConfused)
    <td>true로 설정하면 발음상 혼동의 우려가 있는 부분에 하이픈을 출력해준다 (기본값: true)
  </tr>
  <tr>
    <td>String
    <td>romanize(String string)
    <td>입력받은 문자열 중 한글 영역을 로마자로 변환해 리턴한다
  </tr>
</table>

패치 노트
====
1.0.1 모음이 연속되어 발음이 혼란스러운 모든 경우에 하이픈이 추가되도록 수정

라이선스
====
LGPLv3
