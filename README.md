I noticed that i actually learn a lot during daily work that i need one year later, but of course all i can say then is,
"oh yeah i did that once back then but i have no idea how".

So, this tool should help to avoid that.

### How to use the pensieve

Quickly remember a fact about kubernetes:

```bash
pensieve shortfact tech/kubernetes "Fire up a shell in a cluster with ;;kubectl run tmp-shell --rm -i --tty --image centos -- /bin/bash;;""
```

This will add a seperate line in the file tech/kubernetes/shortfacts.md that contains your fact. Please use `;;` to escape the backtick that is used in github to escape code.

```bash
pensieve edit tech/kubernetes/cheatsheet.md
```

Will create a file if it not exists and fire up a web-editor. Requires `python` to be installed.


I will add more functionality if i see fit
