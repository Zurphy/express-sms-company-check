# ����

* ���״̬��ѯ����֧��˳�ᡢԲͨ����ͨ�ȿ�ݹ�˾
* �ֻ������·���������ע�ᡢ�һ�����ȸ�����Ҫ�ֻ���֤��ĳ���,��Ч���ڴ����ֹ����ը��
* ��ҵ��������鵱ǰ��ҵ�����Ƿ�ռ��

# ǰ��˴��룬�Լ�����ʵ�ַ�ʽ��ϸ˵���ĵ�

[ʹ�þۺ�����APIʵ�֡���ݲ�ѯ-������֤-��ҵ������](http://www.itjiaoshou.com/express-sms-company-check-use-api)

# APPKEY ����

�����е�����������վע�� APPKEY,�Ժ���Ҫ�����Ǹ��Ƶ� `Home/Conf/config.php` ��

* http://www.juhe.cn (��ݡ����� ������)
* http://www.yjapi.com/ ����ҵ��Ϣ ��һ����

# ���ŷ��ͼ�¼���ݿ⣨��Ҫ���ڼ�¼������֤���·���¼��������Ч�ڣ��Լ��˶��û��������֤�룩

�Ѿ����� sql �ļ����� `/Public/` Ŀ¼�£��ڷ������ϵ��뼴��


# �����ļ�����������Ϣ���У���������Ѿ�ɾ������ļ�����������ӣ�

`Home/Conf/config.php` ��������

```php
<?php
return array(
	// ��ݲ�ѯ
	'EXPRESS_APP_KEY' => '��Ŀ�� APPKEY',
	'EXPRESS_QUERY_URL' => 'http://v.juhe.cn/exp/index', //��ݵ��Ų�ѯ
	'EXPRESS_COM_URL' => 'http://v.juhe.cn/exp/com', //��ݹ�˾��ѯ

	// ������
	'SEND_SMS_KEY' => '��Ķ��Žӿ� APPKEY',
	'SEND_SMS_URL' => 'http://v.juhe.cn/sms/send',

	// ����
	'COMPANY_KEY' => '���� APPKEY',
	'COMPANY_URL' => 'http://eci.yjapi.com/ECIFast/Search',

	//���ݿ�������Ϣ
	'DB_TYPE'   => 'mysql', // ���ݿ�����
	'DB_HOST'   => 'localhost', // ��������ַ
	'DB_NAME'   => '������ݿ���', // ���ݿ���
	'DB_USER'   => '������ݿ��û���', // �û���
	'DB_PWD'    => '����', // ����
	'DB_PORT'   => 3306, // �˿�
	'DB_PREFIX' => 'pre_', // ���ݿ��ǰ׺ 
	'DB_CHARSET'=> 'utf8', // �ַ���
);
```
