# Alina Kolbasova
---
### Contacts
__E-mail:__ allklbssss@yandex.ru
__Telegram:__ @alllinochkaaa

---
### About me
lI am a third-year student at Voronezh State University. My field of study is computer science and computer engineering.
I am currently studying React and TypeScript. I got acquainted with React quite recently, but I mastered it quite quickly. Before React I studied JavaScript and made layouts to improve my HTML and CSS skills and got acquainted with adaptive layout. 
In RSSchool I hope to pump up my skills and find my first job. 

---
### Skills
* HTML, CSS
* JavaScript, TypeScript
* React
* Git, GitHub
* VS Code

---
### Code example
__Playing with digits 6 KYU KATA from CODEWARS:__
Some numbers have funny properties. For example:
 
> 89 --> 8¹ + 9² = 89 * 1
> 695 --> 6² + 9³ + 5⁴= 1390 = 695 * 2
> 46288 --> 4³ + 6⁴+ 2⁵ + 8⁶ + 8⁷ = 2360688 = 46288 * 51
 
Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p
 
* we want to find a positive integer k, if it exists, such that the sum of the digits of n taken to the successive powers of p is equal to k * n.
 
In other words:
 
> Is there an integer k such as : (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k
 
If it is the case we will return k, if not return -1.
 
__Note:__ n and p will always be given as strictly positive integers.
 
```
function digPow(n, p){
 const sum = n.toString().split('').map((num, index) => num ** (index + p)).reduce((acc, cur) => acc + cur)
 return sum % n === 0 ? sum / n : -1
}
```
---
### Courses
* JavaScript by Владилен Минин
* React JS by webDev

---
### Languages
* Russian - Native
* English - Pre-Intermediate

