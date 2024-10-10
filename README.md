[![ci/cd](https://github.com/herlandio/teste-tecnico-webjump-gerenciamento-de-produtos/actions/workflows/cicd.yml/badge.svg)](https://github.com/herlandio/teste-tecnico-webjump-gerenciamento-de-produtos/actions/workflows/cicd.yml)

# [Teste técnico WebJump] Sistema básico de gerenciamento de produtos | categorias

O sistema foi criado com arquitetura MVC, composer para gerenciar dependências, para gerenciar rotas foi utilizado bramus router,
foi adicionado a cdn bootstrap | font awesome | sweet alert | javascript para o front-end, no back-end foi utilizado PHP puro orientado a objetos
com banco de dados mysql (PDO e transactions).

OBS: No teste não foi solicitado K8s, docker

- Clone o repositorio

```
git clone https://github.com/herlandio/gerenciamento-de-produtos.git
```

- Basta executar: `kubectl apply -f k8s/` para subir a aplicação.

- Para rodar a aplicação deverá ter o docker e k8s habilitado!
- Acesse a aplicação em `http://localhost`
