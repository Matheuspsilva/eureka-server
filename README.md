# Eureka Server

## Visão Geral
O `eureka-server` é um microserviço Spring Boot configurado como um servidor Eureka para descoberta de serviços. Ele atua como um registro central para que os microserviços possam se registrar e localizar uns aos outros.

## Pré-requisitos
- Java 17
- Maven

## Configuração
O servidor Eureka é configurado principalmente através do arquivo `application.yaml`, definindo a porta e as configurações específicas do Eureka.

## Instalação e Execução
1. Clone o repositório:
```bash
git clone https://github.com/Matheuspsilva/eureka-server.git
```
2. Navegue até a pasta do projeto e execute:
```bash
mvn clean install
```
3. Para iniciar a aplicação, execute:
```bash
mvn spring-boot:run
```

4. Acesse o endereço http://localhost:8761/ para visualizar o painel do Eureka Server.

## Funcionalidades do Eureka Server
- **Registro de Serviços**: Permite que os microserviços se registrem no Eureka Server para que possam ser descobertos por outros serviços.
- **Descoberta de Serviços**: Os microserviços podem consultar o Eureka Server para descobrir a localização de outros serviços registrados.

