# Boas práticas utilizando o git.

## Conventional Commits
link: https://www.conventionalcommits.org/pt-br/v1.0.0/#resumo
---

<tipo> [escopo opcional]: <descrição>

[corpo opcional]

[Rodapé(s) opcional(is)]

1. fix: soluciona um problemda
fix(database): resolve problema de consulta SQL incorreta

2. feat: Adiciona um novo recurso no código(nova feature)
feat(auth): adiciona autenticação por token

3. BREAKING CHANGE: é o rodapé opcional do commit ``` BREAKING CHANGE```,  ou
contém o símbolo ! depois do tipo/escopo, introduz uma modificação que quebra a compatibilidade da API. Um BREAKING CHANGE pode fazer parte de commits de qualquer tipo.

4. build: Alterações que afetam o sitema de compilação ou dependencias externas (npm, gulp, broccoli).

5. ci: Alterações em nossos arquivos e scripts de configuração de CI(Travis, Circle, github actions).

6. docs: Apenas documentação
docs(readme): atualizações na documentação do README

7. style: Mudanças que não afetam o significado do código (espaço em branco, formatação falta de ponto-e-vírgula, etc).

8. refactor: Uma alteração que não corrige um bug, nem adiciona um novo recurso.
refactor(utils): reestrutura a função de utilidade

9. perf: Mudança de código que melhora performance
perf(api): otimiza a busca de dados

10. test: Adiciona testes ausentes ou corrigindo testes existentes.
test(api): adiciona casos de teste para a API de usuário

11. chore: Indica mudanças no proejto que não afetem o sistema ou arquivos de teste. São mudanças de desenvolvimento.

12. revert: Indica a reversão de um commit anterior.

## Exemplo de um commit seguindo o padrão
```
fix(lista-ofertas): ajusta barra de rolagem horizontal para usuários windows

Como usuários de windows não tem magic mouse, a rolagem horizontal na lista de ofertas de um job ficou ruim.
Foi criada uma verificação do sistema operacional para mudar o comportamento da rolagem horizontal para usuários de MACe de windows

Issue TP-123456
```


