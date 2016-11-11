### poll
* Node.js の最もらしい部分
* I/O ポーリング

```text
+-----------------+
|     timers      |<-+
+-----------------+  |
        |            |
+-----------------+  |
|  I/O callbacks  |  |
+-----------------+  |
        |            |
+-----------------+  |
|      poll       |  |
+-----------------+  |
        |            |
+-----------------+  |
|     check       |  |
+-----------------+  |
        |            |
+-----------------+  |
| close callbacks |--+
+-----------------+
```
<!-- .element: style="width: 300px;" class="left" -->