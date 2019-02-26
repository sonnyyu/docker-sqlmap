Grab it from dockerhub:

docker pull sonnyyu/sqlmap

test it:

docker run -it --rm sonnyyu/sqlmap -hh

and use it with:

docker run -it --rm sonnyyu/sqlmap --url www.example.com/?id=1


