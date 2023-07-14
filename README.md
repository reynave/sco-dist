# sco-dist

# Installation Server SCO ver 1.1.x

**Step 1** Install PHP server
 1. Install XAMPP dengan ***PHP Version 7.4.30***
 2. update PHP.INI dengan untuk mengaktifkan sql server *.dll
	 php_pdo_sqlsrv_74_nts.dll, php_pdo_sqlsrv_74_ts.dll, php_sqlsrv_74_nts.dll, 	
	 php_sqlsrv_74_ts.dll
 3. jika sudah terupload semua restart XAMPP service PHP (stop and start)

**Step 2**
1. install SQL Server 2022 Express  (minimun)
2. documentasi via google

**Step 3**
 1. Download zip this github / gitpull repository
 2. Akan terbentuk folder baru yang berisi file-file diatas
 3. Lalu update sesuai dengan file config.js, sesuai dengan API server anda
