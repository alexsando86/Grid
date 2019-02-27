# CSS Grid
## MDN 
> https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Grid_Layout

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

### grid

### grid-area
<<<<<<< HEAD
* item 기둥(column)의 크기를 지정 또는 영역의 이름을 지정한다.
* grid-area : row-start / column-start / row-end / column-end;
* grid-area : header;
* grid-area : sidebar;
=======
* item 기둥(column)의 크기를 지정한다.
>>>>>>> 811f2b1103b52cfa7df5762d5dfa738ae165e1b6

### grid-auto-flow
* item 배치방향을 지정한다. row 또는 column

### grid-auto-rows
* row의 크기를 지정한다.

### grid-column
<<<<<<< HEAD
* 그리드 column항목의 크기와 위치를 지정한다.
***
    grid-column : 1 / 3;
    
    grid-column : start / end;
***
### grid-column-end
* item의 column 끝나는 위치를 지정
***
    grid-column-end : 3;
***
### grid-column-gap
* item column사이의 공간을 지정

### grid-column-start
* item의 column 시작하는 위치를 지정
***
    grid-column-start : 3;
***
### grid-gap
* 그리드사이의 공간을 지정

***
    grid-gap : 10px;
***

### grid-row
* 그리드 row항목의 크기와 위치를 지정한다.
***
    grid-row : 1 / 3;
    
    grid-row : start / end;
***
### grid-row-end
* item의 row 끝나는 위치를 지정
***
    grid-row-end : 3;
***
### grid-row-gap
* item row사이의 공간을 지정

### grid-row-start
* item의 row 시작하는 위치를 지정
***
    grid-row-start : 1;
***
### grid-template
* 영역을 정의한다.
***
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

***
    grid-template-areas: 
        "a a a"
        "b b b"
        "b c c"; 
***

### grid-template-columns

    grid-template-columns: 1fr 30px 30px;
    
### grid-template-rows

    grid-template-rows: 1fr 30px 30px;
=======
* 그리드 항목의 크기와 위치를 지정한다.

    ``` grid-column : 1 / 3;``` 
    
    ``` grid-column : start / end ```

### grid-column-end
* item의 column 끝나는 위치를 지정

    ``` grid-column-end : 3 ```

### grid-column-start
* item의 column 시작하는 위치를 지정

    ``` grid-column-start : 3 ```

### grid-column-gap
* item column사이의 공간을 지정
>>>>>>> 811f2b1103b52cfa7df5762d5dfa738ae165e1b6
