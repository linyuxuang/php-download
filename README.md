# php-download
php文件下载


	header("Content-Type:image/gif");
	header('Content-Disposition: attachment; filename="logo3333.gif"');
	header('Content-Length:'.filesize("logo.gif"));
	readfile("logo.gif");
