---
- name: Dump multiplos databases
  hosts: node2.lab.example.com

  tasks:    
    - name: Dump multiple databases
      community.mysql.mysql_db:
        state: dump
        name:
          - araujo
        target: /tmp/dump_araujo.sql
