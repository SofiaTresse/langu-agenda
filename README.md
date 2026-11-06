# Langu.space — agenda de reuniões

Prévia interativa para aprovação: https://SofiaTresse.github.io/langu-agenda/

Formulário com apenas nome e WhatsApp após a escolha de data e horário. Design em preto, branco, rosa e roxo.

## Demonstração publicada

O index.html funciona no GitHub Pages. Pedidos e respostas são simulados somente na aba atual, sem armazenamento permanente nem envio ao WhatsApp. A área da escola é aberta para testar a aprovação. Não use esta página para coletar agendamentos reais.

## Versão completa

O arquivo langu-agenda-fonte.zip contém o servidor Node.js, o banco SQLite criado na primeira execução, as telas e os testes. Não contém dados pessoais, senhas, banco de dados nem credenciais. Extraia, abra Iniciar.cmd e acesse http://localhost:3000. Node.js 22.13 ou superior. Crie a senha da escola no primeiro acesso.

Para uso real, hospede essa versão em um serviço com servidor Node e disco persistente. O envio automático exige uma integração autorizada de WhatsApp Business. GitHub Pages hospeda apenas a demonstração.

## Validação

Execute npm test na versão completa. Verifica solicitação usando somente nome e WhatsApp, conflitos de horário, aprovação, recusa, bloqueios e acesso protegido.
