# SafeMan 👨‍⚕️

O SafeMan é uma plataforma informativa e interativa dedicada a orientar e promover o cuidado com a saúde do homem em todas as fases da vida. O projeto aborda de forma segmentada os cuidados preventivos e o desenvolvimento na Infância, Adolescência, Vida Adulta e Terceira Idade.

## 🚀 Funcionalidades

* **Navegação Temática:** Páginas específicas detalhando tópicos como vacinação, nutrição, saúde mental, higiene e desenvolvimento para cada faixa etária.
* **Sistema de Busca Integrado:** Barra de pesquisa inteligente que redireciona o usuário para a página de saúde correta com base em palavras-chave mapeadas (ex: "próstata", "vacinação", "estresse").
* **Autenticação Simulada:** Sistema completo de Login e Cadastro na interface utilizando `localStorage`, incluindo suporte nativo a uma conta de Administrador predefinida.
* **Interação via Comentários:** Usuários autenticados podem publicar comentários nas páginas de conteúdo para compartilhar experiências.
* **Filtro de Moderação:** Implementação de um filtro automatizado que analisa e bloqueia termos ofensivos e xingamentos antes da postagem.
* **Design Responsivo:** Interface estilizada, fluida e amigável que se adapta perfeitamente a dispositivos móveis e desktops, incluindo menus interativos e navegação suave.

## 🧠 Estruturas de Dados e Algoritmos

Um dos principais diferenciais técnicos deste projeto no frontend é a manipulação e ordenação dos comentários. O sistema utiliza o algoritmo de ordenação **Radix Sort**, operando em conjunto com o **Counting Sort**, para organizar a lista de comentários de forma cronológica. A ordenação é feita baseada na chave numérica do *timestamp*, garantindo que as mensagens sejam exibidas da mais recente para a mais antiga de forma altamente eficiente.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica das páginas e componentes.
* **CSS3:** Estilização baseada em variáveis nativas, layout em Grid/Flexbox e design 100% responsivo.
* **JavaScript (Vanilla):** Responsável por toda a lógica de negócios no lado do cliente, manipulação do DOM, algoritmos de ordenação e simulação de banco de dados via LocalStorage.
* **SQL:** Arquivo de modelagem do banco de dados relacional criado com tabelas de `Users` e `Comments`, deixando a estrutura preparada para uma futura integração com uma API/Backend.


## Visualização do Projeto
https://harrytaveiros.github.io/SafeMan/
