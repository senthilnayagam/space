space
=====

a simple ruby shell script for handling whitespace


I had to parse "rake routes" and searching google for sed and awk made me write this script


ruby has excellent string processing capabilities, enabling a few in this command

in conjunction with gsub ( https://github.com/senthilnayagam/gsub/ ) this is a useful tool 

install
=======

requires ruby, which comes preinstalled with almost all osx or linux operating systems

move the space file to a path which is loaded by your OS and make it executable


> mv space /usr/bin

> chmod +x space


usage examples
==============

open a new terminal and run the space command without arguments


>  echo "  I love  ruby    :) " | space -l

I love  ruby    :) 

>  echo "  I love  ruby    :) " | space -r

  I love  ruby    :) 
>  echo "  I love  ruby    :) " | space -a

I love  ruby    :)

>  echo "  I love  ruby    :) " | space -s

 I love ruby :) 

>  echo "  I love  ruby    :) " | space -s -l

I love ruby :) 






