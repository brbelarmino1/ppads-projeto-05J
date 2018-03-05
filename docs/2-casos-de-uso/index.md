# Casos de uso

## 1. Diagrama de casos de uso

![](caso-de-uso.jpg)

## 2. Especificação dos casos de uso

### 2.1. Caso de uso **MANTER CADASTRO**

| Campo          | Informação        |
|---|---|
| Identificador: | UC01              |
| Nome:          | Manter cadastro |
| Atores:        | Cliente/Fornecedor |
| Sumário:       | O usuário insere as informações para cadastro. Deve-se respeitar as regras de preenchimento dos campos. |

| Fluxo Principal |
|---|
| 1) O usuário informa os dados para cadastro, e seleciona todos os checkbox. |
| 2) O sistema valida os dados fornecidos e todos os checkbox. |
| 3) Sistema informa sucesso no cadastro, e redireciona para outra tela. Caso de uso é encerrado. |

| Fluxo Alternativo (2a): Os dados informados estão incorretos. |
|---|
| 1) O sistema informa que os dados estão incorretos ou os checkbox não estão selecionados. |
| 2) Enquanto o usuário não informar corretamente os dados e selecionar todos os checkbox, o sistema informa que os dados estão incorretos ou checkbox não estão selecionados. |
| 3) Usuário informa os dados corretamente e seleciona todos os checkbox. |
| 4) Volta ao passo 2 do fluxo principal. |

### 2.2. Caso de uso **BUSCAR PROFISSIONAL**

| Campo          | Informação        |
|---|---|
| Identificador: | UC02              |
| Nome:          | Buscar profissional |
| Atores:        | Cliente |
| Sumário:       | O cliente realiza a busca por um profissional, para realizar determinado serviço. |

| Fluxo Principal |
|---|
| 1) O usuário informa os dados para cadastro, e seleciona todos os checkbox. |
| 2) O sistema retorna uma lista com fornecedores do serviço buscado. |
| 3) Sistema redireciona para outra tela. Caso de uso é encerrado. |

| Fluxo Alternativo (2a): Os dados para busca estão vazios. |
|---|
| 1) O sistema informa que os dados da busca estão incorretos. |
| 2) Enquanto o usuário não informar corretamente os dados para busca, o sistema exibe mensagem de erro. |
| 3) Usuário informa os dados corretamente. |
| 4) Volta ao passo 1 do fluxo principal. |

### 2.3. Caso de uso **CONTRATAR PROFISSIONAL**

| Campo          | Informação        |
|---|---|
| Identificador: | UC03             |
| Nome:          | Contratar Profissional |
| Atores:        | Cliente |
| Sumário:       | O cliente solicita o fornecedor selecionado. |

| Fluxo Principal |
|---|
| 1) O cliente solicita o fornecedor. |
| 2) O sistema notifica o fornecedor. Caso de uso é encerrado. |


