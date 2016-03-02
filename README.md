# katusible
for CentOS6

##使い方
hostsファイルを編集し

    tarrge IPを対象サーバーのIPに変更

site.ymlでroleを指定して実行する

    ansible-playbook -i hosts  site.yml 
