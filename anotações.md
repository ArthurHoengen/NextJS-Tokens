## Access Token:
- **Pra que serve?**
    - Pegar qualquer tipo de informação do usuário
    - Atualizar ...
    - Inserir ...
    - Deletar ...

- **Duração**
    - Dura pouco tempo / O mínimo possível

- **Risco se ele vazar**
    - Quanto maior o tempo de vida dele, maior o estrago que quem tiver o token pode fazer

## Refresh Token:
- **Pra que serve?**
    - Para não precisar pedir a senha e o usuário para gerar um novo access_token

- **Duração**
    - Duração dele é longa
    - O refresh token a nivel de backend está associado ao usuário de alguma forma

- **Risco se ele vazar**
    - Se ele vazar, o usuário novo pode gerar tokens INFINITOS (access e refresh)
    - Precisa ter alguma forma de invalidar os refresh tokens.