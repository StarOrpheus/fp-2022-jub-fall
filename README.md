# HW02

## Срок сдачи -- 23:59 18 сентября

Файл [List.hs](src/List.hs) содержит код для работы со списками, который мы написали на практике, а также несколько "дырок" -- функций, которые вам предстоит реализовать. Для этих функций указан тип, а в комментариях написано, что они должны сделать.

Файл [BinTree.hs](src/BinTree.hs) содержит определение бинарного дерева, а также несколько "дырок" -- функций, которые вам предстоит реализовать. Для этих функций указан тип, а в комментариях написано, что они должны сделать.

Все тесты должны проходить.

* `stack build` собирает проект

* `stack test` запускает тесты

* `stack ghci` запускает `ghci` и подгружает туда зависимости и модули проекта

   * `stack ghci test/Test/List.hs` подгрузит в `ghci` модуль с тестами на список

* `stack run` соберет проект и запустит исполнимый файл.

   * Исполнимый файл запустит функцию `main`, описанную в файле [Main.hs](app/Main.hs). На данный момент она ничего полезного не делает, но можно писать там код, чтобы отлаживаться.
