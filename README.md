# Mulesoft Database Integration

Este projeto demonstra como realizar operações em banco de dados utilizando a plataforma **Mulesoft**, utilizando componentes como **Bulk Insert**, **Bulk Update**, **Select** e outros para manipulação eficiente de dados.

## Funcionalidades

- **Bulk Insert**: Inserção em massa de dados no banco de dados.
- **Bulk Update**: Atualização em massa de registros.
- **Select**: Consulta e extração de dados.
- **Execute DDL**: Execução de comandos de definição de dados, como criar ou modificar tabelas.
- **Execute Script On Table**: Execução de scripts SQL personalizados em tabelas específicas.

## Pré-requisitos

Antes de executar este projeto, você precisará de:

- **Mulesoft Anypoint Studio** instalado.
- Acesso a um **banco de dados** (MySQL, PostgreSQL, etc.).
- Dependências do projeto configuradas no **MuleSoft**.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/Benevanio/mulesoft-database
   ```

2. Abra o projeto no **MuleSoft Anypoint Studio**.

3. Configure a conexão com seu banco de dados no arquivo de configuração (ex: `mule-database-config.xml`).

4. Execute o projeto no **MuleSoft Anypoint Studio**.

5. Teste as operações realizando requests HTTP para a API (caso o fluxo esteja configurado para expor uma API).

## Componentes Utilizados

- **Database Connector**: Conecta a aplicação ao banco de dados.
- **Bulk Insert**: Insere grandes volumes de dados de uma só vez.
- **Bulk Update**: Atualiza múltiplos registros de forma eficiente.
- **Select**: Realiza consultas no banco de dados.
- **Execute DDL**: Executa comandos DDL para alterar a estrutura do banco.
- **Execute Script On Table**: Executa scripts personalizados no banco.

## Contribuição

1. Fork o repositório.
2. Crie uma branch para a sua feature: `git checkout -b minha-feature`.
3. Faça as modificações desejadas.
4. Commit as mudanças: `git commit -am 'Adiciona nova feature'`.
5. Envie para o repositório remoto: `git push origin minha-feature`.
6. Abra um pull request.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais informações.

---

**Divirta-se explorando o Mulesoft e aproveite a simplicidade da integração com bancos de dados!** 😄

---

Se você tiver alguma dúvida ou sugestão, não hesite em abrir uma **issue** ou enviar um **pull request**!
