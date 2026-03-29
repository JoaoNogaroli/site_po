# PO Interativa 🔬

Aplicação web para resolver problemas de **Programação Linear** diretamente no browser, sem servidor.

## Demo

O solver resolve um problema clássico de **mix de produção**:
- Dois produtos (A e B) competem por recursos limitados
- Cada produto tem lucro, consumo de máquina e mão de obra diferentes
- Objetivo: maximizar o lucro total

## Tecnologia

- **[javascript-lp-solver](https://github.com/JWally/jsLPSolver)**: Implementação do Simplex em JavaScript puro
- Roda 100% no browser (client-side)
- Zero dependências de backend
- Hospedável em qualquer servidor de arquivos estáticos

## Como usar

### Opção 1: GitHub Pages (recomendado)

1. Faça fork ou clone este repositório
2. Vá em **Settings** → **Pages**
3. Em "Source", selecione **Deploy from a branch**
4. Escolha a branch `main` e pasta `/ (root)`
5. Clique em **Save**
6. Aguarde ~1 minuto e acesse: `https://SEU-USUARIO.github.io/NOME-DO-REPO`

### Opção 2: Localmente

Basta abrir o `index.html` no browser. Não precisa de servidor.

```bash
# Ou se quiser um servidor local:
npx serve .
# ou
python -m http.server 8000
```

## Estrutura do projeto

```
/
├── index.html    # Aplicação completa (HTML + CSS + JS)
└── README.md     # Este arquivo
```

## Expandindo o projeto

Algumas ideias para continuar:

- [ ] Adicionar mais tipos de problema (mochila, transporte, designação)
- [ ] Visualização gráfica da região viável
- [ ] Análise de sensibilidade
- [ ] Exportar/importar modelos em JSON
- [ ] Suporte a variáveis inteiras (MILP)

## Licença

MIT - use como quiser!

---

Feito durante o mestrado em PO na UFRGS 🎓
