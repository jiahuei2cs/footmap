this is my first file������111
������hehe
22
git init ��Ŀ¼��ʼ����Ϊgit�����Ŀ¼�����ɹ�git�ֿ�
git add xxx.xx (���磺git add liudong.txt) ���ļ���ӵ�git����
git add . ����ǰĿ¼�����ļ����ӵ�git����
git commit -m "�ҽ����ύ�˵�һ��git�ļ�" ����ע��
git status �鿴��ǰgit���еı仯״̬���ܿ��������ܹ�����ļ��仯�б�
git diff liudong.txt �ܿ��������޸���ʲô����
xiexie

git init ��Ŀ¼��ʼ����Ϊgit�����Ŀ¼�����ɹ�git�ֿ�
git add xxx.xx (���磺git add liudong.txt) ���ļ���ӵ�git����
git add . ����ǰĿ¼�����ļ����ӵ�git����
git commit -m "�ҽ����ύ�˵�һ��git�ļ�" ����ע��
git status �鿴��ǰgit���еı仯״̬���ܿ��������ܹ�����ļ��仯�б�
git diff liudong.txt �ܿ��������޸���ʲô����
git log �鿴��־
git log --pretty=oneline ����ʾ��־
git reset --hard HEAD^ �������ϸ��汾
git reset --hard HEAD~100 ������ǰ100���汾
git reset --hard oiqwerqwkejroq123123412 ������ָ����commit ID�汾
git reflog ������־
git checkout -- liudong.txt �ڹ��������޸ĳ���
git reset HEAD liudong.txt ���԰��ݴ������޸ĳ���������������HEADʱ����ʾ���µİ汾��
git add -f App.class	ǿ������һ���ļ���git����

ssh-keygen -t rsa -C "jiahuihb@126.com"	����Key������github
git push -u origin master	����һ�Σ��ѱ��ؿ���������͵�Զ��
git push origin master	�ѱ���master��֧�������޸�������GitHub
git clone https://github.com/jiahuei2cs/test.git	��¡github�������Ŀ������
git checkout -b dev	�����µķ�֧������ָ��ָ���µķ�֧
git checkout master	��ָ��ָ������֧master
git branch	�鿴git�ķ�֧��������鿴ָ��ָ���ĸ���֧
git	merge dev	��ָ����֧�ϲ������ڵķ�֧��(���ٺϲ�)
git branch -d dev	ɾ��ָ����֧
git merge --no-ff -m "���ںϲ���֧" dev ��ͨģʽ�ϲ�,���Կ�����ϸ�ϲ�����
git push origin dev	�ӱ������ͷ�֧��github
git checkout -b dev origin/dev	�ڱ��ش�����Զ�̷�֧��Ӧ�ķ�֧
git branch --set-upstream dev origin/dev	�������ط�֧��Զ�̷�֧�Ĺ���
git pull	��Զ��ץȡ��֧

git tag v1.0	����ǰ��֧���ǩ
git tag v0.9 6224937	����ǰ��֧���ǩ���ǽ���ʷ�ύ��commitid ��Ϊ���ǩ��ָ��
git tag -d v0.9	ɾ��ָ����ǩ
git push origin v1.0	�ύĳ����ǩ��Զ�̿�
git push origin --tags	�����صı�ǩ��ȫ�����͵�Զ�̿�
git push origin :refs/tags/v1.0	ɾ��Զ�̵ı�ǩ(����Ҫɾ�����ص������ǩ)

git config --global alias.co checkout	�����������	(--global ��ȫ�ֲ���)
git config --global alias.ci commit	�����������
git config --global alias.br branch	�����������