
# Mintlify ZENTEK

Clique em `Use this template` para copiar o kit inicial do Mintlify. O kit inicial contém exemplos, incluindo:

- Páginas de guias
- Navegação
- Personalizações
- Páginas de referência de API
- Uso de componentes populares

### Desenvolvimento

Instale o [Mintlify CLI](https://www.npmjs.com/package/mintlify) para visualizar as alterações na documentação localmente. Para instalar, use o seguinte comando:

```
npm i -g mintlify
```

Execute o seguinte comando na raiz da sua documentação (onde o arquivo `mint.json` está localizado):

```
mintlify dev
```

### Publicação de Alterações

Instale nosso aplicativo do GitHub para propagar automaticamente as alterações do seu repositório para a sua implantação. As alterações serão implantadas automaticamente em produção após serem enviadas para o branch padrão. Encontre o link para instalação no seu painel de controle.

#### Solução de Problemas

- Mintlify dev não está rodando: Execute `mintlify install` para reinstalar as dependências.
- A página carrega como um erro 404: Certifique-se de estar executando em uma pasta que contém o arquivo `mint.json`.
