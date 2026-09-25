# Especificação de Caso de Uso

## UC02 — Editar usuário

**Ator principal:** Gerente de sistema  
**Resumo:** Permite que o gerente localize um usuário cadastrado, altere seus dados e salve as mudanças.

### Pré-condições

- O gerente está autenticado no sistema.
- O usuário que será editado já está cadastrado.

### Pós-condições

- As alterações confirmadas são salvas.
- O sistema informa que o usuário foi atualizado.

### Ponto de inclusão

- Buscar usuário (UC04).

### Ponto de extensão

- Nenhum identificado.

### Fluxo principal

| Ator | Sistema |
|---|---|
| 1. Escolhe a opção **Editar usuário**. | 2. Solicita dados para localizar o usuário. |
| 3. Informa um dado de busca, como nome, e-mail ou identificador. | 4. Executa **Buscar usuário** e exibe os resultados. |
| 5. Seleciona o usuário que deseja editar. | 6. Exibe os dados atuais do usuário. |
| 7. Altera os dados desejados. | 8. Valida as informações preenchidas. |
| 9. Confirma as alterações. | 10. Salva as mudanças e informa que a edição foi concluída. |

### Fluxos alternativos

#### A1 — Usuário não encontrado

1. O sistema não encontra usuários com os dados informados.
2. O sistema avisa que nenhum resultado foi encontrado.
3. O gerente informa outros dados para realizar uma nova busca.

#### A2 — Dados inválidos

1. O sistema identifica informações inválidas ou obrigatórias em branco.
2. O sistema mostra quais dados precisam ser corrigidos.
3. O gerente corrige os dados e confirma novamente.

#### A3 — Cancelamento

1. O gerente cancela a edição antes de confirmar as alterações.
2. O sistema descarta as mudanças e mantém os dados anteriores.

### Fluxo de exceção

#### E1 — Falha ao salvar

1. O sistema não consegue salvar as alterações.
2. O sistema informa que ocorreu um erro.
3. Os dados anteriores do usuário são mantidos.
