## bazel 使用入门

该项目主要展示一些 bazel 和 go 结合的入门玩法

#### 示例一：输出程序的当前git commit id

>  bazel run --workspace_status_command=${PWD}/status.sh  cmd/simple

