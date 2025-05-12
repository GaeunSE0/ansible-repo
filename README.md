# 사전 작업시 아래의 command 실행
ansible-galaxy collection install ansible.posix

# Node1 에는 아래의 작업 필요
echo 'Imadev' > passwd --stdin bob
echo 'Imadev' > passwd --stdin fred

# Node2 에는 아래의 작업 필요
echo 'Imadev' > passwd --stdin bob
echo 'Imadev' > passwd --stdin fred
vgcreate research 

# Node2 에는 아래의 작업 필요
useradd natasha
