---
id: 5900f3a21000cf542c50feb5
challengeType: 5
title: 'Problem 54: Poker hands'
videoUrl: ''
localeTitle: 'Проблема 54: Покерные руки'
---

## Description
<section id="description"> В покерной карточной игре рука состоит из пяти карт и оценивается от самого низкого до самого высокого, следующим образом: High Card: карта с наивысшим значением. Одна пара: две карты одинакового значения. Две пары: две разные пары. Три вида: три карты одинакового значения. Прямо: все карты являются последовательными значениями. Flush: все карты одного и того же костюма. Полный дом: три вида и пара. Четыре вида: четыре карты одинакового значения. Straight Flush: все карты являются последовательными значениями одного и того же костюма. Royal Flush: десять, Джек, королева, король, туз, в одном костюме. Карты оцениваются в порядке: 2, 3, 4, 5, 6, 7, 8, 9, 10, Джек, Королева, Король, Туз. Если два игрока имеют одинаковые ранжированные руки, тогда выигрывает звание, состоящее из наибольшего выигрыша; например, пара восьмерок бьет пару пятерок (см. пример 1 ниже). Но если, например, два ранга связаны, у обоих игроков есть пара ферзей, тогда сравниваются старшие карты в каждой руке (см. Пример 4 ниже); если старшие карты связаны, то сравниваются следующие старшие карты и так далее. Рассмотрим следующие пять рук для двух игроков: <p> Ручной игрок 1 Игрок 2 Победитель 1 5H 5C 6S 7S KDPair of Fives 2C 3S 8S 8D TDPair of Eights Player 2 2 5D 8C 9S JS ACHighest карта Ace 2C 5C 7D 8S QHHighest карта Queen Player 1 3 2D 9C AS AH ACThree Aces 3D 6D 7D TD QDFlush с Diamonds Player 2 4 4D 6S 9H QH QCPair QueensHighest карта Девять 3D 6D 7H QD QSPair QueensHighhest карта Семь игроков 1 5 2H 2D 4C 4D 4SFull HouseWith Three Fours 3C 3D 3S 9S 9DFull Housewith Three Threes Player 1 </p><p> Файл, poker.txt, содержит тысячу случайных раздач, раздаваемых двум игрокам. Каждая строка файла содержит десять карт (разделенных одним пробелом): первые пять - карты игрока 1, а последние пять - карты игрока 2. Вы можете предположить, что все руки действительны (нет недопустимых символов или повторных карт), рука каждого игрока не имеет определенного порядка, и в каждой руке есть явный победитель. Сколько рук выигрывает игрок 1? </p></section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: ''
    testString: 'assert.strictEqual(euler54(), 376, "<code>euler54()</code> should return 376.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler54() {
  // Good luck!
  return true;
}

euler54();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
