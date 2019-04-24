# python_build_tools

本小工具使用cython用于编译python模块，生产pyd(Windows)或so(Linux)

## 使用说明
### 简化编译命令
	python complie_tool.py [module_path]
	#eg.
	python complie_tool.py ./demo_project/demo

### 输出
默认输出到当前目录的```build/```下

### 测试
	PYTHONPATH=./build python test.py