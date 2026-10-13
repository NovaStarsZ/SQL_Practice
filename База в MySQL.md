Работа с базой данных в MySQL
===

**Цель:** Закрепить навыки удаления и создания базы данных, работы с таблицами, вставки записей, изменения данных и изменения структуры таблицы.


#### Шаги:

1. Удалить базу данных beer_suppliers. <br> Команда: `DROP DATABASE`

![Изображение](https://i128.fastpic.org/big/2026/1013/cd/069ec76ee93646b3f9814624d4c4d3cd.png)

2. Создать новую базу данных flowers. <br> Команда: `CREATE DATABASE`

![Изображение](https://i128.fastpic.org/big/2026/1013/2e/f4f574877ed206304d70a26a20c5f32e.png)

3. Переключиться на flowers. <br> Команда: `USE`
4. Создать таблицу suppliers со следующими колонками: id, supplier, country, delivery. <br> Команда: `CREATE TABLE`
5. Добавить новую колонку flower после колонки supplier. <br> Команда: `ALTER TABLE ... ADD COLUMN ... AFTER`

![Изображение](https://i128.fastpic.org/big/2026/1013/10/7426596b40042217b99dc39a30898d10.png)

6. Внести 8 записей о поставщиках цветов. <br> Команда: `INSERT INTO ... VALUES`

![Изображение](https://i128.fastpic.org/big/2026/1013/17/a5e21ea9933df93625e9a046c452c617.png)

7. Переименовать одну запись. <br> Команда: `UPDATE ... SET ... WHERE`

![Изображение](https://i128.fastpic.org/big/2026/1013/30/2c85105497e71cf3ead13289bb2f8430.png)

8. Изменить структуру таблицы:
   - увеличить максимальную длину колонки flower до 150 символов;
   - переименовать колонку supplier в provider.

Команды:
- `ALTER TABLE ... MODIFY COLUMN`
- `ALTER TABLE ... CHANGE COLUMN`

9. Проверить результат. <br> Команда: `SELECT * FROM`

![Изображение](https://i128.fastpic.org/big/2026/1013/d6/df62dba71dfdaf648f436d48e5c623d6.png)