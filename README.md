# Crypto Alert
This app shows notifications when crypto value exceeds your saved limit for Bitcoin or Ethereum.

![limit](https://github.com/J268sing/Crypto-Alert/blob/main/limits.gif)&nbsp;&nbsp;&nbsp;&nbsp;![notification](https://github.com/J268sing/Crypto-Alert/blob/main/notification.gif)&nbsp;&nbsp;&nbsp;&nbsp;

## Getting Started

Clone the repository. The repository contains a `backend` folder for the backend server and an `android-app` directory. You can open the Android project directly in Android studio. 

Open the `backend` folder install the following dependencies:

```
$ go get github.com/labstack/echo
$ go get github.com/labstack/echo/middleware
$ go get github.com/pusher/push-notifications-go
```

and run this this command to get your server up:

```
$ go run main.go
```
### Prerequisites

You need the following installed:

- [Android Studio](https://developer.android.com/studio/index) installed on your machine (v3.x or later). Download here.
- Go version 1.10.2 or later [installed](https://golang.org/doc/install#install).



## Built Using
* [Kotlin](https://kotlinlang.org/) - Used to build the Android client
* [Pusher Beams](https://pusher.com/beams) - APIs to enable devs building realtime notifications
* [Go](https://golang.org/doc/install#install) - Used to build the server using echo framework
* [Cryptocompare](https://www.cryptocompare.com) - API Used for real-time, high-quality and reliable cryptocurrency data
* [Firebase](https://firebase.google.com) - to store user data
* [Firebase](https://firebase.google.com) - to store user data




## Upcoming features

- [responsive UI](https://github.com/J268sing/MyCrypto) with integration of all cryptocurrencies.
- `Fake Holdings` allowing users to buy crypto with paper money.
- `Smart Calculations` to allow users to track their holdings and it's change during last 24 hours.
- `No Registration` to remain completely anonymous where app won't track private data about trading strategies.
