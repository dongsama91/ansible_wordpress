## Wordpress+Nginx+PHP-FPM Deployment

- Đổi lại file hosts cho phù hợp
- Triển khai

    `$ ansible-playbook -i hosts site.yml
    `$ ansible-playbook -i hosts site.yml -limit '192.168.100.10'

