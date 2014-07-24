# TuTu ansible role

This role install TuTu - flexible http server mocking tool.
Keep in mind that this role do not set www-serwer, you need to do it on your own.

You can use following variables to configure TuTu:
```
tutu_root_path: /var/www/tutu
tutu_responses_file_path: "{{ tutu_root_path }}/tutu/config/responses.yml"
tutu_resources_path: "{{ tutu_root_path }}/tutu/resources"
```
