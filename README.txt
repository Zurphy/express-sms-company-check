# ����

* ���״̬��ѯ����֧��˳�ᡢԲͨ����ͨ�ȿ�ݹ�˾
* �ֻ������·���������ע�ᡢ�һ�����ȸ�����Ҫ�ֻ���֤��ĳ���,����Ч�ڴ����ֹ������ˢ�ӿ�
* ��ҵ��������鵱ǰ��ҵ�����Ƿ�ռ��

# ע��

�����е�����������վע�� APPKEY,���޸� `Home/Conf/config.php` �Ĳ���,��ʽ����

* http://www.juhe.cn (��ݡ�����)
* http://www.yjapi.com/ ����ҵ��Ϣ��

���ݿ�ṹ�Ѿ����� sql �ļ����� `/Public/` Ŀ¼�£��ڷ������ϵ��뼴��

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

# ��ע

��ע���޸� APPKEY
��ע���޸����ݿ����ӵĲ���
