#O Git

##Conceitos
###O que é o Git
O Git é um sistema de código aberto utilizado para o controle de versão em projetos distribuídos. Atualmente ele é cedido sob licença GNU GPLv2.
O Git foi desenvolvido inicialmente para o controle de versão do kernel do Linux, mas foi adotado para o controle de versão de outros projetos. Apesar de a maioria destes projetos utilizadores do Git serem de software, o Git é aplicável a qualquer tipo de projeto que necessite do gerenciamento de versão.

###O que é um gerenciamento de versão
Numa definição estrita ao conceito de um projeto, uma versão representa uma modificação objetiva no projeto em si e que tem por finalidade o seu ajuste, melhoria ou evolução. O "projeto" nesta ótica pode ser um software, onde cada versão representa uma modificação funcional, pode ser um livro, onde cada versão pode ser uma edição revisada, ou qualquer outro tipo de projeto a que o conceito de versão – enquanto evolução – possa ser aplicado.

###O que é um projeto distribuído
Um projeto distribuído é aquele no qual se há diversas partes do projeto sendo construídas ou modificadas em locais diferentes, geralmente remotos, e que são integradas ao projeto quando estão prontas ou funcionais.

###Como o Git gere um projeto
Para o Git, um projeto necessita de uma área de armazenamento que é denominada de <mark>repositório</mark>. Um repositório pode ser local, quando está num computador, ou remoto, quando está num servidor. O conceito de local ou remoto pode se modificar conforme a organização da infraestrutura do projeto.
O repositório local é um diretório (uma pasta) e o repositório remoto pode ser uma área de armazenamento ou de encapsulamento (tal como um arquivo ".zip" que é interpretado como uma pasta pelo Windows)