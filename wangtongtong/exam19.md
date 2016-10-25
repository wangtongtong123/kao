##19. 你要是在一个 jQuery 事件处理程序里返回了 false 会怎样？
  为了防止冒泡，比如给出ID为d1的DIV加了click事件，这个事件默认也会
加载到d1的父DIV和document，加return false是为了让事件只加给d1，防
止冒泡，产生不必要的麻烦。
