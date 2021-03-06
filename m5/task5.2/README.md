## Task 5.2

Show your location
```
pwd
```
![](https://i.imgur.com/0chVjfm.png)
 
Show list of files in root directory in human readable format, with information about rules, count of hard links, owner and group, size, creation date, and name
```
ls -l / 
```
![](https://i.imgur.com/1fVrPmE.png)

Show only files list
```
ls
```
![](https://i.imgur.com/ggMrQNG.png)

Show files list in user's home directory
```
ls ~
```
![](https://i.imgur.com/pjICBkQ.png)

Show list of hidden files
```
ls -a
```
![](https://i.imgur.com/SCYRCiy.png)

Show information about your home dir (rules, count of hard links, owner and group, size, creation date, and name)
```
ls -lda ~
```
![](https://i.imgur.com/9ylxgzi.png)


 Create a new dir: ``mkdir test``, go to this dir: ``cd test``,  check our location: ``pwd``, create file *test.txt*: ``touch test.txt``, create socond dir: ``mkdir test2``, move *test.txt* to *test2*: ``mv test.txt test2``, go to this dir: ``cd test2``, check files list: ``ls``, rename *test.txt* to *test2.txt*: ``mv test.txt test2.txt``, check files list: ``ls``, copy *test2.txt* one  level below: ``cp test2/txt ../``, go to one level below: ``cd ..``, check files list there: ``ls``, delete dir and file: ``rm -rf test2*``.
* ![](https://i.imgur.com/HjJNPQA.png)

```
cat /etc/fstab
```
![](https://i.imgur.com/OFZ0I6d.png)

```
less /etc/fstab
```
![](https://i.imgur.com/GPvbOEr.png)

```
more /etc/fctab
```
![](https://i.imgur.com/wa7xbfP.png)

The difference between commands ``cat``, ``less`` and ``more`` is that cat displays files content using standard output, commands more and less displays files content using page by page output. Command ``less`` is a more advanced version of the command ``more``.
