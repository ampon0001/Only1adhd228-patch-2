Executa o comando `mvn --batch-mode` para publicar em {% data variables.product.prodname_registry %}. A variável de ambiente `GITHUB_TOKEN` será definida com o conteúdo do segredo `GITHUB_TOKEN`. {% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@3.1" or currentVersion == "github-ae@next" %}The `permissions` key specifies the access granted to the `GITHUB_TOKEN`.{% endif %}