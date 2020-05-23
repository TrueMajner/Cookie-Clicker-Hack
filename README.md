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
  
Получить бизнес номер X в кол-ве N :
  
```javascript
Game.ObjectsById[x].amount=number;
``` 
Где number - любое целое число, x - целое число от 0 до 16 включительно.
  
Список :  
- 0 - курсор  
- 1 - Бабушка  
- 2 - Ферма  
- 3 - Шахта  
- 4 - Фабрика  
- 5 - Банк  
- 6 - Хром  
- 7 - Башня Мага  
- 8 - Shipment  
- 9 - Алхимия  
- 10 - Портал  
- 11 - Машина времени  
- 12 - Antimatter кондиционер  
- 13 - Призма  
- 14 - Chancemaker  
- 15 - Fractal Enige  
- 16 - Консоль JS  

<h4 align="center">Любой ник.</h4> 
```javascript
Game.bakeryName="Что угодно /1/2/21!12341254,.,,./ 8 sjadisjai dsjdij sad";
Game.bakeryNameRefresh();
```
