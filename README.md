Build it:

git clone https://github.com/sonnyyu/docker-sqlmap

cd docker-sqlmap

docker build -t sqlmap .

Grab it from dockerhub:

docker pull sonnyyu/sqlmap

Test it:

docker run -it --rm sonnyyu/sqlmap -hh

Use it with:

docker run -it --rm sonnyyu/sqlmap --url www.example.com/?id=1


