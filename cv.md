## Aleksandr Lobkov
[cv photo](cv.jpg)
###### Contacts of me:<br>
Email: das149848@gmail.com<br>
Discord: @alekprogrammer<br>
###### Some about me:<br>
_I really like programming, it is very exciting for me. I was a little fond of 3d modeling. I study English in order to always be on the crest of the wave of information technology and keep abreast of advanced approaches._<br>
_Almost finished the course JavaScript Algorithms and Data Structures on the site freecodecamp. I passed it 98%. The entire list of solved problems can be viewed in my profile: https://www.freecodecamp.org/alekprogrammer_
###### Skills:<br>
1. HTML
2. CSS
3. Basics JavaScript
4. Basics C #
5. Basics C ++
###### Education<br>
Vocational Pedagogical College named after Gagarin:<br>
Specialty - Computer systems and complexes.
###### Example one of my codes:<br>
I solved the problem https://www.codewars.com/kata/5412509bd436bd33920011bc from the site Codewars.<br>
This is my solve:
```
// return masked string
function maskify(cc) {
 let str = '';
   if(!cc){
   return str;
 }
   for(var i = cc.length-1; i>=cc.length-4;  i--)
   {
     if(!cc[i])
     {
       return str
     }
     else {
       str = cc[i] + str;
       }
   }
   for(i = cc.length-5; i >= 0;  i--){
  if(!cc[i])
  {
    return str;
  }
  else{
     str ='#' +str;
  }
}
  return str;
}
```
