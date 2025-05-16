# Imersão-Alura

# SaúdeBot: Seu Assistente Inteligente para Artigos da Área da Saúde

O SaúdeBot é um protótipo de chatbot desenvolvido em Python para auxiliar na busca, resumo e tradução de artigos científicos da área da saúde. Utilizando inteligência artificial, ele visa facilitar o acesso à informação relevante para não desenvolvedores e profissionais da saúde.

## Funcionalidades

* **Busca de Artigos:** Permite buscar artigos científicos sobre um tema de saúde específico.
* **Resumo de Trechos:** Capacidade de resumir trechos relevantes dos artigos encontrados (a precisão pode variar).
* **Tradução de Trechos:** Permite traduzir trechos dos artigos para diferentes idiomas (a qualidade da tradução pode variar).

  ## Como Usar

1.  Abra o notebook `saudebot.ipynb` no Google Colab.
2.  Execute as células de código em sequência, começando pela instalação das bibliotecas e configuração da API.
3.  Quando o chatbot iniciar, siga as instruções para interagir:
    * Digite `buscar [tema]` para procurar artigos sobre um tema específico (ex: `buscar fibromialgia`).
    * Digite `resumir [número]` para obter um resumo do trecho do artigo correspondente ao número.
    * Digite `traduzir [número] [idioma]` para traduzir o trecho do artigo para o idioma desejado (ex: `traduzir 1 espanhol`). Se o idioma não for especificado, o padrão é português.
    * Digite `buscar novamente` para realizar uma nova busca.
    * Digite `sair` para encerrar o chatbot.

**Observação:** Este é um protótipo, e a precisão na extração de trechos e a qualidade das traduções podem variar dependendo da formatação dos resultados da busca e das capacidades do modelo de linguagem utilizado.

## Requisitos

* Acesso à internet.
* Uma conta Google (para usar o Google Colab).
* Uma chave de API do Google Generative AI (necessária para executar o código).

## AVISO

Este é um **protótipo** desenvolvido para fins de demonstração e aprendizado. A precisão na extração de informações e a qualidade das traduções podem variar. Não utilize as informações fornecidas pelo SaúdeBot para decisões médicas críticas. Sempre consulte um profissional de saúde qualificado.

## Próximos Passos (Ideias)

* Melhorar a lógica de extração de trechos relevantes dos artigos.
* Implementar a funcionalidade de tradução de artigos completos.
* Explorar outras funcionalidades úteis para a pesquisa em saúde.
* Adicionar suporte a diferentes modelos de linguagem.

  ## Autor

[Pedro Scarpa/Okaruner]
