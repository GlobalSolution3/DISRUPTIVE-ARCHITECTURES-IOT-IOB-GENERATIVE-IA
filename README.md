# Faculdade de Informática e Administração Paulista 
 

### Gustavo Araújo Maia RM553270

### Rafael Vida Fernandes RM553721

### Kauã Almeida Silveira RM552618

# Global Solution 


#### VÍDEO: https://www.youtube.com/watch?v=qWzNJC_az3Y&t=2s 

#### REPOSITÓRIO: https://github.com/GlobalSolution3/DISRUPTIVE-ARCHITECTURES-IOT-IOB-GENERATIVE-IA/tree/main 

#### DATASET: https://app.roboflow.com/workspace-sfj9d/postes-urbanos/1


## RESUMO 

Com base nos conhecimentos adquiridos em sala de aula, este projeto visa desenvolver um sistema de visão computacional capaz de identificar linhas de transmissão com vegetação perigosa. 

Essa solução tem como objetivo principal garantir a segurança energética, prevenindo interrupções no fornecimento de energia causadas por falhas relacionadas à vegetação. 

 
## DESCRIÇÃO DO PROBLEMA A RESOLVER 

A proximidade excessiva de vegetação a linhas de transmissão representa um sério risco à segurança energética. Essa condição pode causar curtos-circuitos, incêndios e interrupções no fornecimento de energia, gerando prejuízos financeiros e colocando em risco a vida de pessoas e propriedades. 

Um dos maiores exemplos da gravidade desse problema foi a falta de energia em grandes regiões de São Paulo por conta de chuvas, tendo em vista que muitas arvores caíram em cima de postes. 

 
## OBJETIVOS DA SOLUÇÃO IDEALIZADA 

Desenvolver um sistema de visão computacional capaz de identificar de forma automática a presença de vegetação que se encontra a uma distância perigosa das linhas de transmissão, permitindo a tomada de medidas preventivas e a realização de manutenções de forma mais eficiente. 


## CONCLUSÃO 

Dado meu exemplo pessoal na imagem identificada com a explicação dos motivos no vídeo pitch, podemos concluir que se esse modelo fosse implementado em conjunto com, por exemplo o Google Maps, seria fácil de identificar perigos energéticos em todo o país, quiçá do mundo, facilitando a neutralização do perigo antes da tragédia acontecer.  

Assim, eu não teria sofrido com a perca de energia na minha rua e não teria sido prejudicado, assim como milhões de brasileiros são prejudicados pelos mesmos motivos todos os dias  

 
## FERRAMENTAS UTILIZADAS E COMO SERÃO APLICADAS 

#### RoboFlow: Um grande facilitador quando o assunto é datasets e notação das imagens, além de nós facilmente conseguirmos transportar esse dataset notado para manipular ele dentro do Colab por exemplo 

#### YOLOV8: Assim como o RoboFlow, ele é um grande facilitador para nós, porém para conseguirmos manipular todo o nosso dataset. Com ele conseguimos ajustar hiperparâmetros e colocar nossos objetos para identificação. 

 

### Além dessas foram utilizadas mais bibliotecas para auxílio durante o desenvolvimento dos códigos, são essas: 

 

#### CV2: Uma biblioteca que eu particularmente gosto de usar para o plot das imagens na tela. 

#### IPython.display.Image: Outra opção para exibir imagens no notebook, essa usei para mostrar os gráficos gerados, como por exemplo a matriz de confusão. 

#### Os: Essa biblioteca serve para interagir com os diretórios da máquina, usei para definir o diretório de datasets do modelo. 
