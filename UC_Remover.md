# Especificação de Caso de Uso - UC_Remover - Remover usuário

## Código / Nome do Caso de Uso

| Código / Nome do Caso de Uso | UC_Remover |
| ---------------------------- | ---------------------------------------------------------------------- |
| **Ator Principal** | Gerente de Sistema |
| **Resumo** | Neste caso de uso, o gerente de sistema remove um usuário cadastrado no sistema. |
| **Pré-condições** | O gerente de sistema deve estar conectado ao sistema e o usuário que será removido deve estar cadastrado. |
| **Pós-condições** | O usuário selecionado é removido do sistema e não pode mais acessar o sistema utilizando seu cadastro. |

---

## Fluxo Principal

| **Gerente de Sistema** | **Sistema** |
| ------------------------------------- | -------------------------------------------------------------------- |
| 1. Seleciona a opção de remover usuário. | |
| | 2. Solicita os dados do usuário que será removido. |
| 3. Informa os dados do usuário e confirma a remoção. | |
| | 4. Busca o usuário no sistema. |
| | 5. Exibe os dados do usuário encontrado para confirmação. |
| 6. Confirma a remoção do usuário. | |
| | 7. Remove o usuário do sistema. |
| | 8. Exibe uma mensagem informando que o usuário foi removido com sucesso. |

---
