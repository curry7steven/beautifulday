<!-- GFM-TOC -->
* [ѧϰ����](#ѧϰ����)
* [����ʽ��ֲ�ʽ](#����ʽ��ֲ�ʽ)
* [Git �����ķ�����](#git-�����ķ�����)
* [Git ������](#git-������)
* [��֧ʵ��](#��֧ʵ��)
* [��ͻ](#��ͻ)
* [Fast forward](#fast-forward)
* [��֧�������](#��֧�������)
* [���أ�Stashing��](#����stashing)
* [SSH ��������](#ssh-��������)
* [.gitignore �ļ�](#gitignore-�ļ�)
* [Git ����һ��](#git-����һ��)
<!-- GFM-TOC -->



# ѧϰ����

- [Git - ����ָ��](http://rogerdudler.github.io/git-guide/index.zh.html)
- [ͼ�� Git](http://marklodato.github.io/visual-git-guide/index-zh-cn.html)
- [��ѩ�� : Git �̳�](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
- [Learn Git Branching](https://learngitbranching.js.org/)

# ����ʽ��ֲ�ʽ

Git ���ڷֲ�ʽ�汾����ϵͳ���� SVN ���ڼ���ʽ��

����ʽ�汾����ֻ�����ķ�����ӵ��һ�ݴ��룬���ֲ�ʽ�汾����ÿ���˵ĵ����Ͼ���һ�������Ĵ��롣

����ʽ�汾�����а�ȫ�����⣬�����ķ��������������˶�û�취�����ˡ�

����ʽ�汾������Ҫ�������ܹ�����������ٹ�������ô�ύһ���ļ��Ļ������޷��������ܡ����ֲ�ʽ�汾���Ʋ���Ҫ�������ܹ�����

�ֲ�ʽ�汾�����½���֧���ϲ���֧�����ٶȷǳ��죬������ʽ�汾�����½�һ����֧�൱�ڸ���һ���������롣

# Git �����ķ�����

Git �����ķ�������������ÿ���û����޸ġ�û�����ķ�����Ҳ�ܹ������������ķ������ܹ� 24 Сʱ���ֿ���״̬���������ܸ�����Ľ����޸ġ�Github ����һ�� Git ���ķ�������

# Git ������

<div align="center"> <img src="../pics//a1198642-9159-4d88-8aec-c3b04e7a2563.jpg"/> </div><br>

�½�һ���ֿ�֮�󣬵�ǰĿ¼�ͳ�Ϊ�˹�����������������һ������Ŀ¼ .git�������� Git �İ汾�⡣

Git �汾����һ����Ϊ stage ���ݴ����������Զ������� master ��֧�Լ�ָ���֧�� HEAD ָ�롣

<div align="center"> <img src="../pics//46f66e88-e65a-4ad0-a060-3c63fe22947c.png"/> </div><br>

- git add files ���ļ����޸���ӵ��ݴ���
- git commit ���ݴ������޸��ύ����ǰ��֧���ύ֮���ݴ����ͱ������
- git reset -- files ʹ�õ�ǰ��֧�ϵ��޸ĸ����ݻ����������������һ�� git add files
- git checkout -- files ʹ���ݴ������޸ĸ��ǹ���Ŀ¼���������������޸�

<div align="center"> <img src="../pics//17976404-95f5-480e-9cb4-250e6aa1d55f.png"/> </div><br>

���������ݴ�����ֱ�Ӵӷ�֧��ȡ���޸Ļ���ֱ���ύ�޸ĵ���֧��

- git commit -a ֱ�Ӱ������ļ����޸���ӵ��ݻ���Ȼ��ִ���ύ
- git checkout HEAD -- files ȡ�����һ���޸ģ������������лع�����

# ��֧ʵ��

Git ��ÿ���ύ������һ��ʱ���ߡ���֧ʹ��ָ����ʵ�֣����� master ��ָ֧��ָ��ʱ���ߵ����һ���ڵ㣬Ҳ�������һ���ύ��HEAD ָ��ָ����ǵ�ǰ��֧��

<div align="center"> <img src="../pics//fb546e12-e1fb-4b72-a1fb-8a7f5000dce6.jpg"/> </div><br>

�½���֧���½�һ��ָ��ָ��ʱ���ߵ����һ���ڵ㣬���� HEAD ָ��ָ���·�֧��ʾ�·�֧��Ϊ��ǰ��֧��

<div align="center"> <img src="../pics//bc775758-89ab-4805-9f9c-78b8739cf780.jpg"/> </div><br>

ÿ���ύֻ���õ�ǰ��֧��ǰ�ƶ�����������֧�����ƶ���

<div align="center"> <img src="../pics//5292faa6-0141-4638-bf0f-bb95b081dcba.jpg"/> </div><br>

�ϲ���֧Ҳֻ��Ҫ�ı�ָ�뼴�ɡ�

<div align="center"> <img src="../pics//1164a71f-413d-494a-9cc8-679fb6a2613d.jpg"/> </div><br>

# ��ͻ

��������֧����ͬһ���ļ���ͬһ�н������޸ģ��ڷ�֧�ϲ�ʱ�ͻ������ͻ��

<div align="center"> <img src="../pics//58e57a21-6b6b-40b6-af85-956dd4e0f55a.jpg"/> </div><br>

Git ��ʹ�� <<<<<<< ��======= ��>>>>>>> ��ǳ���ͬ��֧�����ݣ�ֻ��Ҫ�Ѳ�ͬ��֧�г�ͻ�����޸ĳ�һ�����ܽ����ͻ��

```
<<<<<<< HEAD
Creating a new branch is quick & simple.
=======
Creating a new branch is quick AND simple.
>>>>>>> feature1
```

# Fast forward

"���ʽ�ϲ�"��fast-farward merge������ֱ�ӽ� master ��ָ֧��ϲ��ķ�֧������ģʽ�½��з�֧�ϲ��ᶪʧ��֧��Ϣ��Ҳ�Ͳ����ڷ�֧��ʷ�Ͽ�����֧��Ϣ��

�����ںϲ�ʱ���� --no-ff ���������� Fast forward ģʽ�����Ҽ��� -m �����úϲ�ʱ����һ���µ� commit��

```
$ git merge --no-ff -m "merge with no-ff" dev
```

<div align="center"> <img src="../pics//dd78a1fe-1ff3-4bcf-a56f-8c003995beb6.jpg"/> </div><br>

# ��֧�������

master ��֧Ӧ���Ƿǳ��ȶ��ģ�ֻ���������°汾��

�ճ������ڿ�����֧ dev �Ͻ��С�

<div align="center"> <img src="../pics//245fd2fb-209c-4ad5-bc5e-eb5664966a0e.jpg"/> </div><br>

# ���أ�Stashing��

��һ����֧�ϲ���֮�������û�н��޸��ύ����֧�ϣ���ʱ�����л���֧����ô��һ����֧��Ҳ�ܿ����µ��޸ġ�������Ϊ���з�֧������һ����������Ե�ʡ�

����ʹ�� git stash ����ǰ��֧���޸Ĵ�����������ʱ��ǰ�������������޸Ķ��ᱻ�浽ջ�ϣ�Ҳ����˵��ǰ�������Ǹɾ��ģ�û���κ�δ�ύ���޸ġ���ʱ�Ϳ��԰�ȫ���л���������֧���ˡ�

```
$ git stash
Saved working directory and index state \ "WIP on master: 049d078 added the index file"
HEAD is now at 049d078 added the index file (To restore them type "git stash apply")
```

�ù��ܿ������� bug ��֧��ʵ�֡������ǰ���� dev ��֧�Ͻ��п��������Ǵ�ʱ master ���и� bug ��Ҫ�޸������� dev ��֧�ϵĿ�����δ��ɣ����������ύ�����½� bug ��֧���л��� bug ��֧֮ǰ����Ҫʹ�� git stash �� dev ��֧��δ�ύ�޸Ĵ���������

# SSH ��������

Git �ֿ�� Github ���Ĳֿ�֮����ͨ�� SSH ���ܡ�

�����������û�� .ssh Ŀ¼�����߸�Ŀ¼��û�� id_rsa �� id_rsa.pub �������ļ�������ͨ���������������� SSH Key��

```
$ ssh-keygen -t rsa -C "youremail@example.com"
```

Ȼ��ѹ�Կ id_rsa.pub �����ݸ��Ƶ� Github "Account settings" �� SSH Keys �С�

# .gitignore �ļ�

���������ļ���

1. ����ϵͳ�Զ����ɵ��ļ�����������ͼ��
2. �������ɵ��м��ļ������� Java ��������� .class �ļ���
3. �Լ���������Ϣ�������ſ���������ļ���

����Ҫȫ���Լ���д�����Ե� [https://github.com/github/gitignore](https://github.com/github/gitignore) �н��в�ѯ��

# Git ����һ��

<div align="center"> <img src="../pics//7a29acce-f243-4914-9f00-f2988c528412.jpg"/> </div><br>

�Ƚ���ϸ�ĵ�ַ��http://www.cheat-sheets.org/saved-copy/git-cheat-sheet.pdf


