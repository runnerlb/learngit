git config --global user.name ''
git config --global user.email ''
mkdir learngit ����һ��Ŀ¼
pwd  ��ʾ��ǰĿ¼
git init 
git add filename
git commit -m '��ע'
git status
git diff
git log
git log --pretty=oneline
git reset --hard HEAD^ �ص���һ���汾
cat readme.txt ��ʾ���ļ�������
git reset --hard guid �ع���ָ���İ汾
git reflog �鿴�����汾
git diff HEAD -- readme.txt ���Բ鿴�������Ͱ汾���������°汾������
git checkout -- readme.txt  ��readme.txt�ļ��ڹ��������޸�ȫ�����������������������
git rm file path ɾ���ļ�
ssh-keygen -t rsa -C 'lbrunner@163.com' ����SSH
git remote add origin git@github.com:runnerlb/learngit.git ��Զ�̽�������
git push origin master �������ύ��master
git clone git@github.com:runnerlb/gitskills.git  �����븴�Ƶ�����
git branch �鿴��֧
git branch  name������֧
git checkout name �л���֧
git checkout -b name �������л���֧
git merge name �ϲ�ĳ��֧����ǰ��֧
git branch -d name ɾ����֧
git log --graph������Կ�����֧�ϲ�ͼ��
git log --graph --pretty=oneline --abbrev-commit
git merge --no-ff -m "merge with no-ff" dev
git stash ���԰ѵ�ǰ�����ֳ������ء����������Ժ�ָ��ֳ������������
git stash list  �ղŵĹ����ֳ��浽��ȥ��
һ����git stash apply�ָ������ǻָ���stash���ݲ���ɾ��������Ҫ��git stash drop��ɾ����
��һ�ַ�ʽ����git stash pop���ָ���ͬʱ��stash����Ҳɾ�ˣ�
����Զ��stash���ָ���ʱ������git stash list�鿴��Ȼ��ָ�ָ����stash�������
$ git stash apply stash@{0}



http://www.07net01.com/2015/09/922578.html
http://markdownpad.com/download/awesomium_v1.6.6_sdk_win.exe




