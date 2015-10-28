
以下のコマンドを入力してパッケージ取ってね
```
ansible-galaxy install --roles-path=. hnakamur.homebrew-packages
ansible-galaxy install --roles-path=. hnakamur.homebrew-cask-packages
ansible-galaxy install --roles-path=. hnakamur.atom-packages 
```

実行は
```
git clone --recursive https://github.com/328--/mac-ansible.git
ansible-playbook -i hosts playbook.yml
```
