## 第一步：设置 .env
把项目中的 .env 里面的参数配置为自己的

## 第二步设置：

控制某些软件包在编译和运行时是否使用本地（原生）库

执行下面命令：
```
export HNSWLIB_NO_NATIVE=1
```

## 第三步：安装包

执行下面命令：
```
pip install -r requirements.txt
```

## 第四步：运行

#### 运行 rag_demo.py 文件



## 第五步：问问题
```
User: Llama2有多少参数
AI: Llama 2有7B、13B和70B参数的变体。
User: 最少多少
AI: Llama 2的变体中，参数最少的是7B。
User: ChatALL在哪下载
AI: 您可以从 https://github.com/sunner/ChatALL/releases 下载 ChatALL。
User:
```