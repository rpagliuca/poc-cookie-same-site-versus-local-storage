# poc-cookie-same-site-versus-local-storage

## Instruções

1) Clone este repositório

2) Rode `docker-compose up --build`

3) Obtenha os IPs dos seus contêineres do Docker (usando
`docker ps` + `docker inspect` ou alguma outra maneira que você preferir)

4) Com as informações obtidas no passo 3, configure adequadamente os
seguintes hostnames
no seu sistema (alterando arquivo `/etc/hosts`):
    * auth
    * app1

5) Para rodar a demo, acesse as seguintes URLs no seu navegador:
    * https://auth
    * https://app1

## Exemplo de /etc/hosts
A fim de exemplificação apenas, no meu sistema eu precisei adicionar as
seguintes linhas no final do arquivo `/etc/hosts`:

    192.168.16.3 app1
    192.168.16.2 auth
