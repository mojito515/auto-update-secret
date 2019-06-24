# auto-update-secret
auto update aws-ecr secret with a crontab by ansible-playbook





```bash
$ sudo ansible-playbook -i inventory -e "aws_region=<aws_region> aws_access_key_id=<aws_access_key_id> aws_secret_access_key=<aws_secret_access_key>" aws-ecr-creds-os.yml
```
> ``NOTE`` These values are required:  aws_region , aws_access_key_id , aws_secret_access_key
