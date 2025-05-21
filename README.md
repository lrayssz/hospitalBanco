**🏥 Hospital Fundamental - Modelagem de Banco de Dados - Parte 1**

Este projeto consiste na modelagem de um banco de dados relacional para um pequeno hospital local, com foco na digitalização e organização dos dados clínicos, substituindo planilhas e formulários físicos por um sistema informatizado eficiente.

🎯 Objetivo

Desenvolver um Diagrama Entidade-Relacionamento (DER) para estruturar as principais informações do hospital, incluindo médicos, pacientes, consultas, receitas médicas, especialidades, cargos e convênios.

📌 Funcionalidades Modeladas

Cadastro de Médicos: Dados pessoais, cargo (generalista, especialista, residente) e especialidades.
Cadastro de Pacientes: Dados pessoais, documentos e convênio.
Gestão de Consultas: Registro com data, hora, médico, paciente, especialidade e valor.
Prescrição de Receitas: Medicamentos prescritos, quantidade e instruções.
Cadastro de Convênios: Nome, CNPJ e tempo de carência.
Gestão de Especialidades e Cargos: Informações para relacionamento com médicos.


![hospitalBanco (1)](https://github.com/user-attachments/assets/bc864f15-852f-4c4b-bf2b-a25f01c7ec62)

**🏥 Hospital Fundamental - Modelagem de Banco de Dados - Parte 2**

Após a primeira etapa da modelagem do banco de dados, identificou-se a necessidade de expandir o sistema para contemplar o controle de internações de pacientes.

📌 Funcionalidades Incluídas

Registro de internações com data de entrada, previsão e alta efetiva, além da descrição dos procedimentos realizados.
Associação entre internações e quartos, considerando número e tipo de quarto.
Cadastro de tipos de quarto, com valor da diária e descrição (ex: apartamento, duplo, enfermaria).
Vinculação de enfermeiros responsáveis por acompanhar os pacientes durante a internação.
Associação direta da internação a um único médico e ao paciente (um paciente pode ser internado mais de uma vez).

![hospitalBanco2 (1)](https://github.com/user-attachments/assets/42d0111f-107a-4b71-9b77-dd670a0cdcfa)
