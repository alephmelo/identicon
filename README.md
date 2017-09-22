# Identicon
From wikipedia:
> [Identicon](https://en.wikipedia.org/wiki/Identicon) is a visual representation of a hash value, usually of an IP address, that serves to identify a user of a computer system as a form of avatar while protecting the users' privacy. The original Identicon was a 9-block graphic, and the representation has been extended to other graphic forms by third parties.
## Usage
```
$ git clone git@github.com:alephmelo/identicon.git
$ cd identicon
$ iex -S mix
```
It will enter the Elixir interpreter.
```
iex(1)> Identicon.main("test")
:ok
```
## Demo
This identicon is the output for the string "test".

![test](test.png)
