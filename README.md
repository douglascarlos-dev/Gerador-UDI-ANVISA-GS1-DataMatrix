# Gerador UDI ANVISA (GS1 DataMatrix)

### Esse projeto faz parte dos meus estudos sobre desenvolvimento Web Front-End e Rastreabilidade

Aplicativo Web para gerar códigos GS1 DataMatrix (ECC200) voltados à Identificação Única de Dispositivos Médicos (UDI), em conformidade com as exigências da ANVISA e padrões GS1. No seu desenvolvimento foi utilizado HTML, CSS, JavaScript (Vanilla JS), Font Awesome, BWIP-JS e Google Fonts.

## Novidades e Funcionalidades Atuais:

- **Suporte a múltiplos Application Identifiers (AIs):** Preenchimento e estruturação seguindo rigorosamente a ordem **01, 17, 10, 90, 240, 11 e 21**:
  - **(01)** GTIN-14 (com validação nativa de *checksum*)
  - **(17)** Data de Validade (YYMMDD)
  - **(10)** Número do Lote
  - **(90)** Informação do Usuário / Registro
  - **(240)** Identificação Adicional
  - **(11)** Data de Fabricação (YYMMDD)
  - **(21)** Número de Série
- **Preenchimento Automático via URL:** Carregamento automático dos campos e geração imediata do DataMatrix ao acessar a página com parâmetros na URL (`ai01`, `ai17`, `ai10`, `ai90`, `ai240`, `ai11`, `ai21`).
- **Download em PNG:** Botão dedicado para baixar diretamente a imagem em alta resolução do código DataMatrix gerado.
- **Link Compartilhável:** Geração automática de um link direto contendo todos os parâmetros da consulta atual.

## Recursos usados no desenvolvimento:

- HTML5;
- CSS3 (CSS Grid, Flexbox e Design System nativo com Variáveis CSS);
- JavaScript (Vanilla JS - ES6+);
- [BWIP-JS](https://github.com/bwipp/bwip-js) v3.0.0;
- [Font Awesome](https://fontawesome.com/) v6.4.0;
- [Google Fonts](https://fonts.google.com/) (Inter e JetBrains Mono);
- [Git](https://git-scm.com);
- [Visual Studio Code](https://github.com/Microsoft/vscode/);

## Obtendo uma cópia:

```shell
# Antes de tudo, clone o projeto
$ git clone [https://github.com/douglascarlos-dev/Gerador-UDI-ANVISA-GS1-DataMatrix.git](https://github.com/douglascarlos-dev/Gerador-UDI-ANVISA-GS1-DataMatrix.git)