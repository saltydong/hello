# 安装Go编程实验报告
1、前期配置：
  在上次配置好虚拟机以后，开始对其相应的软件进行配置
  按照课件的提示，完成了VS和golang在centos上的安装
  
2、工作空间的创建
  按照指示建立home的工作空间和环境变量GOPATH
  
  然后创建hello的文件，放在自己的git上
  然后在本go run
  
  得到helloworld的结果
  
  3、编写库来使用
  
  先选择路径
  mkdir $GOPATH/src/github.com/saltydong/stringutil
  按照代码进行编译
  
  成功以后得到消息 hello，go
  
  最后得到stringutil/reverse.go的包源码
  
  4、测试
  
  创建一个名字以 _test.go 结尾的，包含名为 TestXXX 且签名为 func (t *testing.T) 函数的文件来编写测试。 测试框架会运行每一个这样的函数；若该函数调用了像 t.Error 或 t.Fail 这样表示失败的函数，此测试即表示失败。

  用go test 进行测试
  
  会得到ok 以及时间
