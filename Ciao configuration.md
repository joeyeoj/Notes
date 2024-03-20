#### 教程出处
[https://cxc.cfa.harvard.edu/ciao/download/index.html](https://cxc.cfa.harvard.edu/ciao/download/index.html)
（注意python版本，比如目前我所使用的是python 3.9）
#### 具体操作
```
$ env CONDA_SUBDIR=osx-64 conda create -n ciao-4.15 \
  -c https://cxc.cfa.harvard.edu/conda/ciao -c conda-forge \
  ciao sherpa ds9 ciao-contrib caldb_main marx python=3.10

$ conda activate ciao-4.15
$ conda config --env --set subdir osx-64

$ conda create -n ciao-4.15 \
  -c https://cxc.cfa.harvard.edu/conda/ciao \
  -c conda-forge \
  ciao sherpa ds9 ciao-contrib caldb_main marx python=3.10

$ softwareupdate --install-rosetta
$ conda deactivate #退出环境
```
安装一个新的终端iTerm，打开后进行复制，对复制后的终端进行改名（如iTerm_Rosetta），放入应用程序中。以后每次均使用该终端。
```
$ conda activate ciao-4.15 #打开Ciao环境
```
#### 卸载
```
conda remove --name ciao-4.15 --all 师兄提供的方法（未尝试）
# 另一种方法
echo $ASCDS_INSTALL #查看Ciao安装位置
rm -rf /path/to/ciao #换成具体安装位置
```
![alt text](1.png)