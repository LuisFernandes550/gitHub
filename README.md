# Workshop de Introdução ao Git

## O que é o Git?

O Git é um sistema de controlo de versões distribuído, gratuito e de código aberto, desenvolvido originalmente pelo <a href="https://pt.wikipedia.org/wiki/Linus_Torvalds">Linus Torvalds</a>, o criador do Kernel do sistema operativo Linux, e atualmente é mantido pelo <a href="https://pt.wikipedia.org/wiki/Junio_Hamano">Junio Hamano</a> juntamente com outros quase 300 colaboradores voluntários.

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1920px-Git-logo.svg.png" width="300" />
</p>

A sua principal utilização visa o desenvolvimento de software, mas pode ser usado para registar o histórico de edições de qualquer tipo de ficheiro.

Comparado com outros sistemas de controlo de versões tradicionais, o Git diferencia-se por ser <b>extremamente rápido</b>, por <b>simplificar o desenvolvimento de software de forma não-linear</b>, onde podemos trabalhar em paralelo em diferentes funcionalidades das aplicações que desenvolvemos e então escolher quais funcionalidades devem fazer parte de cada versão da aplicação conforme o nosso fluxo de trabalho, e principalmente por ser um <b>sistema distribuído</b> bastante versátil e adequado para projetos de qualquer dimensão.

A utilização do GIT permite que um utilizador tenha acesso aos dados que foram por ele guardados ou por outro(s) utilizador(es) que também tenha(m) acesso ao repositório, <b>permitindo que um ficheiro possa ser editado ao mesmo tempo por múltiplas pessoas diferentes</b>. 

<p align="center">
<img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/uzdbcfw21iqc8mzupsk3.gif" width="800" />
</p>

Tem um grande nível de segurança/desempenho e é bastante flexível, porque é <b>compatível com a maioria dos sistemas</b> - possui versões para Windows, Linux e Mac OS X, o que facilita muito o controlo de versões de aplicações desenvolvidas em diferentes plataformas.


## Sistemas de Controlo de Versões (VCS)

Um sistema de controlo de versões deverá conter ferramentas para:
<ul>
  <li>arquivar ficheiros de um projeto (código-fonte e outros)</li>
  <li>registar alterações durante o desenvolvimento</li>
  <li>desfazer alterações ou recuperar versões anteriores</li>
  <li>sincronizar projetos em diferentes computadores</li>  
  <li>permitir a colaboração com outros programadores</li>  
  <li>separar “troncos” de desenvolvimento (ex: produção/desenvolvimento)</li>
</ul>

## VCS distribuidos
Num Sistema de Controlo de Versões Distríbuido: 
<ul>
  <li>Cada cópia dum repositório contém a historia completa</li> 
  <li>Permitem registar modificações mesmo sem acesso a rede</li> 
  <li>Evitam um ponto crítico para falhas</li> 
  <li>Facilitam a introdução de branches experimentais</li> 
</ul>

Git
• Um VCS distribuído
• Desenvolvido em 2005 para o kernel Linux
• Muito usado em projetos open-source
• Características:
– conceção simples mas poderosa
– adequado a projectos grandes (muitos ficheiros e história longa)
– eficiente em espaço e recursos computacionais
– suporte para desenvolvimento não-linear (“branching”)

## Porquê usar Git?

<ul>
  <li>Sincronização de trabalhos entre o computador pessoal e da escola</li>
  <li>Permite experimentar modificações sem receios – podemos reverter facilmente se necessário</li> 
  <li>Repositórios remotos funcionam como backup</li> 
  <li>As mensagens de commits são um registo histórico do desenvolvimento</li> 
  <li>Não apenas para código: documentação, relatórios, dissertações</li> 
</ul>

## Como funciona
<ul>
  <li>Cada repositório consiste de um conjunto de ficheiros e diretórios</li>
  <li>Quando registamos uma modificação (commit), o Git guarda um snapshot de todos os ficheiros</li>
  <li>Ficheiros inalterados são guardados como referências ao commit anterior</li>
</ul>

## Integridade

O Git associa um hash (40 carateres hexadecimais) a cada snapshot, e.g.: 34ac2a6552252987aa493b52f8696cd6d3b00373 <br>
Garante que o conteúdo dos ficheiros não foi corrompido. <br>
Serve também para identificar cada snapshot. <br>

## Repositórios locais e remotos
• Quase todas as operações com Git são locais:
– inicializar repositórios
– acrescentar/remover ficheiros
– registar modificações (commit)
– listar a história
• O Git permite também sincronizar com repositórios remotos 
