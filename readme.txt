//��װ��git�����û���������
$ git config --global  user.name  "xx"    //�����û���

$ git config --global  user.email  "xx@163.com"   //��������

//git init��������Ŀ¼���Git���Թ���Ĳֿ⣺
$ git init
Initialized empty Git repository in Ŀ¼

//����ļ����ֿ�ɷ������ʹ�ã���Ӷ���ļ�
git add readme.txt


//�ύ���ֿ�
git commit  -m  "��ע˵��"


�������������ʱ�����ղֿ⵱ǰ��״̬
git status

//�鿴�޸ļ�¼
git diff  

//�鿴�ύ��־
git  log
//��־��ʾһ��
get  log --pretty=oneline

//���˰汾
Git����֪����ǰ�汾���ĸ��汾����Git�У���HEAD��ʾ��ǰ�汾��Ҳ�������µ��ύ3628164...882e1e0��ע���ҵ��ύID����Ŀ϶���һ��������һ���汾����HEAD^������һ���汾����HEAD^^����Ȼ����100���汾д100��^�Ƚ�������������������д��HEAD~100
git reset --hard HARD^

git reset --hard �汾��


//�����ļ��汾
git  checkout  -- �ļ���

//ɾ���ļ�
//git rm �ļ���

//���Զ�̿� originԶ�ֿ̲������  ��Ŀ��ַ
git remote add origin https://github.com/xiaohua919/vuehua.git

//�����������͵�Զ����Ŀ¼
git push -u origin  master


//Զ�̿����ص�������
git clone   ��ַ��

//������֧ git checkout�������-b������ʾ�������л����൱�������������
git checkout -b dev

//�鿴��֧
git brance


//�л���֧���뵽��֧��Ŀ¼
git checkout  master

//�ϲ���֧
git merge  ��֧��

//ɾ����֧
git branch -d ��֧��


ͨ�����ϲ���֧ʱ��������ܣ�Git����Fast forwardģʽ��������ģʽ�£�ɾ����֧�󣬻ᶪ����֧��Ϣ��

���Ҫǿ�ƽ���Fast forwardģʽ��Git�ͻ���mergeʱ����һ���µ�commit���������ӷ�֧��ʷ�ϾͿ��Կ�����֧��Ϣ��

��������ʵսһ��--no-ff��ʽ��git merge��

git merge --no-ff -m "merge with no-ff" dev

//�鿴��֧�ϲ���־
git log --graph --pretty=oneline --abbrev-commit

Git���ṩ��һ��stash���ܣ����԰ѵ�ǰ�����ֳ������ء����������Ժ�ָ��ֳ����������
git stash


