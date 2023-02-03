# Projeto 2 - Teleinformática e Redes 2

- [ ] Fase1: Projeto de Rede

Para definição do endereçamento das interfaces de cada um dos componentes da rede, deve se considerar o seguinte:
a) A rede é um domínio autônomo, com uma única classe de rede.
b) As subredes e1 e e2 devem ter capacidade para endereçar ao menos 90 hosts em cada uma.
c) As subredes e3 e e4 devem ter capacidade para endereçar ao menos 33 hosts em cada uma
d) Os roteadores de agregação em a1 e a2 devem ser capazes de suportar ao menos 8 subredes cada um.

O relatório, conforme estrutura de todos os relatórios desta disciplina, deve conter, além da seção de introdução e dos de
conceitos teóricos, na seção de Resultados Experimentais os itens seguintes:
1. Descrição da topologia da rede, acompanhada de um diagrama de rede (usar uma ferramenta/software específica
para tal). Detalhar para cada elemento da rede o tipo de equipamento (host, roteador) e especificar o endereço IP
de cada equipamento. No diagrama também devem estar claramente especificados os tipos de enlaces utilizados
e seus padrões (cabo coaxial, par trançado, fibra óptica, sem fio), a sua capacidade a justificativa de uso naquela
parte da rede.
2. Especificação de um algoritmo de roteamento dinâmico que será utilizado na rede. Justificar a escolha desse
algoritmo.

- [ ] Fase 2: Simulação de Rede

1. Verificação do ambiente e correta configuração: a partir do s1 e com os recursos do simulador, verificar a
conectividade de todos os hosts. Demonstrar que a partir do s1, qualquer host da rede é alcançável.
2. Conforme explicado na fase 1, na rede deve ser especificado o uso de algum algoritmo de roteamento dinâmico.
A partir do funcionamento desse algoritmo na rede, listar para os nós s1, a1 e a2 o conteúdo da tabela de
roteamento. Analisar e verificar o conteúdo das tabelas em face ao funcionamento da rede.
3. Escolher dois hosts em subredes diferentes e gerar tráfego de alguma aplicação. Identificar ao menos os seguintes
itens no tráfego entre os dois hosts: 
  a) os protocolos utilizados na camada de aplicação e camada de transporte
  b) formato de mensagens, segmentos, datagramas e quadros 
  c) análise do encapsulamento da pilha TCP/IP entre esses dois pontos, explicitando qual é o overhead do encapsulamento para os dados gerados na camada de
  aplicação.
4. Entre os dois nós escolhidos, com os recursos do simulador calcular:
  1. Atraso médio da aplicação. Dada a topologia da rede, calcular analiticamente o atraso esperado entre
  esses dois hosts. Comparar o atraso resultante da simulação com o atraso calculado analiticamente.
  Explicar e justificar as possíveis variações nos resultados.
  2. Vazão da aplicação fim a fim. Analisar esse resultado em face ao protocolo de transporte utilizado.
5. Link para um vídeo em ambiente público em que o grupo apresenta em 08 minutos o funcionamento do ambiente
configurado no simulador (itens 1 e 2), um exemplo da simulação realizada (itens 3 e 4) com uma análise dos
resultados.
