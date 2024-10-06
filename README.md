# Venust Business

## 1 – Apresentação
O sistema Venust Business é uma plataforma voltada para facilitar o agendamento de serviços em barbearias e salões de beleza. Com um foco na experiência do usuário e na centralização das operações, o sistema visa eliminar a dependência de métodos tradicionais de agendamento, proporcionando uma gestão mais eficiente e organizada.

## 2 – Descrição do Projeto e Usuários
O Venust Business será composto por funcionalidades específicas para diferentes usuários, permitindo um controle efetivo sobre o fluxo de informações. As principais funcionalidades incluem:

- **Agendamentos**: Cadastro e gerenciamento de agendamentos para serviços de beleza.
- **Profissionais**: Cadastro e gestão de profissionais disponíveis para atendimento.
- **Clientes**: Cadastro de informações dos clientes que utilizam os serviços.
- **Notificações**: Envio de notificações automáticas para clientes e profissionais sobre agendamentos.

### Usuários e suas permissões:
- **Administrador**: Acesso a todos os cadastros e configurações do sistema.
- **Profissional**: Acesso apenas ao cadastro de seus próprios agendamentos e informações de clientes.

## 3 – Requisitos Funcionais
- **RF001 – Cadastro de Cliente**  
  Requisito responsável por cadastrar um novo cliente após o preenchimento de todos os campos necessários.

- **RF002 – Cadastro de Profissional**  
  Requisito responsável por cadastrar um novo profissional, incluindo informações como nome, especialidade e disponibilidade.

- **RF003 – Cadastro de Agendamento**  
  Requisito que permite o agendamento de serviços, associando clientes e profissionais disponíveis.

- **RF004 – Notificações**  
  Requisito que envia notificações automáticas para clientes e profissionais sobre agendamentos realizados.

## 4 – Requisitos Não Funcionais
- **RNF001 – Usabilidade**  
  O sistema deve ter uma interface amigável e intuitiva.

- **RNF002 – Desempenho**  
  O sistema deve responder a qualquer operação em até 2 segundos.

- **RNF003 – Segurança**  
  O sistema deve implementar medidas de segurança para proteger dados sensíveis.

- **RNF004 – Manutenção**  
  O sistema deve ser projetado para facilitar a manutenção e atualizações.

- **RNF005 – Compatibilidade**  
  O sistema deve ser compatível com os principais navegadores e dispositivos móveis.

- **RNF006 – Backup Diário**  
  O sistema deve realizar backups automáticos diários.

- **RNF007 – Permissões de Acesso**  
  O sistema deve garantir que as permissões dos usuários estejam configuradas corretamente.

- **RNF008 – Escalabilidade**  
  O sistema deve ser escalável, permitindo a adição de novos usuários e funcionalidades.

- **RNF009 – Suporte Técnico**  
  O sistema deve oferecer suporte técnico acessível.

## 5 – Observações Técnicas
O Venust Business será desenvolvido com as seguintes tecnologias:

- **Linguagem de Programação**: Utilizaremos **Java** para o backend.
- **Banco de Dados**: O sistema usará **MySQL** para armazenar informações.
- **Framework**: Para o frontend, será considerado o uso de **JavaServer Faces (JSF)** ou **Spring Boot**.
- **Autenticação**: A autenticação será gerenciada pelo **Spring Security**.
- **Backup Diário**: O sistema realizará backups automáticos diários.
- **Escalabilidade**: O projeto será estruturado para permitir fácil escalabilidade e manutenção.
- **Regras de Negócio**: Incluirá validações para agendamentos e notificações automáticas.

Essas observações garantem que o **Venust Business** atenda às necessidades de barbearias e salões de beleza.