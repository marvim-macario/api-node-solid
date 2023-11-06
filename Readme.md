# App

Gympass style app.

## Rfs (requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil do usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário marcar um check-in em uma academia;
- [ ] Deve ser possível cadastrar uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;

## RNs (regras de negócio)
- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado.
- [ ] O usuário não pode fazer 2 check-in no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado até 20min após ser criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] A academia só pode ser cadastrada por administradores;

## RNFs (requisitos não funcionais)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSql;
- [ ] Todas  as listas de dados precisam estar paginadas com 20 itens por página;
- [ ] As usuário deve ser identificado por um JWT(Json Web Token);


