이 페이지는 HTML을 구성하는 요소들이 정상적으로 스타일되어 있는지 확인하는 페이지로, 디자인 되지 않은 요소들을 놓치지 않기 위해 제작하였습니다.

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

- - -

## 문단
**본명조**는 *Adobe Type*에서 최근 출시한 두번째 Pan-CJK 서체로, <u>본고딕</u>의 자매 서체입니다. <a href="https://www.adobe.com/" target="_blank">Adobe</a>는 동아시아 15억 명 사용자의 디자인 통합 요구를 반영하여 이들 서체를 출시하게 되었습니다.

본명조는 한국어, 중국어 간체, 중국어 번체, 일본어 등 4개의 동아시아 언어를 지원하며, 서로 다른 언어들의 다양성을 유지하며 일관성 있는 디자인을 가능하게 하는 7가지 두께로 되어있는 65,535개 글리프를 포함하고 있습니다. 또한 Source Serif 프로젝트를 통해 만들어진 라틴어, 그리스어 및 키릴 스크립트를 지원하는 서양 언어권 글리프 세트가 포함되었습니다.

- - -

## 목록
### 정의 목록(dl)
<dl>
  <dt>용어</dt>
  <dd>설명</dd>
</dl>

### 순서있는 목록(ol)
1. 목록 1
2. 목록 2
  1. 하위 목록 1
  2. 하위 목록 2
  3. 하위 목록 3
3. 목록 3

### 순서없는 목록(ul)
* 목록 1
* 목록 2
  * 하위 목록 1
  * 하위 목록 2
  * 하위 목록 3
* 목록 3

- - -

## 테이블
| 제목 1 | 제목 2 | 제목 3 |
| ----- | ----- | ----- |
| 칸 1 | 칸 2 | 칸 3 |
| 칸 1 | 칸 2 | 칸 3 |
| 칸 1 | 칸 2 | 칸 3 |

- - -

## 인용문
> 옥상달빛 ‘밤밤밤’  
> OKDAL 'Nights'
> 
> 가끔은 나를 스쳐가는 모든 슬픔의 이유가  
> 다 나 같아서 슬픈 날이 있다.

- - -

## Pre
<pre>
자유롭고 용감한 소녀 힐다. 편안한 숲을 떠나,
모든 것이 생소한 도시에서 살게 된다.

“그래도 새로운 친구들을 만나는 건 즐거워.
                     신비한 모험을 계속할 수 있으니까!”
― 힐다(2018), Netflix
</pre>

- - -

## Code
`#sleepless`

- - -

## input

<label for="text_field">텍스트 상자:</label>  
<input id="text_field" class="focus-input-color input" type="text" placeholder="미리 입력된 텍스트">

<label for="text_area">텍스트 영역:</label>  
<textarea id="text_area" class="focus-input-color textarea" placeholder="미리 입력된 텍스트"></textarea>

<label for="select_element">선택 상자:</label>  
<select id="select_element" name="select_element">
  <optgroup label="옵션 그룹 1">
    <option value="1">옵션 1</option>
    <option value="2">옵션 2</option>
    <option value="3">옵션 3</option>
  </optgroup>
  <optgroup label="옵션 그룹 2">
    <option value="1">옵션 1</option>
    <option value="2">옵션  2</option>
    <option value="3">옵션 3</option>
  </optgroup>
</select>

<label>라디오 버튼:</label>  
<input type="radio" class="radio" name="radio_button" value="radio_1"> 옵션 1  
<input type="radio" class="radio" name="radio_button" value="radio_2"> 옵션 2  
<input type="radio" class="radio" name="radio_button" value="radio_3"> 옵션 3

<label>체크박스:</label>  
<input type="checkbox" class="checkbox" name="checkboxes" value="check_1"> 옵션 1  
<input type="checkbox" class="checkbox" name="checkboxes" value="check_2"> 옵션 2  
<input type="checkbox" class="checkbox" name="checkboxes" value="check_3"> 옵션 3

<label for="password">비밀번호:</label>  
<input id="password" class="focus-input-color input" type="password" name="password">

<label for="file">파일 첩부:</label>  
<input type="file" id="file" class="file" name="file">


<button class="button" type="reset" disabled><span class="text">취소</span></button> <button class="button background" type="submit"><span class="text">등록</span></button>

- - -

## 시멘틱 요소 – sub, sup, cite, kbd, mark, abbr, del, ins 등.
본명조<sub>위 첨자</sub>는 Adobe Type<sup>아래 첨자</sup>에서 최근 출시한 두번째 Pan-CJK 서체로, 본고딕의 자매 서체입니다. <a href="https://www.adobe.com/" target="_blank">Adobe</a>는 <cite>동아시아</cite> 15억 명 사용자의 디자인 통합 요구를 반영하여<kbd>Alt</kbd> + <kbd>F4</kbd> 이들 서체를 출시하게 되었습니다.

<mark>본명조</mark>는 <del>한글</del><ins>한국어</ins>, 중국어 간체, 중국어 번체, 일본어 등 4개의 동아시아 언어를 지원하며, <abbr title="World Health Organization">WHO</abbr>서로 다른 언어들의 다양성을 유지하며 일관성 있는 디자인을 가능하게 하는 7가지 두께로 되어있는 65,535개 글리프를 포함하고 있습니다. 또한 Source Serif 프로젝트를 통해 만들어진 라틴어, 그리스어 및 키릴 스크립트를 지원하는 서양 언어권 글리프 세트가 포함되었습니다.