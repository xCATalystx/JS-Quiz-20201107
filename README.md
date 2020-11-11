# JS-Quiz-20201107
Quiz

``` js
function printStars(count) {
  let str = '';
  let i, j;

  for(i = 1; i <= count; i++) {
    for(j = 1; j <= i; j++) {
      str += '*';
    }
    str += '\n';
  }
  console.log(str);
}

// 請參考 printStars，
// 並完成 printStars2，使其執行時結果如圖： https://imgur.com/56BptSu
function printStars2(count) {
      let newcount = count + 1;
      let str = '';
      let i, j;
      
      for(i = 1; i < newcount; i++) {
        for(j = 1; j < newcount; j++) {
          if (i + j >= newcount){
          str += '*';
          }
          else{
            str += ' ';
          }
        }
        str += '\n';
      }
      console.log(str);
    }
  // todo...
}

```
