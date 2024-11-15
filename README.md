# dcpractical
create folder (Demo)
openn demo folder in termianl
create two files in this folder
1.index.html and 2, Dockerfile
-> touch index.html
-> touch Dockerfile

step 3) open idex.html file and write code of html
step 4) open Dockerfile and open with any textiditor
and write
-> FROM enginx
   COPY  index.html\usr\share\enginx\html

step 5) open terminal and type command
->  sudo Docker build -t Demo (folder name of our)
->  sudo Docker run -d -p 8080:80 Demo
step 6) open browser and type 0.0.0.0:8080 and enter
