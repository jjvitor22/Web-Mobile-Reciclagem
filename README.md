# Web-Mobile-Reciclagem
Identificação do Problema 
• O grupo reconheceu a crescente geração de lixo eletrônico e o impacto 
ambiental causado pelo descarte incorreto. 
• A necessidade de conscientizar e orientar a população sobre como descartar 
corretamente esses resíduos surgiu como ponto central. 
Pesquisa Inicial 
• Foram levantadas informações sobre impactos à saúde e ao meio ambiente, 
além de legislações e políticas públicas sobre descarte de eletrônicos. 
• Também se analisou exemplos de sites de coleta seletiva e campanhas 
governamentais. 
Definição do Público-Alvo 
• Cidadãos comuns que possuem aparelhos eletrônicos sem uso. 
• Pessoas que não têm conhecimento sobre pontos de coleta ou sobre os riscos 
do descarte incorreto. 
Geração de Ideias 
• Criar uma página simples, de fácil acesso, explicando o que é lixo eletrônico, 
seus impactos e como descartá-lo. 
• Incluir um mapa ou lista de pontos de coleta próximos. 
• Destacar também os benefícios da reciclagem.

# Tutorial do Código HTML e CSS
1. Header (Cabeçalho)

HTML:
Contém uma barra de navegação (nav) com uma lista (ul) de links (a):

-Sobre

-Título

-Contato

CSS:
O cabeçalho tem fundo verde claro (#1bd39d), os links são em negrito, pretos, e mudam para azul ao passar o mouse.
Utiliza Flexbox para centralizar e distribuir os links horizontalmente com espaçamento (gap).
Função: Apresentar o menu principal de navegação da página.

2. Main (Conteúdo Principal)

HTML:
Contém uma seção “.conteudo” com vários títulos (h1, h2, h3), parágrafos (p), listas ordenadas (ol) e não ordenadas (ul):

-Explica sobre o descarte correto do lixo eletrônico.

-Passos para descartar.

-Impactos na saúde e meio ambiente.

-Pontos de coleta com lista personalizada (marcada com emoji 📍).

-Benefícios da reciclagem.

CSS:
O main usa Flexbox para dispor os elementos lado a lado, com espaçamento entre eles.
A seção. Conteúdo ocupa até 65% da largura disponível.
Listas não ordenadas não exibem marcadores padrão, usando emoji 📍 como marcador personalizado.
Função: Exibir o conteúdo principal da página de forma organizada e clara.

3. Footer (Rodapé)

HTML:
Texto simples: "desenvolvedores".

CSS:
Fundo verde igual ao cabeçalho, texto centralizado e com fonte menor.
Função: Identificar o rodapé da página, normalmente usados para informações complementares.

4. Responsividade
Até 900px de largura:
“.conteúdo” principal (main) muda para layout vertical (coluna).
O conteúdo passa a ocupar 100% da largura.
A classe “.imagem” (embora não usada no HTML) se ajusta para largura total e altura fixa.

Até 500px de largura:
O cabeçalho (header) muda para layout vertical, com espaçamento menor e texto centralizado.
A altura da “.imagem” diminui para melhor visualização em telas pequenas.



# Tutorial  do código HTML, CSS e JavaScript
1. Header (Cabeçalho)

HTML:
O cabeçalho contém o título principal do site e uma barra de navegação com links para as páginas:

Página Inicial

Como Descartar

Pontos de Coleta

Contato

CSS:

Fundo verde claro (#1bd39d).

Links pretos, em negrito e que mudam para azul ao passar o mouse.

Navegação organizada com Flexbox, centralizando os itens e aplicando espaçamento.

Função:
Exibir o título e apresentar o menu principal de navegação da página.

2. Main (Conteúdo Principal)

HTML:
O conteúdo principal possui várias seções:

Explicação sobre o descarte consciente do lixo eletrônico.

Lista com os impactos ambientais e na saúde.

Lista ordenada com passos para descartar corretamente.

Lista personalizada com marcador de localização para pontos de coleta.

Benefícios da reciclagem.

Botão “Saiba Mais” que redireciona para a página de descarte.

Botão “Entre em Contato” que abre o formulário em uma nova janela.

Jogo interativo de arrastar e soltar, onde o usuário deve colocar os itens nas lixeiras corretas.

CSS:

O main usa Flexbox para organizar o conteúdo em colunas quando em telas grandes.

A seção .conteudo ocupa até 65% da largura.

Listas não ordenadas não usam marcadores padrão, substituídos por marcador de localização personalizado.

Estilo do formulário (contato.html) com fundo branco, bordas arredondadas e sombra.

Estilo do jogo: itens arrastáveis representados por ícones grandes e lixeiras com borda tracejada.

Função:
Transmitir as informações principais do site de forma clara, organizada e interativa.

3. Footer (Rodapé)

HTML:
O rodapé contém apenas um texto simples com os créditos dos desenvolvedores.

CSS:

Fundo verde (#1bd39d), igual ao cabeçalho.

Texto centralizado.

Fonte menor, para diferenciar do conteúdo principal.

Função:
Identificar o rodapé da página e exibir os créditos dos criadores.

4. Responsividade

Até 900px de largura:

O conteúdo principal (main) muda para layout vertical (coluna).

A seção de conteúdo passa a ocupar 100% da largura.

Até 500px de largura:

O cabeçalho muda para layout vertical, com menos espaçamento.

Links do menu passam a ser exibidos em coluna e centralizados.

A classe .imagem (quando usada) passa a ocupar toda a largura e altura reduzida para melhor exibição em telas pequenas.

5. JavaScript (Interatividade)

Botão "Saiba Mais":
Quando clicado, redireciona o usuário para a página “Como Descartar”.

Botão "Entre em Contato":
Abre o formulário de contato em uma nova janela (popup).

Jogo de Arrastar e Soltar:

O usuário pode arrastar itens como celular, notebook e garrafa plástica.

Cada item tem um tipo definido (eletrônico ou plástico).

Existem lixeiras configuradas para aceitar apenas um tipo de item.

Se o usuário soltar no local correto → aparece mensagem verde: “Acertou! Bom descarte!”.

Se errarz aparece mensagem vermelha: “Lixeira errada! Tente de novo.”

Quando o acerto acontece, o item desaparece da tela.

Função:
Deixar o site mais dinâmico, interativo e educativo.



Nomes e Ra:  
João Vitor Gonçalves / 10737592 
Enzo Carvalho Pagliarini / 10425707 
Alex Cardoso Oliveira / 10736415 
Guilherme Gomes Ferransi / 10403372 
