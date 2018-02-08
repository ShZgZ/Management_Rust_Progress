# hello

module分けの練習

## externとuseの違い
### crateを利用する場合にexternを使う。

```
extern crate crate_name
```

### useはmoduleや関数を省略して使うためのもの

```
use crate_name::mod_name::fun_name;

fun_name();
```


