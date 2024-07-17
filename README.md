https://github.com/veryl-lang/veryl を動作させてみるプロジェクト。タイマーを作成する。

[task](https://github.com/go-task/task) を利用する。下記のコマンドが利用できる。

```
$ task --list-all
task: Available tasks for this project:
* build:
* clean:
* exec:
* fmt:
* test:
* test-verbose:
```

テストベンチの結果を知りたい場合は下記を実行する。`verbose` によって回路の状態をトレースする。 

```
$ task clean test-verbose
```

# 依存

- https://github.com/veryl-lang/veryl
- https://github.com/verilator/verilator