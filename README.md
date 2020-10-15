## Safe remover
for os: linux

Run script as bash command. Enter filename as argument.
That file will be archived and moved to ~/RECYCLE directory.

Moved files will be alive here for 7 days after moving. Every older file will be removed by script for good.


### Prerequisites
```
mkdir ~/bin
echo export PATH="${PATH}:~/bin" >> .bash_profile
source .bash_profile
```

### Installing

```
git clone https://github.com/iamdianahello/srm
mv srm/srm ~/bin/srm
```


### Usage

After installing script is a bash command.  Need 1 argument, absolute or relative path to file

relative example:
```
srm filename
```

absolute example
```
srm /home/user/filename
```

