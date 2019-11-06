# Disk IO test.
Use fio comand for test with csv reuslt

1. 修改配置文件group_vars/all.yml
2. 运行测试
```
ansible-playbook fio.yml -i hosts/host --ask-pass
```
