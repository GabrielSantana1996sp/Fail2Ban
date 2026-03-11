# Fail2Ban
Passos para aplicar
Crie/edite o arquivo:

bash
sudo nano /etc/fail2ban/jail.local
Adicione o bloco [sshd] acima.

Salve e reinicie o serviço:

bash
sudo systemctl restart fail2ban
Verifique se está rodando:

bash
sudo fail2ban-client status sshd            
