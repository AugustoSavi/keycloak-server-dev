# Repositório Keycloak com PostgreSQL

Este repositório contém um arquivo `docker-compose.yml` para configurar um ambiente de desenvolvimento com Keycloak e PostgreSQL, junto com um diretório `imports` para armazenar arquivos de importação, como `realm-export.json`.

## Utilização

1. Clone este repositório:

2. Navegue até o diretório clonado:

   ```bash
   cd keycloak-server-dev
   ```

3. Inicie os serviços utilizando Docker Compose:

   ```bash
   docker-compose up -d
   ```

   Isso iniciará os serviços do Keycloak e do PostgreSQL em contêineres Docker.

## Arquivos de Importação

O diretório `imports` contém arquivos que podem ser importados para o Keycloak durante a inicialização para configurar realms, clientes, usuários, etc. O arquivo `realm-export.json` é um exemplo de arquivo de exportação de realm que pode ser importado.

## Links Úteis

- [Getting Started with Keycloak Docker](https://www.keycloak.org/getting-started/getting-started-docker#_secure_the_first_application)
- [Integrating Spring Boot with Keycloak](https://www.baeldung.com/spring-boot-keycloak)
- [Configuring Keycloak to Use Google as an IDP](https://medium.com/codeshakeio/configure-keycloak-to-use-google-as-an-idp-4e3c59583345)
- [Video Tutorial: Keycloak Authentication in Spring Boot](https://www.youtube.com/watch?v=yUrfBrSkWLg)
- [Video Tutorial: Keycloak and React Authentication](https://www.youtube.com/watch?v=rgcHXpxxaZ0)
- [Video Tutorial: Securing Apps with Keycloak](https://www.youtube.com/watch?v=wgdo5I53GQo&t=1765s)
- [Configuring Sign-in with Google Using Keycloak](https://keycloakthemes.com/blog/how-to-setup-sign-in-with-google-using-keycloak)
- [Integrating Keycloak SSO with Centrifugo](https://centrifugal.dev/blog/2023/03/31/keycloak-sso-centrifugo)
- [Keycloak JavaScript Adapter Documentation](https://www.keycloak.org/docs/latest/securing_apps/index.html#_javascript_adapter)
- [React Keycloak Examples Repository](https://github.com/react-keycloak/react-keycloak-examples/tree/master)