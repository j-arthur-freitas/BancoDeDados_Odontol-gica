# 🦷 Projeto Banco de Dados - Clínica Odontológica

## 📌 Descrição
Este projeto consiste no desenvolvimento de um **banco de dados relacional** para o gerenciamento de uma **clínica odontológica**.  
O sistema foi estruturado em **PostgreSQL** e contempla desde a criação do schema, tabelas, relacionamentos, inserções de dados, até consultas avançadas com **views, índices, updates e deletes**.

O objetivo é fornecer uma base sólida para o controle de pacientes, dentistas, atendentes, procedimentos e consultas.

---

## 🗂 Estrutura do Banco de Dados
O banco de dados foi modelado dentro do schema `clinicabd` e conta com as seguintes tabelas:

- **paciente** → Armazena informações pessoais e histórico de consultas.
- **dentista** → Contém dados profissionais e especialidades.
- **procedimentos** → Lista de procedimentos odontológicos disponíveis.
- **consultas** → Registra consultas realizadas, incluindo prescrições.
- **consulta_procedimentos** → Relaciona consultas e procedimentos.
- **horarios_dentista** → Gerencia horários de atendimento de cada dentista.
- **atendente** → Controle de usuários responsáveis pelo agendamento e recepção.

---

## ⚙️ Funcionalidades
- Criação e gerenciamento do **schema `clinicabd`**.
- **Inserção inicial de 10 registros em cada tabela**, simulando dados reais.
- Definição de **chaves primárias e estrangeiras** para integridade referencial.
- Criação de **índices** para otimizar consultas (por CPF de paciente e data/hora de consultas).
- Operações de **UPDATE e DELETE** com condições específicas.
- Consultas SQL contextualizadas:
  - Quantidade de consultas por especialidade.
  - Total de consultas realizadas por dentista.
  - Pacientes com maior número de consultas.
  - **View** com lista de consultas ordenadas por data.
  - Média de consultas por dentista.

