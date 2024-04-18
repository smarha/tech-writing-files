https://github.com/postgrespro/jsquery
> JsQuery – is a language to query jsonb data type, introduced in PostgreSQL release 9.4.

JsQuery - is a query language for jsonb data type, introduced in PostgreSQL 9.4.

> It's primary goal is to provide an additional functionality to jsonb (currently missing in PostgreSQL), such as a simple and effective way to search in nested objects and arrays, more comparison operators with indexes support. We hope, that jsquery will be eventually a part of PostgreSQL.

It's primary goal is to provide additional functionality to jsonb (currently missing in PostgreSQL), such as a simple and effective way to search in nested objects and arrays, more comparison operators with **index** support. We hope that jsquery **will eventually become** part of PostgreSQL.

> JsQuery is realized as an extension and not available in default PostgreSQL installation. It is available from [github](https://github.com/postgrespro/jsquery) under the same license as [PostgreSQL](https://www.postgresql.org/about/licence/) and supports PostgreSQL 9.4+.

JsQuery is **released** as an extension and **is not** available in the standard PostgreSQL installation. It is available **on**  [github](https://github.com/postgrespro/jsquery) under the same licence as [PostgreSQL](https://www.postgresql.org/about/licence/) and supports PostgreSQL 9.4+.

> JsQuery is PostgreSQL extension which requires PostgreSQL 9.4 or higher. Before build and install you should ensure following:

JsQuery is **a** PostgreSQL extension **that** requires PostgreSQL 9.4 or higher. Before **building and installing** you should ensure **the** following:

> JsQuery was tested on flex 2.5.37-2.5.39, bison 2.7.12.

JsQuery **has been** tested on flex 2.5.37-2.5.39, bison 2.7.12.


> When comparison entries, the path hash is the higher part of entry and the value is the lower part. This determines the features of this opclass. Since the path is hashed and it's the higher part of the entry...

When **comparing** entries, the path hash is the **upper** part of the entry and the value is the lower part. This determines the features of that opclass. Since the path is hashed and it's the **upper** part of the entry...

_____
