# Jurisprudência TJMT

### TJMT case law for Claude, Cursor and AI agents

Search case law from the Mato Grosso state court (TJMT) straight from Claude, ChatGPT or your own agent, covering cível, agrário e contratos rurais. Every ruling comes with the judging body, rapporteur, date, the exact snippet that matched your query and the link to the official site. The same connection reaches 16 other Brazilian courts. Free, no login, hosted by the platform.

- ⚖️ **TJMT** plus 16 other Brazilian courts on the same connection
- 🎯 **The snippet that actually MATCHED**, not the boilerplate opening every ruling shares
- 🔗 **Link to the official court site** on every result
- 📄 **Full text on demand** where the ruling allows it
- 🚦 **Says when it does not know**: an unavailable source becomes an explicit notice
- 🔒 **Read-only**
- ⚡ **Free, no login, no credentials**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue

[Versão em português](README.md) · [Full docs (PT-BR)](docs/) · [Agent skill](skills/)

---

## One-click install

### Claude (Web and Desktop)

Anthropic unified MCP installation at `claude.ai/customize/connectors`. **The same link works for Claude Web and Claude Desktop** (just be logged in):

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

**Manual** (if the deeplink does not open): [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → paste **Name** `Jurisprudência TJMT` and **URL** `https://api.mcp.ai/p_tjmt`.

### Cursor

[➕ Install Jurisprudência TJMT in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=tjmt&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF90am10In0=)

### VS Code (Copilot Chat)

[➕ Install Jurisprudência TJMT in VS Code](vscode:mcp/install?name=tjmt&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_tjmt%22%7D)

### ChatGPT, Manus, OpenClaw and 40+ other clients

Works with any MCP client that speaks **MCP over HTTP**. The server URL is always:

```
https://api.mcp.ai/p_tjmt
```

Per-client details: [INSTALL.md](INSTALL.md).

---

## Example prompts

```
Recent TJMT rulings on consumer damages
Compare TJMT and the Superior Court on limitation periods
Read the full text of the ruling you found and summarise the holding
```

---

## 3 tools available

| Tool | Description |
|---|---|
| `jurisprudencia_buscar` | Busca jurisprudência (acórdãos, súmulas, orientações jurisprudenciais, temas) por termo ou tese. |
| `jurisprudencia_sumulas` | Busca SÚMULAS (incluindo vinculantes) por termo. |
| `jurisprudencia_documento` | Lê o INTEIRO TEOR de uma decisão (texto completo do acórdão, não o resumo). |

Details for each tool: [docs/ferramentas.md](docs/ferramentas.md) (PT-BR)

---

## Pricing

Free.

---

## Privacy & data protection

- **Read-only**, no tool changes data at the source.
- **Sub-processors**: Serper (Google Search), the LLM host you choose (Claude, ChatGPT, Cursor, your own agent). Full list in [docs/privacidade-lgpd.md](docs/privacidade-lgpd.md).
- Data returned by the tools is sent to **the LLM host you choose**, a sub-processor outside our control. We recommend plans with training opt-out.

---

## FAQ

**O TJMT é o único tribunal?**
Não. A conexão serve 17 tribunais: além do TJMT, STF, STJ, TST, TRF3, TRF4, CARF e os demais tribunais de justiça estaduais. Restringir a busca ao TJMT é opcional, e comparar com as cortes superiores é uma pergunta só.

**Precisa de login ou cadastro?**
Não. É grátis e sem credencial, e você não precisa de conta em nenhum tribunal.

**Serve para citar em petição?**
Serve para encontrar e ler. Todo resultado traz o link no site oficial, e a conferência lá é obrigatória antes de citar.

**Por que uma busca voltou vazia?**
Quase sempre é vocabulário: o tribunal nomeia a tese de um jeito diferente do coloquial, e a resposta sugere o que tentar. Se a fonte estiver indisponível no momento, ela diz isso explicitamente, o que é diferente de a decisão não existir.

**O servidor é open source?**
O servidor é proprietário (hosted). Este repositório é o wrapper público com manifestos, docs e skills, tudo MIT.


---

## Support

- 📧 [tjmt@mcp.ai](mailto:tjmt@mcp.ai)
- 🐛 [GitHub Issues](https://github.com/mcp-dir/tjmt-mcp/issues)
- 📄 [docs/](docs/)

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_tjmt` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
