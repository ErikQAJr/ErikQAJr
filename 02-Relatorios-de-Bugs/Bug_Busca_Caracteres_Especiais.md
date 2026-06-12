RELATÓRIO DE BUG: Falha na Busca com Caracteres Especiais
Título do Bug: [Busca] Sistema retorna resultados aleatórios ao pesquisar apenas por caracteres especiais

ID do Teste Origem: CT-004

Ambiente: Google Chrome (Versão Atualizada) / Produção (Site Oficial)

Passos:

° Navegador Chrome atualizado.

1  Acessar a homepage: www.mercadolivre.com.br

2  Clicar na barra de pesquisa superior.

3  Digitar exclusivamente a string de caracteres especiais: %$#@!&*()

4  Pressionar Enter ou clicar na lupa de busca.

Resultado Esperado:
O sistema deveria identificar que a busca é inválida e exibir uma mensagem de sistema vazia amigável (ex: "Não encontramos anúncios com esses termos"), sem carregar nenhum produto.

Resultado Atual (Bug):
O sistema aceita a busca e retorna uma lista com 13 resultados aleatórios (celulares Motorola, tablets e relógios digitais), exibindo no topo da tela os caracteres como se fossem um termo válido.

Severidade: Baixa (Não impede o usuário de usar o sistema ou comprar).
Prioridade: Baixa (Pode ser corrigido nas próximas atualizações sem pressa).

STATUS: 🔴 Aberto (Aguardando Correção).
_______________________________________________________

CASO DE TESTE: CT-005- Filtro de Preço com Valores Invertidos (Cenário de Exceção)

Pré-Condição:

° Navegador Chrome atualizado.

° Acesso a uma página de busca ou categoria de produtos na Shopee.

PASSOS:

1  Acessar www.shopee.com.br e realizar uma busca de qualquer produto

2  Localizar a seção "Filtro de Preço" no menu lateral esquerdo.

3  Digitar o valor 500 no campo "MINIMO"

4  Digitar o valor 10 no campo "MÁXIMO"

5  Clicar no botão "Aplicar" 

RESULTADO ESPERADO:
O Sistema não deve aplicar o filtro nem realizar a busca. ele deve bloquear a ação e exibir uma mensagem amigável ao usuário informando que a faixa de valores é inválida

RESULTADO OBTIDO:
O Sistema bloqueou o filtro corretamente e exibiu a mensagem de alerta esperada: "INSIRA UMA FAIXA DE PREÇO VÁLIDA". Nenhuma querbra de layout ou lentidão foi observada. 

STATUS: ✅ Passou
