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

### 2.2. Controle de Consertos e Manutenções ⚙️

- **RF-04**: Registrar manutenções corretivas e preventivas.
- **RF-05**: Associar peças utilizadas no conserto à respectiva manutenção.
- **RF-06**: Armazenar histórico de manutenções de cada máquina.
- **RF-07**: Criar agendamentos de manutenções preventivas.

### 2.3. Controle de Peças e Inventário 📦

- **RF-08**: Permitir cadastro de peças de hardware no inventário.
- **RF-09**: Registrar peças retiradas do estoque.
- **RF-10**: Emitir alertas para peças com baixa quantidade.

### 2.4. Gerenciamento de Laboratórios 🏢

- **RF-11**: Gerenciar múltiplos laboratórios, associando máquinas e peças.
- **RF-12**: Exibir painel geral com status das máquinas em todos os laboratórios.

### 2.5. Relatórios e Auditorias 📊

- **RF-13**: Gerar relatórios de consertos e manutenções.
- **RF-14**: Gerar relatórios sobre uso e troca de peças.
- **RF-15**: Permitir exportação de relatórios em formatos PDF ou Excel.

### 2.6. Controle de Acesso e Usuários 🔒

- **RF-16**: Criar perfis de usuário com diferentes níveis de acesso.
- **RF-17**: Manter logs de todas as ações dos usuários.

---

## 3. Requisitos Não Funcionais 🚀

### 3.1. Desempenho ⚡

- **RNF-01**: Processar informações de até 1000 máquinas e peças sem perda de desempenho.

### 3.2. Usabilidade 🖱️

- **RNF-02**: Interface intuitiva para registro de manutenções e gerenciamento de inventário.

### 3.3. Confiabilidade 🔄

- **RNF-03**: Backup automático dos dados a cada 24 horas.

### 3.4. Portabilidade 🌐

- **RNF-04**: Multiplataforma: Windows, Linux e macOS.

### 3.5. Segurança 🛡️

- **RNF-05**: Controle de acesso com autenticação de usuário.
- **RNF-06**: Registro de ações dos usuários para auditoria.

---

## 4. Requisitos de Interface 🎨

### 4.1. Interface Gráfica 💻

- **RI-01**: Interface gráfica baseada em JavaFX ou Swing.
- **RI-02**: Exibir gráficos de desempenho com JFreeChart.

### 4.2. Relatórios 📑

- **RI-03**: Geração de relatórios em tempo real com filtros de data, laboratório ou máquina.

---

## 5. Considerações Finais ✨

O sistema "Gerenciador de Hardware para Laboratórios" deve facilitar o controle e monitoramento das máquinas e peças de hardware, proporcionando maior eficiência na gestão de manutenção e inventário dos laboratórios. Este documento deverá ser revisado periodicamente conforme novas funcionalidades e necessidades forem identificadas.

---
