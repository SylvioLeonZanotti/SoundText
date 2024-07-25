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

# Contato
**Email**: leonzanotti96@gmail.com
