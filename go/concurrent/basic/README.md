# 目录说明
- `asyncCallback.go`：回调函数实现异步
- `asyncCallhell.go`：回调地狱
- `chan1mutil.go`：多个协程，使用`chan`传输数据
- `chan1single.go`：单个协程，使用`chan`传输数据，使用`select`进行通道读及并发控制
- `chan2.go`：同步调用，使用`chan`传输数据
- `chan3.go`：同步调用，使用`chan`传输数据
- `multi1.go`：多个协程，使用`time.Sleep`进行并发控制
- `multi2.go`：多个协程，使用`sync.WaitGroup`进行并发控制
- `single1.go`：单个协程
- `single2.go`：单个协程，使用`time.Sleep`进行并发控制
- `syncMutex.go`：同步，使用锁机制
