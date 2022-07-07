# Capacitated_fac_locations
Algoritmos de localização alocação que foram desenvolvidos no âmbito dos trabalhos conducentes à obtenção do grau de Doutor em Políticas Públicas pela Universidade de Aveiro de Jan Wolf, orientado pelo Prof. João Lourenço Marques e co-orientado pelo Prof. Eduardo Castro. 
Estes trabalhos beneficiaram do, e enquadram-se nos, trabalhos desenvolvidos pelo projeto de investigação DRIVIT-UP (POCI-01-0145-FEDER-031905). 

## Objetivo: 
O principal objetivo deste trabalho foi a aplicação de problemas de localização-alocação de equipamentos capacitados para perceber como se podem maximizar diferentes princípios de justiça, considerando os custos das soluções.

## Metodologia: 
A metodologia deste exercício partiu da identificação de: 

1)	um conjunto de pontos numa rede de transporte (os centroides das subsecções da BGRI) que funcionam como potenciais localizações; 

2)	uma procura associada a esses pontos (a população estudantil associada às subsecções): 

3)	um custo de transporte assente na rede de estradas do OpenStreetMaps:
 
4)	custos de instalação e funcionamento para equipamentos
Foram, de seguida, considerados três objetivos para serem minimizados através da solução de problemas de localização-alocação:
    <ol>
      <li>a minimização do somatório de custos, sem quaisquer considerações de acessibilidade; </li>
      <li>a atribuição de um peso maior às distâncias a percorrer pelos alunos (custo do quadrado das distâncias);
      <li>a imposição de uma distância máxima que pode ser percorrida por um aluno (restrição rawlsiana).
     </ol> 


## Resultados: 
Como em outros trabalhos sobre este tema , foi identificada uma redução de custos com a concentração dos alunos num número reduzido de equipamentos, tendo em conta que as economias de escala nos custos de instalação e de funcionamento dos equipamentos não é compensado pelo aumento dos custos de transporte. Assim, a minimização exclusiva dos custos da rede seria melhor conseguida através de uma concentração extrema de equipamentos. 

