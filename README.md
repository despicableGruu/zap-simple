# Log Maestro: Zap in Action

This project showcases the power of the Zap logging library for Go applications.


**Setup:**

```bash
. env.sh
go get go.uber.org/zap
go run src/basic/main.go 
```


**Examples:**

* Minimalist Logging: `./src/basic`
* Configured Logging: `./src/config`
* Shared Logger: `./src/shared`
* Custom Log Format: `./src/format`