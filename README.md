# go-kakaoEmoji

### Example
> ```go
> package main
> 
> import "github.com/app6460/go-kakaoEmoji"
> 
> func main() {
>   client := emoji.New("email", "password")
>   client.Login()// 이곤몽미
>   client.SendEmoji("shaky-animals-2", 1)
> }
> ```