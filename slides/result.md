## 結果
* イベントループは V8 ではなく libuv が提供
* キューを何個も持つ、かなり複雑な構造
* 今回調べたのは Linux 用、Mac/Windows はまた違う
* それでも、単純なイベントループに見えるのはすごい!