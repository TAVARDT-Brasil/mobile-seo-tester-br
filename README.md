# Testador de SEO Mobile e Compatibilidade para Dispositivos Moveis

[![Mobile SEO Tester](https://img.shields.io/badge/TAVARDT-Mobile%20SEO-5b3cf5.svg)](https://tools.tavardt.com/br/teste-seo-mobile/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Auditoria tecnica de configuracao de viewport, responsividade, legibilidade tipografica e espacamento de elementos tateis segundo o Google Mobile-First Indexing.

Desenvolvido e mantido pela divisao de engenharia mobile e performance de busca da **TAVARDT**.

***

## Capacidades de Auditoria de SEO Mobile

* **Inspecao de Meta Viewport**: Validacao de `width=device-width, initial-scale=1.0` e deteccao de bloqueios prejudiciais como `user-scalable=no` ou `maximum-scale=1.0`.
* **Identificacao de Elementos Responsaveis**: Analise de tags de imagem e midia sem proporcoes flexiveis e verificacao de regras CSS de adaptabilidade.
* **Auditoria de Alvos de Toque (Tap Targets)**: Deteccao de botoes e links com dimensoes reduzidas ou espacamento inferior aos padroes ergonomicos minimos (48x48px).
* **Verificacao de Legibilidade Tipografica**: Identificacao de definicoes de fontes estaticas excessivamente pequenas que prejudicam a leitura sem ampliacao.
* **Pontuacao de Conformidade Mobile-First**: Indice quantitativo de 0 a 100 com detalhamento de falhas tecnicas segundo as diretrizes do Google Mobile-First Indexing.

***

## Instalacao e Execucao

Requer Python 3.8 ou superior sem necessidade de pacotes externos adicionais.

```bash
git clone https://github.com/TAVARDT-Brasil/mobile-seo-tester-br.git
cd mobile-seo-tester-br
python mobile_seo_tester.py https://empresa.com.br
```

Para gerar relatorio estruturado em formato JSON:

```bash
python mobile_seo_tester.py https://empresa.com.br -json
```

***

## Diagnostico Completo na Web

Para auditoria visual completa e teste de renderizacao de dispositivos moveis:

* **Teste de SEO Mobile Oficial**
* **[Portal Corporativo TAVARDT](https://ag.tavardt.com/br/)**

***

## Consultoria em Otimizacao Mobile e SEO Tecnico

Para suporte avancado em responsividade e conformidade com Diretrizes Google Mobile-First Index e W3C Responsive Standards, consulte os especialistas da **TAVARDT**.

***

## Links Úteis

* **Portal Corporativo:** https://ag.tavardt.com/br/
* **Suíte de Diagnósticos:** https://tools.tavardt.com/br/
* **Contato Técnico:** https://ag.tavardt.com/br/contato/

***

### Licença
Distribuído sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes completos.

***

© 2026 TAVARDT. Todos os direitos reservados.
