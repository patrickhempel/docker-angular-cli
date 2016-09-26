#docker-angular-cli
[angular-cli 1.0.0.beta-15](https://github.com/angular/angular-cli) in a container

node 4.15.0  
npm 3.10.8


#Usage
docker-angular-cli runs with `ng serve` in default mode.
   
```bash
 docker run --rm -it -v $PWD:/data -p 4200:4200 -p 49153:49153 patrickhempel/angular-cli  