<div align="center">

<pre>
        ·        ˚          ✦              ·
   ˚                  .             ˚
              a  r  i  h  a  n  t
     .                      ·            ✦
          ✦        ˚                 .
</pre>

<sub><i>below every abstraction there is a machine. i go down there.</i></sub>

</div>

<br>

```c
#include <stddef.h>

static const struct self {
    const char *name;
    const char *base;
    const char *tongue[4];
    const char *realm;
} arihant = {
    .name   = "arihant jain",
    .base   = "paris, fr",
    .tongue = { "go", "c", "c++", NULL },
    .realm  = "syscalls, sockets, consensus, the space between two packets",
};
```

<br>

### ◈ artifacts

- [`command-shell`](https://github.com/arihant-dev/command-shell): a unix shell from nothing. `fork`, `execve`, pipes, redirection, job control.
- [`distributed-kvstore`](https://github.com/arihant-dev/distributed-kvstore): a replicated key-value store on a hand-rolled raft. write-ahead log, elections, chaos.
- [`p2p-version-control`](https://github.com/arihant-dev/Action-learning-p2p-version-control): version control with no center. a c++ watcher, vector clocks, peers only.
- [`tvplay`](https://github.com/arihant-dev/tvplay): video, decoded and drawn as ansi escape codes, straight into your tty.

<br>

### ◈ currently

```
$ ps -o cmd= -u arihant
raft        --lab 6.824
heapify     --lab 6.006
nvim        ~/dotfiles
```

<br>

<div align="center">

<sub>

[site](https://arihant-jain.me) · [linkedin](https://linkedin.com/in/ariihantijain) · [mail](mailto:jainarj411@gmail.com)

</sub>

<br>

<sub><code>0x00 · nothing is magic, only undocumented</code></sub>

</div>
