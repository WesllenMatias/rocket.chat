# Rocket.Chat
Rocket Chat no Docker.

- Para rodar esse docker compose deve ser feita a instalacao do NGNIX e configurado com um certificado digital, assim como manda a documentacao, para evitar confusao (como eu mesmo me confundi no inicio), tomei a liberdade de nao incluir a configuracao de um firewall e do FailtoBan como foi feito na documentacao original.

## Etapas da configuracao

1. Criar certificado digital SSL.
2. Instalar servidor ngnix.
3. Instalar o docker.
4. Instalar o docker-compose.
5. Configurar ngnix com o certificado.
6. Criar pastas onde vão ficar os volumes dos containers.
7. Criar o o docker-compose de acordo com a documentação.

## Documentacao Original:
### https://rocket.chat/docs/installation/docker-containers/index.html

## Dicas:
Para um ambiente de teste agil, creio que seja mais rapido para criar um teste, usar o vagrant e subir uma VM ubuntu com docker ja instalado, estarei providenciando na sequencia o arquivo Vagrantfile para facilitar o ambiente de teste, afinal configurar VM step-by-step realmente torna o teste um martirio.
