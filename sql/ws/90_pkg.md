# ws:90_pkg

## pg_store_proc

```sql
/*
  Описание ф-и pg_store_proc_descr
*/
SELECT * FROM ws.pg_store_proc_descr('ws') WHERE name = 'pg_store_proc_descr' ORDER BY name ASC
;
```
        name         |                                    comment                                    |         args          |                                  result                                   
---------------------|-------------------------------------------------------------------------------|-----------------------|---------------------------------------------------------------------------
 pg_store_proc_descr | получить описание аргументов и параметров хранимых процедур в указанной схеме | [["a_schema","text"]] | [["args","json"], ["comment","text"], ["name","text"], ["result","json"]]

