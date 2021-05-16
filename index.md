# 概念
## 术语概念
1. database <span><input type="text"/></span>
2. collection <span><input type="text"/></span>
3. document <span><input type="text"/></span>
4. filed <span><input type="text"/></span>
5. index <span><input type="text"/></span>
6. primary key <span><input type="text"/></span>

## 数据库
1. 默认数据库 <span><input type="text"/></span> <button type="button"  class="btn btn-success" onclick="alert('hello!')">正解</button>
2. <span><input type="text"/></span> 命令可以显示所有数据的列表
3. <span><input type="text"/></span> 命令可以显示当前数据库对象或集合
4. <span><input type="text"/></span> 命令可以连接到一个指定的数据库
5. 数据库名的要求：<span><input type="text"/></span>
6. 以下特殊数据库的作用分别是什么？
 - admin：<span><input type="text"/></span>
 - local：<span><input type="text"/></span>
 - config：<span><input type="text"/></span>

## 数据类型

|数据类型|描述|
| -- | -- |
|String| <span><input type="text"/></span> |
|Integer| <span><input type="text"/></span> |
|Boolean| <span><input type="text"/></span> |
|Double| <span><input type="text"/></span> |
|Min/Max keys	| <span><input type="text"/></span> |
|Array| <span><input type="text"/></span> |
|Timestamp| <span><input type="text"/></span> |
|Object| <span><input type="text"/></span> |
|Null| <span><input type="text"/></span> |
|Symbol| <span><input type="text"/></span> |
|Date| <span><input type="text"/></span> |
|Object ID| <span><input type="text"/></span> |
|Binary Data| <span><input type="text"/></span> |
|Code| <span><input type="text"/></span> |
|Regular expression| <span><input type="text"/></span> |


??? note "answer"
  1. db
  2. 'show db'
  3. 'db'
  4. 'use 数据库名'
  5. 全部小写；最多64字节；不能有空字符串、￥ / \0 . 等
  6. ① root数据库，库下的用户自动继承所有权限；② 该库不会被复制，存储限于本地单台服务器的任意集合； ③ Mongo用于分片设置时，该库在内部使用，用于保存分片信息
