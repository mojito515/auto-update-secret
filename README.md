# auto-update-secret
auto update aws-ecr secret with a crontab by ansible-playbook



### 第一步：登陆到master001节点
### 第二步：从github上拉取脚本 https://github.com/mojito515/auto-update-secret.git
### 第三步：执行命令行，如下：
```bash
$ sudo ansible-playbook -i inventory -e "aws_region=<aws_region> aws_access_key_id=<aws_access_key_id> aws_secret_access_key=<aws_secret_access_key>" aws-ecr-creds-os.yml
```
> ``NOTE`` 有三个必传的值:  aws_region , aws_access_key_id , aws_secret_access_key
