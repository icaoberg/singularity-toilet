# singularity-toilet
![Release](https://img.shields.io/badge/release-prealpha-red.svg)
[![GitHub issues](https://img.shields.io/github/issues/icaoberg/singularity-toilet.svg)](https://github.com/icaoberg/singularity-toilet/issues)
[![GitHub forks](https://img.shields.io/github/forks/icaoberg/singularity-toilet.svg)](https://github.com/icaoberg/singularity-toilet/network)
[![GitHub stars](https://img.shields.io/github/stars/icaoberg/singularity-toilet.svg)](https://github.com/icaoberg/singularity-toilet/stargazers)
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/quick-guide-gplv3.en.html)

```
   mm  m     m mmmmmm  mmmm   mmmm  m    m mmmmmm
   ##  #  #  # #      #"   " m"  "m ##  ## #
  #  # " #"# # #mmmmm "#mmm  #    # # ## # #mmmmm
  #mm#  ## ##" #          "# #    # # "" # #
 #    # #   #  #mmmmm "mmm#"  #mm#  #    # #mmmmm
```

A simple container with [toilet](https://en.wikipedia.org/wiki/TOIlet).

## Building the container
```
bash ./run.sh
```

## List app(s)
```
singularity apps toilet.simg                                     
toilet
```

## Get help!
```
singularity help --app toilet toilet.simg

    For more information visit http://caca.zoy.org/toilet.html
```

## Running the app

```
singularity run --app toilet toilet.simg -f term -F border --gay "De anchoas, de muzzarela, con palmitos, jardinera, con ananá..."
┌───────────────────────────────────────────────────────────────┐
│De anchoas, de muzzarela, con palmitos, jardinera, con ananá...│
└───────────────────────────────────────────────────────────────┘

singularity run --app toilet toilet.simg -f future "Yyo pido cualquier pizza..."
╻ ╻╻ ╻┏━┓   ┏━┓╻╺┳┓┏━┓   ┏━╸╻ ╻┏━┓╻  ┏━┓╻ ╻╻┏━╸┏━┓   ┏━┓╻╺━┓╺━┓┏━┓
┗┳┛┗┳┛┃ ┃   ┣━┛┃ ┃┃┃ ┃   ┃  ┃ ┃┣━┫┃  ┃┓┃┃ ┃┃┣╸ ┣┳┛   ┣━┛┃┏━┛┏━┛┣━┫
 ╹  ╹ ┗━┛   ╹  ╹╺┻┛┗━┛   ┗━╸┗━┛╹ ╹┗━╸┗┻┛┗━┛╹┗━╸╹┗╸   ╹  ╹┗━╸┗━╸╹ ╹╹╹╹
```

## Download

To download the image, click [here](https://drive.google.com/open?id=1Y_yc15avjayJrEoHMIvXr6ZYAUjTWf7u)

---
[![CBD](http://www.cbd.cmu.edu/wp-content/uploads/2017/07/wordpress-default.png)](http://www.cbd.cmu.edu)

Copyleft © 2018-2019 [icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Computational Biology Department](http://www.cbd.cmu.edu) in [Carnegie Mellon University](http://www.cmu.edu)
