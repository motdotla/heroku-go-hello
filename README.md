# heroku-go-hello

A Hello World Go application that can deploy to heroku

## Development

```
git clone https://github.com/scottmotte/heroku-go-hello.git
cd heroku-go-hello
go get github.com/codegangsta/martini
go run app.go
```

## Production

```
git clone https://github.com/scottmotte/heroku-go-hello.git
cd heroku-go-hello 
heroku create -b https://github.com/kr/heroku-buildpack-go.git 
git push heroku master
```
