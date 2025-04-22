# FIAP-F2-Atv1-Iara-para-todos

Documento Descritivo de Acessibilidade

Estrutura Semântica
Uso de elementos HTML semânticos como <header>, <main>, <footer>, <nav> e <section> para
organizar o conteúdo e oferecer suporte a tecnologias assistivas.

Atributos de Acessibilidade
• aria-label: Descreve a função de links, botões, campos de entrada e seções,
melhorando a interação com leitores de tela.
• aria-hidden: Oculta elementos decorativos de leitores de tela.

Imagens
As imagens possuem descrições claras com o atributo alt, garantindo acessibilidade para
usuários com deficiência visual. Além disso, o layout em grid é responsivo para telas menores.

Campos Obrigatórios
Os campos de formulário usam required e aria-required para indicar obrigatoriedade de forma
clara, orientando o preenchimento correto.

Menu Responsivo
O menu é adaptável a dispositivos móveis, com descrições adicionais (via aria-label) para
facilitar a navegação.

Mensagens de Feedback
Formulários incluem mensagens dinâmicas para erros ou preenchimentos inválidos, com
suporte ao atributo aria-live.

Responsividade
Uso de meta tags para ajuste do layout em diferentes tamanhos de tela, garantindo
acessibilidade em dispositivos móveis.

Formulário Acessível
• Disponível nas páginas "Login", "Cadastre-se" e "Contato", além de "Alterar Senha" na
página de Login.
• Rótulos e Campos de Entrada: Cada <input> está associado a um <label> com o
atributo for para leitores de tela.
• Placeholders Descritivos: Direcionam sobre o formato esperado (ex.: data de
nascimento).
• Atributos Dinâmicos: Uso de aria-label para descrever a função de cada campo (ex.:
"Digite seu nome completo").

Botões Funcionais
Os botões têm aria-label descritivos, como "Cancelar e voltar para a página inicial" e "Enviar
formulário". O botão "Cancelar" usa JavaScript para redirecionamento, evitando redundâncias.