#3���� �����͵� ����: "�ڱ�Ұ�" ��� �����

1. �ؾ��� ��
	-���� �������丮 Fork #����� ������
	-Fork�� �������丮�� ���÷� �޾ƿ���
	-���ÿ��� branch ����
	-�ش� branch���� ���� ����
	-���� ���� README.md ���� �� �ڱ�Ұ� ���� ����
	-remote �������丮�� ������ branch push
	-���� �������丮�� Pull Request #����� ������

2. Git CMD
	-Fork�� �������丮�� ���÷� �޾ƿ���
		#��ɾ� ����: git clone [<options>] [--] <repo> [<dir>]
		ex) 'git clone https://github.com/shimminseo/webstudy-homework-minseo-2798.git'

	-branch ����
		#���� ���ϴ� �������丮�� �̵�
		ex) 'cd C:\Users\rebec\webstudy-homework-minseo-2798'

		#��ɾ� ����: git branch [������ branch �̸�]
		ex) 'git branch minseo#2798'

		#branch Ȯ�� ��ɾ�: 'git branch -r' or 'git branch'

	-�ش� branch���� ���� ����
		#branch �̵� ��ɾ�: 'git checkout [branch �̸�]'
		
		#��ɾ� ����: mkdir [������]
		ex) 'mkdir minseo#2798'

	-���� ���� README.md ���� �� �ڱ�Ұ� ���� ����
		#VS�� README.md �ۼ�

	-remote �������丮�� ������ branch push
		#remote�� ���� �̸��� branch�� ������ �� ��ɾ�: 'git push'

		#�ƴ� ���, ��ɾ� ����: git push --set-upstream origin [�귣ġ��]
		ex) git push --set-upstream origin minseo#2798


3. Commit Message ����
	-type(Ÿ��) : title(����)

	-body(����, ���� ����)

	-Resolves : #issueNo, ...(�ذ��� �̽� , ���� ����)

	-See also : #issueNo, ...(���� �̽�, ���� ����)
 
	#���� https://jane-aeiou.tistory.com/93