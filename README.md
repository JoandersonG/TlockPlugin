<h1 align="center">Tlock Plugin</h1>

## :bulb: Objetivo
Plugin para a IDE Eclipse, desenvolvido em Java, para permitir a conversão de modelos de coreografia BPMN 2.0 criados com a ferramenta open-source <a href="http://bpmn.sourceforge.net/">Yaoqiang</a> para a linguagem de descrição de arquitetura pi-ADL. Além disso, através do plugin também é possível testar a ocorrência de deadlocks no modelo criado.

## 🌟 Funcionalidades
Este é um plugin criado pra realizar duas tarefas distintas:
1. A primeira tarefa que o programa resolve é a geração de código na linguagem pi-ADL a partir de arquivos .bpmn gerados na plataforma, chamada Yaoqiang, de design de modelos do diagrama de coreografia BPMN 2.0. O programa utiliza o mapeamento de BPMN para pi-ADL utilizando o trabalho de mestrado de Leila de Carvalho Costa do Programa de Pós-Graduação em Ciência da Computação da Universidade Federal da Bahia.
2. A segunda tarefa que o programa resolve é o teste de ocorrência de deadlocks, incluindo o nome do elemento que ocasionou o deadlock no modelo original BPMN.

## :floppy_disk: Instalando os plugins necessários
1. Instale a IDE Eclipse
2. Instale o plugin para a linguagem pi-ADL seguindo os passos descritos <a href="http://plasma4pi-adl.gforge.inria.fr/manual/ar01s02.html#%CF%80-adl-editor-and-code-generator-installation">aqui</a>
3. Agora, entre novamente no menu "Help"
4. Selecione "Install new software ..."
5. Coloque o seguinte link no campo "Work with": https://joandersong.github.io/TlockPlugin/
6. Selecione a opção "uncategorized"
7. Click em Next, Next, aceite os termos de licença e clique em Finish
8. Durante o dowload, um aviso de segurança aparecerá, continue com a instalação.
9. Por fim, será pedida a reinicialização da IDE e o plugin estará instalado.
Finally, you will be asked to restart Eclipse, and the Pi-ADL plugin is installed.

## :bar_chart: Executando seus modelos BPMN 2.0
Quando instalado, uma opção extra aparecerá na barra de menu, aquela no topo da janela, com o nome "Tlock". Para executar seus modelos gerados, é preciso:
1. Clicar em Gerar pi-ADL
2. Selecionar o arquivo .bpmn salvo a partir de um modelo de coreografia válido criado na ferramenta Yaoqiang
3. Quando perguntado, confirme que deseja converter o projeto para um projeto Xtext
4. Será então automaticamente criado ou atualizado um projeto com mesmo nome do modelo, com um arquivo gerado e o código pi-ADL para o modelo exibido
<br>
Em Seguida, será possível testar a ocorrência de deadlocks, bastando, para isso:
<br>
1. Selecionar no menu a opção "Testar deadlocks"<br>
2. Aguardar até uma mensagem de ocorrência ou ausência de deadlocks no modelo ser exibida
<br>
Lembrando que a ocorrência de deadlocks funciona corretamente somente com o último modelo gerado, então sempre que quiser testar a ocorrência de deadlocks de modelos diferentes será necessário primeiro utilizar a opção de gerar o modelo desejado, a menos que o modelo tenha acabado de ser gerado, nesse caso é possível testar a ocorrência de deadlocks multiplas vezes.

## :bow: Autor
<p align="center">
Feito por Joanderson Gonçalves Santos<br>
Bacharelando em Ciência da Computação<br>
Bolsista FAPESB do Programa de Iniciação Científica<br>
Sob tutoria de Leila de Carvalho Costa<br>
E sob orientação da profa. Dra. Rita Suzana Pitangueira Maciel<br>
Departamento de Ciência da Computação<br>
Instituto de Matemática<br>
Universidade Federal da Bahia
</p>
<p align="center">
  <a href="https://www.linkedin.com/in/joanderson-gon%C3%A7alves-1055351b9/">LinkedIn</a> •
  <a href="mailto:joandersongsantos@yahoo.com">E-mail</a>
</p>
