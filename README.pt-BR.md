# Love Maths walkthrough

Jogo de aritmética no navegador com adição, subtração, multiplicação, divisão, verificação de respostas e contadores.

[English](README.md)

## Ideia e processo

Código revisado em 01/10/2026. Walkthrough educacional baseado em material do Code Institute. Não foram encontrados planejamento datado, wireframes ou diário pessoal de design nos arquivos revisados. Registro do exercício, não história original de produto.

## Arquitetura e design

index.html fornece botões, operandos, entrada e placares. assets/js/script.js registra clique/Enter, gera números de 1 a 25 e guarda estado visível no DOM. Subtração ordena operandos para evitar negativos; divisão usa produto dividido pelo menor operando, gerando inteiro. Sem backend ou persistência de placar. Interface usa cores por operação, ícones e Google Fonts.

## Preview local

```bash
python3 -m http.server 8000
```

Abra `http://localhost:8000/`. Fontes/ícones/imagens externas precisam de rede. Preview não executado nesta atualização; deploy público atual não confirmado.

## Testes e limites

Suíte automatizada não encontrada na listagem revisada da raiz. Testes de navegador/manuais não executados. Verifique quatro operações, Enter/botão, foco, placar e recarregamento. parseInt trunca decimais; vazio vira NaN e conta como erro. Link do CSS em index.html não fecha com >. Revise nomes acessíveis de botões só com ícones e da entrada. Observações não são aprovação de testes.

## Capturas

Nenhuma captura de aplicação verificada ou adicionada. Arquivos futuros datados em `docs/assets/` devem mostrar estados reais desktop/mobile, sem dados pessoais de formulário. Só adicione links após arquivos existirem, sem inventar estado funcional.

## Créditos e licença

Material de curso/template Code Institute, bibliotecas e assets mantêm direitos originais. Nenhuma licença nova. README original mantido no [apêndice em inglês](README.md#original-readme), como fonte histórica.
