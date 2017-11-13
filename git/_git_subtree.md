git

# git subtree��ʲô��Ϊʲôʹ��git subtree

git subtree ����ʵ��һ���ֿ���Ϊ�����ֿ���Ӳֿ⡣
![image](http://oxnimkw03.bkt.clouddn.com/BeforeAfterGitSubtreeDiagram.png)

ʹ��git subtree �����¼���ԭ��
* �ɰ汾��gitҲ֧��(���ϰ汾���Ե� v1.5.2).
* git subtree��git submodule��ͬ�����������κ���`.gitmodule`�������µ�Ԫ�����ļ�.
* git subtree������Ŀ�е�������Ա͸������ζ�ſ��Բ�֪��git subtree�Ĵ���.

��Ȼ��git subtreeҲ������ȱ�㣬������Щȱ�㻹�ڿ��Խ��ܵķ�Χ�ڣ�
* ����ѧϰ�µ�ָ��(�磺git subtree).
* �Ӳֿ�ĸ���������ָ����Ը��ӡ�

# git subtree ��ʹ��


git subtree����Ҫ�����У�
```sh
git subtree add   -P <prefix> <commit>
git subtree add   -P <prefix> <repository> <ref>
git subtree pull  -P <prefix> <repository> <ref>
git subtree push  -P <prefix> <repository> <ref>
git subtree merge -P <prefix> <commit>
git subtree split -P <prefix> [OPTIONS] [<commit>]
```

## ׼��

������׼��һ���ֿ��photoshop��һ���ֿ��libpng��Ȼ������ϣ����libpng��Ϊphotoshop���Ӳֿ⡣
photoshop��·��Ϊ`https://github.com/test/photoshop.git`���ֿ�����ļ��У�
```
photoshop
    |
    |-- photoshop.c
    |-- photoshop.h
    |-- main.c
    \-- README.md
```
libPNG��·��Ϊ`https://github.com/test/libpng.git`���ֿ�����ļ��У�
```
libpng
    |
    |-- libpng.c
    |-- libpng.h
    \-- README.md
```

���²�����λ�ڸ��ֿ�ĸ�Ŀ¼�У���д���ĵ�ʱgit subtreeҪ�����е�git subtree�������λ�ڸ��ֿ�ĸ�Ŀ¼����ִ�У���

## �ڸ��ֿ��������Ӳֿ�

```sh
git subtree add --prefix sub/libpng https://github.com/test/libpng.git master --squash
```
(`--squash`������ʾ����ȡ��ʷ��Ϣ����ֻ����һ��commit��Ϣ��)

ִ��`git status`���Կ�����ʾ��������commit:
![image](http://oxnimkw03.bkt.clouddn.com/git_status.png)

`git log`�鿴��ϸ�޸ģ�
![image](http://oxnimkw03.bkt.clouddn.com/git_log.png)

ִ��`git push`���޸����͵�Զ��photoshop�ֿ⣬���ڱ��زֿ���Զ�˲ֿ��Ŀ¼�ṹΪ��
```sh
photoshop
    |
    |-- sub/
    |   |
    |   \--libpng/
    |       |
    |       |-- libpng.c
    |       |-- libpng.h
    |       \-- README.md
    |
    |-- photoshop.c
    |-- photoshop.h
    |-- main.c
    \-- README.md
```

# ����

* [Git subtree: the alternative to Git submodule](https://www.atlassian.com/blog/git/alternatives-to-git-submodule-git-subtree)
* [The power of Git subtree](https://legacy-developer.atlassian.com/blog/2015/05/the-power-of-git-subtree/)
