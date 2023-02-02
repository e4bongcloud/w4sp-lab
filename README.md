![lab](https://user-images.githubusercontent.com/96872399/211072216-d7782108-60f1-4df2-a689-34d0036f2fb3.png)

I have solved the problem of the w4sp-lab environment not working when configured according to the instructions in the previous book. To set up the environment, do the following:

https://github.com/slowdodo/w4sp-lab

[kali_linux docker install](https://www.kali.org/docs/containers/installing-docker-on-kali/)

``` bash
useradd -m w4sp-lab -s /bin/bash -G sudo -U
```
``` bash
passwd w4sp-lab
```
`user change kali -> w4sp-lap `
(If you log in from the terminal with su w4sp , even sudo will not run. You need to log out and connect to w4sp.)
``` bash
git clone https://github.com/slowdodo/w4sp-lab.git
```
``` bash
sudo python ./w4sp-lab/w4sp_webapp.py 
```


Please note that this lab may take a long time to set up, as it involves downloading multiple images. This is not due to any errors. If you have successfully set up the lab as described above, congratulations and happy learning!
