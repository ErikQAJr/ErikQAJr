Teste de Software: Fundamentos e Prática 

caso de test: CT-001- login do Mercado Livre com Email Valido 

PASSOS:
1. Acessar www.mercadolivre.com.br
2. Clicar no botão "Entrar"
3. Digitar email no campo "Email"
4. Digitar senha no campo "Senha"
5. Clicar em "Entrar"

RESULTADO ESPERADO:
- Login realizado com sucesso✅
- Usuário redirecionado para homepage logado✅
- Nome do usuário exibido no menu superior✅

RESULTADO OBTIDO:O procedimento de test de login com email valido foi obtido êxito, todos campos estão funcionando  

STATUS: ✅ Passou 
__________________________________________________________________________

CASO DE TESTE: CT-002 - Busca de Produto Específico (Caminho Feliz)
PRÉ-CONDIÇÃO:

Navegador Chrome atualizado aberto

Acesso à homepage do Mercado Livre

PASSOS:

Acessar www.mercadolivre.com.br

Clicar na barra de pesquisa no topo da página

Digitar o texto "Notebook Dell Inspiron"

Pressionar a tecla Enter ou clicar no ícone de lupa

RESULTADO ESPERADO:

O sistema deve carregar uma nova página com a lista de resultados contendo produtos relacionados a Notebook Dell Inspiron

O termo pesquisado deve permanecer visível na barra de busca superior

RESULTADO OBTIDO:
O sistema carregou com sucesso a página de busca, exibindo as opções do notebook pesquisado na listagem inferior e mantendo o termo "Notebook Dell Inspiron" em destaque na barra de pesquisa superior.

STATUS: ✅ Passou

__________________________________________________________________________

CASO DE TESTE: CT-003 - Login com Formato de E-mail Inválido (Cenário de Erro)
PRÉ-CONDIÇÃO:

Navegador Chrome atualizado aberto

Acesso à homepage do Mercado Livre

PASSOS:

Acessar www.mercadolivre.com.br

Clicar no botão "Entrar" no menu superior

Digitar no campo de e-mail o valor com formato inválido: erik.com@

Clicar no botão "Continuar"

RESULTADO ESPERADO:

O sistema não deve permitir o avanço para a tela de preenchimento de senha

O sistema deve travar o fluxo e exibir uma mensagem de erro clara alertando o usuário sobre o formato incorreto do e-mail

RESULTADO OBTIDO:
O sistema bloqueou corretamente o avanço para a tela de senha e exibiu a mensagem de atenção: "VERIFIQUE O DADO OU DIGITE O TELEFONE ASSOCIADO À SUA CONTA", alertando que o e-mail digitado estava inválido.

STATUS: ✅ Passou

__________________________________________________________________________

CASO DE TESTE: CT-004 - Busca com Caracteres Especiais (Cenário de Erro)

__________________________________________________________________________


CASO DE TESTE: CT-004 - Busca com Caracteres Especiais (Cenário de Erro)
PRÉ-CONDIÇÃO:

Navegador Chrome atualizado aberto

Acesso à homepage do Mercado Livre

PASSOS:

Acessar www.mercadolivre.com.br

Clicar na barra de pesquisa no topo da página

Digitar apenas caracteres especiais: %$#@!&*()

Pressionar a tecla Enter ou clicar no ícone de lupa

RESULTADO ESPERADO:

O sistema não deve quebrar o layout da página ou apresentar erros internos de servidor

O sistema deve exibir uma mensagem amigável informando que nenhum produto foi encontrado para aquela busca

RESULTADO OBTIDO:
O sistema não quebrou o layout, porém não exibiu a mensagem de produto não encontrado. Em vez disso, a busca retornou 13 resultados, exibindo no canto superior esquerdo os caracteres digitados ($ &%¨@&% ) e apresentando em destaque um celular Motorola, seguido por tablets e relógios digitais na listagem inferior.

STATUS: ❌ Falhou

