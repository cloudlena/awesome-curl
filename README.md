# Awesome cURL

:sunglasses: A collection of awesome web services that can simply be used by `curl`-ing them from the command line.

## [wttr.in](https://wttr.in/)

:partly_sunny: The right way to check the weather

```shell
$ curl wttr.in

# Get the weather for a specific location
$ curl wttr.in/bern
```

## [ifconfig.co](https://ifconfig.co/)

IP address lookup service

```shell
$ curl ifconfig.co

# Get your currently detected country
$ curl ifconfig.co/country
# Get your currently detected city
$ curl ifconfig.co/city
```

## [tinyurl.com](https://tinyurl.com/)

URL shortener

```shell
$ curl -s 'tinyurl.com/api-create.php?url=https://curl.se'
```

## [getnews.tech](https://getnews.tech)

Read the news

```shell
$ curl getnews.tech

# Get the news for a specific topic
$ curl getnews.tech/linux
```

## [dict.org](https://dict.org)

Get the definition of a term

```shell
$ curl dict.org/d:linux
```

## [cheat.sh](https://cheat.sh)

Get a cheat sheet for terminal commands

```shell
$ curl cheat.sh/tar
```

## [rate.sx](https://rate.sx)

Get the latest cryptocurrentcy rates

```shell
$ curl rate.sx
```

## [parrot.live](https://parrot.live)

Get a dancing parrot in your terminal

```shell
$ curl parrot.live
```

## [sprunge.us](https://sprunge.us)

Terminal pastebin

```shell
$ echo 'cURL is great!' | curl -F 'sprunge=<-' http://sprunge.us
```

## [rickrollrc](https://github.com/keroserene/rickrollrc)

Get RickRoll'd

```shell
$ curl https://raw.githubusercontent.com/keroserene/rickrollrc/master/roll.sh | bash
```

## Sources

- [DistroTube on YouTube](https://www.youtube.com/watch?v=QJuz_O01mDg)
