# Bootcamp Microsoft Certification Challenge #1 - AI 102

## Tradutor de Artigos Técnicos com AzureAI

### O Que o Azure AI Oferece para Tradução?
O Azure AI disponibiliza dois serviços principais para tradução:

API REST de Tradução Multilíngue
Detecção de Idioma: Identifica automaticamente o idioma do texto.
Tradução de Uma para Muitos: Traduza um texto para múltiplos idiomas simultaneamente.
Transliteração de Script: Converte entre sistemas de escrita, como do japonês para romaji.
Como Funciona?
Detecção: A API analisa o idioma original.
Tradução: O texto é traduzido para os idiomas escolhidos.
Transliteração: Caso necessário, o texto pode ser convertido para outro alfabeto.
Tradução Personalizada
Criando um Modelo Personalizado
Configure seu modelo no Portal do Tradutor Personalizado.
Vincule um espaço de trabalho ao recurso de tradutor no Azure.
Carregue dados de treinamento para treinar o modelo.
Após o treinamento, chame o modelo personalizado pela API usando o parâmetro category.

### Exemplos Práticos com Python

- Tradução de documentos usando Python
- Traducao de paginas Web usando Python

