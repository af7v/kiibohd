# Instructions for setting up my custom keyboards

Go to ~/source/controller

Start the docker container
`docker run -it --rm -v "$(pwd):/controller" controller.archlinux`

Set up the environment
`pipenv install`
`pipenv shell`

Add lines for all layers found in My_KLL_Files in Scan/Infinity_Ergodox/
