# PROJETO INTEGRADOR I
## DOCUMENTAÇÃO TÉCNICA

**Nome do Responsável:** Gabriel Soares Colares  
**Nome do Sistema:** Venust Business  
**Versão:** 1.0  

---

### 1 – Apresentação:
O Venust Business é um sistema voltado para gerenciar barbearias, salões de beleza e estúdios de estética, facilitando o agendamento de serviços, controle de profissionais, estoque e finanças. Com uma interface simples e intuitiva, ele centraliza operações como cadastro de clientes, controle de caixa e envio de promoções personalizadas, ajudando a aumentar a eficiência e a organização do negócio.

### 2 – Descrição do Projeto e Usuários:
O Venust Business será composto por funcionalidades focadas em otimizar a gestão de barbearias e salões de beleza, com um banco de dados que centraliza todas as operações do negócio. O sistema contará com diferentes tipos de usuários e permissões, garantindo um controle eficiente de informações e acessos.

**Funcionalidades e Cadastros:**
- Clientes;
- Profissionais;
- Serviços;
- Agendamentos;
- Caixa;

**Os usuários e suas permissões:**
- **Administrador** – Acesso completo a todas as funcionalidades, incluindo cadastros, relatórios e controle financeiro;
- **Recepcionista** – Acesso aos cadastros de clientes, profissionais, agendamentos e caixa;
- **Profissionais** – Acesso à agenda de serviços e ao histórico de clientes.

O sistema também contará com backup diário, gerando relatórios de clientes, agendamentos e fluxo de caixa, enviados automaticamente para o administrador via e-mail e armazenados no servidor.

### 3 – Requisitos Funcionais
**Exemplo:**
- **RF001 – Cadastro de Cliente**  
  O sistema deve permitir o cadastro de clientes com informações como nome, telefone, e-mail e histórico de serviços.
  
- **RF002 – Cadastro de Profissional**  
  O sistema deve possibilitar o cadastro de profissionais, incluindo nome, especialidade, horários de trabalho e disponibilidade.
  
- **RF003 – Cadastro de Serviço**  
  O sistema deve permitir o cadastro de serviços oferecidos, com campos para nome, descrição, preço e duração.
  
- **RF004 – Agendamento de Serviço**  
  O sistema deve possibilitar o agendamento de serviços, registrando a data, horário, cliente e profissional responsável.
  
- **RF005 – Controle de Caixa**  
  O sistema deve permitir o registro de movimentações financeiras, incluindo vendas, pagamentos e despesas.

### 4 – Requisitos Não Funcionais
- **RNF001 – Usabilidade**  
  O sistema deve ter uma interface amigável e intuitiva, permitindo que usuários com diferentes níveis de experiência naveguem e utilizem suas funcionalidades com facilidade.
  
- **RNF002 – Desempenho**  
  O sistema deve responder a qualquer operação realizada em até 2 segundos, mesmo com um número elevado de usuários simultâneos.
  
- **RNF003 – Segurança**  
  O sistema deve implementar medidas de segurança, como criptografia de dados sensíveis (por exemplo, senhas), e garantir a proteção contra acessos não autorizados.
  
- **RNF004 – Backup Diário**  
  O sistema deve realizar backups automáticos diários, garantindo a integridade e a recuperação dos dados em caso de falhas.
  
- **RNF005 – Permissões de Acesso**  
  O sistema deve garantir que as permissões dos usuários estejam configuradas de acordo com o nível do login executado, evitando acessos não autorizados a informações sensíveis.

### 5 – Observações Técnicas
O Venust Business será desenvolvido com as seguintes tecnologias:
- **Linguagem de Programação:** Utilizaremos Java para o backend, garantindo robustez e segurança;
- **Banco de Dados:** O sistema usará MySQL para armazenar informações de clientes, profissionais e agendamentos.
- **Backup Diário:** O sistema realizará backups automáticos diários para garantir a segurança dos dados.
- **Regras de Negócio:** Incluirá validações para agendamentos e notificações automáticas para clientes e profissionais.