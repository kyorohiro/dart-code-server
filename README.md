# 

run a docker image.
 
```
git clone https://github.com/kyorohiro/dart-code-server.git
cd dart-code-server
docker build -t dart_vscode .
docker run -p 8443:8443 -p 8080:8080 -it dart_vscode bash
```


run vscode at code-server

```
mkdir /works/w
/works/code-server /works/w --allow-http --no-auth
```

and you open 'http://127.0.0.1:8443/' at your browser 

![](root_page.jpg)




