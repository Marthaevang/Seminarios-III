##Plano de Testes de Software
### Cenários de Testes para a Aplicação

A seguir, serão apresentados os cenários de testes realizados para avaliar se os requisitos da plataforma educacional inclusiva foram atendidos. O foco é verificar a funcionalidade e a usabilidade do sistema, garantindo que ele seja acessível e funcional para alunos com deficiência auditiva.

#### 1. **Cenário de Teste 1: Verificação da Comunicação em Libras**

**Objetivo**: Validar se o vídeo de boas-vindas em Libras está sendo exibido corretamente na página inicial, garantindo que alunos surdos possam entender a navegação e como utilizar a plataforma.

- **Funcionalidade Avaliada**: Exibição do vídeo de boas-vindas em Libras.
- **Grupo de Usuários**: Usuários com deficiência auditiva.
- **Ferramentas Utilizadas**:
  - Navegador web (Chrome, Firefox).
  - Ferramenta de acessibilidade para testar navegação sem áudio (leitores de tela).
- **Passos do Teste**:
  1. Acessar a página inicial.
  2. Verificar se o vídeo de boas-vindas em Libras é exibido corretamente.
  3. Confirmar se o vídeo apresenta informações claras e acessíveis sobre como navegar na plataforma.
- **Resultado Esperado**: O vídeo de boas-vindas é exibido corretamente e é legível, com a tradução em Libras sendo clara e sem falhas de exibição.

#### 2. **Cenário de Teste 2: Navegação nas Aulas de Matemática**

**Objetivo**: Validar se as aulas de adição, subtração, multiplicação e divisão estão funcionando corretamente, com os conteúdos sendo acessíveis e claros para os usuários.

- **Funcionalidade Avaliada**: Navegação na página de aulas, seleção dos tópicos de matemática e visualização do conteúdo multimídia.
- **Grupo de Usuários**: Usuários surdos e com deficiência auditiva, com familiaridade básica com navegação na web.
- **Ferramentas Utilizadas**:
  - Navegador web (Google Chrome, Safari).
  - Ferramentas de navegação sem mouse (navegação por teclado).
  - Testes de usabilidade.
- **Passos do Teste**:
  1. Acessar a página "Aulas".
  2. Selecionar os tópicos: "Aula - Adição", "Aula - Subtração", "Aula - Multiplicação" ou "Aula - Divisão".
  3. Verificar se o conteúdo de cada aula é acessível em formato visual e se inclui um vídeo ou animação explicativa.
  4. Confirmar a clareza das explicações, tanto visuais quanto escritas, e se o conteúdo em Libras está adequado.
- **Resultado Esperado**: O sistema exibe corretamente o conteúdo das aulas, incluindo vídeos e animações explicativas, e o conteúdo visual é bem explicado.

#### 3. **Cenário de Teste 3: Funcionalidade da Calculadora**

**Objetivo**: Validar a funcionalidade da calculadora, garantindo que as operações matemáticas básicas (adição, subtração, multiplicação e divisão) funcionem corretamente para os usuários praticarem.

- **Funcionalidade Avaliada**: Interatividade e funcionamento correto da calculadora.
- **Grupo de Usuários**: Usuários surdos ou com deficiência auditiva.
- **Ferramentas Utilizadas**:
  - Navegador web.
  - Ferramentas de teste interativo de interfaces web.
  - Ferramenta de acessibilidade para garantir que a calculadora é navegável sem o uso do mouse (com teclado ou dispositivo assistivo).
- **Passos do Teste**:
  1. Acessar a página "Calculadora".
  2. Realizar uma operação de adição (exemplo: 2 + 3).
  3. Realizar operações de subtração, multiplicação e divisão.
  4. Verificar se os resultados das operações estão corretos.
  5. Confirmar se todos os botões são acessíveis e utilizáveis por teclados ou dispositivos assistivos.
- **Resultado Esperado**: A calculadora deve realizar corretamente as operações, e os resultados devem ser exibidos sem erros. A calculadora também deve ser acessível via teclado e outros dispositivos assistivos.

#### 4. **Cenário de Teste 4: Acessibilidade e Responsividade do Layout**

**Objetivo**: Validar se o site é responsivo e acessível em diferentes dispositivos, incluindo smartphones e tablets, com foco em garantir que a interface visual seja clara e navegável para alunos surdos.

- **Funcionalidade Avaliada**: Responsividade da interface e acessibilidade em dispositivos móveis.
- **Grupo de Usuários**: Usuários surdos com diferentes tipos de dispositivos (desktop, tablet, smartphone).
- **Ferramentas Utilizadas**:
  - Navegador web (Chrome Developer Tools para testar responsividade).
  - Testes de usabilidade em diferentes dispositivos.
  - Ferramentas de acessibilidade como o **Google Lighthouse** para auditoria de acessibilidade.
- **Passos do Teste**:
  1. Acessar o site em dispositivos móveis (smartphones e tablets).
  2. Verificar se o conteúdo é redimensionado corretamente para diferentes tamanhos de tela.
  3. Confirmar que todos os elementos da interface são acessíveis e funcionam adequadamente em dispositivos móveis.
  4. Avaliar a legibilidade dos textos e vídeos em telas menores.
- **Resultado Esperado**: O site deve ser totalmente responsivo, adaptando-se a diferentes tamanhos de tela e mantendo a clareza da interface.

#### 5. **Cenário de Teste 5: Acessibilidade no Uso de Leitores de Tela**

**Objetivo**: Garantir que os alunos com deficiência visual ou aqueles que dependem de leitores de tela possam navegar no sistema sem dificuldades.

- **Funcionalidade Avaliada**: Acessibilidade com leitores de tela.
- **Grupo de Usuários**: Usuários surdos com deficiência visual ou que utilizam leitores de tela.
- **Ferramentas Utilizadas**:
  - Leitores de tela como o **NVDA** ou **JAWS**.
  - Ferramenta de auditoria de acessibilidade **Wave**.
- **Passos do Teste**:
  1. Ativar o leitor de tela no sistema.
  2. Navegar pela página inicial, páginas de aulas e a calculadora.
  3. Verificar se o conteúdo é lido corretamente e se as descrições são claras para o usuário com deficiência visual.
  4. Testar a navegação por teclado para garantir que todos os elementos da interface são acessíveis.
- **Resultado Esperado**: O conteúdo do site deve ser lido corretamente pelo leitor de tela, e a navegação por teclado deve ser fluida e sem obstáculos.

### Conclusão dos Testes

Os testes realizados garantem que a plataforma cumpre os requisitos funcionais e não funcionais estabelecidos. A funcionalidade de vídeos em Libras, as aulas interativas, a calculadora acessível e a interface responsiva foram testadas com diferentes grupos de usuários e em diversos dispositivos, validando a acessibilidade e a usabilidade da plataforma.

Esses cenários de testes demonstram que a plataforma está adaptada para atender às necessidades de alunos com deficiência auditiva, garantindo um aprendizado inclusivo e interativo.
