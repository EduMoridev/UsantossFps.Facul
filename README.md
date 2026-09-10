# FRAMELAB — Entrega 1 (fundação em HTML)

Projeto acadêmico: website institucional em HTML puro, sem CSS/estilização,
para a organização **FRAMELAB — Otimização de Performance para Jogos**.

---

## 1. Integrantes do grupo

| Nome completo | RGM | Usuário GitHub |
|---|---|---|
| [NOME COMPLETO 1] | [RGM 1] | [@usuario1] |
| [NOME COMPLETO 2] | [RGM 2] | [@usuario2] |

> Preencher com os dados reais de todos os integrantes antes da entrega.

---

## 2. Link do site e validação W3C

- **Site hospedado:** [COLAR AQUI o link do GitHub Pages ou Netlify após publicar]
- **Validação W3C:** todas as 10 páginas foram checadas em https://validator.w3.org/
  (opção "Validate by File Upload" ou "Validate by Direct Input").
  [COLAR AQUI um print ou link do resultado "Document checking completed. No errors
  or warnings to show." para cada página, ou pelo menos para a página inicial.]

Para validar localmente antes de subir para o W3C:
1. Acesse https://validator.w3.org/#validate_by_upload
2. Envie cada arquivo `.html` (index, sobre, servicos, planos, resultados,
   depoimentos, como-funciona, faq, contato, orcamento)
3. Corrija qualquer erro apontado antes da entrega final

---

## 3. Introdução

A FRAMELAB é uma organização que presta serviço de otimização remota de
computadores para jogos: ajustes de sistema operacional, drivers, BIOS e rede
para aumentar FPS e reduzir latência, sem necessidade de troca de hardware.
Esta Entrega 1 corresponde à fundação em HTML do site institucional da
organização, ainda sem estilização visual (CSS será adicionado na Entrega 2).

[EXPANDIR: contar brevemente a história/contexto real da organização —
quando começou, que problema resolve, para quem atende.]

---

## 4. Contato com o responsável

**Formato da entrevista:** [presencial / Zoom / Google Meet]
**Data:** [DD/MM/AAAA]
**Responsável entrevistado:** [NOME e CARGO/FUNÇÃO na organização]

**Comprovação:**

[INSERIR AQUI a foto/print que comprove a entrevista — por exemplo, um
print da chamada de Zoom/Meet com data e horário visíveis, ou uma foto do
encontro presencial. Adicionar o arquivo de imagem neste repositório
(ex.: `docs/entrevista.png`) e referenciá-lo aqui com
`![Entrevista com o responsável](docs/entrevista.png)`.]

**Relato da entrevista:**

[DESCREVER o que foi conversado: como a organização começou, quais são os
principais desafios do negócio hoje, o que o responsável espera do site,
quais informações ele considerou mais importantes de estarem no site.
Mínimo recomendado: um parágrafo.]

> Conversas apenas por WhatsApp/Discord não são aceitas como comprovação —
> é necessário áudio/vídeo (Zoom, Meet) ou encontro presencial.

---

## 5. Conclusão

[ESCREVER a reflexão do grupo sobre os aprendizados desta etapa: o que foi
mais difícil em estruturar o conteúdo apenas com HTML semântico (sem CSS),
o que a entrevista com o responsável mudou na forma de organizar as
páginas, e o que o grupo pretende ajustar na Entrega 2.]

---

## Estrutura do repositório

```
index.html            Página inicial
sobre.html             Quem faz (institucional)
servicos.html          Lista de serviços
planos.html            Planos e preços
resultados.html        Cases de antes/depois (inclui vídeo)
depoimentos.html       Depoimentos de clientes (inclui áudio)
como-funciona.html     Processo em 5 etapas (inclui vídeo)
faq.html                Perguntas frequentes (com <details>/<summary>)
contato.html            Formulário de contato com validação HTML5
orcamento.html          Formulário de pedido de orçamento com validação HTML5
README.md               Este arquivo
```

## Como rodar localmente

Não há build nem dependências — é HTML puro. Basta abrir `index.html`
diretamente no navegador, ou servir a pasta com qualquer servidor estático
(ex.: extensão "Live Server" do VS Code).

## Como publicar no GitHub Pages

1. Suba os arquivos para um repositório público no GitHub.
2. Vá em **Settings → Pages**.
3. Em "Branch", selecione `main` e a pasta `/ (root)`.
4. Salve e aguarde alguns minutos — o link aparecerá na própria página de Pages.
5. Cole o link no topo deste README, na seção 2.

## Requisitos atendidos nesta entrega

- [x] 10 páginas HTML interligadas: index, contato, orçamento + 7 páginas de
      conteúdo (sobre, serviços, planos, resultados, depoimentos,
      como-funciona, faq)
- [x] Estrutura semântica em todas as páginas: `header`, `nav`, `main`,
      `section`, `article`, `footer` (e complementarmente `figure`,
      `table`, `address`, `details`/`summary`, `time`, `data`)
- [x] Formulário de contato e formulário de orçamento com validação nativa
      HTML5 (`required`, `pattern`, `type="email"`, `type="tel"`,
      `type="number"`, `minlength`/`maxlength`)
- [x] Recursos de áudio (`depoimentos.html`) e vídeo (`resultados.html` e
      `como-funciona.html`)
- [ ] Validação W3C sem erros — **pendente de execução e comprovação** (ver
      seção 2)
- [ ] Hospedagem pública — **pendente de publicação** (ver seção 2)
