# Instructions for setting up my custom keyboards

Go to ~/source/controller

Start the docker container
`docker run -it --rm -v "$(pwd):/controller" controller.archlinux`

Set up the environment
`pipenv install`
`pipenv shell`

`cd My_KLL_Files`

Copy over the files to /root/.local/share/virtualenvs/Keyboards-41-guJFC/lib/python3.9/site-packages/kll/layouts/infinity_ergodox/ folder
`cp *.kll /root/.local/share/virtualenvs/Keyboards-41-guJFC/lib/python3.9/site-packages/kll/layouts/infinity_ergodox/`


# Files to copy
* mdergo1Overlay.kll - The default layer
* Layer_1.kll
* Layer_2.kll
* Layer_3.kll
* Layer_4.kll
* Layer_5.kll
* Layer_6.kll
