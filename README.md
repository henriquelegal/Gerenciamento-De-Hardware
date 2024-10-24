# Gerenciador de Hardware para Laboratórios 💻🔧

## 📄 Documento de Levantamento de Requisitos

**Data**: 24/10/2024  
**Responsável**: Henrique dos Santos e Bruno de Lima 

---

## 1. Introdução

### 1.1. Objetivo 🎯

Este documento visa detalhar os requisitos funcionais e não funcionais do sistema "Gerenciador de Hardware para Laboratórios", que permitirá o controle e monitoramento de máquinas, consertos, peças trocadas e inventário de componentes em um ou mais laboratórios.

### 1.2. Escopo 🗂️

O sistema gerenciará:
- Cadastro e controle de máquinas de diversos laboratórios.
- Registro de manutenções, consertos e peças trocadas.

### 1.3. Definições, Acrônimos e Abreviações 📚

- **Máquina**: Equipamento de hardware a ser monitorado.
- **Peça**: Componente de hardware que pode ser substituído.
- **Conserto**: Ação de reparar uma máquina.
- **Inventário**: Registro de peças disponíveis.

---

## 2. Requisitos Funcionais ✅

### 2.1. Cadastro de Máquinas 🖥️

- **RF-01**: Permitir cadastro de máquinas, incluindo especificações de hardware (CPU, RAM, armazenamento).
- **RF-02**: Associar cada máquina a um laboratório específico.
- **RF-03**: Exibir status atual da máquina (funcionando, em manutenção, fora de uso).
- **RF-04**: Permitir a edição de informações cadastrais das máquinas.

### 2.2. Controle de Consertos e Manutenções ⚙️

- **RF-05**: Registrar manutenções corretivas e preventivas.
- **RF-06**: Associar peças utilizadas no conserto à respectiva manutenção.
- **RF-07**: Armazenar histórico de manutenções de cada máquina.
- **RF-08**: Criar agendamentos de manutenções preventivas.
- **RF-09**: Enviar notificações de lembrete para manutenções agendadas.

### 2.3. Controle de Peças e Inventário 📦

- **RF-10**: Permitir cadastro de peças de hardware no inventário.
- **RF-11**: Registrar peças retiradas do estoque.
- **RF-12**: Emitir alertas para peças com baixa quantidade.
- **RF-13**: Permitir a categorização de peças por tipo e uso.

### 2.4. Gerenciamento de Laboratórios 🏢

- **RF-14**: Gerenciar múltiplos laboratórios, associando máquinas e peças.
- **RF-15**: Exibir painel geral com status das máquinas em todos os laboratórios.
- **RF-16**: Permitir o compartilhamento de recursos entre laboratórios.

### 2.5. Relatórios e Auditorias 📊

- **RF-17**: Gerar relatórios de consertos e manutenções.
- **RF-18**: Gerar relatórios sobre uso e troca de peças.
- **RF-19**: Permitir exportação de relatórios em formatos PDF ou Excel.
- **RF-20**: Oferecer relatórios personalizados com critérios de filtragem.

### 2.6. Controle de Acesso e Usuários 🔒

- **RF-21**: Criar perfis de usuário com diferentes níveis de acesso.
- **RF-22**: Manter logs de todas as ações dos usuários.
- **RF-23**: Permitir a redefinição de senhas pelos usuários.

---

## 3. Requisitos Não Funcionais 🚀

### 3.1. Desempenho ⚡

- **RNF-01**: Processar informações de até 1000 máquinas e peças sem perda de desempenho.
- **RNF-02**: Responder a requisições de usuários em menos de 2 segundos.

### 3.2. Usabilidade 🖱️

- **RNF-03**: Interface intuitiva para registro de manutenções e gerenciamento de inventário.
- **RNF-04**: Incluir tutoriais interativos para novos usuários.

### 3.3. Confiabilidade 🔄

- **RNF-05**: Backup automático dos dados a cada 24 horas.
- **RNF-06**: Sistema de recuperação de dados em caso de falha.

### 3.4. Portabilidade 🌐

- **RNF-07**: Multiplataforma: Windows, Linux e macOS.
- **RNF-08**: Aplicativo mobile para acesso remoto ao sistema.

### 3.5. Segurança 🛡️

- **RNF-09**: Controle de acesso com autenticação de usuário.
- **RNF-10**: Registro de ações dos usuários para auditoria.
- **RNF-11**: Criptografia de dados sensíveis no armazenamento.

---

## 4. Requisitos de Interface 🎨

### 4.1. Interface Gráfica 💻

- **RI-01**: Interface gráfica baseada em JavaFX ou Swing.
- **RI-02**: Exibir gráficos de desempenho com JFreeChart.
- **RI-03**: Menu de navegação intuitivo e acessível.

### 4.2. Relatórios 📑

- **RI-04**: Geração de relatórios em tempo real com filtros de data, laboratório ou máquina.
- **RI-05**: Visualização de relatórios em formato de gráficos interativos.

---

## 5. Considerações Finais ✨

O sistema "Gerenciador de Hardware para Laboratórios" deve facilitar o controle e monitoramento das máquinas e peças de hardware, proporcionando maior eficiência na gestão de manutenção e inventário dos laboratórios. Este documento deverá ser revisado periodicamente conforme novas funcionalidades e necessidades forem identificadas.
