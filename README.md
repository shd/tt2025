Курс теории типов, КТ, весна 2025
=================================
## Материалы
+ [конспект лекций] (https://github.com/shd/tt2018-conspect)
+ [теоретические домашние задания] (https://github.com/shd/tt2025/blob/master/hw-theory.pdf)
+ [материал для первой половины курса] Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 0
### Лямбда-исчисление, базовые определения, примеры
+ Немного об истории
+ Парадокс Карри
+ Типизация по Чёрчу и по Карри.
+ Правила вывода
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ J. Barkley Rosser: Highlights of the history of the Lambda-Calculus

## Лекция 1
### Теорема Чёрча-Россера, Y-комбинатор
+ Бета-редуцируемость и параллельная бета-редукция
+ Теорема Чёрча-Россера
+ Нормальные формы, ленивые вычисления, нормальный порядок редукции
+ Теоремы о типизации редукции, Чёрча-Россера, об уникальности типизации по Чёрчу.
+ Три задачи (проверка обитаемости, проверка типа, вывод типа)
+ Задача унификации
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 2
### Теоремы о просто типизированном лямбда исчислении
+ Вывод типа в просто типизированном лямбда-исчислении
+ Выразительная сила просто типизированного лямбда-исчисления
+ Невыразимость связок ИИВ через друг друга
+ Сильная и слабая нормализуемость
+ Теорема о сильной нормализуемости исчисления
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf

## Лекция 3
### Исчисление предикатов второго порядка, система F, типовая система Хиндли-Милнера
+ Исчисление предикатов второго порядка и система F, введение
+ Выразимость всех связок через кванторы существования и импликацию
+ Правила для кванторов существования
+ Экзистенциальные типы
+ Ранг типа
+ Типовая система Хиндли-Милнера
### Где почитать
+ Morten Heine B. Sørensen, Pawel Urzyczyn: Lections on the Curry-Howard Isomorphism
https://disi.unitn.it/~bernardi/RSISE11/Papers/curry-howard.pdf
+ John C. Mitchell, Gordon D. Plotkin, Abstract Types Have Existential Type
http://homepages.inf.ed.ac.uk/gdp/publications/Abstract_existential.pdf
+ Luis Damas and Robin Milner, Principal type-schemes for functional programs
POPL'82: Proceedings of the 9th ACM SIGPLAN-SIGACT symposium on Principles of programming languages, ACM, pp. 207–212
+ Robin Milner, A theory of type polymorphism in programming (1978) // Journal of Computer and System Sciences, 1978, vol. 17, pp. 348--375
https://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.67.5276
+ Бенджамин Пирс, Типы в языках программирования. Издательство «Лямбда пресс» & «Добросвет», Москва, 2011

## Лекция 4
### Обобщённые типовые системы. Лямбда-куб Барендрегта
+ Алгоритм W
+ Рекурсивные типы, Y-комбинатор.
+ Генерики, зависимые типы
+ Аксиоматика обобщённой типовой системы
+ Лямбда-куб
+ Изоморфизм Карри-Ховарда для зависимых типов
+ Примеры зависимых типов в языке программирования Идрис
### Где почитать
+ Henk Barendregt, Introduction to generalized type systems.
Journal of Functional Programming 1 (2): 125-154, April 1991
+ Documentation for the Idris language
http://docs.idris-lang.org/en/latest/

## Лекция 5
### Язык Аренд. Изоморфизм Карри-Ховарда-Воеводского. Гомотопическая теория типов
+ Интуиционистская теория типов.
+ Общие сведения об индуктивных типах.
+ Экстенсиональный и интенсиональный вариант теории.
+ Гомотопическая теория типов, равенство.
+ Изоморфизм Карри-Ховарда-Воеводского
+ Общие сведения о языке Аренд.
+ Равенство в языке Аренд.
### Где почитать
+ Документация по языку Аренд.
https://arend-lang.github.io/documentation/
+ <<HoTT book>> Homotopy Type Theory: Univalent Foundations of Mathematics.  The Univalent Foundations Program
Institute for Advanced Study. 
https://homotopytypetheory.org/book/
+ Хатчер А, Алгебраическая топология. Издательство МЦНМО, Москва, 2011

## Лекция 6
### Иерархии универсумов в Аренде
+ Prop и Set в Coq
+ Обобщение: гомотопическая иерархия в Аренде
+ Пропозициональное усечение
+ Сорта в языках с зависимыми типами, мотивация для сортов выше звёздочки
+ Парадокс Жирара (формулировка)
+ Предикативная иерархия
### Где почитать
+ Документация по языку Coq
https://coq.inria.fr/doc/V8.13.0/refman/addendum/extraction.html
+ Документация по языку Аренд
https://arend-lang.github.io/documentation/
+ A.J.C. Hurkens, A Simplification of Girard's Paradox. 
In: Dezani-Ciancaglini, M., Plotkin, G. (eds) Typed Lambda Calculi and Applications. 
TLCA 1995. Lecture Notes in Computer Science, vol 902. Springer, Berlin, Heidelberg. 

## Лекция 7
### Алгебраическая топология
+ Гомеоморфизм, гомотопия, гомотопическая эквивалентность
+ Сферы, фундаментальная группа
+ Фундаментальная группа S^1
+ Фундаментальные группы в Аренде
+ Аксиома унивалентности
### Где почитать
+ Документация по языку Аренд
https://arend-lang.github.io/documentation/
+ Хатчер А, Алгебраическая топология. Издательство МЦНМО, Москва, 2011
+ <<HoTT book>> Homotopy Type Theory: Univalent Foundations of Mathematics. The Univalent Foundations Program
Institute for Advanced Study. 
https://homotopytypetheory.org/book/

## Лекция 8
### Аксиома выбора, сетоиды, теорема Диаконеску
+ Set не множество, доказуемость аксиомы выбора для Set-ов.
+ Сетоиды, теорема Диаконеску
+ Аксиома выбора в HoTT
+ Доказательство теоремы Диаконеску на Аренде
### Где почитать
+ Стандартная библиотека языка Аренд
+ <<HoTT book>> Homotopy Type Theory: Univalent Foundations of Mathematics. The Univalent Foundations Program
Institute for Advanced Study. 
https://homotopytypetheory.org/book/

## Лекция 9
### Ещё о равенстве в Аренде, Парадокс Жирара
+ Эта-экспансия в Аренде
+ Фактор-множества в Аренде
+ Доказательство равенства всех экземпляров данного пропа в Аренде
+ Парадокс Бурали-Форти
+ Адаптация и упрощение парадокса: парадоксальные универсумы
+ Конструкции из U и U^-, позволяющие выразить упрощённый парадокс
+ Первая версия доказательства лжи в U^-
+ Мощные универсумы, дальнейшее упрощение парадокса
+ Вторая версия доказательтсва лжи
### Где почитать
+ Antonius Hurkens, A Simplification of Girard's Paradox.

## Лекция 10
### Линейные и уникальные типы
+ Линейная логика (вариант Филиппа Вадлера)
+ Комбинаторный базис BCKW и линейные типы
+ Уникальные типы (вариант Эдско де Вриеса и др.)
+ Применение идеи в языках программирования
### Где почитать
+ Philip Wadler. A taste of linear logic
+ Edsko de Vries, Rinus Plasmeijer, David M Abrahamson. Uniqueness Typing Simplified
