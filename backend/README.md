# API Connect

## Configurações do Banco de Dados

Para configurar e gerar o banco de dados, siga os passos abaixo:

1. **Suba os containers do Docker Compose**:

   - Certifique-se de que os containers estão em execução antes de prosseguir.

2. **Gere o schema do Drizzle**:

   - Após os containers estarem de pé, execute o seguinte comando para gerar o schema:
     ```bash
     npx drizzle-kit generate
     ```

3. **Execute a migration**:
   - Após gerar o schema, execute a migration para aplicar as alterações no banco de dados:
     ```bash
     npx drizzle-kit migrate
     ```

Seguindo esses passos, o banco de dados estará configurado e pronto para uso.
