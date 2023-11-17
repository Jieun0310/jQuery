# jquery 기본연습

## jquery basic
- animate()
...

 $('.btn2').on('click',function(){
        $('.text2').animate({marginLeft: '+=50px',fontSize:30},2000,function(){
            alert('hello?')
        })
    })