```
bundle install --path vendor/bundler --jobs 20
bundle exec rails s
```

http://localhost:3000/?a=1&b=2

```
2017-05-10T08:43:26+09:00       outing  {"messages":["Started GET \"/?a=1&b=2\" for 127.0.0.1 at 2017-05-10 08:43:26 +0900","Processing by Rails::WelcomeController#index as HTML","  Parameters: {\"a\"=>\"1\", \"b\"=>\"2\"}","  Rendered vendor/bundler/ruby/2.4.0/gems/railties-4.2.8/lib/rails/templates/rails/welcome/index.html.erb (0.1ms)","Completed 200 OK in 4ms (Views: 2.8ms | ActiveRecord: 0.0ms)"],"severity":"INFO","mt":"GET","pt":"/?a=1&b=2","ip":"127.0.0.1","ua":"Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.87 Safari/537.36","rf":null,"params":{"a":"1","b":"2"},"parameters":{"a":"1","b":"2"}}
```
