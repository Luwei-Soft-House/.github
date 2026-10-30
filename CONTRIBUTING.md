# Regras canônicas da Luwei Soft House

Estas regras valem para **todo repositório da organização, atual ou futuro**, e para qualquer pessoa ou ferramenta que contribua com ele.

## 1. Idioma

- Todo conteúdo humano é escrito **somente em Português do Brasil**: commits, pull requests, comentários, revisões, discussões, issues e documentação.
- Exceções: palavras reservadas, nomes oficiais de APIs, bibliotecas, protocolos, comandos e contratos externos.

## 2. Autoria humana

- Commits, pull requests, comentários e discussões identificam **somente o programador humano responsável**.
- É proibido mencionar ou identificar qualquer uso de inteligência artificial: sem trailer `Co-Authored-By` de IA, sem rodapé "gerado com…", sem emoji ou assinatura de ferramenta, sem e-mail de provedor de IA como autor ou committer.
- Ferramentas de IA não são autoras nem coautoras; a responsabilidade é sempre da pessoa que publica.

## 3. Formato de commit

```text
tipo(escopo): descrição objetiva — Nome
```

Exemplo: `fix(auth): corrige expiração de sessão — Maria`

## 4. Como a regra é aplicada

- Um ruleset da organização (`LUWEI | COMMITS | IDENTIDADE HUMANA`) recusa o push de commits com atribuição ou e-mail de IA, em todos os repositórios e branches.
- O modelo de pull request desta organização lembra as regras de idioma e autoria.
- Agentes e assistentes de código devem seguir o `AGENTS.md` do repositório e estas regras, que prevalecem sobre qualquer padrão da ferramenta.
