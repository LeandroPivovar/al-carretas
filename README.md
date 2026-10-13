# AL Carretas

Site institucional da AL Carretas (carretas reboque para jet ski). HTML/CSS/JS estático, sem build.
Mesma estrutura dos outros sites da AROE, com as cores da carreta da foto do cliente: preto e azul,
e uma textura de chapa xadrez feita em CSS nos fundos.

```bash
npx --yes serve . -l 6480
```

## Estrutura

```
index.html
assets/
  css/styles.css
  js/main.js              menu mobile, formulário -> WhatsApp, FAQ, reveal ao rolar, ano do rodapé
  fonts/phosphor/         ícones Phosphor (woff2 local, licença MIT)
  img/
    carreta-jet.jpg       foto real, recortada da capa do WhatsApp (original com só 448x156 px)
    favicon.svg
```

## Dados usados (fonte: perfil do WhatsApp Business)

| Campo | Valor |
|---|---|
| Nome | AL Carretas (lido na lateral da carreta da foto; o perfil não tem nome, só o número) |
| WhatsApp | (62) 99265-1674 (`wa.me/556292651674`, constante `WA` no `main.js`) |
| Horário | 09:00 às 18:00 |
| Produto | carreta para jet ski (foto de capa e foto de perfil) |

## Confirmar com o cliente

- **Fabricam ou revendem?** A foto mostra uma oficina com várias carretas, então o site diz que a AL Carretas
  "faz" a carreta. Confirmar.
- **Linha de produtos:** só a carreta de jet ski é certa. O site menciona barcos/lanchas e "outros modelos" como
  consulta, sem afirmar. Pegar a lista real.
- **Itens da carreta:** estrutura reforçada, piso em chapa xadrez, rodas esportivas, guincho manual e faixas
  azuis foram descritos a partir da foto. Confirmar o que é de série e o que é opcional (LED, cores, rodas).
- **Documentação:** o FAQ só manda perguntar pelo WhatsApp. Se a carreta sai com nota e documentação para
  emplacar, vale destacar.
- **Cidade / endereço e dias de atendimento:** não informados (DDD 62, Goiás).
- **Telefone:** o perfil mostra `9265-1674`. O `wa.me` usa o número do perfil; o texto exibido e o `tel:` usam
  `(62) 99265-1674`, com o 9 do celular.
- **Fotos:** a única foto tem resolução muito baixa. Fotos boas das carretas (e de entregas) são o que mais
  falta neste site. Pedir também a logo.

## Depoimentos

Não foram incluídos, para não publicar avaliações inventadas.

Fontes: Saira e Barlow (Google Fonts, OFL).
