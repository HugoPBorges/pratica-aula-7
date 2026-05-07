## Dependências Versionadas

O projeto utiliza controle de dependências baseado em **Versionamento Semântico (Semantic Versioning)** para garantir compatibilidade, previsibilidade e estabilidade nas atualizações.

### Lista de Dependências

| Dependência | Versão |
|---|---|
| `@react-pdf/renderer` | `^4.1.3` |
| `@testing-library/jest-dom` | `^5.17.0` |
| `@testing-library/react` | `^13.4.0` |
| `@testing-library/user-event` | `^13.5.0` |
| `axios` | `^1.7.7` |
| `bootstrap` | `^5.3.3` |
| `boxicons` | `^2.1.4` |
| `chart.js` | `^4.4.5` |
| `chartjs-plugin-datalabels` | `^2.2.0` |
| `js-cookie` | `^3.0.5` |
| `js-cookies` | `^1.0.4` |
| `jwt-decode` | `^4.0.0` |
| `pdfjs-dist` | `^4.8.69` |
| `qrcode.react` | `^4.1.0` |
| `react` | `^18.3.1` |
| `react-datepicker` | `^7.5.0` |
| `react-dom` | `^18.3.1` |
| `react-pdf` | `^9.1.1` |
| `react-router-dom` | `^6.28.0` |
| `react-scripts` | `5.0.1` |
| `web-vitals` | `^2.1.4` |

---

# Política de Versionamento

O projeto segue o padrão de **Versionamento Semântico**, utilizando o formato:

```text
MAJOR.MINOR.PATCH
```

Exemplo:

```text
4.1.3
│ │ └── PATCH
│ └──── MINOR
└────── MAJOR
```

## Significado de cada nível

| Nível | Nome | Quando é alterado |
|---|---|---|
| `MAJOR` | Versão principal | Mudanças incompatíveis com versões anteriores |
| `MINOR` | Funcionalidades | Inclusão de novas funcionalidades mantendo compatibilidade |
| `PATCH` | Correções | Ajustes internos, correções de bugs e melhorias menores |

---

## Uso do caractere `^`

Grande parte das dependências utiliza o prefixo:

```json
"react": "^18.3.1"
```

O caractere `^` permite atualizações automáticas apenas para versões compatíveis dentro da mesma versão principal (**MAJOR**).

### Atualizações permitidas

| Versão Atual | Pode atualizar para |
|---|---|
| `^18.3.1` | `18.3.2` |
| `^18.3.1` | `18.4.0` |
