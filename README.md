# SoundText

O projeto é uma aplicação robusta desenvolvida para a empresa Malborg Tecnologia, destinada a converter texto em áudio de forma eficiente e versátil. O sistema é projetado para integrar-se perfeitamente com equipamentos de sonorização profissionais da Telex e Barix, proporcionando uma solução completa para necessidades de comunicação e disseminação de informações em ambientes corporativos, comerciais e industriais. Disponível em versões desktop e web, o SoundText oferece um conjunto abrangente de funcionalidades para criação, gerenciamento e distribuição de conteúdo em áudio.

# Principais Funcionalidades
- **Conversão de Texto em Áudio**:
- Converte texto em áudio de alta qualidade com suporte a múltiplos formatos (MP3, WAV).
- Opções de personalização de voz, idioma e velocidade de narração para atender a diferentes necessidades.

# **Integração com Equipamentos de Sonorização:** 
- Compatibilidade total com sistemas de áudio da Telex e Barix, permitindo a transmissão direta do conteúdo gerado para múltiplos dispositivos e zonas de áudio.
- Suporte a protocolos de comunicação padrão da indústria, garantindo confiabilidade e desempenho na distribuição de áudio.

# **Interface Web Moderna:**
- Plataforma web responsiva e intuitiva, facilitando o acesso e gerenciamento do sistema a partir de qualquer dispositivo com navegador.
- Controle centralizado de transmissões de áudio, agendamento de mensagens e monitoramento em tempo real.

# **Integração com Spotify:**
- Controle de playlists do Spotify diretamente pela aplicação, incluindo funcionalidades de reprodução, pausa e ajuste de volume.
- Automação inteligente que reduz o volume da música durante a reprodução de mensagens de áudio, garantindo clareza e profissionalismo nas transmissões.

# **Relatórios e Análises Avançadas:**
- Geração de relatórios detalhados em formatos PDF e XLS, incluindo estatísticas de uso, desempenho do sistema e histórico de transmissões.
- Visualizações gráficas que facilitam a análise e tomada de decisões baseadas em dados.

# **Gerenciamento de Usuários e Segurança**:
- Sistema de autenticação robusto com controle de acesso baseado em funções (administrador, operador, visualizador).
- Logs completos de atividades dos usuários, incluindo tentativas de login e ações executadas dentro do sistema.
- Políticas de segurança alinhadas com as melhores práticas de proteção de dados e conformidade regulatória.

# **Logs de Áudio e Arquivamento:**
- Armazenamento organizado de todos os arquivos de áudio gerados, com recursos de pesquisa e recuperação facilitados.
- Opções de arquivamento e backup automático para garantir a integridade e disponibilidade do conteúdo ao longo do tempo.


# **Backend** 

O backend do projeto SoundText foi desenvolvido utilizando Python com Flask, uma micro-framework altamente eficiente para a criação de APIs. O sistema foi projetado para ser robusto, garantindo uma comunicação fluida entre as diferentes partes da aplicação. A arquitetura do backend inclui:

- **Autenticação de Usuários**: Implementada com SQLite, fornecendo uma gestão segura de login, senha, e sessões.
- **Geração de Áudio**: Utiliza a biblioteca gTTS para transformar texto em áudio, com suporte para formatos como MP3 e WAV.
- **Integração com Equipamentos de Sonorização**: Desenvolvido especialmente para equipamentos Telex e Barix, otimizando a transmissão de áudio.
- **Gerenciamento de Logs**: Registra eventos de login e geração de áudio, facilitando a auditoria e o monitoramento.
- **API do Spotify**: Integrada para controle de playlists e ajuste de volume, proporcionando uma experiência de sonorização completa.

# Tecnologias Utilizadas
**Python (Flask)**: Estrutura principal do backend.

**SQLite**: Banco de dados leve para armazenar credenciais e logs.

**gTTS**: Geração de áudio em diferentes formatos a partir de texto.

**Pydub**: Manipulação de arquivos de áudio, incluindo conversões.

**Jinja2**: Template engine utilizada para a geração dinâmica das páginas HTML.

**HTML, CSS e JavaScript**: Para a construção da interface web.

**API do Spotify**: Integração para reprodução de playlists e controle de áudio.

Este backend foi desenhado para ser altamente configurável e fácil de expandir, permitindo adaptações rápidas para novas funcionalidades e equipamentos. A infraestrutura modular também facilita a manutenção e a escalabilidade do sistema.

# Contato
**Email**: leonzanotti96@gmail.com
**Malborg**: malborg.com
