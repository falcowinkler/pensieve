## What is pensieve

I noticed that i actually learn a lot during daily work that i need one year later, but of course all i can say then is,
"oh yeah i did that once back then but i have no idea how".

So, this tool should help to avoid that.

## Setup

Set the two required environment variables in your `~/.bash_profile`: 

```bash
export PENSIEVE_HOME=/Users/myuser/Desktop/my-pensieve-folder
export PENSIEVE_GIT=https://github.com/my-user/pensieve
```

Put the `pensieve` script somewhere in your `PATH`, e.g. in `/usr/local/bin`.

## How to Use

Quickly remember a useful kubernetes command (or anything else you want to remember):

```bash
pensieve shortfact tech/kubernetes "get all pods ;;kubectl get pods --all-namespaces""
```

This will add a seperate line in the file tech/kubernetes/shortfacts.md that contains your fact. Please use `;;` to escape the backtick that is used in github to escape code.

```bash
pensieve edit tech/kubernetes/cheatsheet.md
```

Will create a file if it not exists and fire up a web-editor. Requires `python` to be installed.


I will add more functionality if i see fit
