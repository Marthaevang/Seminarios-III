
# Arquitetura da Solução

A aplicação é composta por diversos componentes que trabalham em conjunto para oferecer uma experiência interativa, acessível e eficiente ao usuário. A estrutura do software é dividida em componentes principais, cada um responsável por uma funcionalidade específica. Abaixo, estão os componentes principais e o ambiente de hospedagem:

## Frontend (Interface do Usuário)
A interface do usuário é a camada visível e interativa do site, onde o usuário interage diretamente com o conteúdo. Ela é composta por:

- HTML5: A estruturação do conteúdo, garantindo que as informações sejam bem organizadas e acessíveis.
- CSS3: A estilização da interface, garantindo que o site seja visualmente atraente e responsivo, adaptando-se a diferentes dispositivos e tamanhos de tela.
- JavaScript: A linguagem de programação usada para adicionar interatividade ao site, como redirecionamento para páginas, funcionalidades da calculadora e controle de vídeos em Libras.
- React: A biblioteca JavaScript usada para construir a interface de forma dinâmica. React permite a criação de componentes reutilizáveis, proporcionando uma navegação ágil e atualizações eficientes do conteúdo sem recarregar a página inteira.

## Funcionalidades Interativas
Além da estrutura visual, o site conta com funcionalidades interativas essenciais para a experiência do usuário:

- Botões e Navegação: Botões são usados para direcionar o usuário para as aulas e para ativar a calculadora. Esses botões são gerenciados por JavaScript e React para garantir uma navegação fluida.
- Incorporação de Vídeos: Os vídeos em Libras são incorporados diretamente do YouTube utilizando a tag `<iframe>`. O site também assegura que esses vídeos sejam facilmente acessíveis e funcionais em todos os dispositivos.
- Calculadora: A calculadora interativa é gerida por JavaScript, permitindo que os usuários realizem operações matemáticas diretamente no site de forma simples e eficiente.

## Componentes de Acessibilidade
A acessibilidade é uma prioridade na estrutura do site. Para garantir que todos os usuários, incluindo aqueles com deficiência auditiva ou visual, possam utilizar o site, são implementadas as seguintes práticas:

- Teclado e Navegação por Leitores de Tela: O site é projetado para ser navegável por teclado e compatível com leitores de tela, assegurando uma experiência inclusiva para pessoas com deficiência visual.
- Vídeos: Embora os vídeos sejam incorporados do YouTube, que oferece a tradução visualmente em libras, o design do site garante que esses vídeos sejam exibidos de maneira adequada e acessível.


## Diagrama de componentes

![image](https://github.com/user-attachments/assets/d29654ef-0f80-4cd4-9e2c-4c6a0aa85665)
![image](https://github.com/user-attachments/assets/6f4b0886-3e3d-43fd-93b5-823a9c018b5c)
![image](https://github.com/user-attachments/assets/cf611cd9-98d1-4137-8188-4da0083c99ec)
![image](https://github.com/user-attachments/assets/329d453f-e6df-4e0f-98a1-5ced966a4827)
![image](https://github.com/user-attachments/assets/eba23a7b-07b8-4ed5-97ba-80e381da39c1)

## Tecnologias Utilizadas


### HTML
   - Estrutura do Site: O site é desenvolvido com HTML5, proporcionando uma estrutura clara e semântica para o conteúdo. Ele organiza as diferentes partes do site de maneira lógica, o que facilita a navegação e melhora a acessibilidade. A estruturação com HTML5 permite que o conteúdo seja facilmente entendido por diferentes tipos de usuários e seja compatível com ferramentas de acessibilidade, como leitores de tela.

### CSS
   - Estilo e Layout Responsivo: A estilização do site é feita com CSS, garantindo que ele tenha um visual moderno e se adapte a diferentes dispositivos. Através de **media queries**, o layout do site é responsivo, ou seja, ele se ajusta automaticamente para telas menores ou maiores, oferecendo uma experiência fluida em celulares, tablets e desktops. O CSS também cuida da aparência dos botões e outros elementos interativos, tornando a navegação visualmente agradável e intuitiva.

### JavaScript
   - Interatividade: JavaScript é a chave para tornar o site interativo e dinâmico. Ele é usado para fazer com que os botões e funcionalidades do site, como o redirecionamento para as aulas e a operação da calculadora, funcionem de forma fluida e sem complicação. Cada clique nos botões é tratado dinamicamente pelo JavaScript, garantindo que os usuários tenham uma experiência prática e sem frustrações.

### React
   - Biblioteca para Interface Dinâmica: O site foi desenvolvido com **React**, uma biblioteca JavaScript que facilita a criação de interfaces de usuário interativas e rápidas. Usando componentes reutilizáveis, React permite que partes do site sejam atualizadas sem precisar recarregar a página inteira, o que melhora a experiência do usuário. Isso é especialmente importante para os botões que redirecionam para as aulas ou ativam a calculadora, garantindo uma navegação ágil e sem interrupções.

### YouTube Embedded Videos
   - Vídeos de Libras: Para exibir os vídeos em Libras, o site utiliza a tag `<iframe>` para incorporar diretamente vídeos do **YouTube**. Isso torna o processo de visualização simples e eficiente, permitindo que os usuários acessem o conteúdo educativo de forma prática. A escolha de vídeos do YouTube também garante que os vídeos sejam compatíveis com diferentes dispositivos e navegadores.

### GitHub Pages
   - Hospedagem: O site é hospedado no GitHub Pages, uma plataforma gratuita e eficiente para sites estáticos. Isso permite que o site seja facilmente publicado e mantido, sem a necessidade de um servidor complexo. GitHub Pages oferece uma solução simples e confiável para hospedar esse tipo de conteúdo.

### Acessibilidade
   - Foco em Acessibilidade: A acessibilidade é uma prioridade no design e desenvolvimento do site. Mesmo com vídeos do YouTube, que já são em libras e controles de acessibilidade, o site foi projetado para ser facilmente navegável por todos os usuários. A navegação pelos botões, como os que levam às aulas ou à calculadora, é otimizada para que possa ser realizada com o teclado ou leitores de tela, garantindo uma experiência inclusiva para pessoas com diferentes necessidades.

