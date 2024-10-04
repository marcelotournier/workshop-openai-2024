# Bonus - Criando pesquisas avançadas usando o Notebook LM

# Site:
https://notebooklm.google

# Instruções:
- Acesse o site https://notebooklm.google
- Clique em "novo notebook"
- Clique em "adicionar fontes"
- Faça upload do arquivo [abstracts.txt](./abstracts.txt), que contém algumas dezenas de abstracts de papers relacionados a Ozempic e Diabetes
- Adicione o seguinte prompt ao NotebookLM:
```
Eu sou um cientista buscando informações para escrever uma revisão sobre Ozempic (Semaglutide) para tratamento de Diabetes.

O arquivo em anexo contém abstracts de clinical trials extraídos do Pubmed.

Faça um resumo crítico dos artigos, agrupando os artigos por desfechos clínicos semelhantes e cite pontos fortes e fracos de alguns estudos agrupados. Vincule referências bibliográficas para saber de quais estudos se está descrevendo.

Não utilize nenhuma informação sobre Ozempic (Semaglutide) que não esteja no arquivo em anexo.

O texto final deve ter o máximo de 2000 palavras.
```
- Caso necessário, adicione mais um prompt se ele solicitar mais contexto, por exemplo:
```
Diabetes, Ozempic e Obesidade
```
