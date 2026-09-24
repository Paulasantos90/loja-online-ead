# ADR 001: Uso do Github Actions para Integracao Continua

## Contexto
O projeto precisa de rodar testes automaticamente a cada Pull Request.
Existem varias ferramentas de CI no mercado (Jenkins, CircleCI, Github Actions).

## Decisao
Vamos usar o GitHub Actions.

## Motivo
Ja hospedamos o codigo no Github, entao e preciso integrar com outra plataforma. E gratuito para repositorios publicos e a configuracao fica no proprio repositorio, versionada junto com o codigo.

## Consequencias
Ficamos dependentes do ecossistema Github. Se um dia migrarmos de plataforma de hospedagem, o pipeline de CI precisara ser recriado.
