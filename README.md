# SafeMan 👨‍⚕️

O SafeMan é uma plataforma informativa e interativa dedicada a orientar e promover o cuidado com a saúde do homem em todas as fases da vida[cite: 5]. O projeto aborda de forma segmentada os cuidados preventivos e o desenvolvimento na Infância[cite: 6], Adolescência[cite: 1], Vida Adulta[cite: 2] e Terceira Idade[cite: 4].

## 🚀 Funcionalidades

* **Navegação Temática:** Páginas específicas detalhando tópicos como vacinação, nutrição, saúde mental, higiene e desenvolvimento para cada faixa etária[cite: 1, 2, 4, 6].
* **Sistema de Busca Integrado:** Barra de pesquisa inteligente que redireciona o usuário para a página de saúde correta com base em palavras-chave mapeadas (ex: "próstata", "vacinação", "estresse")[cite: 7].
* **Autenticação Simulada:** Sistema completo de Login e Cadastro na interface utilizando `localStorage`, incluindo suporte nativo a uma conta de Administrador predefinida[cite: 7].
* **Interação via Comentários:** Usuários autenticados podem publicar comentários nas páginas de conteúdo para compartilhar experiências[cite: 7].
* **Filtro de Moderação:** Implementação de um filtro automatizado que analisa e bloqueia termos ofensivos e xingamentos antes da postagem[cite: 7].
* **Design Responsivo:** Interface estilizada, fluida e amigável que se adapta perfeitamente a dispositivos móveis e desktops, incluindo menus interativos e navegação suave[cite: 7, 8].

## 🧠 Estruturas de Dados e Algoritmos

Um dos principais diferenciais técnicos deste projeto no frontend é a manipulação e ordenação dos comentários. O sistema utiliza o algoritmo de ordenação **Radix Sort**, operando em conjunto com o **Counting Sort**, para organizar a lista de comentários de forma cronológica[cite: 7]. A ordenação é feita baseada na chave numérica do *timestamp*, garantindo que as mensagens sejam exibidas da mais recente para a mais antiga de forma altamente eficiente[cite: 7].

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica das páginas e componentes[cite: 1, 5].
* **CSS3:** Estilização baseada em variáveis nativas, layout em Grid/Flexbox e design 100% responsivo[cite: 8].
* **JavaScript (Vanilla):** Responsável por toda a lógica de negócios no lado do cliente, manipulação do DOM, algoritmos de ordenação e simulação de banco de dados via LocalStorage[cite: 7].
* **SQL:** Arquivo de modelagem do banco de dados relacional criado com tabelas de `Users` e `Comments`, deixando a estrutura preparada para uma futura integração com uma API/Backend[cite: 3].

## 👨‍💻 Equipe Desenvolvedora (Grupo MVP)

Este projeto foi idealizado e desenvolvido por:
* Harry Rocha[cite: 1]
* Iandro Augusto[cite: 1]
* Erick Emanuel[cite: 1]
* Guilerme Sousa[cite: 1]
* Brunno Lima[cite: 1]
* Emerson Melo[cite: 1]
* Guilherme Augusto[cite: 1]
* Enzo Gabriel[cite: 1]
