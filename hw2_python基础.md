# hw2_python基础

- 姓名：黄浩扬
- 学号：2201212800
- 导师：王荣刚

# 1、安装Anaconda

## （1）下载Anaconda并安装

前往Anaconda官网[https://www.anaconda.com/](https://www.anaconda.com/)点击download，下载完安装包后点击安装

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled.png)

## （2）验证是否安装成功

在终端输入conda，提示如下界面即为安装成功

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%201.png)

输入conda -V可查看conda的版本

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%202.png)

# 2、安装虚拟环境并删除

## （1）更新Anaconda至最新版本

在终端输入以下命令，更新Anaconda至最新版本

```markdown
conda update -n base -c defaults conda
```

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%203.png)

出现以上界面即为更新成功

## （2）创建虚拟环境

在终端输入以下命令创建一个虚拟环境

```markdown
conda create -n <your_env_name> python=x.x
```

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%204.png)

出现以上界面即创建成功

## （3）查看已创建的虚拟环境

在终端输入

```markdown
conda info --env
```

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%205.png)

可以看见虚拟环境成功创建

## （4）删除创建的虚拟环境

在终端输入以下命令

```markdown
conda remove -n <your_env_name> --all
```

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%206.png)

删除后查看虚拟环境列表，可见虚拟环境已被删除

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%207.png)

# 3、运行给定四个.ipynb文件

## （1）Python-00.ipynb

由于单个文件所有运行结果太多，只截取了部分结果，之后的几个文件同理

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%208.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%209.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2010.png)

## （2）Python-01.ipynb

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2011.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2012.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2013.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2014.png)

## （3）Python-02.ipynb

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2015.png)

生成的二维码如下：

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2016.png)

带有背景的二维码如下：

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2017.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2018.png)

## （4）Python-03.ipynb

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2019.png)

![Untitled](hw2_python%E5%9F%BA%E7%A1%80%20d5bddc1113d044d3902cb9be6d952f7b/Untitled%2020.png)