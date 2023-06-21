## Initialize Go app
go mod init github.com/NickMarinade/react_go_todo

## Install Fiber v2
go get -u github.com/gofiber/fiber/v2

## Create client app with Vite
npx create-vite client --template react-ts

## Install dependencies
npm install @mantine/hooks @mantine/core swr @primer/octicons-react