								Api�ĵ�
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