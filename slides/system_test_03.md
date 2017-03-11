### [System tests](https://github.com/rails/rails/pull/26703)

* デフォルトでApplicationSystemTestCase という親クラスが生成されるようになっている
* driven_by メソッドでテストに使用するdriverを使用出来る
  * :rack_test、:selenium、:poltergeist
  * selenium driverの場合のみbrowser、screen sizeを指定可能
* テスト失敗時に自動でスクリーンショットをとってくれるようになっている
