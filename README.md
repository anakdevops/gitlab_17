```
docker compose version
Docker Compose version v2.29.1-desktop.1
```


```
git clone https://github.com/anakdevops/gitlab_17.git
cd gitlab_17
docker compose up -d
```


```
cat /etc/gitlab/initial_root_password
```


```
Admin Area
Create user -> anakdevops
create group -> IT
create project -> Python_Hello
Assign project Python_Hello ke anakdevops
```

```
generate sshkey 2048
ssh-keygen -t rsa -b 2048 -C "gitlab-local"
add sshkey to gitlab
```

```
clone with ssh
git clone ssh://git@localhost:223/anakdevops/python_hello.git
```
