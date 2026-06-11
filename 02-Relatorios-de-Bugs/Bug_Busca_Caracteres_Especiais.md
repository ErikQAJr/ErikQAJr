RELATÓRIO DE BUG: Falha na Busca com Caracteres Especiais
Título do Bug: [Busca] Sistema retorna resultados aleatórios ao pesquisar apenas por caracteres especiais

ID do Teste Origem: CT-004

Ambiente: Google Chrome (Versão Atualizada) / Produção (Site Oficial)

Passos para Reproduzir:

Acessar a homepage: www.mercadolivre.com.br

Clicar na barra de pesquisa superior.

Digitar exclusivamente a string de caracteres especiais: %$#@!&*()

Pressionar Enter ou clicar na lupa de busca.

Resultado Esperado:
O sistema deveria identificar que a busca é inválida e exibir uma mensagem de sistema vazia amigável (ex: "Não encontramos anúncios com esses termos"), sem carregar nenhum produto.

Resultado Atual (Bug):
O sistema aceita a busca e retorna uma lista com 13 resultados aleatórios (celulares Motorola, tablets e relógios digitais), exibindo no topo da tela os caracteres como se fossem um termo válido.

Severidade: Baixa (Não impede o usuário de usar o sistema ou comprar).
Prioridade: Baixa (Pode ser corrigido nas próximas atualizações sem pressa).
