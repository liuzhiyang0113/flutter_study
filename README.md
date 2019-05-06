# flutter_study

### Problem Points Solved
 - 多个ssh key 时，访问github访问不了，内网限制 在外网的环境下，一切使用正常。
   - 常见错误 ：
    1. ssh -T git@github.com
	    > error: ssh_exchange_identification: read: Connection reset by peer
    2. git clone (一个github的仓库)
	    > error:
	      ssh_exchange_identification: read: Connection reset by peer
	      fatal: Could not read from remote repository.

	      Please make sure you have the correct access rights
	      and the repository exists.
 - 将IP永久的添加到hosts文件(ip对应域名) ====> 52.74.223.119 github.com
    - 遇见错误：
      1. Warning: Permanently added the RSA host key for IP address '52.74.223.119' to the list of known hosts.