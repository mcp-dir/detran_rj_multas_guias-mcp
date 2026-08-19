# DETRAN RJ: Multas (Guia de Recolhimento de Multas)

### DETRAN RJ: Multas (Guia de Recolhimento de Multas) para Claude, ChatGPT e agentes de IA

DETRAN RJ: Multas (Guia de Recolhimento de Multas), consulta em fonte oficial. Hospedado pela plataforma, sem credenciais da plataforma, pague por consulta com crédito pré-pago.

- 📊 **1 ferramenta**
- 🔒 **Somente leitura**
- 💬 **Funciona com qualquer cliente MCP**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Login via magic-link (sem senha)**

[English version](README.en.md) · [Documentação completa](docs/) · [Skill pra agentes](skills/)

---

## Instalar em 1 clique

### Claude (Web e Desktop)

A Anthropic unificou a instalação de MCPs em `claude.ai/customize/connectors`. **O mesmo link serve pra Claude Web e Claude Desktop** (basta estar logado):

[➕ Abrir no Claude e conectar](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (se o deeplink não abrir): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Adicionar conector personalizado** → cole **Nome** `DETRAN RJ: Multas (Guia de Recolhimento de Multas)` e **URL** `https://api.mcp.ai/p_detran_rj_multas_guias`.

### Cursor

[➕ Instalar DETRAN RJ: Multas (Guia de Recolhimento de Multas) no Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=detran_rj_multas_guias&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9kZXRyYW5fcmpfbXVsdGFzX2d1aWFzIn0=)

### VS Code (Copilot Chat)

[➕ Instalar DETRAN RJ: Multas (Guia de Recolhimento de Multas) no VS Code](vscode:mcp/install?name=detran_rj_multas_guias&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_detran_rj_multas_guias%22%7D)

### ChatGPT, Manus, OpenClaw e mais 40+ clientes

Funciona em qualquer cliente MCP que suporte **MCP over HTTP**. A URL do servidor é sempre:

```
https://api.mcp.ai/p_detran_rj_multas_guias
```

Detalhes por cliente: [INSTALL.md](INSTALL.md).

---

## Exemplos de uso

```
Consultar DETRAN RJ: Multas (Guia de Recolhimento de Multas)
```

---

## 1 ferramenta disponível

| Tool | Descrição |
|---|---|
| `detran_rj_multas_guias_consultar` | DETRAN RJ: Multas (Guia de Recolhimento de Multas), consulta em fonte oficial. |

Detalhe de cada tool: [docs/ferramentas.md](docs/ferramentas.md)

---

## Preços

Pré-pago (carteira de créditos), paga por uso. Veja [docs/precos.md](docs/precos.md).

---

## Privacidade & LGPD

- **Somente leitura**, nenhuma ferramenta altera dados na origem.
- **Sub-processadores**: o LLM host que você escolher (Claude, ChatGPT, Cursor, agente próprio). Lista completa em [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Os dados retornados pelas tools são enviados ao **LLM host que você escolher**, sub-processador fora do nosso controle. Recomendamos planos com opt-out de treinamento.

---

## Perguntas frequentes

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills — tudo MIT.

**Posso usar com agente próprio (não Claude/Cursor)?**
Sim — qualquer cliente que suporte MCP over HTTP. URL: `https://api.mcp.ai/p_detran_rj_multas_guias`.


---

## Suporte

- 📧 [detran_rj_multas_guias@mcp.ai](mailto:detran_rj_multas_guias@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/detran_rj_multas_guias-mcp/issues)
- 📄 [docs/](docs/)

---

## Licença

MIT — veja [LICENSE](LICENSE). O servidor MCP em `api.mcp.ai/p_detran_rj_multas_guias` é proprietário (hosted); este repositório (manifestos, docs, skills) é MIT.
