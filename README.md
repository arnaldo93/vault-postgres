# vault-postgres
>Nesse modelo temos uma aplicação Vault utilizando o backend do postgres, o container utiliza o modo de prod atendendo algumas medidas de segurança como:

- $PG_SSLCERT: Define o certificado ssl para o postgres. 
- $HA_ENABLE: Habilita a alta disponibilidade dos pods (recomendado pelomenos 3 nós).
- PKCS11_LIB: é uma variável de ambiente que indica o caminho para a biblioteca PKCS #11 em um sistema operacional. PKCS #11 é um padrão criptográfico que define uma interface para acesso a dispositivos de criptografia, como smart cards e tokens USB.
