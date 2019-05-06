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
