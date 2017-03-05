### [Yarn Support](https://github.com/rails/rails/pull/26836)

* 下記対応が行われています
  * `bin/yarn` stubの追加
  * assets path に`node_modules`を追加
  * `assets:precompile` task 実行前にyarn installの実行
* `bin/yarn` stub及び assets pathの追加は`rails new`時に追加・設定されるので、既存のアプリを更新する場合は`app:update` task等により追加作業が必要です
