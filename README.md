# docker-swarm-stack
# Following are the docker commands to manage docker
    1  telnet
    2  docker version
    3  docker-machine start default
    4  docker-machine start
    5  dokcer-machine create default
    6  docker-machine create default
    7  npm install
    8  npm
    9  cd Projects/NSFWALES_INTRANET/
   10  npm install
   11  ng run
   12  ng start
   13  npm install -g @angular/cli
   14  ng start
   15  ng run
   16  npm start
   17  ng build --production
   18  ng build
   19  ng build --prod
   20  exit
   21  java -jar jenkins.war 
   22  docker run ello-world
   23  docker run hello-world
   24  catlina.bat
   25  ./catalina.bat
   26  ./catalina.bat run
   27  cd C:/
   28  cd Users/
   29  cd jnath/Projects/Jenkins/
   30  ls
   31  java -jar jenkins.war 
   32  java -jar jenkins.war 
   33  java -jar jenkins.war 
   34  cd ..
   35  ls
   36  docker container images ls
   37  docker image ls
   38  docker image rm *
   39  docker system prune
   40  docker netowrk ls
   41  docker network ls
   42  docker network inspect bridge
   43  docker container run -d -p 80:80 --name webapp nginx
   44  docker network inspect bridge
   45  docker network ls
   46  docker network create my_app_net
   47  docker network ls
   48  docker network inspect my_app_net
   49  docker container run -d --name new_nginx --network my_app_net nginx
   50  docker network inspect my_app_net
   51  docker container ls
   52  docker network connect 8c2c05 305b3d
   53  docker network connect 5a3cf 305b3d
   54  docker container inspect 305b3d
   55  docker network disconnect 5a3cf 305b3d
   56  docker container inspect 305b3d
   57  clear
   58  docker network l
   59  docker network ls
   60  docker container ls
   61  docker container run -d --name my_nginx --network my_app_net
   62  docker container run -d --name my_nginx --network my_app_net nginx
   63  docker network inspect my_app_net
   64  docker container ls
   65   docker container stop my_nginx new_nginx webapp
   66   docker container rm my_nginx new_nginx webapp
   67  docker container run -d --name new_nginx --network my_app_net nginx:alpine
   68  docker container run -d --name my_nginx --network my_app_net nginx:alpine
   69  docker network inspect my_app_net
   70  docker container exec -it new_nginx ping my_nginx
   71  winpty docker container exec -it new_nginx ping my_nginx
   72  clear
   73  docker container ls
   74  docker container my_nginx new_nginx
   75  docker container stop my_nginx new_nginx
   76  docker container rm my_nginx new_nginx
   77  docker container ls
   78  docker container run -d --name ubuntu --rm ubuntu
   79  docker container run -d --name centos --rm centos
   80  docker container ps
   81  docker container run -d --name ubuntu  ubuntu
   82  docker container ps
   83  docker container ls
   84  docker container run  --name ubuntu  ubuntu
   85  docker container stop 02b6a64
   86  docker container rm 02b6a64
   87  docker container rm ubuntu
   88  docker container run  --name ubuntu  ubuntu
   89  docker container ls
   90  docker container rm ubuntu
   91  docker container run  -d --name ubuntu  ubuntu
   92  docker container ls
   93  docker container ps
   94  docker container ls -a
   95  docker container run -it --name ubuntu ubuntu bash
   96  winpty docker container run -it --name ubuntu ubuntu bash
   97  docker container rm ubuntu
   98  winpty docker container run -it --name ubuntu ubuntu bash
   99  docker container rm ubuntu
  100  winpty docker container run -it --name centos centos bash
  101  docker container rm centos
  102  docker system prune
  103  docker network create search_network
  104  docker container run -d --name elasticsearch1 --network search_network --net-alias search elasticsearch:2
  105  docker container ls
  106  docker container run -d --name elasticsearch2 --network search_network --net-alias search elasticsearch:2
  107  docker container ls
  108  docker network inspect search_network
  109  docker container run --name alpine alpine nslookup search 
  110  docker container run -it centos
  111  winpty docker container run -it centos
  112  docker container ls
  113  docker container run --network search_network --name alpine alpine nslookup search 
  114  docker container rm alpine
  115  docker container run --network search_network --name alpine alpine nslookup search 
  116  winpty docker container run -it --network search_network centos
  117  docker container ls
  118  docker image ls
  119  docker history nginx:latest
  120  clear
  121  docker history nginx:latest
  122  ls
  123  echo docker history nginx:latest > history.text
  124  ls
  125  cat history.text 
  126  docker history nginx:latest > history.text
  127  cat history.text 
  128  code .
  129  docker image inspect nginx
  130  docker image tag --help
  131  docker image ls
  132  docker image tag nginx jyotirmoy/nginx
  133  docker image ls
  134  docker image push jyotirmoy/nginx
  135  docker login
  136  docker image push jyotirmoy/nginx
  137  cat .docker/config.json
  138  docker image push jyotirmoy/nginx
  139  docker image push jyotirmoy/nginx
  140  cd c:
  141  cd Users/jnath/Projects/udemy-docker-mastery/dockerfile-smaple-2
  142  cd Users/jnath/Projects/udemy-docker-mastery/dockerfile-sample-2
  143  code .
  144  docker build -t jyotirmoy/mywebapp -f Dockerfile .
  145  docker container run -p 91:80 jyotirmoy/mywebapp:latest
  146  docker image tag jyotirmoy/mywebapp jyotirmoy/mywebappwithhtml
  147  docker login
  148  docker push jyotirmoy/mywebappwithhtml
  149  cd ..
  150  cd ..
  151  ls
  152  cd dockertuts/
  153  ls
  154  rm dockertuts/
  155  code .
  156  clear
  157  docker pull mysql
  158  docker inspect mysql
  159  docker container run -d --name mysql_server -e MYSQL_ALLOW_EMPTY_PASSWORD=True mysql
  160  docker container inspect mysql_server
  161  docker volume ls
  162  docker volume inspect 5567e
  163  docker volume inspect 5567e02
  164  docker container stop mysql_server
  165  docker container rm -f mysql_server
  166  docker container run -d --name mysql_server -e MYSQL_ALLOW_EMPTY_PASSWORD=True -v mysql-db:/var/lib/mysql mysql
  167  docker volume ls
  168  docker volume inspect mysql-db
  169  ls
  170  clear
  171  cd ..
  172  mkdir dockerproj2
  173  cd dockerproj2/
  174  code .
  175  docker container run -d --name mywebserver2 -p 92:80 -v $(pwd):/usr/share/nginx/html nginx
  176  docker container run -d --name mywebserver2 -p 92:80 -v $(pwd):./usr/share/nginx/html nginx
  177  docker container run -d --name mywebserver2 -p 92:80 -v $(pwd):/usr/share/nginx/html nginx
  178  docker container run -d --name mywebserver2 -p 92:80 -v ./:/usr/share/nginx/html nginx
  179  docker container run -d --name mywebserver2 -p 92:80 -v .:/usr/share/nginx/html nginx
  180  docker container run -d --name mywebserver2 -p 92:80 -v /:/usr/share/nginx/html nginx
  181  docker container run -d --name mywebserver2 -p 92:80 -v //c/users/jnath/projects/dockerproj2:/usr/share/nginx/html nginx
  182  docker container exec -it mywebserver2 bash
  183  winpty docker container exec -it mywebserver2 bash
  184  ls
  185  clear
  186  docker container run -d -v //c/users/jnath/projects/dockerproj2:/var/lib/postgresql/data postgres:9.6.1
  187  docker logs d59204
  188  docker logs d59204
  189  docker logs d59204 -f
  190  docker logs -f d59204
  191  ls
  192  docker container ls
  193  docker container stop $(docker container ls)
  194  docker container stop 
  195  docker container stop $(docker container ls -a)
  196  docker container stop $(docker container ls)
  197  docker container run -d -v //c/users/jnath/projects/dockerproj2/data:/var/lib/postgresql/data postgres:9.6.1
  198  docker logs 430d58
  199  docker logs 430d58
  200  docker logs 430d58
  201  docker logs 430d58
  202  docker logs 430d58
  203  docker container ls
  204  docker logs 430d58
  205  docker logs 430d58
  206  docker container stop 430d58
  207  docker container run -d -v //c/users/jnath/projects/dockerproj2/data:/var/lib/postgresql/data postgres:latest
  208  docker logs e70af
  209  docker logs e70af
  210  docker container ;s
  211  docker container ls
  212  cd c:
  213  cd Users/jnath/Projects/
  214  ls
  215  cd udemy-docker-mastery/
  216  ls
  217  cd docker-sample-1
  218  cd dockerfile-sample-1
  219  code .
  220  ll
  221  docker image -t jyotirmoy/webserver2 build -f Dockerfile .
  222  docker image  build -f Dockerfile -t jyotirmoy/webserver2 .
  223  docker image ls
  224  docker image  build -f Dockerfile -t jyotirmoy/webserver2 .
  225  cd ..
  226  dockerfile-assignment-1/
  227  cd dockerfile-assignment-1/
  228  cdoe .
  229  code .
  230  cd ..
  231  cd bindmount-sample-1/
  232  code .
  233  rtt
  234  docker run -d --name Jekyll -p 40:80 -v //c/users/jnath/projects/udemy-docker-mastery/bindmount-sample-1:/site bretfisher/jekyll-serve
  235  docker run -d --name Jekyll2 -p 42:4000 -v //c/users/jnath/projects/udemy-docker-mastery/bindmount-sample-1:/site bretfisher/jekyll-serve
  236  docker container run
  237  docker container ls
  238  docker container stop Jekyll mywebserver2 mysql_server 048e 3f4b -f
  239  docker container stop Jekyll mywebserver2 mysql_server 048e 3f4b 
  240  docker container ls
  241  docker conttainer rm -f 859d 3393 c582
  242  docker conttainer rm  859d 3393 c582 -f
  243  docker container rm  859d 3393 c582 -f
  244  docker container ls
  245  docker system prune
  246  docker container ls
  247  docker container logs Jekyll2
  248  docker container logs Jekyll2 -f
  249  docker container port Jekyll2
  250  docker container logs Jekyll2 -f
  251  docker container stop Jekyll2
  252  docker run -d --name Jekyll -p 80:4000 -v //c/users/jnath/projects/udemy-docker-mastery/bindmount-sample-1:/site bretfisher/jekyll-serve
  253  docker container ls
  254  docker container ls
  255  docker image tag Jekyll hackelsmith/Jekyll_serve
  256  docker image tag Jekyll hackelsmith/jekyll-server
  257  docker image tag Jekyll hackelsmith/jekyll
  258  docker image tag Jekyll hackelsmith/jekyllapp:latest
  259  docker image tag bretfisher/jekyll-serve hackelsmith/jekyllapp:latest
  260  docker push hackelsmith/jekyllapp
  261  clear
  262  cd ..
  263  cd compose-sample-1
  264  code .
  265  docker info
  266  docker swarm init
  267  docker swarm ls
  268  docker node ls
  269  docker service create alpine:alpine ping 8.8.8.8
  270  docker service create --detatch alpine:alpine ping 8.8.8.8
  271  docker serv:alpine ping 8.8.8.8
  272  docker service ps l5whvyqmff8huql93gr3c7sp3
  273  docker container ls
  274  docker node ls
  275  docker node --help
  276  docker swarm --help
  277  docker service --help
  278  clear
  279  docker service --help
  280  docker service create nginx:alpine ping 8.8.8.8
  281  docker service ls
  282  docker service ps yv5yle
  283  docker container ls
  284  docker service update yv5yle --replicas 3
  285  docker service ps yv5yle
  286  docker service ls
  287  docker service update --help
  288  docker container ls
  289  docker container rm -f 256a722
  290  docker service ls
  291  docker service ls
  292  docker service ps yv5yle
  293  docker service rm yv5vle
  294  docker service rm yv5yle
  295  docker containerls
  296  docker container ls
  297  docker container ls
  298  git log
  299  history
  300  cd c:/users/jnath
  301  cd Projects/
  302  history > dockercommands_14-feb-2019.text
  303  ls
  304  nano dockercommands_14-feb-2019.text 
  305  cat dockercommands_14-feb-2019.text 
  306  clear
  307  cd c:
  308  cd Users/jnath/Projects/udemy-docker-mastery/
  309  ls
  310  cd swarm-app-1
  311  code .
  312  cd ..
  313  ls
  314  swarm-stack-1
  315  cd swarm-satck-1
  316  cd swarm-stack-1
  317  ls
  318  code .
  319  cd ..
  320  cd Dockerst
  321  ls
  322  cd ..
  323  cd Dockerstack/
  324  code .
  325  cd ..
  326  cd udemy-docker-mastery/
  327  cd swarm-app-2
  328  ls
  329  code .
  330  cd ..
  331  ls
  332  cd swarm-stack-2
  333  ls
  334  code .
  335  code .
  336  docker service ls
  337  docker service ps voting
  338  docker stack ls voting
  339  docker stack ls
  340  docker stack rm voting
  341  cd ..
  342  cd ..
  343  ls
  344  cd Dockerstack/
  345  ls
  346  docker stack deploy -c example-drupal-2.yml drupalapp
  347  echo "example" | docker secret create psql-pw -
  348  docker stack deploy -c example-drupal-2.yml drupalapp
  349  git add .
  350  git commit -m "FIxed compose file"
  351  git push origin master
  352  docker stack ls
  353  docker service ls
  354  docker stack rm drupalapp
  355  clear
  356  cd ..
  357  cd udemy-docker-mastery/secrets-sample-2
  358  code .
  359  cd ..
  360  cd swarm-stack-3
  361  ls
  362  code .
  363  docker-compose up
  364  docker-compose down
  365  docker-compose -f docker-compose.yml -f docker-compose.test.yml up -d
  366  docker-compose -f docker-compose.yml -f docker-compose.test.yml down
  367  docker-compose -f docker-compose.yml -f docker-compose.prod.yml config > output.yml
  368  ls
  369  clear
  370  docker service create -p 8088:80 --name mywebapp nginx:1.13.7
  371  docker service ls mywebapp
  372  docker service ls 
  373  docker service ps mywebapp
  374  docker service inspect mywebapp
  375  docker service update --image nginx:1.2 mywebapp
  376  docker service rm mywebapp
  377  docker service create -p 8088:80 --name mywebapp --detach nginx:1.13.7
  378  docker service ls
  379  docker service scale mywebapp=3
  380  docker service ls
  381  docker service ls
  382  docker service ls
  383  docker service update --image nginx:1.13.6 mywebapp
  384  docker service ls
  385  docker service ls
  386  docker service ls
  387  docker service ls
  388  docker service ls
  389  docker service update --publish-rm 8088 --publish-add 9099 mywebapp
  390  docker service ls
  391  docker service ls
  392  docker service ls
  393  docker service ls
  394  docker service scale mywebapp=5
  395  docker service ls
  396  docker service update --force mywebapp
  397  docker service ls
  398  docker service rm mywebapp
  399  clear
  400  docker run  --health-cmd="curl -f localhost:9200/_cluster/health || false" --health-interval=5s --health-retires=3 --health-timeout=2s --health-start-period=15s elasticsearch:2
  401  docker run  --health-cmd="curl -f localhost:9200/_cluster/health || false" --health-interval=5s --health-retries=3 --health-timeout=2s --health-start-period=15s elasticsearch:2
  402  docker service ps
  403  docker service ps pe
  404  docker service ps pe
  405  docker service ps p2
  406  docker service ps p2
  407  docker service ps p2
  408  docker service ps p2
  409  docker service ps p2
  410  clear
  411  curl -L https://raw.githubusercontent.com/docker/compose/1.23.2/contrib/completion/bash/docker-compose -o /etc/bash_completion.d/docker-compose
  412  curl -L https://raw.githubusercontent.com/docker/compose/1.23.2/contrib/completion/bash/docker-compose -o /etc/bash_completion.d/docker-compose
  413  docker ls
  414  docker ps
  415  docker service create --name pe postgres
  416  docker service create --name p2 --health-cmd="pg_ready -U postgres || exit 1"  postgres
  417  docker service create --name p3 --health-cmd="pg_isready -U postgres || exit 1"  postgres
  418  docker service rm $(docker service ls)
  419  docker service ls
  420  clear
  421  docker container run -d -p 5000:5000 --name registry registry
  422  clear
  423  history
  424  docker container ;s
  425  docker container ls
  426  docker pull hello-world
  427  docker container run hello-world
  428  docker container tag hello-world 127.0.0.1:5000/hello-world
  429  docker image tag hello-world 127.0.0.1:5000/hello-world
  430  docker push 127.0.0.1:5000/hello-world
  431  docker container rm 127.0.0.1:5000/hello-world
  432  docker image rm 127.0.0.1:5000/hello-world
  433  docker pull 127.0.0.1:5000/hello-world
  434  docker container kill registry
  435  docker container rm registry
  436  docker container run -d -p 5000:5000 -v $(pwd):/var/lib/registry --name registry registry
  437  docker container run -d -p 5000:5000 -v $(pclear:/var/lib/registry --name registry registry
  438  cd c:
  439  cd Users/jnath/Projects/
  440  mkdir docker_registry
  441  cd docker_registry/
  442  docker container run -d -p 5000:5000 -v c//users/jnath/projects/docker_registry:/var/lib/registry --name registry registry
  443  docker container run -d -p 5000:5000 -v //c/users/jnath/projects/docker_registry:/var/lib/registry --name registry registry
  444  ll
  445  docker container pull hello-world
  446  docker image pull hello-world
  447  docker image tag hello-world 127.0.0.1:5000/hello-world
  448  docker image ls
  449  docker push 127.0.0.1:5000/hello-world
  450  ls
  451  cd docker/
  452  ls
  453  cd docker
  454  cd registry/
  455  ls
  456  cd ..
  457  cd..
  458  cd ..
  459  clear
  460  cd ..
  461  ls
  462  cd dockercommands_14-feb-2019.text 
  463  history > dockercommands_14-feb-2019.text -a 
  464  cat dockercommands_14-feb-2019.text 
  465  history
  466  history > dockercommands_14-feb-2019.text
