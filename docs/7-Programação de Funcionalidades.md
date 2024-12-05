# Programação de Funcionalidades

### Implementação do Sistema: Requisitos Funcionais e Não Funcionais

#### 1. **Requisitos Funcionais**
Os requisitos funcionais são as ações que o sistema deve ser capaz de executar para atender ao objetivo do projeto. No caso do sistema de ensino de operações matemáticas para alunos com deficiência auditiva, os requisitos funcionais incluem a criação de funcionalidades que permitem o aprendizado de operações matemáticas básicas de forma acessível.

Abaixo, relacionamos os requisitos funcionais e como cada um foi atendido com a implementação:

- **Requisito 1: Comunicação em Libras (Língua Brasileira de Sinais)**
  - **Descrição**: A plataforma deve fornecer vídeos explicativos em Libras para que alunos com deficiência auditiva possam entender como utilizar o sistema e aprender as operações matemáticas.
  - **Solução Implementada**: A página inicial contém um vídeo de boas-vindas em Libras, explicando como navegar e utilizar a plataforma. Esse vídeo é exibido logo após o carregamento da página, garantindo que todos os usuários tenham acesso a ele de maneira fácil e direta.
  - **Estrutura de Dados**: Para o vídeo, utilizamos um arquivo multimídia armazenado em formato MP4, com um player de vídeo incorporado na página inicial.

- **Requisito 2: Interface Visual Amigável**
  - **Descrição**: O sistema deve ter uma interface visual clara e amigável, facilitando a navegação e o aprendizado.
  - **Solução Implementada**: A interface foi projetada com uma navegação simples e intuitiva. Cada página tem um design limpo, com botões grandes e áreas bem delimitadas para as aulas de adição, subtração, multiplicação e divisão. Cores contrastantes são usadas para garantir a legibilidade.
  - **Estrutura de Dados**: Para a interface, foram utilizados arquivos de CSS para estilização e imagens em formato PNG/JPG para ícones.

- **Requisito 3: Aulas de Operações Matemáticas**
  - **Descrição**: A plataforma deve oferecer quatro aulas interativas sobre adição, subtração, multiplicação e divisão, com explicações visuais e exemplos práticos.
  - **Solução Implementada**: Cada aula é em Libras, e o conteúdo é dividido em seções para cada operação.
  - **Estrutura de Dados**: Os vídeos são armazenados em formato MP4.

- **Requisito 4: Calculadora Interativa**
  - **Descrição**: O sistema deve fornecer uma calculadora para que os alunos possam praticar as operações matemáticas.
  - **Solução Implementada**: Uma calculadora foi desenvolvida para realizar adição, subtração, multiplicação e divisão, permitindo que os usuários pratiquem as operações de forma interativa. A interface da calculadora inclui botões grandes e visíveis.
  - **Estrutura de Dados**: A funcionalidade da calculadora foi implementada com HTML, CSS e JavaScript para interatividade e cálculos dinâmicos.

- **Requisito 5: Página “Sobre”**
  - **Descrição**: A plataforma deve ter uma página “Sobre”, explicando a missão e os desenvolvedores do projeto.
  - **Solução Implementada**: A página “Sobre” foi criada com informações sobre o projeto, incluindo sua missão de inclusão educacional, e detalhes sobre os desenvolvedores e a equipe envolvida no desenvolvimento do sistema.
  - **Estrutura de Dados**: O conteúdo dessa página está armazenado em arquivos HTML, com textos estáticos.

#### 2. **Requisitos Não Funcionais**
Os requisitos não funcionais envolvem as qualidades do sistema, como desempenho, acessibilidade, segurança, etc.

- **Requisito 1: Acessibilidade**
  - **Descrição**: O sistema deve ser acessível, especialmente para pessoas com deficiência auditiva.
  - **Solução Implementada**: Além dos vídeos em Libras, a plataforma tem um contraste adequado, fontes legíveis e navegação simplificada que contribui para a acessibilidade.
  - **Estrutura de Dados**: Utilizamos um layout responsivo (CSS) e marcação semântica (HTML5) para garantir que o sistema seja acessível em diversos dispositivos.

- **Requisito 2: Performance**
  - **Descrição**: O sistema deve carregar rapidamente e ser eficiente, mesmo com o uso de vídeos e conteúdos interativos.
  - **Solução Implementada**: Os vídeos são otimizados para streaming eficiente e os recursos do sistema, como a calculadora e as animações, foram projetados para garantir que o site carregue rapidamente em qualquer dispositivo.
  - **Estrutura de Dados**: Utilizamos técnicas de otimização, como compressão de imagens e vídeos, e carregamento assíncrono de recursos para melhorar a performance do site.

- **Requisito 3: Segurança**
  - **Descrição**: O sistema deve ser seguro, garantindo a privacidade dos dados dos usuários.
  - **Solução Implementada**: Implementação de protocolos HTTPS para criptografar as comunicações entre o usuário e o servidor. Não há coleta de dados pessoais, garantindo a privacidade dos usuários.
  - **Estrutura de Dados**: Não há armazenamento de dados sensíveis, portanto, não foi necessário implementar banco de dados para coleta de informações pessoais.

#### 3. **Estruturas de Dados Utilizadas**
- **Arquivos de Vídeo (MP4)**: Para os tutoriais em Libras, armazenados de forma que possam ser facilmente acessados pelos alunos.
- **Arquivos de Texto (HTML)**: Para o conteúdo das aulas e explicações, organizados em formato semântico para facilitar a leitura por leitores de tela.
- **Imagens (PNG/JPG)**: Para os ícones, botões e animações da interface do usuário.
- **Arquivos CSS e JavaScript**: Para a estilização da página e a interatividade da calculadora.

#### 4. **Instruções de Acesso e Verificação**
Para acessar e verificar a implementação, siga os seguintes passos:

1. **Acesso ao Sistema**:
   - Acesse a URL da plataforma (a ser fornecida após o deploy).
   - O sistema estará hospedado em um servidor web, acessível via qualquer navegador moderno.

2. **Verificação da Funcionalidade**:
   - Na **página inicial**, verifique se o vídeo explicativo em Libras é exibido corretamente.
   - Navegue até a **página Aulas** e verifique se os tutoriais de adição, subtração, multiplicação e divisão estão acessíveis.
   - Teste a **calculadora** interativa para verificar se ela realiza os cálculos corretamente.
   - Acesse a **página Sobre** para verificar as informações do projeto e desenvolvedores.

3. **Testes de Acessibilidade**:
   - Utilize ferramentas como o **Google Lighthouse** para verificar a pontuação de acessibilidade da plataforma.
   - Teste a navegação com teclado e leitores de tela para garantir que todos os elementos são acessíveis.

4. **Verificação de Desempenho**:
   - Utilize o **Google PageSpeed Insights** para verificar a performance do site e a otimização de vídeos e imagens.

5. **Segurança**:
   - Verifique se o site está acessível via **HTTPS** para garantir que as comunicações são seguras.

Com esses passos, a implementação do sistema pode ser verificada, e seu funcionamento deverá estar conforme os requisitos propostos.
