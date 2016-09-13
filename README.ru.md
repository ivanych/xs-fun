XS - это клёво
==============

Любой XS-гуру скажет вам, что XS - это просто. Я слышал это много раз.
Но, хотя это и может быть правдой, я понял одну вещь: XS может быть страшным.

Цель этого руководства - сделать XS клёвым. Да, клёвым. Попробуйте - если вы не будете
ощущать такого же восторга, как и я, когда будете подниматься по лестнице знаний XS -
я полностью возмещу ваше обучение.

Основные правила
----------------

1. Мы будем использовать шаблон вместо [`h2xs`](http://perldoc.perl.org/h2xs.html).
2. Мы не будем связываться с дополнительной C-библиотекой
3. Мы предполагаем, что у вас есть, как минимум, Perl 5.14.2.

Это лучшие советы, которые я когда-либо получал, и они доказали свою важность.

`h2xs` старый и кривой, от него одни проблемы. Вместо него в это руководство
включена заготовка для каждого упражнения, которую можно скопировать и использовать
каждый раз, когды вы начинаете новый проект.

Упаковка дополнительных C-библиотек требует хаков с `ExtUtils::MakeMaker`
(что уже само по себе проблема), включая ночной кошмар табуляций и
дополнительные рекурсивные Makefile. Один из способов обойти пресловутую
проблему "you need to have this library installed" предоставляет пакет `Alien`.
Это руководство может перейти на него в какой-то момент, но обещать не могу.

Отказ от использования `h2xs` и упаковки любых сторонних (написанных не нами) C-библиотек
избавляет от множества лишних сложностей.

Perl 5.14.2 достаточно распространен, чтобы считать его отправной точкой, хотя этот
пункт не так уж и важен.

См. также
---------

* [perlxs](http://perldoc.perl.org/perlxs.html) (`perldoc perlxs`)
* [perlapi](http://perldoc.perl.org/perlapi.html) (`perldoc perlapi`)

Более продвинутые и специализированные источники
------------------------------------------------

* [General index](http://perldoc.perl.org/index-internals.html)
* [perlxstypemap](http://perldoc.perl.org/perlxstypemap.html) (`perldoc perlxstypemap`)
* [perlhack](http://perldoc.perl.org/perlhack.html) (`perldoc perlhack`)
* [perlhacktips](http://perldoc.perl.org/perlhacktips.html) (`perldoc perlhacktips`)
* [perlhacktut](http://perldoc.perl.org/perlhacktut.html) (`perldoc perlhacktut`)
* [perlguts](http://perldoc.perl.org/perlguts.html) (`perldoc perlguts`)
* [perlintern](http://perldoc.perl.org/perlintern.html) (`perldoc perlintern`)
* [perlinterp](http://perldoc.perl.org/perlinterp.html) (`perldoc perlinterp`)
* [perlcall](http://perldoc.perl.org/perlcall.html) (`perldoc perlcall`)
* [perlsource](http://perldoc/perl.org/perlsource.html) (`perldoc perlsource`)
