# NSQLite3DemoForUE
this is demo to use NSQLite3

# what can this plugin support
This is a code plugin that can make you access sqlite3 database very easy.

by using this plugin in your project, you can access sqlite3 database using Blueprints or C++。

you can execute sql statement such as select * from t_xxx where id=1 or insert into t_xxx(id, name) values  (1, 'ngcod') or other sql.

when we use select. the Blueprint node return a row. you can call it's GetNumber() by pass index or column name to gain you data.

# how to use
![useage](https://github.com/eonelv/NSQLite3DemoForUE/assets/8274145/3c4d5716-865a-47d2-baf9-fcf3227019a6)

![executequery](https://github.com/eonelv/NSQLite3DemoForUE/assets/8274145/51d8cd1e-8969-486f-bf51-b072907391c6)

![executesql](https://github.com/eonelv/NSQLite3DemoForUE/assets/8274145/2c69d4a3-0c7a-4036-999a-6000286126ea)

![open](https://github.com/eonelv/NSQLite3DemoForUE/assets/8274145/a559eb91-a02c-43d7-b7db-087623374b3b)

# access the database by UI
you can enter some sql in UI. and click relative button to execute
if you enter select, the result will show on ui 
![query](https://github.com/eonelv/NSQLite3DemoForUE/assets/8274145/ff56cece-4882-4479-bd54-7a10ec099579)


