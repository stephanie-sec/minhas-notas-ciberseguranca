# DNS — Domain Name System

## O que é?

DNS (Domain Name System) é o sistema responsável por relacionar nomes de domínio a endereços IP.

Ele permite que utilizemos nomes fáceis de lembrar, como `google.com`, em vez de precisarmos memorizar um endereço IP.

## Para que serve?

Sua principal função é realizar a resolução de nomes.

De forma simplificada:

**Nome de domínio → Endereço IP**

## Analogia

O DNS funciona de maneira semelhante a uma agenda telefônica.

Em vez de precisar memorizar o número de uma pessoa, procuramos seu nome na agenda para descobrir o número correspondente.

Na rede, ocorre algo parecido:

**Nome do site → DNS → Endereço IP**

## Onde aparece na prática?

Quando digitamos o endereço de um site no navegador, o dispositivo precisa descobrir qual endereço IP está associado àquele domínio para estabelecer a comunicação com o servidor.

O DNS participa desse processo.

## Exemplo

Ao acessar:

`www.exemplo.com`

o dispositivo consulta o DNS para descobrir o endereço IP associado ao domínio.

De forma simplificada:

```text
www.exemplo.com
       ↓
      DNS
       ↓
  endereço IP
       ↓
          servidor
```

## Relação com segurança

O DNS também está relacionado à segurança de redes.

Atacantes podem explorar mecanismos relacionados à resolução de nomes para direcionar usuários a destinos maliciosos ou comprometer a comunicação.

Por isso, compreender DNS é importante para entender posteriormente diferentes problemas e mecanismos de segurança de redes.

## Resumo

**DNS é o sistema que permite relacionar nomes de domínio a endereços IP, facilitando a localização de serviços na rede.**

## Conceitos relacionados

- Endereço IP
- DHCP
- Gateway
- Servidores
- Redes de computadores
- Segurança de redes
