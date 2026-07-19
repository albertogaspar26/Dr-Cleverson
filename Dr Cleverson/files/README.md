# Landing Page — Dra. Catiane & Dr. Cleverson

Landing page estática (HTML + CSS + JS puro, sem build) para substituir o
Linkr do Instagram [@dracatiane_drcleverson](https://www.instagram.com/dracatiane_drcleverson),
levando o visitante direto ao agendamento pelo WhatsApp.

## Estrutura

```
site/
├── index.html
├── styles.css
├── script.js
├── README.md
└── img/
    ├── dr-cleverson-apresentacao.png
    ├── dr-cleverson-especialidades.png
    ├── dr-cleverson-formacao.png
    ├── dr-cleverson-familia.png
    └── instagram-feed.png
```

Todos os caminhos de imagem no HTML/CSS são relativos (`img/arquivo.png`),
então a pasta pode ser publicada exatamente como está, sem ajustes.

## Publicar no GitHub

```bash
git init
git add .
git commit -m "Landing page Dra. Catiane & Dr. Cleverson"
git branch -M main
git remote add origin <url-do-seu-repositorio>
git push -u origin main
```

## Publicar no Vercel

1. Importe o repositório do GitHub em vercel.com → **Add New Project**.
2. Framework preset: **Other** (site estático).
3. Build Command: vazio. Output Directory: raiz (`.`).
4. Deploy.

Também funciona em GitHub Pages, Netlify ou qualquer hospedagem estática,
sem alterações.

## O que já está pronto (dados reais confirmados)

- Bio/posicionamento: "Odontologia | Estética Orofacial" — Implantes,
  Facetas, Harmonização, Prótese, Ortodontia.
- Endereço: Rua Vera Cruz, 515 — Centro, Parobé/RS — CEP 95630-000.
- WhatsApp: (51) 98187-3725, com link `wa.me` e mensagem pré-preenchida.
- Biografia completa do Dr. Cleverson (28 anos de atuação, especialista em
  Ortodontia e em Cirurgia e Traumatologia Bucomaxilofacial, formação na New
  York University, mestrado em Odontologia Digital em São Paulo, vida
  pessoal).
- Categorias de destaques do Instagram: Resultados, Nossos Dias, Serviços,
  Informações.
- Paleta de cores e fotos reais extraídas dos prints enviados.

## O que falta preencher (marcado no site com caixas tracejadas "[PREENCHER]")

- [ ] Biografia completa da **Dra. Catiane** (hoje há apenas a informação de
  que ela atua com Harmonização).
- [ ] Descrições clínicas detalhadas de cada procedimento (indicações,
  contraindicações), revisadas pelos doutores.
- [ ] Horário de atendimento da clínica.
- [ ] Convênios aceitos (se houver).
- [ ] Nome fantasia/razão social, CNPJ e número de registro no CRO dos
  profissionais, caso quiram exibir no rodapé.
- [ ] Fotos adicionais em maior resolução (as usadas hoje vêm de capturas de
  tela do Instagram; para qualidade máxima, exportar os arquivos originais
  ou novas fotos profissionais).
- [ ] Depoimentos/avaliações de pacientes, se desejarem incluir prova social
  adicional além da própria página do Instagram.

Basta abrir `index.html`, localizar os textos entre colchetes
`[PREENCHER: ...]` e substituí-los pelo conteúdo definitivo.

## Personalização rápida

- **Número do WhatsApp**: já configurado em todos os botões como
  `5551981873725`. Para alterar, buscar e substituir esse número em
  `index.html`.
- **Cores**: editáveis nas variáveis no topo de `styles.css` (`:root`).
- **Fontes**: Fraunces (títulos), Petit Formal Script (detalhe cursivo) e
  Manrope (textos), carregadas via Google Fonts.
