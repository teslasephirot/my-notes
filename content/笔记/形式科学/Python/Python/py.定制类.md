##### 定制类
- 定制类
	- 一个类可以通过定义具有特殊名称的方法来实现由特殊语法来发起调用的特定操作 (例如算术运算或抽取与切片), 这是 Python 实现[[py.符号|运算符]]重载的方式, 允许每个类自行定义基于该语言运算符的特定行为. 举例来说, 如果一个类定义了名为 `__getitem__()` 的方法, 并且 `x` 是该类的一个实例, 则 `x[i]` 基本就等价于 `type(x).__getitem__(x, i)`
 - 定制类实现
	- 基本定制重写覆盖[[py.object 类方法|object 类方法]]
	- [[py.自定义属性访问|自定义属性访问]]
	- [[py.模拟可调用对象|模拟可调用对象]]
	- [[py.模拟容器类型|模拟容器类型]]
	- [[py.模拟数字类型|模拟数字类型]]
	- [[py.上下文管理器对象|模拟上下文管理器]]
	

