# FIAP-F2-Atv1-Iara-para-todos
Documento Descritivo de Acessibilidades

Estrutura Semântica

HTML semântico como <header>, <main>, <footer>, <nav> e <section>, garantindo uma organização clara do conteúdo e melhor suporte para tecnologias assistivas.
Atributos de Acessibilidade

Campos de formulário e elementos interativos estão complementados com atributos como:

aria-label: Utilizado para descrever a função de links, botões, campos de entrada e seções. Isso ajuda os leitores de tela a fornecer informações precisas ao usuário.

aria-hidden: Aplicado a elementos decorativos para evitar confusão em leitores de tela.


Imagens

As imagens possuem descrições adequadas através do atributo alt, permitindo que usuários com deficiência visual entendam o propósito ou contexto das imagens.

Grid Layout nas imagens do jogo com responsividade para telas menores.

Campos Obrigatórios
Os campos de formulário identificados como obrigatórios utilizam o atributo required, acompanhado de aria-required, proporcionando uma experiência inclusiva e orientando o preenchimento correto.

Menu Responsivo
O menu é adaptável para dispositivos móveis e conta com descrições adicionais (aria-label) para facilitar a navegação, mesmo em tecnologias assistivas.

Mensagens de Feedback
Em formulários, é possível incluir mensagens visíveis ou auditivas para situações de erro ou preenchimento inválido, utilizando técnicas como aria-live para atualizações dinâmicas.

Responsividade
Meta tags para controle de viewport garantem que os layouts funcionem em diferentes tamanhos de tela, mantendo a acessibilidade em dispositivos móveis.



# Formulário Acessível 

* Os formulários serão encontrados nas abas da pagina inicial "Login", "Cadastre-se" e "Contato". Na pagina de "Login" também terá a opção para o formulário "Alterar Senha".*

Rótulos Conectados a Campos de Entrada:- Cada campo <input> está associado a um <label> por meio do atributo for, garantindo que leitores de tela identifiquem corretamente o propósito de cada campo.

# Atributos de Acessibilidade nos Campos:

O uso de required combinado com aria-required="true" informa claramente que os campos são obrigatórios, ajudando tanto usuários com leitores de tela quanto outros.

# Placeholders Descritivos:

No campo de data de nascimento, o placeholder orienta o usuário sobre o formato esperado.

Atributo aria-label nos Campos:

Cada campo possui uma descrição específica para ajudar na compreensão (exemplo: "Digite seu nome completo" e "Digite sua senha").



# Botões Funcionais

Os botões possuem aria-label que descrevem suas ações, como "Cancelar e voltar para a página inicial" e "Enviar formulário de cadastro".

O botão "Cancelar" usa JavaScript (onclick) para redirecionar, eliminando a redundância do link <a> dentro do botão.

Atributos Dinâmicos

Uso do atributo aria-label no formulário e seus elementos para fornecer informações adicionais e melhorar a navegação em leitores de tela.

Responsividade

A meta tag viewport garante que o layout seja adaptável a diferentes tamanhos de dispositivos, favorecendo a acessibilidade em dispositivos móveis.




