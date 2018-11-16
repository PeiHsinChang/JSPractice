# JSPractice 
Class note
little code &amp; take notes 

[專位國中生寫的javascript程式書](https://ccckmit.gitbooks.io/javascript/content/ch2/chapter2.html) 習題練習

###Ch2-1
```
function factorial(num){
  let sum = 1;
  if(num > 0){
    for (let i = 1; i<=num;i++){
	  	sum = i * sum ;
	  	console.log(sum);	
	  }
  }else if(num == 0){
    sum = 1 ;
  }else {
	sum = "不是正整數";
  }		
  console.log(sum);		 	
  return sum;
}
factorial(5);
factorial(-5);
factorial(0);

```
