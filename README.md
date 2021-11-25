# unix-streams
standard input/output/error

![Output](https://user-images.githubusercontent.com/58792/143476648-735c106b-3679-4f2d-b1ae-d718347ad68c.png)

## Standard Out

* Filtering examples:  Sort and Uniq

echo -e "Apple\nCarrot\nBanana" | sort
echo -e "Apple\nCarrot\nBanana\nApple" | sort | uniq -c 

* Grep

echo -e "Apple\nCarrot\nBanana\nApple" | sort | uniq -c | grep Apple

ps -ef | grep python

* Rev

echo 1993
echo 1993 | rev