# Controle de Medicamentos

## Projeto

Desenvolvido durante o curso Fullstack da [Academia do Programador](https://www.academiadoprogramador.net) 2024

---
## Funcionalidades

### 1. Controle de Medicamentos

- **Registrar Medicamento:** O registro de um medicamento ir� ser formado por: nome, descri��o e quantidade do estoque. Caso
o mesmo j� esteja cadastrado, � atualizado a quantidade.
- **Visualizar Medicamentos:** Exibe uma lista exibindo detalhes de todos os medicamentos registrados, **tamb�m dever� exibir quais medicamentos est�o em falta** (<20 unidades).
- **Editar Medicamentos:** Oferece a possibilidade de modificar informa��es de um medicamento existente.
- **Excluir Medicamentos:** Permite remover um medicamento do sistema, atualizando a lista de medicamentos registrados.

### 2. Controle de Paciente

- **Registrar Paciente:** O paciente dever� ser registrado com as seguintes informa��es: nome, telefone e cart�o do SUS.
- **Visualizar Pacientes:** Exibe uma lista exibindo detalhes de todos os medicamentos registrados.
- **Editar Pacientes:** Oferece a possibilidade de modificar informa��es de um paciente cadastrado.
- **Excluir Pacientes:** Permite remover um registro de paciente do sistema.

### 3. Controle de Requisi��es de Sa�da

- **Registrar Requisi��o:** O paciente poder� registrar uma nova requisi��o que incluir�: data da requisi��o, dados do paciente, dados do medicamento e a quantidade do medicamento requisitada.
- **Visualizar Requisi��es:** Exibe uma lista exibindo detalhes de todas as requisi��es registradas.
- **Visualizar Requisi��es de um Paciente:** Permite visualizar uma lista de requisi��es realizadas por um paciente espec�fico.

**Ao fazer uma requisi��o de medicamento, ser� necess�rio verificar se a quantidade do mesmo est� dispon�vel no estoque. Tamb�m ser� necess�rio subtrair esta quantidade do registro do estoque.**

### 4. Controle de Funcion�rio

- **Registrar Funcion�rio:** O funcion�rio dever� ser registrado com as seguintes informa��es: nome, telefone e CPF.
- **Visualizar Funcion�rios:** Exibe uma lista exibindo detalhes de todos os funcion�rios registrados.
- **Editar Funcion�rio:** Oferece a possibilidade de modificar informa��es de um funcion�rio cadastrado.
- **Excluir Funcion�rio:** Permite remover um registro de funcion�rio do sistema.

### 5. Controle de Fornecedor

- **Registrar Fornecedor:** O fornecedor dever� ser registrado com as seguintes informa��es: nome, telefone e CNPJ.
- **Visualizar Fornecedores:** Exibe uma lista exibindo detalhes de todos os fornecedores registrados.
- **Editar Fornecedor:** Oferece a possibilidade de modificar informa��es de um fornecedor cadastrado.
- **Excluir Fornecedor:** Permite remover um registro de fornecedor do sistema.

### 6. Controle de Requisi��es de Entrada

- **Registrar Requisi��o de Entrada:** O usu�rio poder� fazer uma requisi��o de entrada de medicamento que incluir�: data da requisi��o, dados do medicamento, dados do fornecedor, dados do funcion�rio e a quantidade requisitada do medicamento. *A quantidade do medicamento deve ser atualizada*.
- **Visualizar Requisi��es de Entrada:** Exibe uma lista exibindo detalhes de todas as requisi��es de Entrada registradas.