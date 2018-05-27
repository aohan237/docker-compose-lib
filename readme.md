# Instruction

this project is for people,who just want to deploy some service but dont want to study the way how to deploy.

Its purpose is to provide convenience for developping

Just download and run, Enjoy.

you are welcome to contrib to this repo

## Denpendency

* docker
* python
* docker-compose

## Version Check

until now, there is none.

you are welcome to help me to do this

## Usage

* Just download the entire directory you are interested in.(or clone the entire project and cd to the dir)

* Run docker-compose up (-d to be a daemon backgroud process)

* Enjoy

* If you reboot,you maybe need to cd to the dir and run " docker-compose start"
  for more information,refer to docker-compose

## Tips

* For Chinese developper,you can refer [USTC Docker source](https://lug.ustc.edu.cn/wiki/mirrors/help/docker)

* most common used libs have a single official sample,[docker sample](https://docs.docker.com/samples/),you can refer this to get your information

* some of libs are from other repos as a submodule, if you want to clone all the repo,
you need to add "--recurse-submodules" to your git clone

* submodule lib have their separate instructions ,but others may not have instructions right now. 