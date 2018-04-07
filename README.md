# 虚拟开发环境配置（for Ubuntu & Mac）by知鱼

---

## 虚拟环境
虚拟环境 virtual environment

使用虚拟环境安装开发环境，可以避免包的混乱和版本的冲突。
虚拟环境是Python解释器的副本，在虚拟环境中你可以安装扩展包，为每个程序单独创建的虚拟环境，可以保证程序只能访问虚拟环境中的包。
不会影响系统中安装的全局Python解释器，从而保证全局解释器的整洁。

---

## 复习

### 1.pip
####安装Python的包
```
pip install 包名称
pip3 install 包名称
```
####查看当前环境下安装的Python包
`pip list` 或者 `pip freeze`
### 2.查看当前使用Python解释器的路径
#### Pycharm中
在运行结果上方可以看到
* 当前使用的Python解释器
* 当前运行的Python程序的位置
![](/assets/屏幕快照 2018-04-07 下午9.29.13.png)

#### 终端/命令行/控制台中
在Python环境中执行如下命令查看
```
import sys
sys.executable
```

###3.重定向

* `>`将输出结果写在目标文件中，新建或覆盖目标文件
* `>>`将输出结果追加在目标文件末尾




