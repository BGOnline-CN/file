		`						Api�ĵ�
		//��¼
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=login";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
        $post_data = array (
          "auth" => $auth,
          "name" => "admin",
          "pwd" => "123456",
		  "authTime"=>time()
        );
		*/
		//���admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
          "uname" => "admin",
          "pwd" => "123456",
		  "authTime"=>time()
        );
		*/
		//�鿴admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=getUser";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "uid"=>'18', //����
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//�޸�admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "uid"=>18,
		  "fid"=>'1', //����
		  "mobile"=>'321',  //����
		  "pwd"=>'123456',  //����
		  "uname"=>'aaa',   //����
		  "image"=>'image', //����	  
        );
		*/
		//ɾ��admin
		/*
		$url = "http://127.0.0.1/api/api.php?c=admin&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "uid"=>18,
        );
		*/
		
		//�鿴�û��˺�
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=getUser";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "uid"=>'',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//�޸��û���Ϣ
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "uid"=>9,
		  "fmobile"=>'123', //����
		  "mobile"=>'321',  //����
		  "pwd"=>'123456',  //����
		  "uname"=>'aaa',   //����
		  "image"=>'image', //����
		  "isSaler"=>'1'   //0 ��ͨ  1  ����
		  
        );
		*/
		//ɾ���û���Ϣ
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "uid"=>10,
        );
		*/
		//���user
		/*
		$url = "http://127.0.0.1/api/api.php?c=user&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "mobile"=>'18222323233',
          "pwd" => "123456",
		  "uname"=>'uname',
		  "fmobile" => "fmobile",//����
		  "ip" => "ip",//����
		  "createTime" => "123123",//����
		  "image" => "image",//����
		  "isSaler" => "1" //0 ��ͨ  1 ����
        );
		*/
		
		//�鿴���ÿ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=getCredit";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "id"=>'5',
		  "page"=>1,
		  "authTime"=>time()
        );
		*/
		//�޸��û���Ϣ
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=update";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>5,
		  "title"=>'���ÿ�2',
		  "image"=>'image2',
          "sketch" => "sketch2", //��Ҫ����
		  "bank"=>'bank2',
		  "limit" => "10",//���
		  "describe" => "describe2",//����
		  "url" => "url2"//����
		  
        );
		*/
		//ɾ���û���Ϣ
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=delete";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "id"=>10,
        );
		*/
		//������ÿ�
		/*
		$url = "http://127.0.0.1/api/api.php?c=credit&m=add";
		$code='9561e4a736e89d89';
		$auth=md5('api_'.$code.time());
		$post_data = array (
          "auth" => $auth,
		  "authTime"=>time(),
		  "title"=>'���ÿ�',
		  "image"=>'image',
          "sketch" => "sketch", //��Ҫ����
		  "bank"=>'bank',
		  "limit" => "limit",//���
		  "describe" => "describe",//����
		  "url" => "url"//����
		  
        );
		*/`