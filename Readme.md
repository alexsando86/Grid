# CSS Grid
## MDN 
- > https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Grid_Layout
- > https://medium.com/deemaze-software/css-grid-layout-crossed-sections-fca9e956e725?sk=4a50491079fec5afaa0788e9347fbefa

***

## Grid? 

***

## fr(fraction) ?
* 유연한 크기를 갖는 단위로 남은 공간을 사용한다.

## grid box 요소
>
    display: grid;
    grid-auto-flow;
    grid-auto-columns;
    grid-auto-rows;
    grid-template;
    grid-template-columns;
    gird-template-rows;
    grid-gap;
    grid-column-gap;
    grid-row-gap;

## grid item 요소
>
    grid-area;
    grid-column;
    grid-column-start;
    grid-column-end;
    grid-row;
    grid-row-start;
    grid-row-end;
    grid-template-areas;
***

## Property

- [ ] grid
- [ ] grid-area
- [ ] grid-auto-columns
- [ ] grid-auto-flow
- [ ] grid-auto-rows
- [ ] grid-column
- [ ] grid-column-end
- [ ] grid-column-gap
- [ ] grid-column-start
- [ ] grid-gap
- [ ] grid-row
- [ ] grid-row-end
- [ ] grid-row-gap
- [ ] grid-row-start
- [ ] grid-template
- [ ] grid-template-areas
- [ ] grid-template-columns
- [ ] grid-template-rows

***

### grid
* 모든 명시 적 그리드 속성 (그리드 템플릿 행, 그리드 템플릿 열 및 그리드 템플릿 영역)과 모든 암시 적 그리드 속성 (그리드 자동 행, 그리드 자동 열 및 그리드 자동 흐름)을 단일 선언으로 제공합니다.

>
    grid: auto-flow / 1fr 1fr 1fr;
    grid: repeat(3, 80px) / auto-flow;
***

### grid-area
* 그리드 item영역의 시작과 끝 위치를 지정하고 사이즈만큼 영역을 확보한다.
>
    grid-area : row-start / column-start / row-end / column-end;
    grid-area : 2 / 3 / 5 / 4;
    grid-area : header;

***

### grid-auto-flow
* item이 배치될 방향 가로(column) 또는 세로(row)
>
    grid-auto-flow : column;
***

### grid-auto-rows
* row의 크기를 지정한다.

***

### grid-auto-columns
* 암시 적으로 생성 된 격자 열 트랙의 크기를 지정합니다.

### grid-column
* 그리드 column항목의 크기와 위치를 지정한다.
>
    grid-column : 1 / 3;
    
    grid-column : start / end;
***
### grid-column-end
* item의 column 끝나는 위치를 지정
>
    grid-column-end : 3;

***
### grid-column-gap
* item column사이의 공간을 지정

***

### grid-column-start
* item의 column 시작하는 위치를 지정
>
    grid-column-start : 3;
***
### grid-gap
* 그리드사이의 공간을 지정

>
    grid-gap : 10px;
***

### grid-row
* 그리드 row항목의 크기와 위치를 지정한다.
>
    grid-row : 1 / 3;
    
    grid-row : start / end;
***
### grid-row-end
* item의 row 끝나는 위치를 지정

>
    grid-row-end : 3;
***

### grid-row-gap
* item row사이의 공간을 지정
***

### grid-row-start
* item의 row 시작하는 위치를 지정

***
>
    grid-row-start : 1;
***
### grid-template
* 영역을 정의한다.

>
    grid-template: repeat(4, 1fr) / repeat(2, 1fr);

    grid-template: 
        "a a a" 40px
        "b c c" 40px
        "b c c" 40px / 1fr 1fr 1fr;

    grid-template: 
        "a a ." minmax(50px, auto)
        "a a ." 80px
        "b b c" auto / 2em 3em auto;
***
### grid-template-areas
* grid-areas로 명명된 격자의 영역을 지정.

>
    grid-template-areas: 
        "a a a"
        "b b b"
        "b c c"; 
***

### grid-template-columns
>
    grid-template-columns: 1fr 30px 30px;
    
### grid-template-rows
>
    grid-template-rows: 1fr 30px 30px;

## Grid와 FlexBox