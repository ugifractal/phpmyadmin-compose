# phpmyadmin-compose
pack phpmyadmin 2.5.7.0 on docker for easier install.

## usage

```
git clone https://github.com/ugifractal/phpmyadmin-compose.git
cd phpmyadmin-compose
```
open ```docker-compose.yml``` using text editor. edit the ```host.app``` to point 
to IP address of your mysql IP address. mysql should run on 0.0.0.0 if installed locally (default is 127.0.0.0)

```
docker-compose up
```

open your browser and go to ```http://localhost:8000```
