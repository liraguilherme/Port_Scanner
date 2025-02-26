

Port Scanner em Python

Um scanner de portas simples escrito em Python, desenvolvido para fins educacionais e de aprendizado em cybersecurity. Este projeto verifica quais portas estão abertas em um determinado endereço IP.

🚀 Como Funciona
O script utiliza a biblioteca socket para tentar se conectar a cada porta de um intervalo especificado (1 a 65535) em um endereço IP. Se a conexão for bem-sucedida, a porta é considerada aberta e é adicionada a uma lista de portas abertas.

🖥️ Exemplo de Saída
Aqui está um exemplo de como a saída do script pode parecer:


Open Ports are: 
[22, 80, 443]

🛡️ Considerações de Segurança
Use com responsabilidade: Este script foi desenvolvido para fins educacionais. Certifique-se de ter permissão para escanear o IP ou sistema alvo.

Teste em ambientes controlados: Recomenda-se testar o script em seu próprio sistema (localhost) ou em ambientes de teste autorizados.

🤝 Contribuição
Contribuições são bem-vindas! Se você tiver alguma sugestão, melhoria ou correção, sinta-se à vontade para abrir uma issue ou enviar um pull request.

📄 Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
