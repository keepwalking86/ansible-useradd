## Create user account with sudo no password

**Step1: Change ansible hosts**

- Change value in ansible_hosts file

**Step2: Change value of variable `sudoers`**

- Change value "user01" in playbook file

**Step3: Add public-key file**

- Change user01.pub with your public-key file

**Step4: Run ansible-play**

`ansible-playbook -i ansible_hosts playbook.yml -vvvvv`
