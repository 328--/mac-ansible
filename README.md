```
ansible-galaxy install --roles-path=. hnakamur.homebrew-packages
ansible-galaxy install --roles-path=. hnakamur.homebrew-cask-packages
ansible-galaxy install --roles-path=. hnakamur.atom-packages 
```

```
ansible-playbook -i hosts playbook.yml
```
