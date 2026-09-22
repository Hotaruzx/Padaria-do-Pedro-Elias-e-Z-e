# Projeto Lanchonete

## Questionário

### 1. Qual é a diferença entre Working Directory, Staging Area e Repository?

O **Working Directory** é o local onde os arquivos do projeto ficam e onde fazemos as alterações.

A **Staging Area** é a área onde colocamos os arquivos que queremos incluir no próximo commit.

O **Repository** é onde o Git armazena os commits e o histórico das alterações do projeto.

### 2. Qual é a diferença entre `git commit` e `git push`?

O **git commit** registra as alterações no histórico do repositório local.

O **git push** envia os commits que estão no repositório local para o repositório remoto, como o GitHub.

### 3. É possível realizar vários commits antes de executar um `git push`? Explique.

Sim. É possível realizar vários commits localmente antes de executar o git push. Cada commit registra uma alteração no histórico local. Depois, o git push pode enviar todos esses commits para o repositório remoto.

### 4. Por que é interessante realizar commits pequenos e descritivos?

Porque commits pequenos e com mensagens descritivas facilitam a organização e a compreensão do histórico do projeto. Assim, fica mais fácil identificar o que foi alterado em cada etapa e localizar alterações específicas.

### 5. O que acontece com os commits locais quando ainda não executamos o `git push`?

Os commits continuam armazenados no repositório local. Eles fazem parte do histórico local do Git, mas ainda não foram enviados para o repositório remoto. Eles serão enviados ao GitHub quando executarmos o git push.

### 6. Como verificar, pelo GitHub, se os commits foram enviados corretamente?

É possível verificar acessando o repositório no GitHub e conferindo o histórico de commits. Na página do repositório, podemos verificar a quantidade de commits e acessar o histórico de alterações para confirmar que os commits realizados localmente foram enviados para o repositório remoto.
