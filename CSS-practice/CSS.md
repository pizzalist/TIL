# CSS

## CSS의 기초 문법과 적용 방법

### 선택자의 종류

select : CSS의 주어와 같은 역할로, 중요

1. id : 단 한번 선택
   `#select`

2. class : 여러개 선택해서 그룹화
   `.deactive`

3. 부모 자식

### pseudo class selector

가상클래스 선택자 : element의 상태에 따라 선택하는 선택자
a:link{ color: black;}
a:visited{color: red;}
a:hover{color:yellow;
}
a:active{
color: green;
}
a:focus{
color: white;
}

- `a:link { color: blue; }` /_ 방문하지 않은 링크 _/
- `a:visited { color: purple; }` /_ 방문한 링크 _/
- `a:hover { background: yellow; }` /_ 마우스를 올린 링크 _/
- `a:active { color: red; }` /_ 활성화한 링크 _/
- `a:focus{ color: white; }`