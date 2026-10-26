# Roboeduc AI Create

Protótipo educacional de um pequeno modelo de linguagem Transformer treinado do zero no navegador.

## Como usar
1. Abra `index.html` num navegador com internet (TensorFlow.js é carregado por CDN).
2. Edite o corpus de texto.
3. Clique em **Treinar do zero** e aguarde o treinamento.
4. Teste prompts com palavras que existam no vocabulário treinado.

## Limitações
- Não usa pesos pré-treinados nem API de chatbot.
- O vocabulário é simples, baseado em palavras e pontuação, não em BPE.
- O treinamento é pequeno e ocorre no dispositivo; respostas incoerentes são esperadas.
- Os pesos não persistem ao fechar/recarregar a página; o corpus pode ser salvo localmente.
- Não insira informações pessoais no corpus.
