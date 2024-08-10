# SoundText

**SoundText** é um sistema de sonorização desenvolvido para a empresa **Malborg Tecnologia**. O sistema é utilizado em hospitais infantis para criar avisos sonoros a partir de textos digitados pelos usuários. Este repositório contém uma descrição do projeto, suas funcionalidades, tecnologias utilizadas e prints da interface do usuário. Os códigos fontes não estão presentes devido à confidencialidade do projeto.

# Funcionalidades

- **Criação de Áudios**: Permite a criação de arquivos de áudio a partir de textos digitados.
- **Gerenciamento de Usuários**: Inclui funcionalidades de login, criação, suspensão e reativação de usuários.
- **Integração com APIs**: Envio de logs de atividades do sistema para um servidor central.
- **Backup Automático**: Backup periódico do banco de dados e envio por e-mail.
- **Interface Moderna**: Utiliza uma interface gráfica moderna e intuitiva desenvolvida com CustomTkinter.

# Tecnologias Utilizadas

- **Linguagem de Programação**: Python
- **Frameworks**: Flask (para a API), CustomTkinter (para a interface gráfica)
- **Banco de Dados**: SQLite
- **Outras Bibliotecas**: Pygame (para reprodução de áudio), Requests (para integração com a API)
- **Frontend**: HTML, CSS, JavaScript

# Como Funciona

- **Tela de Login**: O usuário se autentica no sistema usando seu email e senha.
- **Tela Principal**: Após o login, o usuário pode digitar um texto e gerar um arquivo de áudio.
- **Administração de Usuários**: Usuários com privilégios administrativos podem gerenciar outros usuários, suspendendo ou reativando contas conforme necessário.
- **Envio de Logs**: Todas as atividades importantes são registradas e enviadas para um servidor central através de uma API.
- **Backup Automático**: O sistema realiza backups periódicos do banco de dados e os envia por e-mail.

#  API do Projeto Sound Text
A **API do projeto Sound Text** foi desenvolvida para gerenciar e controlar um sistema de sonorização personalizado. Esta API permite o gerenciamento de usuários, autenticação, controle de sessões, geração de relatórios do sistema, manipulação de dados no banco de dados, e uma interface administrativa robusta para monitorar e modificar parâmetros do sistema. A API foi desenvolvida utilizando o framework Flask, com SQLite como banco de dados.

# Funcionalidades
- **1. Autenticação de Usuários**
**Autenticação**: Permite que usuários façam login com suas credenciais. Implementa verificação de email e senha com suporte para usuários suspensos e inativos.
Criação de Novos Usuários: Facilita o registro de novos usuários no sistema.
**Recuperação de Senha**: Disponibiliza funcionalidade para recuperação de senha via email.

- **2. Controle Administrativo**
**Administração Completa do Sistema**: Através da interface admin.html, administradores podem monitorar o status do sistema, suspender ou reativar contas de usuários, e definir credenciais de suporte.
Definir Credenciais de Suporte: Permite que administradores configurem remotamente o login e a senha de contas de suporte específicas.
**Suspensão do Sistema**: Administradores podem alterar o status do sistema para inativo, prevenindo novos logins.
**Logs Detalhados**: A API registra todas as tentativas de login, fornecendo logs detalhados para auditoria.
  
- **3. Geração de Relatórios**
**Relatório do Sistema**: Gera relatórios PDF com estatísticas do sistema, incluindo número de usuários ativos, usuários suspensos, e gráficos de estabilidade do sistema.
**Logs de Acesso**: Exporta logs de acessos, tentativas de login e outras atividades dos usuários em formatos legíveis e analisáveis.

- **4. Gerenciamento de Usuários**
**Listagem e Edição de Usuários**: A API permite listar todos os usuários registrados, editar informações e status de contas diretamente através da interface administrativa.
**Suspensão e Reativação de Usuários**: Administradores podem suspender ou reativar contas de usuários conforme necessário.
- **5. Integração com a Interface Gráfica**
**Páginas Personalizadas**: Interface para exibição de logs e status do sistema diretamente na página admin.html.
**Relatórios Visuais**: Gráficos e estatísticas geradas são integrados visualmente com a interface para fácil monitoramento.

# Registro de novos usuários
![image](https://github.com/user-attachments/assets/8b171004-a4b5-4463-82de-b2f7c9cc032b)

# Painel Administrativo
![image](https://github.com/user-attachments/assets/659d2313-3933-4235-ab05-1d43c17be29b)


# Contato
**Email**: leonzanotti96@gmail.com
