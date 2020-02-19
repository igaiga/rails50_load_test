autoloadとeager_loadのテストサンプルアプリ

Rails 5.0.7.2
Ruby 2.6.5

lib以下にFooクラス定義

テストコマンド

- $ DISABLE_SPRING=true RAILS_ENV=production rails runner "Foo.new.foo"
