Reproduction case for https://github.com/reactjs/react-rails/issues/1276.

```
cd react-rails-2-7-ssr-bug
bundle install
bin/rails s
```

Visit '/' to render
https://github.com/tf/react-rails-2-7-ssr-bug/blob/main/app/views/test/index.html.erb
and get error of the form:

```
TypeError: Cannot read properties of undefined (reading 'version')
```
