# 概念
## 术语概念
1. database <span><input type="text"/></span>
2. collection <span><input type="text"/></span>
3. document <span><input type="text"/></span>
4. filed <span><input type="text"/></span>
5. index <span><input type="text"/></span>
6. primary key <span><input type="text"/></span>

## 数据库
1. 默认数据库 <span><input type="text"/></span> <button type="button"  class="btn btn-success" onclick="alert('data路径下的db库')">正解</button>
2. <span><input type="text"/></span> 命令可以显示所有数据的列表<button type="button"  class="btn btn-success" onclick="alert('show db')">正解</button>
3. <span><input type="text"/></span> 命令可以显示当前数据库对象或集合<button type="button"  class="btn btn-success" onclick="alert('db')">正解</button>
4. <span><input type="text"/></span> 命令可以连接到一个指定的数据库<button type="button"  class="btn btn-success" onclick="alert('use 数据库名')">正解</button>
5. 数据库名的要求：<span><input type="text"/></span><button type="button"  class="btn btn-success" onclick="alert('①全部小写；②最多64字节；③不能有空字符串、￥ / \0 . 等')">正解</button>
6. 以下特殊数据库的作用分别是什么？
 - admin：<span><input type="text"/></span><button type="button"  class="btn btn-success" onclick="alert('root数据库，库下的用户自动继承所有权限')">正解</button>
 - local：<span><input type="text"/></span><button type="button"  class="btn btn-success" onclick="alert('该库不会被复制，存储限于本地单台服务器的任意集合')">正解</button>
 - config：<span><input type="text"/></span><button type="button"  class="btn btn-success" onclick="alert('Mongo用于分片设置时，该库在内部使用，用于保存分片信息')">正解</button>

## 数据类型

|数据类型|描述|正解|
| -- | -- | -- |
|String| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('字符串。存储数据常用的数据类型。在 MongoDB 中，UTF-8 编码的字符串才是合法的。')">正解</button>|
|Integer| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('整型数值。用于存储数值。根据你所采用的服务器，可分为 32 位或 64 位。')">正解</button>|
|Boolean| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('布尔值')">正解</button>|
|Double| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('双精度浮点值')">正解</button>|
|Min/Max keys	| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('将一个值与 BSON（二进制的 JSON）元素的最低值和最高值相对比。')">正解</button>|
|Array| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('用于将数组或列表或多个值存储为一个键。')">正解</button>|
|Timestamp| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('时间戳。记录文档修改或添加的具体时间。')">正解</button>|
|Object| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('用于内嵌文档')">正解</button>|
|Null| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('用于创建空值')">正解</button>|
|Symbol| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('符号。该数据类型基本上等同于字符串类型，但不同的是，它一般用于采用特殊符号类型的语言。')">正解</button>|
|Date| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('日期时间。用 UNIX 时间格式来存储当前日期或时间。你可以指定自己的日期时间：创建 Date 对象，传入年月日信息。')">正解</button>|
|Object ID| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('对象 ID。用于创建文档的 ID。')">正解</button>|
|Binary Data| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('二进制数据')">正解</button>|
|Code| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('代码类型')">正解</button>|
|Regular expression| <span><input type="text"/></span> |<button type="button"  class="btn btn-success" onclick="alert('代码类型')">正解</button>|

