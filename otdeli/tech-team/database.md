# База данни

В момента платформата използва [PostgreSQL](https://www.postgresql.org/) за запазване на данните от отделните модули.

### Структура на базата данни

Структурата, на която се спряхме е да имаме 1 база данни, в която всеки модул да има собствен потребител и собствена schema. Правата на даден модул са ограничени единствено до собствената му схема като не е разрешена нито промяната нито четенето на записи от други модули на ниво база данни.

