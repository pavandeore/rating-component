let starDiv = document.querySelector('.star-div');

let s1 = document.querySelector('#s-1')
let s2 = document.querySelector('#s-2')
let s3 = document.querySelector('#s-3')
let s4 = document.querySelector('#s-4')
let s5 = document.querySelector('#s-5')

let stars = document.querySelectorAll('.star');
let current = 0;

stars.forEach(star => {
  star.addEventListener('mouseover',function(e){
    
    if(e.target.dataset.no){
        current = Number(e.target.dataset.no)
        
        
        switch(current){
          case 1 :  s1.style.fill = 'red'
                    s2.style.fill = 'none';
                    s3.style.fill = 'none';
                    s4.style.fill = 'none';
                    s5.style.fill = 'none';
            break;
          case 2 :  s1.style.fill = 'red';
                    s2.style.fill = 'red';
                    s3.style.fill = 'none';
                    s4.style.fill = 'none';
                    s5.style.fill = 'none';
            break;
          case 3 :  s1.style.fill = 'red'
                    s2.style.fill = 'red';
                    s3.style.fill = 'red';
                    s4.style.fill = 'none';
                    s5.style.fill = 'none';
            break;
          case 4 :  s1.style.fill = 'red';
                    s2.style.fill = 'red';
                    s3.style.fill = 'red';
                    s4.style.fill = 'red';
                    s5.style.fill = 'none';
            break;
          case 5 :  s1.style.fill = 'red';
                    s2.style.fill = 'red';
                    s3.style.fill = 'red';
                    s4.style.fill = 'red';
                    s5.style.fill = 'red';
            break;
        }
        
        
    }
    
    
    
  })
})

