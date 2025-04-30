# conversor
Conversor Automático de Capacidade (ml / L)

Utilizei este script em um site onde o cliente cadastra suas embalagens, que vão desde 10ml até 2,5L.
O cadastro no painel administrativo é feito sempre com números inteiros, como:

10 (para representar 10ml)

2500 (para representar 2,5L)

O sufixo é adicionado automaticamente pelo front-end, e este script cuida da conversão visual.

# O que o script faz?

Este script percorre automaticamente todos os itens de lista de ícones do Elementor e converte valores de mililitros (ml) para litros (L), sempre que:

• A palavra "Capacidade" estiver presente no texto;

• O número for maior ou igual a 1000ml.

# Exemplo do que o script faz:

Antes:
<span class="elementor-icon-list-text">Capacidade: 1500ml</span>

Depois:
<span class="elementor-icon-list-text">Capacidade: 1.5L</span>

# Como usar

• Insira o código em um widget de HTML no rodapé da página;

• Ou insira em Elementor Custom Code, no </body> - End.


