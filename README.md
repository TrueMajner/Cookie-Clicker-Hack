<h2 align="center">Cookie Clicker Hack 2020</h2> 

[Cookie Clicker](https://orteil.dashnet.org/cookieclicker)
  
[Русскоязычная версия](https://github.com/TrueMajner/Cookie-Clicker-Hack/blob/master/README.md)  
[English version](https://github.com/TrueMajner/Cookie-Clicker-Hack/blob/master/README-EN.md)  
    
<h4 align="center">Основная информация.</h4> 
Главный объект игры - Game.
Код покупки объектов в игре работает так, что если у вас есть infinity "печенек" и вы купите что-либо за infinity "печенек" то у вас не останется "печенек".
  
<h4 align="center">Выдача "печенек"</h4> 
Выдать "печеньки" можно двумя способами :
  
Именно выдать "печеньки" :
```javascript
Game.Earn(number);
```  
Где number - любое целое число.
  
Либо установить кол-во "печенек" :
```javascript
Game.cookies = number;
```
Где number - любое целое число.
  

<h4 align="center">Бизнесы.</h4> 
Получить все бизнесы в кол-ве N :  
```javascript
for(i = 0; i < 17; i ++) {
Game.ObjectsById[i].amount=number;
}
```
Где number - любое целое число.
