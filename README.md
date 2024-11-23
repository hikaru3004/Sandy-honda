# SandyHonda

- [SandyHonda](#sandyhonda)
  - [1. Introdução](#1-introdução)
  - [2. Descrição do negócio](#2-descrição-do-negócio)
  - [2.1. Requisitos](#21-requisitos)
    - [Requisitos Funcionais e Não Funcionais](#requisitos-funcionais-e-não-funcionais)
  - [3. Visão geral do sistema](#3-visão-geral-do-sistema)
    - [Visão Geral do Sistema](#visão-geral-do-sistema)
      - [**Descrição do Sistema e Suas Relações**](#descrição-do-sistema-e-suas-relações)
      - [Relações do Sistema](#relações-do-sistema)
      - [O que o sistema entrega do ponto de vista do usuário final](#o-que-o-sistema-entrega-do-ponto-de-vista-do-usuário-final)
  - [4. Diagrama ER](#4-diagrama-er)
  - [4.1.  Descrição Entidade e Relacionamento](#41--descrição-entidade-e-relacionamento)
    - [**Entidades**](#entidades)
  - [4.2. Relacionamentos](#42-relacionamentos)
    - [4.2.1 **Relacionamentos Detalhados**](#421-relacionamentos-detalhados)
  - [5. Diagrama de classes](#5-diagrama-de-classes)
  - [5.1. Descrição das Classes e Relacionamentos](#51-descrição-das-classes-e-relacionamentos)
  - [5.2. Relacionamentos](#52-relacionamentos)
  - [6. Casos de uso](#6-casos-de-uso)
  - [6.1 Casos de uso](#61-casos-de-uso)
  - [6.2 Histórias de usuario](#62-histórias-de-usuario)
    - [1. Marcar Animais com RFID](#1-marcar-animais-com-rfid)
    - [2. Atender Apenas Gatos e Cachorros](#2-atender-apenas-gatos-e-cachorros)
    - [3. Cadastro de Clientes e Animais](#3-cadastro-de-clientes-e-animais)
    - [4. Informar Condições do Animal](#4-informar-condições-do-animal)
    - [5. Informar Tipo de Ração](#5-informar-tipo-de-ração)
    - [6. Informar Hábitos do Animal](#6-informar-hábitos-do-animal)
    - [7. Atendimentos com Mais de Um Veterinário](#7-atendimentos-com-mais-de-um-veterinário)
    - [8. Agenda do Dia para Atendimentos](#8-agenda-do-dia-para-atendimentos)
    - [9. Ficha e Prontuário para Cada Animal](#9-ficha-e-prontuário-para-cada-animal)
    - [10. Marcar Horários Futuramente](#10-marcar-horários-futuramente)
    - [11. Atendimento Gera Receita](#11-atendimento-gera-receita)
    - [12. Atendimento Inicial pelo Atendente](#12-atendimento-inicial-pelo-atendente)
    - [13. Verificar Agenda de Veterinários](#13-verificar-agenda-de-veterinários)
    - [14. Colocar na Fila de Espera](#14-colocar-na-fila-de-espera)
    - [15. Levar Cliente ao Veterinário](#15-levar-cliente-ao-veterinário)
    - [16. Realizar Entrevista com o Dono](#16-realizar-entrevista-com-o-dono)
    - [17. Registro do Resultado da Entrevista](#17-registro-do-resultado-da-entrevista)
    - [18. Anotar Observações no Prontuário](#18-anotar-observações-no-prontuário)
    - [19. Receitar Medicamentos](#19-receitar-medicamentos)
    - [20. Serviços de Banho e Tosa](#20-serviços-de-banho-e-tosa)
    - [21. Realização de Cirurgias, Injeções e Curativos](#21-realização-de-cirurgias-injeções-e-curativos)
    - [22. Serviço de Pintura de Cachorro](#22-serviço-de-pintura-de-cachorro)
    - [23. Serviços de Fisioterapia e Nutrição](#23-serviços-de-fisioterapia-e-nutrição)
    - [24. Visualizar Animais e Fichas](#24-visualizar-animais-e-fichas)
    - [25. Visualizar Receitas](#25-visualizar-receitas)
    - [26. Auxílio para Animais com Sobrepeso](#26-auxílio-para-animais-com-sobrepeso)
    - [27. Acesso ao Receituário dos Animais](#27-acesso-ao-receituário-dos-animais)
    - [28. Comunicação Direta com Profissionais](#28-comunicação-direta-com-profissionais)
    - [29. Serviço de Hotel para Animais](#29-serviço-de-hotel-para-animais)
  - [7. Diagrama de componentes](#7-diagrama-de-componentes)
  - [8. Diagrama de implantação](#8-diagrama-de-implantação)
  - [9. Diagramas C4](#9-diagramas-c4)
  - [9.1. Diagrama de contexto](#91-diagrama-de-contexto)
  - [9.2. Diagrama de container](#92-diagrama-de-container)
  - [9.3. Diagrama de componente](#93-diagrama-de-componente)
  - [9.4. Diagrama de código](#94-diagrama-de-código)
  - [10. Protótipo de telas](#10-protótipo-de-telas)
    - [1. Login](#1-login)
    - [1. Tela Inicial](#1-tela-inicial)
    - [2. Agenda](#2-agenda)
    - [3. Editar Agenda](#3-editar-agenda)
    - [4. Detalhes Agenda](#4-detalhes-agenda)
    - [5. Animal](#5-animal)
    - [6. Editar Animal](#6-editar-animal)
    - [7. Detalhes Animal](#7-detalhes-animal)
    - [8. Atentendente](#8-atentendente)
    - [9. Editar Atendente](#9-editar-atendente)
    - [10. Detalhes Atendente](#10-detalhes-atendente)
    - [11. Cliente](#11-cliente)
    - [12. Editar Cliente](#12-editar-cliente)
    - [13. Detalhes Cliente](#13-detalhes-cliente)
    - [14. Comunicação](#14-comunicação)
    - [15. Editar Comunicação](#15-editar-comunicação)
    - [16. Detalhes Comunicação](#16-detalhes-comunicação)
    - [17. Ficha](#17-ficha)
    - [18. Editar Ficha](#18-editar-ficha)
    - [19. Detalhes Ficha](#19-detalhes-ficha)
    - [20. Hotel](#20-hotel)
    - [21. Editar Hotel](#21-editar-hotel)
    - [22. Detalhe Hotel](#22-detalhe-hotel)
    - [23. Prontuario](#23-prontuario)
    - [24. Editar Pronturario](#24-editar-pronturario)
    - [25. Detalhe Prontuario](#25-detalhe-prontuario)
    - [26. Serviço](#26-serviço)
    - [27. Editar Serviço](#27-editar-serviço)
    - [28. Detalhe Serviço](#28-detalhe-serviço)
    - [29. Veterinario](#29-veterinario)
    - [30. Editar Veterinario](#30-editar-veterinario)
    - [31. Detalhes Veterinario](#31-detalhes-veterinario)
    - [32. Atendimento](#32-atendimento)
    - [33. Editar Atendimento](#33-editar-atendimento)
    - [34. Detalhes Atendimento](#34-detalhes-atendimento)
    - [35. Grafico Barra](#35-grafico-barra)
    - [36. Grafico Pizza](#36-grafico-pizza)
    - [37. Grafico Linha](#37-grafico-linha)
    - [38. Dashboard](#38-dashboard)
  - [11. Diagrama de navegação de telas](#11-diagrama-de-navegação-de-telas)
  - [12. Pilha tecnologica](#12-pilha-tecnologica)
  - [13. Requisitos de sistemas](#13-requisitos-de-sistemas)
  - [13.1. Requisitos lado do Cliente](#131-requisitos-lado-do-cliente)
    - [Sistema Operacional](#sistema-operacional)
    - [Navegador](#navegador)
    - [Acesso à Internet](#acesso-à-internet)
    - [Recursos de Hardware](#recursos-de-hardware)
    - [Permissões e Configurações de Segurança](#permissões-e-configurações-de-segurança)
    - [Forma de Autenticação](#forma-de-autenticação)
  - [13.2. Requisitos lado do Servidor](#132-requisitos-lado-do-servidor)
    - [Tipo de Sistema Operacional](#tipo-de-sistema-operacional)
    - [**Tipo de Processador**](#tipo-de-processador)
    - [**Memória RAM**](#memória-ram)
    - [**Armazenamento**](#armazenamento)
    - [**Rede**](#rede)
    - [**Segurança**](#segurança)
    - [**Capacidade de Escalar o Ambiente**](#capacidade-de-escalar-o-ambiente)
    - [**Serviços, Servidor e Mídia para Backups**](#serviços-servidor-e-mídia-para-backups)
    - [**Requisitos Adicionais**](#requisitos-adicionais)
  - [14. Considerações sobre segurança](#14-considerações-sobre-segurança)
  - [14.1. Lado do Cliente](#141-lado-do-cliente)
    - [Validação por CAPTCHA](#validação-por-captcha)
    - [Comunicação Segura](#comunicação-segura)
  - [14.2. Lado Servidor](#142-lado-servidor)
    - [**Configuração de Pastas**](#configuração-de-pastas)
      - [**Verificação de Dados de Entrada**](#verificação-de-dados-de-entrada)
      - [**Gerenciamento de Atualizações**](#gerenciamento-de-atualizações)
      - [**Hospedagem Segura**](#hospedagem-segura)
      - [**Uso de Certificados no Servidor**](#uso-de-certificados-no-servidor)
      - [**Sistema de Monitoramento e Alertas**](#sistema-de-monitoramento-e-alertas)
      - [**Sistema Automatizado de Backup**](#sistema-automatizado-de-backup)
      - [**Serviços Gerando Logs**](#serviços-gerando-logs)
  - [15. Manutenção, instalação e novas funcionalidades](#15-manutenção-instalação-e-novas-funcionalidades)
  - [15.1. Instalando no servidor](#151-instalando-no-servidor)
    - [**2. Requisitos de Infraestrutura**](#2-requisitos-de-infraestrutura)
      - [**3. Configuração de Funcionalidades Específicas**](#3-configuração-de-funcionalidades-específicas)
      - [**4. Monitoramento e Logs**](#4-monitoramento-e-logs)
      - [**5. Gerenciamento de Atualizações**](#5-gerenciamento-de-atualizações)
      - [**6. Backup e Recuperação**](#6-backup-e-recuperação)
      - [**7. Configuração de Serviços Complementares**](#7-configuração-de-serviços-complementares)
      - [**8. Teste e Homologação**](#8-teste-e-homologação)
      - [**9. Escalabilidade**](#9-escalabilidade)
  - [15.2. Manutenção](#152-manutenção)
    - [**1. Manutenção Corretiva**](#1-manutenção-corretiva)
      - [**Processo de Manutenção**](#processo-de-manutenção)
      - [**Exemplos de Manutenção Corretiva**](#exemplos-de-manutenção-corretiva)
    - [**2. Manutenção Evolutiva**](#2-manutenção-evolutiva)
      - [**Processo**](#processo)
      - [**Exemplos de Manutenção Evolutiva**](#exemplos-de-manutenção-evolutiva)
    - [**3. Manutenção Adaptativa**](#3-manutenção-adaptativa)
      - [**Processo**](#processo-1)
      - [**Exemplos de Manutenção Adaptativa**](#exemplos-de-manutenção-adaptativa)
    - [**Ferramentas de Suporte à Manutenção**](#ferramentas-de-suporte-à-manutenção)
    - [**Política de Manutenção**](#política-de-manutenção)
  - [15.3. Novas funionalidades](#153-novas-funionalidades)
    - [**1. Formalização do Pedido**](#1-formalização-do-pedido)
      - [**Regras para Formalização**](#regras-para-formalização)
    - [2. A decisão depende de 3 critérios](#2-a-decisão-depende-de-3-critérios)
      - [**a) A Equipe Tem Tempo?**](#a-a-equipe-tem-tempo)
      - [**b) É Economicamente Viável?**](#b-é-economicamente-viável)
      - [**c) É Tecnologicamente Viável?**](#c-é-tecnologicamente-viável)
    - [**3. Implementação**](#3-implementação)
      - [**Etapas**](#etapas)
    - [**Exemplo de Aplicação**](#exemplo-de-aplicação)
    - [**Política de Reavaliação**](#política-de-reavaliação)
  - [16. Treinamento](#16-treinamento)
  - [16.1. Usuário](#161-usuário)
    - [**Manual de Treinamento**](#manual-de-treinamento)
      - [**1. Como acessar o sistema - Usuário**](#1-como-acessar-o-sistema---usuário)
      - [**2. Operações básicas principais**](#2-operações-básicas-principais)
        - [**Cadastro**](#cadastro)
        - [**Agendamento**](#agendamento)
        - [**Visualização de dados**](#visualização-de-dados)
      - [**3. Operações avançadas**](#3-operações-avançadas)
      - [**4. Backup (se estiver disponível)**](#4-backup-se-estiver-disponível)
      - [**5. Como solicitar suporte**](#5-como-solicitar-suporte)
      - [**6. Como documentar falhas**](#6-como-documentar-falhas)
      - [**Regras de Negócio Específicas**](#regras-de-negócio-específicas)
      - [**Serviços Exclusivos**](#serviços-exclusivos)
  - [16.2. Admin](#162-admin)
    - [**Manual de Treinamento Lado do Administrador**](#manual-de-treinamento-lado-do-administrador)
      - [**1. Como acessar o sistema**](#1-como-acessar-o-sistema)
      - [**2. Principais operações básicas**](#2-principais-operações-básicas)
        - [**Gerenciamento de usuários**](#gerenciamento-de-usuários)
        - [**Gerenciamento de animais**](#gerenciamento-de-animais)
      - [**3. Operações especiais**](#3-operações-especiais)
      - [**4. Backup do sistema e dados**](#4-backup-do-sistema-e-dados)
        - [**Realização de backup**](#realização-de-backup)
        - [**Gerenciamento de backups**](#gerenciamento-de-backups)
      - [**5. Como restaurar o sistema e dados**](#5-como-restaurar-o-sistema-e-dados)
        - [**Restauração de dados**](#restauração-de-dados)
        - [**Procedimento de recuperação**](#procedimento-de-recuperação)
      - [**6. Gerenciamento de contas**](#6-gerenciamento-de-contas)
        - [**Gestão de contas de usuários**](#gestão-de-contas-de-usuários)
        - [**Gerenciamento de senhas**](#gerenciamento-de-senhas)
      - [**7. Configurações necessárias dos servidores e clientes**](#7-configurações-necessárias-dos-servidores-e-clientes)
        - [**Configuração do servidor**](#configuração-do-servidor)
        - [**Configuração do cliente**](#configuração-do-cliente)
  - [17. Script SQL](#17-script-sql)
  - [17.1 Comando create table](#171-comando-create-table)
  - [17.2 Comandos para inserção de dados ficticios](#172-comandos-para-inserção-de-dados-ficticios)

## 1. Introdução

O projeto a seguir apresenta um sistema desenvolvido para um petshop. A empresa nomeada Clinica especializada em animais Pet+ é considerada micro e iniciou suas atividades recentemente. Ao possuir serviços exclusivos, os sistemas presentes no mercado não se enquadra, desta forma, os proprietários decidiram desenvolver uma solução. Esta solução é detalhada a seguir:

[Voltar ao Início](#sandyhonda)

## 2. Descrição do negócio

Descrição do cenário onde o sistema deverá funcionar:

1. Marcar animais com RFID.
2. Uma clínica veterinária atende apenas os animais: gatos e cachorros.
3. Os clientes devem fazer um cadastro de si e dos animais.
4. Os clientes devem informar as condições nas quais os animais chegam.
5. Os clientes devem informar o tipo de ração que o animal come.
6. O cliente deve informar hábitos do animal.
7. Para cada animal é possível que mais de um veterinário o atenda.
8. Os animais podem chegar e serem atendidos de acordo com uma agenda do dia.
9. Cada animal atendido receberá uma ficha e um prontuário.
10. Outros dono podem querer marcar horários de atendimento futuro.
11. O atendimento gera uma receita para o animal.
12. Quando um cliente chega na clínica veterinária ele é atendido por um atendente.
13. O atendente deve verificar se existe agenda disponível com um veterinário.
14. O atendente deve colocar o cliente e seu animal na fila de espera, se for o caso.
15. O atendente deve levar o cliente e o animal até o veterinário.
16. O veterinário deve realizar uma entrevista com o dono do animal.
17. O resultado da entrevista deve ir para um formulário.
18. O veterinário deverá examinar o animal e anotar em prontuário(ficha) suas observações.
19. Dependendo da situação do animal este receberá uma receita.
20. O pet shop oferece serviços de banho e tosa.
21. A pet shop realiza cirurgias, injeções e curativos.
22. O cliente pode escolher se quer o serviço de pintura de cachorro.
23. São oferecidos serviços de fisioterapia e nutrição
24. O sistema deve permitir que o cliente possa visualizar seus animais e suas fichas.
25. O sistema deve permitir que o cliente possa visualizar suas receitas.
26. A pet shop tem serviços para auxiliar os donos de animais com sobrepeso.
27. A pet shop deve oferecer aos clientes um lugar para ter acesso ao receituario dos animais.
28. A pet shop deve oferecer um meio de comunicação direta com os profissionais para que os donos possão sanar eventuais dúvidas.
29. A petshop oferece serviços de hotel para animais.

[Voltar ao Início](#sandyhonda)

## 2.1. Requisitos

### Requisitos Funcionais e Não Funcionais

| **Tipo de Requisito** | **Descrição**                                                                                           |
|------------------------|-------------------------------------------------------------------------------------------------------|
| **Funcional**          | Marcar animais com RFID.                                                                              |
|           | Realizar cadastro dos clientes e seus animais.                                                       |
|           | Permitir que clientes informem as condições dos animais ao chegar.                                    |
|           | Registrar o tipo de ração consumida pelo animal.                                                     |
|           | Registrar os hábitos do animal.                                                                      |
|           | Permitir que mais de um veterinário atenda o mesmo animal.                                            |
|           | Gerenciar uma agenda de atendimento diário para os animais.                                          |
|           | Criar ficha e prontuário para cada animal atendido.                                                  |
|           | Permitir o agendamento de horários de atendimento futuros.                                           |
|           | Gerar uma receita após o atendimento.                                                                |
|           | Permitir o atendimento de clientes por um atendente na chegada.                                      |
|           | Verificar disponibilidade de agenda com veterinários.                                                |
|           | Gerenciar uma fila de espera, se necessário.                                                         |
|           | Realizar entrevistas com donos dos animais e armazenar os resultados.                                |
|           | Registrar observações do veterinário no prontuário do animal.                                        |
|           | Oferecer serviços de banho, tosa, cirurgias, injeções e curativos.                                   |
|           | Disponibilizar serviços de fisioterapia, nutrição e pintura de cachorros.                            |
|           | Permitir que clientes visualizem fichas e receitas dos seus animais.                                 |
|           | Auxiliar donos de animais com sobrepeso.                                                             |
|           | Oferecer um meio de comunicação direta entre clientes e profissionais.                               |
|           | Disponibilizar serviços de hotel para animais.                                                       |
| **Não Funcional**      | O sistema deve ser acessível por dispositivos móveis e desktops.                                      |
|       | Garantir a segurança dos dados armazenados no sistema.                                               |
|       | Oferecer tempos de resposta inferiores a 2 segundos para operações comuns.                           |
|       | Garantir alta disponibilidade do sistema, com uptime superior a 99%.                                 |
|       | Permitir integração com dispositivos RFID para identificação dos animais.                            |
|       | Armazenar os dados em um banco de dados relacional (ex.: MySQL).                                      |
|       | Garantir conformidade com a Lei Geral de Proteção de Dados (LGPD).                                   |
|       | Implementar sistema de notificações em tempo real para atualizações sobre o status dos animais.       |
|       | Suportar mais de 100 conexões simultâneas sem perda significativa de desempenho.                      |
|       | Utilizar autenticação baseada em tokens para garantir segurança no login dos usuários.               |

[Voltar ao Início](#sandyhonda)

## 3. Visão geral do sistema

### Visão Geral do Sistema

#### **Descrição do Sistema e Suas Relações**

O sistema para o pet shop é um software integrado que gerencia as operações de uma clínica veterinária e pet shop. Ele conecta clientes, atendentes, veterinários e administradores, permitindo o cadastro, controle e acompanhamento de animais, além de gerenciar serviços oferecidos pelo estabelecimento, como banho, tosa, consultas, e hospedagem. O sistema está dividido em três principais camadas:

1. **Frontend (Interface do Usuário):**
   - Fornece uma interface intuitiva para clientes e funcionários acessarem o sistema.
   - É acessível via dispositivos móveis e desktops.
   - Permite o login seguro e o acesso às funcionalidades, como agendamento, visualização de fichas e receitas, e comunicação direta com os profissionais.

2. **Backend (Processamento de Dados):**
   - Responsável por gerenciar a lógica do sistema, incluindo o controle de agendamentos, geração de receitas, e armazenamento de prontuários.
   - Utiliza um banco de dados relacional para armazenar dados de clientes, animais, etc.
   - Processa os dados recebidos do frontend e os organiza no banco de dados.

3. **Banco de Dados:**
   - Armazena as informações de clientes, animais, serviços, agendas, receitas e fichas de atendimento.
   - Garante integridade e segurança dos dados seguindo normas de proteção, como a LGPD.

O sistema também inclui integração com dispositivos RFID para identificação rápida dos animais, simplificando o atendimento e os processos administrativos.

#### Relações do Sistema

- **Cliente ⇔ Sistema:**
  - O cliente utiliza a interface do sistema para registrar animais, agendar consultas, visualizar prontuários, e comunicar-se com profissionais a fim de solucionar possiveís dúvidas.
- **Atendente ⇔ Sistema:**
  - O atendente organiza a agenda, verifica disponibilidade de veterinários e gerencia filas de espera.
- **Veterinário ⇔ Sistema:**
  - O veterinário utiliza o sistema para registrar informações no prontuário, emitir receitas e gerenciar as condições dos animais.
- **Administrador ⇔ Sistema:**
  - O administrador monitora operações, controla dados do banco e garante o bom funcionamento do sistema.

#### O que o sistema entrega do ponto de vista do usuário final

Do ponto de vista do usuário final, o sistema entrega:

1. **Clientes:**
   - Facilidade para cadastrar seus dados e dos seus animais.
   - Agendamento online de consultas e serviços.
   - Acompanhamento de prontuários e histórico médico dos animais.
   - Comunicação direta com veterinários e outros profissionais.
   - Acesso rápido e seguro às receitas e fichas médicas.
   - Serviços adicionais, como banho, tosa, hospedagem e fisioterapia.

2. **Veterinários:**
   - Agenda organizada com informações completas sobre os atendimentos.
   - Ferramentas para registrar observações e diagnósticos no prontuário dos animais.
   - Histórico médico dos animais para acompanhamento de tratamentos.
   - Emissão rápida de receitas.

3. **Atendentes:**
   - Controle total da agenda de serviços e veterinários.
   - Facilidade para gerenciar filas de espera e organizar o fluxo de clientes.
   - Ferramentas para verificar disponibilidade de horários.

4. **Administradores:**
   - Visão geral de todas as operações da clínica e pet shop.
   - Monitoramento do desempenho do sistema e suporte para ajustes ou melhorias.
   - Relatórios gerenciais e dados de desempenho.

[Voltar ao Início](#sandyhonda)

## 4. Diagrama ER

```mermaid
erDiagram
    CLIENTE {
        int id_cliente PK
        string nome
        string telefone
        string endereco
    }
    ANIMAL {
        int id_animal PK
        string nome
        string rfid
        string especie
        string condicoes_chegada
        string tipo_racao
        string habitos
    }

    VETERINARIO {
        int id_veterinario PK
        string nome
        string especialidade
    }

    ATENDENTE {
        int id_atendente PK
        string nome
    }

    AGENDA {
        int id_agenda PK
        date data
        time horario
        string status
    }

    FICHA {
        int id_ficha PK
        string observacoes
    }

    PRONTUARIO {
        int id_prontuario PK
        string detalhes
        string receita
    }

    SERVICO {
        int id_servico PK
        string tipo
        string descricao
        float preco
    }

    COMUNICACAO {
        int id_comunicacao PK
        string mensagem
        date data_envio
        date data_resposta
    }

    HOTEL {
        int id_hotel PK
        date checkin
        date checkout
        string detalhes
    }

    CLIENTE ||--o{ ANIMAL : "possui"
    ANIMAL ||--o{ VETERINARIO : "é atendido por"
    ANIMAL ||--o{ FICHA : "tem"
    FICHA ||--|| PRONTUARIO : "tem"
    VETERINARIO ||--o{ AGENDA : "disponível em"
    CLIENTE ||--o{ AGENDA : "marca"
    ANIMAL ||--o{ SERVICO : "recebe"
    CLIENTE ||--o{ COMUNICACAO : "tem"
    CLIENTE ||--o{ HOTEL : "marca"
    ANIMAL ||--o{ HOTEL : "fica hospedado em"
    ATENDENTE ||--o{ AGENDA : "verifica"
```

## 4.1.  Descrição Entidade e Relacionamento

### **Entidades**  

- **Cliente**: Representa os clientes da clínica/pet shop. Atributos principais: CPF, Nome, Endereço, e Telefone.  
- **Animal**: Representa os animais cadastrados. Atributos principais: RFID, Nome, Espécie (gato ou cachorro), Tipo de Ração, Hábitos, e Condições de Chegada.  
- **Veterinário**: Representa os profissionais veterinários. Atributos principais: CRMV, Nome, e Especialização.  
- **Atendimento**: Representa cada sessão de atendimento entre o cliente, animal, e o veterinário. Atributos principais: ID, Data, e Receita gerada.  
- **Ficha**: Detalha informações coletadas sobre o animal durante o atendimento. Atributos principais: ID, Observações, e Resultado da Entrevista.  
- **Prontuário**: Registra observações médicas e exames realizados nos animais. Atributos principais: ID e Observações de Exame.  
- **PetShop**: Representa os serviços gerais da clínica e pet shop. Atributo principal: Serviços oferecidos.  
- **Receita**: Prescrições médicas geradas para os animais. Atributos principais: ID e Descrição.  
- **Agendamento**: Representa a marcação de horários para atendimentos futuros. Atributos principais: ID e Horário.  
- **Atendente**: Representa os profissionais responsáveis por organizar a agenda e recepcionar os clientes. Atributos principais: ID e Nome.  
- **Cirurgia**: Serviços especializados oferecidos pelo pet shop. Atributo principal: Tipo.  
- **Serviço**: Detalha os serviços gerais disponíveis, como banho, tosa, fisioterapia, nutrição, etc. Atributos principais: ID e Descrição.  
- **HotelParaAnimais**: Representa o serviço de hospedagem oferecido para animais. Atributo principal: Descrição.  
- **Comunicação**: Canal de contato entre os clientes e profissionais.  

[Voltar ao Início](#sandyhonda)

## 4.2. Relacionamentos

1. **Cliente - Animal**: Um cliente pode possuir vários animais, mas cada animal pertence a apenas um cliente.  
2. **Cliente - Atendimento**: Um cliente realiza vários atendimentos.  
3. **Animal - Atendimento**: Um animal pode ser atendido várias vezes.  
4. **Veterinário - Atendimento**: Um veterinário realiza vários atendimentos, podendo atender diferentes animais.  
5. **Atendimento - Receita**: Um atendimento pode gerar uma ou mais receitas para um animal.  
6. **Animal - Ficha**: Cada animal possui uma ficha detalhando suas condições e histórico.  
7. **Ficha - Prontuário**: A ficha está associada a um prontuário com observações adicionais.  
8. **PetShop - Serviço**: O pet shop oferece diversos serviços aos clientes.  
9. **PetShop - HotelParaAnimais**: O pet shop oferece hospedagem para animais.  
10. **Cliente - PetShop**: O cliente tem acesso aos serviços e funcionalidades oferecidos pelo pet shop.  
11. **Atendente - Agendamento**: O atendente realiza agendamentos e organiza a agenda do dia.  
12. **Atendimento - Agendamento**: O atendimento é agendado previamente.  
13. **PetShop - Comunicação**: O pet shop oferece um canal de comunicação direta para clientes.  

### 4.2.1 **Relacionamentos Detalhados**  

1. **Cliente - Animal**:  
   - Tipo: 1:N (Um cliente possui muitos animais).  
   - Explicação: Cada cliente cadastra os animais que possui para os atendimentos e serviços.  

2. **Animal - Atendimento**:  
   - Tipo: 1:N (Um animal pode ser atendido várias vezes).  
   - Explicação: Um animal pode receber atendimentos regulares ou esporádicos dependendo de sua condição.  

3. **Veterinário - Atendimento**:  
   - Tipo: N:N (Vários veterinários podem atender o mesmo animal e um veterinário pode atender vários animais).  
   - Explicação: Um atendimento pode envolver múltiplos veterinários, dependendo da complexidade.  

4. **Atendimento - Receita**:  
   - Tipo: 1:1 (Cada atendimento gera no máximo uma receita).  
   - Explicação: O atendimento veterinário pode levar à emissão de uma receita para medicamentos ou tratamentos específicos.  

5. **Animal - Ficha**:  
   - Tipo: 1:1 (Cada animal tem sua própria ficha).  
   - Explicação: A ficha contém informações únicas e atualizadas sobre o histórico do animal.  

6. **Ficha - Prontuário**:  
   - Tipo: 1:1 (Cada ficha está associada a um único prontuário).  
   - Explicação: O prontuário complementa as informações médicas registradas na ficha.  

7. **Cliente - Atendimento**:  
   - Tipo: 1:N (Um cliente realiza muitos atendimentos).  
   - Explicação: Clientes podem agendar e participar de atendimentos conforme necessário.  

8. **Atendente - Agendamento**:  
   - Tipo: 1:N (Um atendente organiza muitos agendamentos).  
   - Explicação: O atendente verifica a disponibilidade da agenda e realiza as marcações.  

9. **PetShop - Serviço**:  
   - Tipo: 1:N (O pet shop oferece diversos serviços).  
   - Explicação: Serviços como banho, tosa, nutrição, e fisioterapia estão disponíveis para os animais.  

10. **PetShop - HotelParaAnimais**:  
    - Tipo: 1:N (O pet shop pode hospedar muitos animais).  
    - Explicação: O serviço de hospedagem é oferecido como uma opção adicional para os clientes.  

11. **Cliente - PetShop**:  
    - Tipo: 1:N (Um cliente pode contratar vários serviços do pet shop).  
    - Explicação: Os clientes têm acesso a funcionalidades e serviços como visualização de receitas e comunicação com profissionais.  

12. **PetShop - Comunicação**:  
    - Tipo: 1:N (A comunicação atende vários clientes).  
    - Explicação: O pet shop mantém um canal aberto para sanar dúvidas ou fornecer informações.

[Voltar ao Início](#sandyhonda)

## 5. Diagrama de classes

```mermaid

classDiagram
    class Cliente {
        +String nome
        +String telefone
        +String endereco
        +visualizarAnimais()
        +visualizarFichas()
        +visualizarReceitas()
        +fazerCadastro()
    }

    class Animal {
        +String nome
        +String rfid
        +String especie
        +String condicoesChegada
        +String tipoRacao
        +String habitos
        +receberAtendimento()
        +obterProntuario()
        +obterFicha()
    }

    class Veterinario {
        +String nome
        +String especialidade
        +entrevistarDono()
        +examinarAnimal()
        +gerarProntuario()
        +gerarReceita()
    }

    class Ficha {
        +String observacoes
        +registrarObservacoes()
    }

    class Prontuario {
        +String detalhes
        +String receita
        +gerarReceita()
    }

    class Agenda {
        +Date data
        +Time horario
        +String status
        +marcarHorario()
    }

    class Atendente {
        +String nome
        +verificarAgenda()
        +adicionarNaFilaDeEspera()
        +levarAoVeterinario()
    }

    class Servico {
        +String tipo
        +String descricao
        +Float preco
        +executarServico()
    }

    class Comunicacao {
        +String mensagem
        +Date dataEnvio
        +Date dataResposta
        +enviarMensagem()
        +responderMensagem()
    }

    class Hotel {
        +Date checkin
        +Date checkout
        +String detalhes
        +reservarHotel()
    }

    Cliente "1" --o "0..*" Animal : possui
    Cliente "1" --o "0..*" Agenda : marca
    Cliente "1" --o "0..*" Comunicacao : comunica-se

    Animal "1" --o "0..1" Ficha : possui
    Animal "1" --o "0..1" Prontuario : possui
    Animal "1" --o "0..*" Veterinario : é atendido por
    Animal "1" --o "0..*" Agenda : é agendado
    Animal "1" --o "0..*" Hotel : pode ficar hospedado
    Animal "1" --o "0..*" Servico : pode receber

    Ficha "1" --o "1" Prontuario : gera

    Veterinario "1" --o "0..*" Prontuario : cria
    Veterinario "1" --o "0..*" Agenda : agenda

    Atendente "1" --o "0..*" Agenda : gerencia
    Atendente "1" --o "0..*" Cliente : atende

    Servico "0..*" --o "1" Animal : aplica-se a
```

[Voltar ao Início](#sandyhonda)

## 5.1. Descrição das Classes e Relacionamentos

1. **Cliente:**  
   Contém informações sobre os clientes da clínica. Cada cliente pode possuir vários animais e agendar consultas.  
   - Atributos: `idCliente`, `nome`, `telefone`, `email`, `endereço`.  
   - Métodos: `cadastrarCliente()`, `editarCliente()`, `listarAnimais()`, `visualizarHistorico()`.

2. **Animal:**  
   Contém informações detalhadas sobre os animais, como identificação, tipo, hábitos, e condição de chegada.  
   - Atributos: `idAnimal`, `nome`, `tipo` (gato ou cachorro), `condicao`, `tipoRacao`, `habitos`, `RFID`.  
   - Métodos: `cadastrarAnimal()`, `atualizarCondicao()`, `listarConsultas()`.

3. **Atendente:**  
   Representa os funcionários que organizam os atendimentos e gerenciam a fila de espera.  
   - Atributos: `idAtendente`, `nome`, `turno`, `telefone`.  
   - Métodos: `verificarAgenda()`, `inserirFilaEspera()`, `direcionarClienteVeterinario()`.

4. **Veterinario:**  
   Contém informações sobre os veterinários e suas responsabilidades no atendimento.  
   - Atributos: `idVeterinario`, `nome`, `especialidade`, `CRMV`.  
   - Métodos: `realizarEntrevista()`, `examinarAnimal()`, `emitirReceita()`, `registrarProntuario()`.

5. **Consulta:**  
   Representa o atendimento realizado para um animal em uma data específica.  
   - Atributos: `idConsulta`, `data`, `hora`, `idAnimal`, `idVeterinario`, `prontuario`.  
   - Métodos: `agendarConsulta()`, `registrarProntuario()`, `emitirReceita()`.

6. **Prontuario:**  
   Contém o registro médico do animal, incluindo observações do veterinário e recomendações de tratamento.  
   - Atributos: `idProntuario`, `idAnimal`, `data`, `observacoes`.  
   - Métodos: `adicionarObservacao()`, `visualizarProntuario()`.

7. **Receita:**  
   Representa os medicamentos e tratamentos prescritos para o animal após uma consulta.  
   - Atributos: `idReceita`, `idConsulta`, `descricao`, `dataEmissao`.  
   - Métodos: `gerarReceita()`, `visualizarReceita()`.

8. **ServicoPetShop:**  
   Representa serviços adicionais, como banho, tosa, hospedagem, ou fisioterapia.  
   - Atributos: `idServico`, `descricao`, `preco`, `idAnimal`.  
   - Métodos: `agendarServico()`, `listarServicos()`.

9. **Agenda:**  
   Gerencia os horários disponíveis para atendimentos e serviços.  
   - Atributos: `idAgenda`, `data`, `hora`, `disponibilidade`.  
   - Métodos: `verificarDisponibilidade()`, `reservarHorario()`.

10. **Comunicação:**  
    Facilita a troca de mensagens entre os clientes e os profissionais do pet shop.  
    - Atributos: `idMensagem`, `idCliente`, `idVeterinario`, `conteudo`, `data`.  
    - Métodos: `enviarMensagem()`, `visualizarMensagens()`.

[Voltar ao Início](#sandyhonda)

## 5.2. Relacionamentos

- **Cliente ↔ Animal:**  
  - Um cliente pode ter **vários animais**.  
  - Um animal pertence a **um cliente**.  

- **Animal ↔ Veterinario:**  
  - Um animal pode ser atendido por **vários veterinários**.  
  - Um veterinário pode atender **vários animais**.  

- **Animal ↔ Consulta:**  
  - Um animal pode ter **várias consultas**.  
  - Cada consulta é associada a **um animal**.  

- **Consulta ↔ Veterinario:**  
  - Uma consulta é realizada por **um veterinário**.  
  - Um veterinário pode realizar **várias consultas**.  

- **Consulta ↔ Prontuario:**  
  - Cada consulta gera **um prontuário**.  
  - Um prontuário está associado a **uma consulta**.  

- **Consulta ↔ Receita:**  
  - Uma consulta pode gerar **uma ou mais receitas**.  
  - Uma receita está associada a **uma consulta**.  

- **Animal ↔ ServicoPetShop:**  
  - Um animal pode utilizar **vários serviços**.  
  - Cada serviço está associado a **um animal**.  

- **Cliente ↔ Comunicação:**  
  - Um cliente pode trocar **várias mensagens** com profissionais.  
  - Cada mensagem pertence a **um cliente**.  

- **Veterinario ↔ Comunicação:**  
  - Um veterinário pode receber **várias mensagens**.  
  - Cada mensagem pode ser enviada a **um veterinário**.  

- **Agenda ↔ Consulta/Servicos:**  
  - A agenda gerencia os horários disponíveis para consultas e serviços.  
  - Uma consulta ou serviço utiliza **um horário específico** da agenda.

[Voltar ao Início](#sandyhonda)

## 6. Casos de uso

## 6.1 Casos de uso

![Casos de uso](imagens/Diagrama_casos_de_uso.png)

[Voltar ao Início](#sandyhonda)

## 6.2 Histórias de usuario

### 1. Marcar Animais com RFID

**Como um** veterinário  
**Eu quero** marcar os animais com um código RFID  
**Para que** eu possa identificá-los rapidamente no sistema e garantir o controle sobre seu histórico.

### 2. Atender Apenas Gatos e Cachorros

**Como uma** clínica veterinária  
**Eu quero** limitar o atendimento a gatos e cachorros  
**Para que** possamos focar nosso atendimento especializado nessas espécies.

### 3. Cadastro de Clientes e Animais

**Como um** cliente  
**Eu quero** fazer um cadastro no sistema para mim e para meus animais  
**Para que** eu possa ter meus dados e os dados dos meus animais registrados no sistema.

### 4. Informar Condições do Animal

**Como um** cliente  
**Eu quero** informar as condições nas quais meu animal chegou à clínica  
**Para que** os veterinários possam ter essa informação no atendimento.

### 5. Informar Tipo de Ração

**Como um** cliente  
**Eu quero** informar o tipo de ração que meu animal consome  
**Para que** o veterinário possa ajustar o tratamento ou fazer recomendações adequadas.

### 6. Informar Hábitos do Animal

**Como um** cliente  
**Eu quero** informar os hábitos do meu animal  
**Para que** o veterinário tenha mais informações para realizar o diagnóstico.

### 7. Atendimentos com Mais de Um Veterinário

**Como um** sistema  
**Eu quero** permitir que mais de um veterinário atenda o mesmo animal  
**Para que** seja possível realizar atendimentos colaborativos e mais completos.

### 8. Agenda do Dia para Atendimentos

**Como um** cliente  
**Eu quero** que meu animal seja atendido de acordo com uma agenda do dia  
**Para que** eu possa planejar melhor meu tempo e o atendimento do meu animal.

### 9. Ficha e Prontuário para Cada Animal

**Como um** veterinário  
**Eu quero** criar uma ficha e um prontuário para cada animal atendido  
**Para que** eu possa registrar o histórico médico e o tratamento do animal.

### 10. Marcar Horários Futuramente

**Como um** cliente  
**Eu quero** poder agendar atendimentos futuros para meu animal  
**Para que** eu possa garantir um horário conveniente para o tratamento.

### 11. Atendimento Gera Receita

**Como um** veterinário  
**Eu quero** gerar uma receita médica ao finalizar o atendimento  
**Para que** o cliente saiba qual medicação ou tratamento seu animal precisa seguir.

### 12. Atendimento Inicial pelo Atendente

**Como um** cliente  
**Eu quero** ser atendido inicialmente por um atendente ao chegar à clínica  
**Para que** meu caso seja direcionado adequadamente.

### 13. Verificar Agenda de Veterinários

**Como um** atendente  
**Eu quero** verificar se há veterinários disponíveis na agenda  
**Para que** eu possa confirmar se o atendimento pode ser realizado.

### 14. Colocar na Fila de Espera

**Como um** atendente  
**Eu quero** colocar o cliente e seu animal na fila de espera  
**Para que** eles aguardem caso não haja veterinário disponível no momento.

### 15. Levar Cliente ao Veterinário

**Como um** atendente  
**Eu quero** encaminhar o cliente e seu animal ao veterinário  
**Para que** o atendimento possa ser realizado após o cadastro.

### 16. Realizar Entrevista com o Dono

**Como um** veterinário  
**Eu quero** realizar uma entrevista com o dono do animal  
**Para que** eu possa coletar todas as informações necessárias para o atendimento.

### 17. Registro do Resultado da Entrevista

**Como um** veterinário  
**Eu quero** registrar o resultado da entrevista com o dono em um formulário  
**Para que** essas informações estejam disponíveis no prontuário.

### 18. Anotar Observações no Prontuário

**Como um** veterinário  
**Eu quero** anotar minhas observações no prontuário do animal  
**Para que** o histórico de saúde do animal esteja sempre atualizado.

### 19. Receitar Medicamentos

**Como um** veterinário  
**Eu quero** prescrever uma receita médica para o animal  
**Para que** o dono saiba qual tratamento seguir.

### 20. Serviços de Banho e Tosa

**Como um** cliente  
**Eu quero** utilizar os serviços de banho e tosa oferecidos pela clínica  
**Para que** meu animal esteja sempre bem cuidado.

### 21. Realização de Cirurgias, Injeções e Curativos

**Como um** veterinário  
**Eu quero** realizar cirurgias, injeções e curativos  
**Para que** o animal receba o tratamento necessário.

### 22. Serviço de Pintura de Cachorro

**Como um** cliente  
**Eu quero** escolher o serviço de pintura de cachorro  
**Para que** meu animal possa receber um tratamento estético diferenciado.

### 23. Serviços de Fisioterapia e Nutrição

**Como um** cliente  
**Eu quero** utilizar os serviços de fisioterapia e nutrição oferecidos pela clínica  
**Para que** meu animal tenha uma melhor qualidade de vida.

### 24. Visualizar Animais e Fichas

**Como um** cliente  
**Eu quero** visualizar meus animais e suas fichas de atendimento  
**Para que** eu possa acompanhar o histórico médico de cada um deles.

### 25. Visualizar Receitas

**Como um** cliente  
**Eu quero** visualizar as receitas médicas dos meus animais  
**Para que** eu saiba quais medicamentos seguir.

### 26. Auxílio para Animais com Sobrepeso

**Como um** cliente  
**Eu quero** utilizar os serviços oferecidos para animais com sobrepeso  
**Para que** meu animal receba o suporte necessário para sua saúde.

### 27. Acesso ao Receituário dos Animais

**Como um** cliente  
**Eu quero** ter acesso ao receituário dos meus animais  
**Para que** eu possa consultar todas as receitas emitidas.

### 28. Comunicação Direta com Profissionais

**Como um** cliente  
**Eu quero** ter um meio de comunicação direta com os profissionais da clínica  
**Para que** eu possa sanar dúvidas sobre meu animal a qualquer momento.

### 29. Serviço de Hotel para Animais

**Como um** cliente  
**Eu quero** utilizar o serviço de hotel para animais oferecido pela pet shop  
**Para que** meu animal tenha um lugar seguro para ficar enquanto eu estiver fora.

[Voltar ao Início](#sandyhonda)

## 7. Diagrama de componentes

![alt text](imagens/Diagrama_de_componente.png)

[Voltar ao Início](#sandyhonda)

## 8. Diagrama de implantação

![alt text](imagens/Diagrama_de_implantação.png)

[Voltar ao Início](#sandyhonda)

## 9. Diagramas C4

## 9.1. Diagrama de contexto

```mermaid
graph TD
    Client[Cliente] -->|Acessa| WebApp[Aplicação Web/Cliente]
    WebApp -->|Envia Dados| Server[Servidor Backend]
    Server -->|Armazena e Recupera| DB[Banco de Dados]
    Server -->|Envia Mensagens| RFID[Leitor RFID]
    Server -->|Envia Notificações| Notif[Serviço de Notificação]
    Server -->|Comunica com| Vet[Veterinário]
    Server -->|Comunica com| Atendente[Atendente]
```

## 9.2. Diagrama de container

```mermaid
graph TD
    subgraph Cliente
        Browser[Browser Aplicativo Web]
    end

    subgraph Servidor
        Backend[Backend Spring Boot]
        Frontend[Frontend Vue.js]
        API[API REST]
        DBService[Banco de Dados MySQL]
        Notification[Serviço de Notificações]
        RFIDService[Integração com Leitor RFID]
    end

    Browser --> Frontend
    Frontend --> API
    API --> Backend
    Backend --> DBService
    Backend --> Notification
    Backend --> RFIDService

```

## 9.3. Diagrama de componente

```mermaid
graph TD
    API[API REST] -->|Consulta/Gravação| ClientController[Controlador Cliente]
    API -->|Consulta/Gravação| AnimalController[Controlador Animal]
    API -->|Consulta| ScheduleController[Controlador Agenda]
    API -->|Comunica com| RFIDService[Serviço de RFID]
    API -->|Comunica com| NotificationService[Serviço de Notificações]
    
    subgraph Backend Spring Boot
        ClientController --> ClientService[Serviço de Cliente]
        AnimalController --> AnimalService[Serviço de Animal]
        ScheduleController --> ScheduleService[Serviço de Agenda]
        ClientService --> DB[Repositório Cliente]
        AnimalService --> DB[Repositório Animal]
        ScheduleService --> DB[Repositório Agenda]
    end

```

## 9.4. Diagrama de código

```mermaid
graph TD
    classDef entity fill:#f9f,stroke:#333,stroke-width:2;

    ClientService --> ClientRepository
    AnimalService --> AnimalRepository
    ScheduleService --> ScheduleRepository

    class ClientRepository,AnimalRepository,ScheduleRepository entity

```

[Voltar ao Início](#sandyhonda)

## 10. Protótipo de telas

### 1. Login

![alt text](imagens/login.png)

### 1. Tela Inicial

![alt text](imagens/inicial.jpeg)

### 2. Agenda

![!\[alt text\]](imagens/agenda.jpeg)

### 3. Editar Agenda

![!\[alt text\]](imagens/editar_agenda.jpeg)

### 4. Detalhes Agenda

![!\[alt text\]](imagens/detalhes_agenda.jpeg)

### 5. Animal

![!\[alt text\]](imagens/animal.jpeg)

### 6. Editar Animal

![!\[alt text\]](imagens/editar_animal.jpeg)

### 7. Detalhes Animal

![!\[alt text\]](imagens/detalhes_animal.jpeg)

### 8. Atentendente

![!\[alt text\]](imagens/atentendente.jpeg)

### 9. Editar Atendente

![!\[alt text\]](imagens/editar_atendente.jpeg)

### 10. Detalhes Atendente

![!\[alt text\]](imagens/detalhes_atendente.jpeg)

### 11. Cliente

![!\[alt text\]](imagens/cliente.jpeg)

### 12. Editar Cliente

![!\[alt text\]](imagens/cliente_editar.jpeg)

### 13. Detalhes Cliente

![!\[alt text\]](imagens/detalhes_cliente.jpeg)

### 14. Comunicação

![!\[alt text\]](imagens/comunicação.jpeg)

### 15. Editar Comunicação

![!\[alt text\]](imagens/editar_comunicação.jpeg)

### 16. Detalhes Comunicação

![!\[alt text\]](imagens/detalhes_comunicação.jpeg)

### 17. Ficha

![!\[alt text\]](imagens/ficha.jpeg)

### 18. Editar Ficha

![!\[alt text\]](imagens/editar_ficha.jpeg)

### 19. Detalhes Ficha

![!\[alt text\]](imagens/detalhes_ficha.jpeg)

### 20. Hotel

![!\[alt text\]](imagens/hotel.jpeg)

### 21. Editar Hotel

![!\[alt text\]](imagens/editar_hotel.jpeg)

### 22. Detalhe Hotel

![!\[alt text\]](imagens/detalhe_hotel.jpeg)

### 23. Prontuario

![!\[alt text\]](imagens/prontuario.jpeg)

### 24. Editar Pronturario

![!\[alt text\]](imagens/editar_pronturario.jpeg)

### 25. Detalhe Prontuario

![!\[alt text\]](imagens/detalhe_prontuario.jpeg)

### 26. Serviço

![!\[alt text\]](imagens/serviço.jpeg)

### 27. Editar Serviço

![!\[alt text\]](imagens/editar_serviço.jpeg)

### 28. Detalhe Serviço

![!\[alt text\]](imagens/detalhe_serviço.jpeg)

### 29. Veterinario

![!\[alt text\]](imagens/veterinario.jpeg)

### 30. Editar Veterinario

![!\[alt text\]](imagens/editar_veterinario.jpeg)

### 31. Detalhes Veterinario

![!\[alt text\]](imagens/detalhes_veterinario.jpeg)

### 32. Atendimento

![!\[alt text\]](imagens/atendimento.jpeg)

### 33. Editar Atendimento

![!\[alt text\]](imagens/editar_atendimento.jpeg)

### 34. Detalhes Atendimento

![!\[alt text\]](imagens/detalhes_atendimento.jpeg)

### 35. Grafico Barra

![!\[alt text\]](imagens/grafico_barra.jpeg)

### 36. Grafico Pizza

![!\[alt text\]](imagens/grafico_pizza.jpeg)

### 37. Grafico Linha

![!\[alt text\]](imagens/grafico_linha.jpeg)

### 38. Dashboard

![alt text](imagens/dashboard.jpeg)

[Voltar ao Início](#sandyhonda)

## 11. Diagrama de navegação de telas

![Diagrama de Telas](imagens/DiagramaTelas.png)

[Voltar ao Início](#sandyhonda)

## 12. Pilha tecnologica

```mermaid

graph TD;
    A[Pilha Tecnológica] --> B[Frontend]
    A --> C[Backend]
    A --> D[Banco de Dados]
    A --> E[Servidor Web]
    A --> F[Segurança]
    A --> G[Ambiente de Desenvolvimento]
    
    %% Frontend Details
    B --> B1[HTML/CSS/JavaScript]
    B --> B2[Scriptcase]
    B --> B3[Formulários Dinâmicos de Cadastro e Atendimento]
    B --> B4[Visualização de Prontuários e Fichas]
    B --> B5[Gestão de Agendas e Fila de Espera]
    
    %% Backend Details
    C --> C1[PHP]
    C --> C2[Framework Laravel]
    C --> C3[Componentes do Sistema]
    C1 --> C4[Gerenciamento de Sessões e Usuários]
    C1 --> C5[Validação de Dados]
    C3 --> C6[Cadastro de Cliente e Animal]
    C3 --> C7[Atendimentos e Prontuários]
    C3 --> C8[Controle de Agendas e Fila de Espera]
    C3 --> C9[Serviços do Pet Shop]
    C3 --> C10[Comunicação com RFID]

    %% Database Details
    D --> D1[MySQL]
    D --> D2[phpMyAdmin ou MySQL Server]
    D --> D3[Tabelas: Clientes, Animais, Atendimentos, Prontuários, Veterinários, Serviços]
    D --> D4[Relatórios de Atendimento e Receita]
    
    %% Web Server Details
    E --> E1[Apache HTTP Server]
    E --> E2[XAMPP, WAMP ou MAMP]
    E --> E3[Gerenciamento de Hospedagem Local e Nuvem]

    %% Security Details
    F --> F1[SSL e TLS]
    F --> F2[Let’s Encrypt]
    F --> F3[Autenticação Baseada em Token JWT]
    F --> F4[Controle de Acesso por Nível de Usuário]
    
    %% Development Environment Details
    G --> G1[Visual Studio Code, Sublime Text ou PHPStorm]
    G --> G2[Git para Controle de Versão]
    G --> G3[GitHub, GitLab ou Bitbucket para Repositórios]
    G --> G4[Composer para Gerenciamento de Dependências]
    G --> G5[PHPUnit para Testes Automatizados]
    G --> G6[Docker para Contêineres]

```

[Voltar ao Início](#sandyhonda)

## 13. Requisitos de sistemas

## 13.1. Requisitos lado do Cliente

### Sistema Operacional

- **Compatibilidade**:
  - Windows 10 ou superior.
  - macOS Catalina ou superior.
  - Linux (Ubuntu 20.04 ou superior).
  - Android 10 ou superior.
  - iOS 13 ou superior.

### Navegador

- **Requisitos mínimos**:
  - Google Chrome (v90 ou superior).
  - Mozilla Firefox (v88 ou superior).
  - Microsoft Edge (v90 ou superior).
  - Safari (v14 ou superior).
- **Configuração obrigatória**:
  - Suporte a JavaScript habilitado.
  - Cookies habilitados para autenticação e sessão.

### Acesso à Internet

- **Largura de banda mínima**:
  - Conexão estável de 1 Mbps para navegação básica.
  - 5 Mbps recomendados para carregamento rápido de fichas e formulários.
  - Acesso offline restrito a visualização de informações previamente sincronizadas.

### Recursos de Hardware

- **PC ou Mobile**:
  - Processador de 2 GHz (dual-core) ou superior.
  - Memória RAM de 4 GB (mínimo), recomendados 8 GB.
  - Armazenamento: 100 MB livres para cache do navegador e dados locais.
- **Resolução de tela**:
  - Mínima: 1280x720 (HD).
  - Recomendada: 1920x1080 (Full HD).
  - Compatibilidade responsiva com telas menores para dispositivos móveis.

### Permissões e Configurações de Segurança

- **Permissões**:
  - Acesso ao sistema de notificações para lembretes de agenda.
  - Localização opcional para serviços de busca próximos (ex.: hotel para animais).
  - Leitura de RFID opcional para interação com tags físicas.
- **Configurações de segurança**:
  - Certificado SSL/TLS para conexões seguras.
  - Antivírus atualizado recomendado.
  - Configuração mínima de firewall para permitir comunicação com o servidor.

### Forma de Autenticação

- **Métodos suportados**:
  - Autenticação por e-mail e senha.
  - Autenticação baseada em tokens (JWT).
  - Suporte a autenticação em duas etapas (2FA) via aplicativo ou SMS.
- **Sessões**:
  - Tempo limite de sessão inativa configurável (padrão: 15 minutos).
  - Possibilidade de salvar credenciais de login com segurança no navegador.

[Voltar ao Início](#sandyhonda)

## 13.2. Requisitos lado do Servidor

### Tipo de Sistema Operacional

- **Opções Suportadas**:
  - **Linux**: Ubuntu Server 20.04 ou superior, CentOS 8, ou Debian 10.
  - **Windows**: Windows Server 2019 ou superior.
- Justificativa: Compatibilidade com servidores web amplamente usados como Apache e Nginx (Linux) e IIS (Windows).

### **Tipo de Processador**

- **Mínimo**: Processador de 2 núcleos, 2.5 GHz.
- **Recomendado**: Processador de 4 núcleos, 3.0 GHz ou superior (Intel Xeon ou AMD EPYC).

### **Memória RAM**

- **Mínimo**: 4 GB para ambiente de desenvolvimento ou teste.
- **Recomendado**: 8 GB para ambiente de produção.
- Justificativa: Suporte a múltiplas conexões simultâneas e serviços de banco de dados.

### **Armazenamento**

- **Mínimo**: 50 GB para códigos, logs, e base de dados básica.
- **Recomendado**: 100 GB com escalabilidade para atender dados de usuários e prontuários.
- **Tecnologia recomendada**: SSD para desempenho de leitura/escrita otimizado.

### **Rede**

- **Largura de Banda**:
  - **Mínima**: 10 Mbps para pequenos acessos.
  - **Recomendada**: 50 Mbps para múltiplos usuários simultâneos.
- **Endereço IP ou Nome de Domínio**:
  - IP fixo recomendado.
  - Nome de domínio registrado para facilitar o acesso ao sistema (ex.: `clinica.pet+.com`).

### **Segurança**

- **Certificados SSL/TLS**:
  - Certificados obrigatórios para todas as comunicações.
  - Suporte a Let’s Encrypt ou certificados comerciais.
- **Firewall**:
  - Configuração para bloquear portas desnecessárias.
  - Regras personalizadas para proteger contra ataques DDoS e acessos não autorizados.
- **Autenticação e Controle**:
  - Integração com serviços de autenticação baseados em OAuth ou JWT.
  - Registro e auditoria de acessos no sistema.

### **Capacidade de Escalar o Ambiente**

- **Escalabilidade Horizontal e Vertical**:
  - Suporte para adicionar nós adicionais ao cluster.
  - Capacidade de upgrade de recursos (CPU, memória, armazenamento) no ambiente cloud ou local.
- **Conexões Simultâneas**:
  - Capacidade inicial para 50 conexões simultâneas com suporte a expansão.

### **Serviços, Servidor e Mídia para Backups**

- **Serviços**:
  - Backup diário automático de banco de dados e arquivos.
  - Ferramentas de monitoramento, como Zabbix ou Grafana.
- **Servidor de Backup**:
  - Backup remoto (AWS S3, Google Cloud Storage ou servidor físico dedicado).
- **Política de Retenção**:
  - Retenção de backups por 30 dias.
  - Recuperação de dados em menos de 1 hora.

### **Requisitos Adicionais**

1. **Servidor Web**:
   - Apache ou Nginx (Linux).
   - IIS (Windows).
2. **Banco de Dados**:
   - MySQL 8.0 ou PostgreSQL 12.
3. **Gerenciamento de Dependências**:
   - Suporte ao Composer (PHP) para gerenciar bibliotecas e frameworks.
4. **Ambiente Virtualizado (opcional)**:
   - Docker ou Kubernetes para containers.
5. **Integração com Hardware RFID**:
   - APIs ou drivers configurados para comunicação com leitores de RFID.

[Voltar ao Início](#sandyhonda)

## 14. Considerações sobre segurança

## 14.1. Lado do Cliente

Conexões Seguras

- **Uso de HTTPS**:
  - Todas as conexões entre o cliente e o servidor devem ser protegidas por HTTPS para evitar interceptação de dados sensíveis.
  
**Validações no Navegador**

- **Compatibilidade**:
  - Garantir que o sistema funcione apenas em navegadores atualizados e confiáveis (ex.: Chrome, Firefox, Edge, Safari).
- **Desativação de Scripts Maliciosos**:
  - Implementar Content Security Policy (CSP) para prevenir ataques como Cross-Site Scripting (XSS).

 Validações de Páginas e Conteúdo

- **Validações do Lado Cliente**:
  - Usar JavaScript para validação de campos obrigatórios antes do envio de formulários.
  - Exibir mensagens claras para erros de preenchimento.
- **Validações do Lado Servidor**:
  - Complementar as validações feitas no cliente, evitando que dados corrompidos ou maliciosos sejam enviados.

**Segurança de Autenticação**

1. **Regras de Senha**:
   - Mínimo de 8 caracteres.
   - Uso obrigatório de:
     - 1 letra maiúscula.
     - 1 número.
     - 1 caractere especial.
   - Proibição de senhas comuns ou fáceis de adivinhar.
2. **Autenticação em 2 Fatores (2FA)**:
   - Implementar autenticação por meio de código enviado por e-mail ou SMS.
3. **Recuperação de Senha**:
   - Envio de um link ou código de redefinição para o e-mail cadastrado.
   - O link de redefinição deve expirar após 10 minutos.
4. **Bloqueio de Conta**:
   - Bloquear temporariamente a conta após 5 tentativas consecutivas de login mal sucedido.

### Validação por CAPTCHA

- **Implementação**:
  - Inserir CAPTCHA em formulários de login, cadastro e redefinição de senha.
  - Usar reCAPTCHA ou outra solução para evitar bots.

**Antivírus**

- **Recomendações ao Usuário**:
  - Orientar clientes a utilizarem softwares antivírus atualizados para protegerem seus dispositivos.
  - Exibir notificações sobre boas práticas de segurança na página de login e nas seções principais.

**Proteção contra Ameaças**

1. **Prevenção de Sessões Não Autorizadas**:
   - Finalizar automaticamente a sessão do cliente após 15 minutos de inatividade.
2. **Armazenamento Seguro no Navegador**:
   - Nunca armazenar senhas no LocalStorage ou SessionStorage.
   - Utilizar cookies com flag `HttpOnly` e `Secure`.

### Comunicação Segura

- **Chat com Profissionais**:
  - Todas as mensagens trocadas entre clientes e profissionais devem ser criptografadas.

**Exemplo de Aplicação em Regras de Negócio**

1. **Cadastro de Cliente e Animal**:
   - Validação completa dos dados no formulário.
   - Captcha para evitar bots.
   - Senhas com as regras acima.
2. **Consulta de Fichas e Receitas**:
   - Exigir autenticação do cliente e, se necessário, 2FA.
3. **Comunicação Direta**:
   - Garantir criptografia ponta-a-ponta.
   - Verificar se a identidade do cliente está autenticada antes de enviar mensagens.
4. **Agendamento e Serviços**:
   - Implementar confirmação via e-mail/SMS para horários agendados.

[Voltar ao Início](#sandyhonda)

## 14.2. Lado Servidor

### **Configuração de Pastas**

1. **Separação de Pastas**:
   - Configurar pastas separadas para armazenar:
     - Código do sistema.
     - Dados de usuários (com restrição de acesso).
     - Logs de atividades do sistema.
   - As pastas de dados sensíveis devem ter permissões restritas no servidor (ex.: apenas leitura para serviços específicos).
2. **Permissões de Arquivos**:
   - Implementar política de permissões no Linux:
     - Usuários sem privilégios não podem acessar pastas críticas.
     - Garantir que apenas o administrador do sistema acesse arquivos de configuração.

#### **Verificação de Dados de Entrada**

1. **Filtragem de Dados**:
   - Validar todas as entradas recebidas para prevenir ataques como SQL Injection e XSS.
   - Utilizar prepared statements para interações com o banco de dados.
2. **Sanitização de Dados**:
   - Remover caracteres maliciosos antes de salvar informações.
3. **Controle de Tamanho de Dados**:
   - Limitar a quantidade de caracteres em campos de entrada, como descrições de hábitos dos animais.

#### **Gerenciamento de Atualizações**

1. **Atualizações do Sistema**:
   - Manter o sistema operacional e os pacotes de software atualizados.
   - Utilizar um cronograma para checar atualizações semanalmente.
2. **Teste de Atualizações**:
   - Atualizações devem ser testadas em um ambiente de homologação antes da aplicação no servidor de produção.

#### **Hospedagem Segura**

1. **Firewall e Monitoramento**:
   - Configurar firewall para bloquear acessos não autorizados.
   - Monitorar tráfego suspeito e alertar administradores.
2. **Ambiente Isolado**:
   - Usar contêineres ou máquinas virtuais para separar serviços críticos, como o banco de dados.
3. **Proteção de Credenciais**:
   - Armazenar senhas e chaves de acesso usando ferramentas como **HashiCorp Vault**.

#### **Uso de Certificados no Servidor**

1. **SSL/TLS**:
   - Garantir que todo o tráfego entre o cliente e o servidor esteja criptografado.
2. **Certificados Atualizados**:
   - Certificados SSL devem ser renovados automaticamente antes do vencimento.

#### **Sistema de Monitoramento e Alertas**

1. **Logs de Sistema**:
   - Monitorar eventos do sistema em tempo real.
   - Gerar logs para autenticações, tentativas de acesso não autorizadas e falhas de sistema.
2. **Alertas Automatizados**:
   - Configurar alertas para eventos críticos, como falha no backup ou ataque DDoS.
3. **Monitoramento de Performance**:
   - Verificar utilização de CPU, memória e largura de banda.

#### **Sistema Automatizado de Backup**

1. **Backup Regular**:
   - Implementar a seguinte política:
     - Backup completo mensal e quinzenal.
     - Backup incremental diário ao final do expediente.
2. **Localização do Backup**:
   - Armazenar backups em um local seguro, com redundância.
   - Realizar backup na nuvem e localmente.
3. **Restauração de Backup**:
   - Testar periodicamente os backups para verificar integridade e garantir restauração confiável.

#### **Serviços Gerando Logs**

1. **Rastreamento de Atividades**:
   - Log de acessos, ações de usuários e alterações de dados sensíveis.
2. **Gerenciamento de Logs**:
   - Utilizar ferramentas como **ELK Stack (ElasticSearch, Logstash e Kibana)** para análise e armazenamento de logs.
3. **Retenção de Logs**:
   - Manter logs por pelo menos 6 meses, seguindo normas de compliance.

[Voltar ao Início](#sandyhonda)

## 15. Manutenção, instalação e novas funcionalidades

## 15.1. Instalando no servidor

**1. Configuração Inicial do Servidor**

- **Sistema Operacional**:
  - Utilizar uma distribuição Linux (preferencialmente Ubuntu Server LTS ou CentOS) por sua estabilidade e suporte.
- **Ambiente Web**:
  - Instalar um servidor web como **Apache** ou **Nginx**.
  - Configurar suporte para HTTPS com **certificados SSL/TLS** válidos (Let’s Encrypt ou certificados comerciais).
- **Linguagem e Frameworks**:
  - Instalar e configurar a linguagem de programação usada no software (ex.: PHP 8+, Node.js, Python).
  - Configurar os frameworks necessários para a aplicação (Laravel, Django, etc.).
- **Banco de Dados**:
  - Instalar e configurar um servidor de banco de dados (ex.: MySQL 8+, PostgreSQL).
  - Criar tabelas específicas para suportar as regras de negócio, como:
    - Cadastro de clientes.
    - Registro de animais e fichas médicas.
    - Agendamentos e receitas.
- **Controle de Acesso**:
  - Configurar chaves SSH para acesso remoto.
  - Criar usuários específicos para manutenção e operação do servidor com permissões mínimas.

---

### **2. Requisitos de Infraestrutura**

- **Hardware**:
  - **Processador**: Pelo menos 4 núcleos para suportar múltiplos acessos simultâneos.
  - **Memória RAM**: Mínimo de 8 GB para desempenho ideal.
  - **Armazenamento**:
    - SSD de 500 GB para o sistema operacional, software e banco de dados.
    - Configuração adicional para backups.
- **Rede**:
  - Conexão de banda larga de alta velocidade.
  - Endereço IP fixo e configuração de DNS para acesso externo.
- **Segurança**:
  - Configurar um firewall para permitir apenas portas necessárias (ex.: 443 para HTTPS, 22 para SSH).
  - Instalar software de segurança como **Fail2Ban** e **iptables** para prevenir ataques.
  - Garantir a instalação de um sistema de detecção de intrusão (IDS).

---

#### **3. Configuração de Funcionalidades Específicas**

- **Marcar Animais com RFID**:
  - Configurar o servidor para integrar dispositivos RFID via API ou banco de dados.
  - Certificar-se de que o middleware de integração esteja funcionando corretamente.
- **Cadastro de Clientes e Animais**:
  - Garantir que o sistema web permita validação de entradas e criptografia de dados no envio e armazenamento.
- **Gestão de Agendamentos**:
  - Configurar um serviço de tarefas agendadas (ex.: **cron** ou **scheduler**) para notificações e gerenciamento de agendas.
  - Criar tabelas no banco de dados para registro de agendamentos, status e notificações.
- **Ficha e Prontuário dos Animais**:
  - Implementar um repositório dedicado no banco de dados para armazenar dados sensíveis de forma segura e organizada.
  - Garantir acesso controlado apenas por usuários autorizados.
- **Gerar Receitas e Relatórios**:
  - Configurar serviços para gerar documentos (PDFs) a partir do sistema.
  - Certificar que o servidor tenha bibliotecas instaladas para manipulação de arquivos (ex.: **FPDF**, **wkhtmltopdf**).

---

#### **4. Monitoramento e Logs**

- **Monitoramento do Servidor**:
  - Instalar ferramentas como **Prometheus** e **Grafana** para monitorar CPU, RAM, espaço em disco e tráfego de rede.
- **Logs**:
  - Configurar logs detalhados para:
    - Acessos ao sistema.
    - Alterações em dados sensíveis.
    - Falhas no servidor.
  - Utilizar ferramentas como **ELK Stack** (Elasticsearch, Logstash e Kibana) para análise de logs.

---

#### **5. Gerenciamento de Atualizações**

- **Sistema Operacional e Software**:
  - Configurar atualizações automáticas para segurança.
- **Software do Sistema**:
  - Estabelecer um processo de controle de versão com ferramentas como **Git**.
  - Realizar deploys em ambiente de homologação antes de enviar para produção.

---

#### **6. Backup e Recuperação**

- **Backup Regular**:
  - Implementar backups incrementais diários e backups completos quinzenais/mensais.
  - Configurar scripts automatizados para armazenar backups em local seguro (ex.: Amazon S3, Google Drive).
- **Testes de Restauração**:
  - Realizar testes regulares para garantir que os backups podem ser restaurados sem perda de dados.

---

#### **7. Configuração de Serviços Complementares**

- **Notificações e Comunicação**:
  - Configurar envio de e-mails para agendamentos, lembretes e comunicações via SMTP seguro.
  - Integrar API de mensagens (ex.: WhatsApp ou SMS) para interações rápidas.
- **Acesso ao Receituário**:
  - Criar um portal seguro e acessível para clientes visualizarem receitas e fichas.
- **Comunicação Direta**:
  - Configurar serviços de chat ou videoconferência para suporte entre clientes e veterinários.

---

#### **8. Teste e Homologação**

- Realizar testes de carga para garantir que o sistema pode atender múltiplas conexões simultâneas.
- Validar a funcionalidade de todas as regras de negócio antes de liberar o ambiente para produção.

---

#### **9. Escalabilidade**

- Configurar o servidor para escalar horizontalmente (adicionando novos servidores) ou verticalmente (aumentando os recursos).
- Utilizar serviços como **Docker** para containerizar a aplicação e facilitar a replicação.

[Voltar ao Início](#sandyhonda)

## 15.2. Manutenção

### **1. Manutenção Corretiva**

Correção de erros e falhas identificadas no sistema, seja durante sua operação ou por relatos de usuários.

#### **Processo de Manutenção**

1. **Identificação do Problema**:
   - Monitorar logs do sistema para identificar erros críticos.
   - Receber relatórios de falhas dos usuários através de um sistema de ticket ou formulário.
2. **Análise**:
   - Determinar a causa raiz do problema (código, configuração ou banco de dados).
   - Classificar o erro:
     - **Crítico**: Impacta operações essenciais (ex.: sistema indisponível).
     - **Moderado**: Diminui o desempenho ou gera inconsistências.
     - **Leve**: Afeta funcionalidades não essenciais (ex.: interface ou texto incorreto).
3. **Correção**:
   - Realizar correções no ambiente de desenvolvimento e testar em um ambiente de homologação antes de aplicar em produção.
4. **Testes**:
   - Validar que a correção não gerou novos erros.
   - Executar testes unitários, de integração e de regressão.
5. **Registro**:
   - Documentar o problema e a solução em um banco de conhecimento para futuras referências.

#### **Exemplos de Manutenção Corretiva**

- Corrigir erros de cadastro de animais (ex.: campos não aceitando certos caracteres).
- Resolver falhas em agendamentos que não aparecem na agenda do dia.
- Corrigir erros na geração de prontuários ou receitas.

---

### **2. Manutenção Evolutiva**

Melhorias e atualizações para atender novas necessidades dos usuários ou integrar novas funcionalidades, só será efetuada caso o contrato inclua a adição de novas funcionalidades, caso contrario, será feita somente a manutenção corretiva.

#### **Processo**

1. **Identificação das Necessidades**:
   - Recolher feedback dos usuários através de pesquisas e análises do uso do sistema.
   - Identificar novas demandas do mercado (ex.: integração com dispositivos RFID avançados ou APIs de terceiros).
2. **Planejamento**:
   - Criar um roadmap para implementar melhorias sem interromper as operações.
   - Priorizar funcionalidades com maior impacto para os usuários.
3. **Desenvolvimento**:
   - Implementar as alterações no ambiente de desenvolvimento.
   - Integrar novas funcionalidades ao sistema existente de forma modular.
4. **Testes**:
   - Executar testes funcionais e de usabilidade para garantir que as novas funcionalidades atendem aos requisitos.
5. **Treinamento e Comunicação**:
   - Atualizar a documentação do sistema.
   - Comunicar os usuários sobre as melhorias e, se necessário, oferecer treinamentos.

#### **Exemplos de Manutenção Evolutiva**

- Adicionar suporte a notificações por WhatsApp para lembretes de consulta.
- Implementar gráficos no painel do cliente mostrando histórico de peso do animal.
- Adicionar relatórios financeiros para o administrador do sistema.
- Integrar uma funcionalidade de videoconferência para consultas remotas.

---

### **3. Manutenção Adaptativa**

Ajustes no sistema para garantir sua compatibilidade com novos ambientes tecnológicos ou regulamentações.

#### **Processo**

1. **Monitoramento de Mudanças**:
   - Identificar atualizações de dependências, como versões de frameworks, bibliotecas e banco de dados.
   - Acompanhar alterações em regulamentações legais, como proteção de dados (ex.: LGPD, GDPR).
2. **Planejamento e Testes de Compatibilidade**:
   - Testar o sistema em novos ambientes, como sistemas operacionais atualizados, navegadores modernos e dispositivos móveis recentes.
   - Planejar alterações necessárias para manter compatibilidade.
3. **Implementação**:
   - Atualizar o código ou a configuração do sistema para suportar os novos ambientes.
   - Reconfigurar servidores ou serviços integrados, se necessário.
4. **Validação**:
   - Garantir que o sistema continua operando como esperado em todos os cenários previstos.
5. **Comunicação**:
   - Informar aos usuários sobre possíveis alterações que impactem a experiência, como suporte descontinuado para sistemas antigos.

#### **Exemplos de Manutenção Adaptativa**

- Ajustar o sistema para compatibilidade com uma nova versão do banco de dados MySQL/PostgreSQL.
- Atualizar o sistema para suportar autenticação com novos métodos de dois fatores.
- Configurar o software para rodar em um servidor Linux atualizado (ex.: Ubuntu 24.04).
- Garantir que o sistema atenda a uma nova regulamentação exigindo maior segurança no armazenamento de dados sensíveis.

---

### **Ferramentas de Suporte à Manutenção**

- **Monitoramento**:
  - Ferramentas como **Prometheus**, **Grafana** e **New Relic** para identificar problemas em tempo real.
- **Controle de Versão**:
  - Utilização de **Git** para gerenciar alterações no código.
- **Sistema de Tickets**:
  - Ferramentas como **Jira**, **Trello** ou **Zendesk** para gerenciar solicitações de manutenção.
- **Ambientes Separados**:
  - Garantir que os ambientes de desenvolvimento, homologação e produção estejam isolados para evitar interrupções.

---

### **Política de Manutenção**

- **Ciclos Regulares**:
  - Planejar ciclos mensais de manutenção preventiva para realizar correções e ajustes menores.
- **Resolução de Emergências**:
  - Estabelecer um SLA (Acordo de Nível de Serviço) para resposta a problemas críticos (ex.: resolução em até 4 horas).
- **Avaliações Periódicas**:
  - Realizar auditorias trimestrais para identificar melhorias de desempenho e segurança.

[Voltar ao Início](#sandyhonda)

## 15.3. Novas funionalidades

### **1. Formalização do Pedido**

Todos os pedidos de novas funcionalidades devem ser formalizados e documentados para análise e aprovação.

#### **Regras para Formalização**

1. **Solicitação Estruturada**:
   - O pedido deve conter:
     - **Descrição**: O que a funcionalidade deve fazer.
     - **Motivação**: Por que essa funcionalidade é necessária.
     - **Impacto**: Quem será afetado (clientes, veterinários, atendentes, etc.).
     - **Urgência**: É uma prioridade alta ou algo para melhorias futuras?
2. **Responsável pela Solicitação**:
   - O responsável pela funcionalidade deve ser claramente identificado (ex.: gestor, dev, ou equipe técnica).
3. **Registro**:
   - O pedido deve ser registrado em documento previamente acordado entre ambas as partes e após deve ser colocado um sistema de gerenciamento de tarefas, como **Jira**, **Trello** ou outro equivalente e distribuido as tarefas entre os devs.
4. **Critérios Não-Negociáveis**:
   - O cliente ou solicitante não deve interferir no design ou estética da interface, a menos que esteja relacionado à usabilidade.

---

### 2. A decisão depende de 3 critérios

Antes de iniciar o desenvolvimento, o pedido será analisado sob os seguintes critérios:

#### **a) A Equipe Tem Tempo?**

1. **Análise de Capacidade**:
   - Verificar a carga de trabalho atual da equipe e disponibilidade para o projeto.
   - Utilizar ferramentas de gerenciamento de tarefas para monitorar prazos e entregas.
2. **Priorização**:
   - Definir se a funcionalidade é mais importante do que as tarefas em andamento.
   - Classificar a funcionalidade como **alta**, **média** ou **baixa** prioridade.

#### **b) É Economicamente Viável?**

1. **Análise de Custo-Benefício**:
   - Estimar o custo do desenvolvimento (horas de trabalho, recursos e licenças).
   - Avaliar o impacto financeiro esperado:
     - Geração de receita direta (ex.: serviço premium para clientes).
     - Redução de custos (ex.: automação de tarefas manuais).
2. **Aprovação do Orçamento**:
   - Caso o custo seja elevado, a funcionalidade deve passar por análise e aprovação da gestão.

#### **c) É Tecnologicamente Viável?**

1. **Compatibilidade Técnica**:
   - Verificar se a tecnologia atual do sistema suporta a funcionalidade.
   - Considerar atualizações de infraestrutura ou dependências, se necessário.
2. **Análise de Risco**:
   - Avaliar se a funcionalidade pode comprometer o desempenho ou a segurança do sistema.
3. **Protótipo**:
   - Caso existam dúvidas sobre a viabilidade, criar um protótipo para validação.

---

### **3. Implementação**

Após a aprovação, a funcionalidade será desenvolvida seguindo as melhores práticas de desenvolvimento ágil.

#### **Etapas**

1. **Planejamento**:
   - Criar histórias de usuário (user stories) com requisitos claros.
   - Dividir o trabalho em tarefas menores e alocar para a equipe.
2. **Desenvolvimento**:
   - Seguir padrões de código e boas práticas para garantir a manutenção futura.
3. **Testes**:
   - Realizar testes unitários, funcionais e de integração para garantir que a funcionalidade atenda aos requisitos sem impactar o sistema existente.
4. **Homologação**:
   - Disponibilizar a funcionalidade para revisão em um ambiente de teste.
   - Coletar feedback de usuários e ajustar, se necessário.
5. **Implantação**:
   - Lançar a funcionalidade em produção durante uma janela de manutenção para minimizar interrupções.
6. **Treinamento e Documentação**:
   - Atualizar manuais e fornecer treinamento para os usuários, se necessário.

---

### **Exemplo de Aplicação**

1. **Pedido**: Adicionar a funcionalidade de consulta ao histórico de vacinas do animal.
   - **Motivação**: Facilitar o controle das vacinas pelos clientes e veterinários.
   - **Impacto**: Reduz chamadas telefônicas para a clínica e melhora a experiência do cliente.
   - **Urgência**: Alta, pois os clientes têm dificuldade em acompanhar esse histórico.
2. **Critérios**:
   - **Equipe tem tempo?**: Sim, após concluir as tarefas de priorização atual.
   - **Economicamente viável?**: Sim, requer poucas horas de desenvolvimento e tem alto impacto.
   - **Tecnologicamente viável?**: Sim, basta criar um filtro no prontuário já existente.
3. **Resultado**:
   - Funcionalidade desenvolvida em duas semanas.
   - Lançamento em produção após aprovação na homologação.

---

### **Política de Reavaliação**

- Periodicamente, todas as funcionalidades adicionadas serão revisadas para identificar possíveis melhorias ou ajustes, garantindo que continuem atendendo às necessidades do negócio.

[Voltar ao Início](#sandyhonda)

## 16. Treinamento

## 16.1. Usuário

### **Manual de Treinamento**

Este manual descreve as etapas e regras de negócio para o funcionamento da Pet+. Siga as instruções abaixo para garantir que todas as operações sejam realizadas corretamente.

---

#### **1. Como acessar o sistema - Usuário**

- **Acesso inicial:** O cliente deve acessar o sistema por meio do site ou aplicativo da clínica.
- **Login:** Utilize suas credenciais previamente cadastradas (e-mail e senha). Caso não tenha cadastro, o cliente pode criar uma conta.
- **Navegação:** Após o login, o cliente terá acesso ao painel principal, onde poderá gerenciar informações pessoais e dos animais.

---

#### **2. Operações básicas principais**

##### **Cadastro**

- **Cadastro do cliente:** Inclui informações básicas como nome, telefone, endereço e e-mail.
- **Cadastro dos animais:** O cliente deve informar dados como nome, espécie (gato, cachorro, etc), idade, peso, raça e características específicas.

##### **Agendamento**

- **Agendamento de consultas:** Escolha uma data e horário disponíveis no sistema para atendimento.
- **Agendamento de serviços adicionais:** Selecione serviços como banho, tosa, fisioterapia ou hospedagem.

##### **Visualização de dados**

- **Fichas e prontuários:** O cliente pode consultar os históricos de atendimentos, receitas e observações feitas pelos veterinários.
- **Acompanhamento de serviços:** Verifique o status de serviços agendados, como banho ou tosa.

---

#### **3. Operações avançadas**

- **Marcar animais com RFID:** Todos os animais devem ser identificados com um dispositivo RFID para facilitar o controle e histórico de atendimento.
- **Atendimento com múltiplos veterinários:** Caso o animal tenha necessidade de acompanhamento especializado, mais de um veterinário pode estar envolvido no processo.

---

#### **4. Backup (se estiver disponível)**

- **Backup de dados:** O sistema realiza backups automáticos diários para proteger os registros do cliente e dos animais.
- **Recuperação de dados:** Em caso de perda de informações, o cliente pode solicitar suporte para restaurar os dados.

---

#### **5. Como solicitar suporte**

- **Contato pelo sistema:** Acesse o painel de ajuda no sistema e envie uma solicitação diretamente aos atendentes.
- **Telefone:** Ligue para o número de suporte disponível no site.
- **E-mail:** Envie uma descrição detalhada do problema para o endereço indicado na página de contato.

---

#### **6. Como documentar falhas**

- **Identificação do problema:** Anote os detalhes da falha, como mensagens de erro ou comportamento inesperado.
- **Captura de tela:** Sempre que possível, capture imagens ou grave a tela para ilustrar o problema.
- **Envio ao suporte:** Envie as informações coletadas pelo painel de ajuda ou por e-mail.

---

#### **Regras de Negócio Específicas**

1. **Cadastro e recepção:**
   - O cliente deve informar as condições em que o animal chegou à clínica, bem como seus hábitos alimentares e comportamentais.

2. **Fila de espera:**
   - Se não houver veterinário disponível no momento, o atendente colocará o cliente na fila de espera.

3. **Prontuários e receitas:**
   - Cada atendimento gerará um prontuário detalhado com as observações e possíveis receitas prescritas.

4. **Serviços adicionais:**
   - Banho, tosa, pintura, fisioterapia, nutrição e outros serviços especializados podem ser agendados separadamente.
   - A clínica oferece suporte para animais com sobrepeso, incluindo planos de alimentação e exercícios.

5. **Hospedagem:**
   - Os serviços de hotel incluem alimentação, monitoramento e atividades para o bem-estar dos animais hospedados.

6. **Comunicação com profissionais:**
   - O cliente pode acessar um canal direto de comunicação com veterinários ou outros profissionais para dúvidas ou orientações pós-consulta.

7. **Relatórios e receituário:**
   - O cliente tem acesso ao histórico completo do animal, incluindo receituários digitais disponíveis no sistema.

---

#### **Serviços Exclusivos**

- **Cirurgias e curativos:** A clínica está preparada para atender emergências e realizar procedimentos cirúrgicos.
- **Injeções:** Serviços de aplicação de medicamentos são realizados por profissionais qualificados.
- **Acompanhamento nutricional:** Os clientes podem obter orientações para melhorar a saúde e nutrição de seus animais.
- **Hotel para animais:** Um espaço seguro e confortável para estadia de curto ou longo prazo.

[Voltar ao Início](#sandyhonda)

## 16.2. Admin

### **Manual de Treinamento Lado do Administrador**

Este manual descreve as etapas e responsabilidades do administrador para gerenciar o sistema da Pet+. Siga as instruções abaixo para garantir que todas as operações sejam realizadas corretamente e de forma segura.

---

#### **1. Como acessar o sistema**

- **Acesso de administrador:** O administrador deve acessar o sistema por meio de um login exclusivo para a área administrativa, utilizando um e-mail e senha fornecidos durante o cadastro do administrador.
- **Painel de Controle:** Após o login, o administrador terá acesso ao painel de controle do sistema, onde pode gerenciar configurações, usuários, dados e relatórios.

---

#### **2. Principais operações básicas**

##### **Gerenciamento de usuários**

- **Cadastro de clientes e veterinários:** O administrador pode adicionar, editar ou remover registros de clientes, veterinários e atendentes no sistema.
- **Controle de agendamentos:** O administrador tem acesso completo à agenda de todos os veterinários, podendo alterar horários e gerenciar a disponibilidade de serviços.

##### **Gerenciamento de animais**

- **Cadastro de animais:** O administrador pode adicionar, editar ou excluir registros de animais, garantindo que todas as informações estejam corretas (nome, espécie, condição de saúde, etc.).
- **Controle de prontuários e receitas:** O administrador pode acessar e revisar prontuários e receitas dos animais atendidos, garantindo que todos os registros estejam completos e corretamente arquivados.

---

#### **3. Operações especiais**

- **Controle de agenda:** O administrador tem a capacidade de visualizar e ajustar a agenda dos veterinários, incluindo serviços de banho, tosa, fisioterapia e outros serviços especializados.
- **Controle de filas de espera:** Caso necessário, o administrador pode gerenciar a fila de espera para os atendimentos, decidindo a ordem de priorização dos animais com base na situação e urgência.

---

#### **4. Backup do sistema e dados**

##### **Realização de backup**

- **Backup automático:** O sistema realiza backups automáticos diários, mas o administrador pode configurar a frequência dos backups de acordo com a necessidade da clínica.
- **Backup manual:** O administrador pode executar backups manuais a qualquer momento, garantindo a segurança e a integridade dos dados do sistema.
  
##### **Gerenciamento de backups**

- **Localização dos backups:** Os backups podem ser armazenados em servidores externos ou na nuvem. O administrador deve garantir que os dados estejam sendo armazenados de maneira segura e em conformidade com as políticas de segurança da informação.

---

#### **5. Como restaurar o sistema e dados**

##### **Restauração de dados**

- **Restaurar backup:** Caso o sistema apresente falhas ou perca dados, o administrador pode restaurar os dados a partir dos backups automáticos ou manuais.
- **Restaurar versão anterior do sistema:** Caso necessário, o administrador pode restaurar a versão anterior do sistema, utilizando backups feitos antes de qualquer atualização ou modificação que tenha gerado problemas.

##### **Procedimento de recuperação**

- **Passo a passo para recuperação:** O administrador deve seguir o processo documentado para restaurar dados de forma eficiente e sem causar mais interrupções no serviço.
- **Verificação de integridade:** Após a restauração, o administrador deve verificar a integridade dos dados, testando funcionalidades do sistema para garantir que tudo foi restaurado corretamente.

---

#### **6. Gerenciamento de contas**

##### **Gestão de contas de usuários**

- **Criação de novas contas:** O administrador pode criar novas contas para clientes, veterinários, atendentes e outros profissionais, atribuindo permissões e funções específicas a cada um.
- **Modificação de permissões:** O administrador pode alterar as permissões de acesso de usuários conforme necessário, garantindo que cada pessoa tenha acesso apenas às informações e funções pertinentes ao seu cargo.
  
##### **Gerenciamento de senhas**

- **Redefinição de senhas:** O administrador pode redefinir senhas de usuários caso eles esqueçam ou precisem de uma nova senha para acessar o sistema.
- **Segurança das contas:** O administrador deve garantir que todos os usuários usem senhas fortes e únicas, e pode forçar a troca periódica de senhas para garantir a segurança da plataforma.

---

#### **7. Configurações necessárias dos servidores e clientes**

##### **Configuração do servidor**

- **Servidor de banco de dados:** O administrador deve garantir que o servidor de banco de dados esteja configurado corretamente, com a segurança adequada, backups regulares e acesso controlado.
- **Servidor de aplicação:** O servidor que hospeda o sistema da clínica veterinária deve ser configurado para suportar o tráfego esperado e ter as configurações de segurança necessárias (firewall, criptografia, etc.).
- **Atualizações do servidor:** O administrador deve garantir que o servidor e as dependências do sistema sejam atualizados periodicamente para corrigir vulnerabilidades e melhorar o desempenho.

##### **Configuração do cliente**

- **Instalação do sistema nos clientes:** O administrador deve garantir que todos os dispositivos clientes (computadores, tablets, smartphones) estejam configurados corretamente para acessar o sistema.
- **Configuração de rede:** A rede de comunicação entre os dispositivos clientes e servidores deve ser configurada para garantir um tráfego de dados eficiente e seguro, incluindo o uso de VPN ou outras medidas de segurança, se necessário.
- **Verificação de compatibilidade:** O administrador deve garantir que todos os dispositivos clientes sejam compatíveis com o sistema (sistemas operacionais, navegadores, aplicativos, etc.).

---

[Voltar ao Início](#sandyhonda)

## 17. Script SQL

## 17.1 Comando create table

```SQL
-- Tabela para Clientes
CREATE TABLE Cliente (
    id_cliente INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100) NOT NULL,
    telefone VARCHAR(20),
    endereco VARCHAR(200)
);

-- Tabela para Animais
CREATE TABLE Animal (
    id_animal INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100) NOT NULL,
    rfid VARCHAR(50) UNIQUE NOT NULL,
    especie ENUM('gato', 'cachorro') NOT NULL,
    condicoes_chegada TEXT,
    tipo_racao VARCHAR(100),
    habitos TEXT,
    id_cliente INT,
    FOREIGN KEY (id_cliente) REFERENCES Cliente(id_cliente)
);

-- Tabela para Veterinários
CREATE TABLE Veterinario (
    id_veterinario INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100) NOT NULL,
    especialidade VARCHAR(100)
);

-- Tabela para Ficha de Atendimento
CREATE TABLE Ficha (
    id_ficha INT PRIMARY KEY AUTO_INCREMENT,
    observacoes TEXT,
    id_animal INT,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal)
);

-- Tabela para Prontuário
CREATE TABLE Prontuario (
    id_prontuario INT PRIMARY KEY AUTO_INCREMENT,
    detalhes TEXT,
    receita TEXT,
    id_ficha INT,
    FOREIGN KEY (id_ficha) REFERENCES Ficha(id_ficha)
);

-- Tabela para Atendentes
CREATE TABLE Atendente (
    id_atendente INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100) NOT NULL
);

-- Tabela para Agendamento
CREATE TABLE Agenda (
    id_agenda INT PRIMARY KEY AUTO_INCREMENT,
    data DATE NOT NULL,
    horario TIME NOT NULL,
    status VARCHAR(50),
    id_animal INT,
    id_veterinario INT,
    id_cliente INT,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal),
    FOREIGN KEY (id_veterinario) REFERENCES Veterinario(id_veterinario),
    FOREIGN KEY (id_cliente) REFERENCES Cliente(id_cliente)
);

-- Tabela para Serviços da Pet Shop
CREATE TABLE Servico (
    id_servico INT PRIMARY KEY AUTO_INCREMENT,
    tipo VARCHAR(100) NOT NULL,  -- banho, tosa, cirurgia, fisioterapia, etc.
    descricao TEXT,
    preco DECIMAL(10, 2)
);

-- Tabela para Comunicação entre Cliente e Profissional
CREATE TABLE Comunicacao (
    id_comunicacao INT PRIMARY KEY AUTO_INCREMENT,
    mensagem TEXT NOT NULL,
    data_envio DATETIME NOT NULL,
    data_resposta DATETIME,
    id_cliente INT,
    id_veterinario INT,
    FOREIGN KEY (id_cliente) REFERENCES Cliente(id_cliente),
    FOREIGN KEY (id_veterinario) REFERENCES Veterinario(id_veterinario)
);

-- Tabela para Hotel de Animais
CREATE TABLE Hotel (
    id_hotel INT PRIMARY KEY AUTO_INCREMENT,
    checkin DATE,
    checkout DATE,
    detalhes TEXT,
    id_animal INT,
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal)
);

-- Tabela para Relacionar Veterinários que Atendem Animais
CREATE TABLE Veterinario_Atendimento (
    id_animal INT,
    id_veterinario INT,
    PRIMARY KEY (id_animal, id_veterinario),
    FOREIGN KEY (id_animal) REFERENCES Animal(id_animal),
    FOREIGN KEY (id_veterinario) REFERENCES Veterinario(id_veterinario)
);
```

[Voltar ao Início](#sandyhonda)

## 17.2 Comandos para inserção de dados ficticios

```SQL
-- Inserindo Clientes
INSERT INTO Cliente (nome, telefone, endereco) VALUES 
('João Silva', '555-1234', 'Rua A, 123'),
('Maria Souza', '555-5678', 'Avenida B, 456'),
('Carlos Pereira', '555-8765', 'Travessa C, 789');

-- Inserindo Animais
INSERT INTO Animal (nome, rfid, especie, condicoes_chegada, tipo_racao, habitos, id_cliente) VALUES 
('Rex', 'RFID123', 'cachorro', 'Chegou com ferimentos na pata', 'Ração Premium', 'Brincalhão, gosta de correr', 1),
('Mimi', 'RFID456', 'gato', 'Chegou com tosse e espirros', 'Ração Light', 'Calmo, gosta de dormir', 2),
('Bolt', 'RFID789', 'cachorro', 'Chegou cansado e sem apetite', 'Ração Energy', 'Muito ativo, corre bastante', 3);

-- Inserindo Veterinários
INSERT INTO Veterinario (nome, especialidade) VALUES 
('Dra. Ana Mendes', 'Cirurgia Geral'),
('Dr. Pedro Oliveira', 'Nutrição e Fisioterapia'),
('Dra. Laura Ribeiro', 'Clínica Geral');

-- Inserindo Fichas
INSERT INTO Ficha (observacoes, id_animal) VALUES 
('Animal apresenta cortes superficiais na pata.', 1),
('Animal com sinais de infecção respiratória leve.', 2),
('Exame físico mostra sinais de exaustão.', 3);

-- Inserindo Prontuários
INSERT INTO Prontuario (detalhes, receita, id_ficha) VALUES 
('Receitado pomada para aplicar na pata 2x ao dia.', 'Pomada Cicatrizante', 1),
('Receitado antibiótico por 7 dias.', 'Antibiótico XYZ', 2),
('Receitado descanso e suplementação de vitaminas.', 'Suplemento Vitaminico', 3);

-- Inserindo Atendentes
INSERT INTO Atendente (nome) VALUES 
('Lucas Santos'),
('Fernanda Lima'),
('Ricardo Carvalho');

-- Inserindo Agendamentos
INSERT INTO Agenda (data, horario, status, id_animal, id_veterinario, id_cliente) VALUES 
('2024-09-17', '09:30:00', 'Confirmado', 1, 1, 1),
('2024-09-18', '11:00:00', 'Pendente', 2, 2, 2),
('2024-09-18', '14:00:00', 'Confirmado', 3, 3, 3);

-- Inserindo Serviços da Pet Shop
INSERT INTO Servico (tipo, descricao, preco) VALUES 
('Banho', 'Banho completo com shampoo especial', 50.00),
('Tosa', 'Tosa completa ou parcial', 70.00),
('Fisioterapia', 'Sessão de fisioterapia para reabilitação', 150.00),
('Cirurgia', 'Cirurgia geral para tratamento de problemas diversos', 500.00);

-- Inserindo Comunicação entre Cliente e Veterinário
INSERT INTO Comunicacao (mensagem, data_envio, data_resposta, id_cliente, id_veterinario) VALUES 
('Meu cachorro ainda está mancando, o que faço?', '2024-09-16 10:00:00', '2024-09-16 12:00:00', 1, 1),
('A tosse do gato piorou, devo trazer de novo?', '2024-09-17 15:00:00', NULL, 2, 2),
('O cachorro está se recuperando, precisa voltar para fisioterapia?', '2024-09-18 09:00:00', NULL, 3, 3);

-- Inserindo Registro de Hotel
INSERT INTO Hotel (checkin, checkout, detalhes, id_animal) VALUES 
('2024-09-20', '2024-09-25', 'Animal ficou hospedado e recebeu cuidados especiais', 1),
('2024-09-22', '2024-09-28', 'Animal hospedado e com dieta personalizada', 2),
('2024-09-25', '2024-09-30', 'Animal hospedado com tratamento fisioterápico', 3);

-- Inserindo Relação entre Veterinário e Animais Atendidos
INSERT INTO Veterinario_Atendimento (id_animal, id_veterinario) VALUES 
(1, 1),
(2, 2),
(3, 3),
(1, 3); -- O animal 1 também foi atendido por outro veterinário
```

[Voltar ao Início](#sandyhonda)
