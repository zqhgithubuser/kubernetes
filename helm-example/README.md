Create a new namespace
```
$ kubectl create namespace guestbook
```

Install chart
```
$ helm -n guestbook install guestbook ./guestbook --dependency-update
```
