# Perfil Profissional - Eduardo Barreto

Este projeto é um portfólio pessoal desenvolvido para apresentar informações profissionais, contatos e redes sociais de forma moderna e responsiva.

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página e organização dos componentes.
- **CSS3**: Estilização avançada, incluindo Flexbox para alinhamento, gradientes, responsividade e efeitos visuais.
- **Markdown**: Utilizado para separar e organizar os conteúdos dos perfis (pessoal e profissional), facilitando futuras edições.
- **JavaScript**: Carregamento dinâmico dos arquivos markdown e manipulação do DOM.
- **SVG**: Ícones personalizados e banners para melhor identidade visual.
- **Git/GitHub**: Controle de versão e hospedagem do projeto.
- **Dev Container (Ubuntu 24.04.2 LTS)**: Ambiente de desenvolvimento isolado e padronizado.

## Estrutura do Projeto

- `/index.html`: Página principal, responsável por exibir o layout e carregar dinamicamente os perfis.
- `/assets/css/style.css`: Arquivo de estilos, responsável pelo visual moderno, espaçamento, cores e responsividade.
- `/perfil-profissional.md`: Perfil profissional em markdown, exibido na área principal.
- `/perfil-pessoal.md`: Perfil pessoal em markdown, utilizado na sidebar (quando necessário).
- `/images/`: Pasta com avatar, banners e ícones SVG.
- `/assets/js/`: Scripts para carregamento dinâmico do markdown.

## Como foi feito

1. **Layout**: Sidebar à esquerda com avatar, nome, bio, contatos e ícones sociais. Área principal à direita para banners, projetos e informações detalhadas.
2. **Responsividade**: Utilização de Flexbox e media queries para garantir boa visualização em diferentes dispositivos.
3. **Visual Moderno**: Gradientes, sombras, ícones SVG e efeitos de hover para melhor UX/UI.
4. **Conteúdo Dinâmico**: Perfis em markdown carregados via JavaScript, facilitando manutenção e atualização.
5. **Separação de Perfis**: Perfil pessoal e profissional organizados em arquivos distintos para facilitar futuras pesquisas e adaptações.
6. **Controle de Versão**: Todo o desenvolvimento foi versionado via Git, permitindo rastreabilidade e colaboração.

## Segurança

Este projeto não possui credenciais sensíveis (senhas, tokens, chaves de API) embutidas no código-fonte. Todas as informações presentes são públicas, como links de redes sociais e e-mail. Recomenda-se sempre evitar o uso de credenciais hardcoded para garantir a segurança do sistema.

## Para futuras pesquisas

- O uso de markdown para perfis permite integração fácil com outros sistemas ou exportação para diferentes formatos.
- O layout modular facilita a inclusão de novas seções, como blog, projetos ou depoimentos.
- O CSS pode ser expandido para temas claros/escuros ou personalização por usuário.
- O ambiente dev container garante que o projeto rode de forma idêntica em qualquer máquina compatível com Docker.

---

Sinta-se à vontade para adaptar, expandir ou pesquisar novas soluções a partir deste projeto!