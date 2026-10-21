# Projeto Balloone - Grupo 5

Repositório do Grupo 5 no processo seletivo da equipe Titans. Contém a documentação, código-fonte e registros de desenvolvimento do projeto Balloone.

## Sobre o Projeto

O Balloone é um robô móvel controlado remotamente, equipado com uma ESP32-CAM, um mecanismo frontal para estouro de balões e um suporte para o balão do próprio robô. 

O projeto consiste em operar o robô na Praça Solar (UnB Gama - FCTE), localizando alvos através da transmissão de vídeo da ESP32-CAM e estourando balões, incluindo aqueles posicionados fora da linha de visão direta dos operadores.

## Especificações Técnicas

### Hardware e Mecânica

*   **Locomoção:** O robô deve possuir locomoção própria.
*   **Mecanismo frontal:** Capaz de estourar balões, com comprimento máximo horizontal de 25 cm.
*   **Suporte do balão:** 
    *   Extremidade superior deve estar a 10 cm do chão.
    *   Centro do balão deve ficar a aproximadamente 11 cm acima da extremidade superior do suporte (direção vertical).
    *   Balão deve permanecer exposto em todas as direções (sem estruturas ou carenagens de proteção).
    *   Deve permitir a substituição do balão caso seja estourado.
*   **Dimensões máximas do robô:** Comprimento de 23 cm e largura de 20 cm (considerando rodas e componentes laterais).
*   **Estrutura e Eletrônica:**
    *   Estrutura capaz de acomodar os componentes eletrônicos.
    *   Suporte seguro para a ESP32-CAM.
    *   Sistema de alimentação.
    *   Chave física liga/desliga.
    *   LEDs de indicação.
    *   Estrutura robusta para operar durante os três rounds.

### Software e Sistema de Controle

*   **Movimentação:** Controle remoto permitindo movimentação para frente, para trás, para a esquerda e para a direita.
*   **Transmissão de Vídeo:** ESP32-CAM fornecendo visão frontal do robô.
*   **Interface:** Visualização da transmissão via aplicação web, desktop, mobile ou outra solução justificável.
*   **Requisitos de Transmissão:** O desenvolvimento deve avaliar e justificar protocolos considerando latência, estabilidade, taxa de quadros, resolução, ocorrência de travamentos, consumo de recursos e comportamento diante de instabilidades de rede.

## Entregas Requeridas

Itens a serem apresentados até o final do processo trainee:

1.  Balloone funcional.
2.  Mecanismo frontal funcional para estouro dos balões.
3.  Suporte para o balão do próprio robô em conformidade com os requisitos mecânicos.
4.  Controle remoto funcional para o Balloone.
5.  ESP32-CAM transmitindo a visão frontal.
6.  Interface de operação.
7.  Integração funcional entre hardware e software.
8.  Código-fonte.
9.  Documentação.
10. Relatório final.
11. Participação nos três rounds da competição final.

## Estrutura do Relatório Final

O documento deve ser entregue até 4 de dezembro de 2026 contendo:

*   Descrição geral do projeto e arquitetura do sistema.
*   Divisão de responsabilidades.
*   Decisões técnicas adotadas, alternativas consideradas e justificativas.
*   Imagens de CAD e esquemáticos eletrônicos.
*   Códigos, organização do software e descrição da interface.
*   Protocolos de comunicação utilizados.
*   Testes realizados, dificuldades encontradas e limitações do projeto.
*   Resultados obtidos e possíveis melhorias futuras.

## Calendário

| Data | Horário | Programação |
| :--- | :--- | :--- |
| 31/10/2026 | 10h | Ponto de controle 1 (duração de até 1 hora). Esclarecimento de dúvidas, acompanhamento e alinhamento do projeto. |
| 21/11/2026 | 10h | Ponto de controle 2 (duração de até 1 hora). Esclarecimento de dúvidas, acompanhamento e alinhamento final do projeto. |
| 04/12/2026 | - | Entrega do relatório final do projeto. |
| 05/12/2026 | 10h | Competição final (Rounds 1, 2 e 3) na Praça Solar da UnB Gama - FCTE. |

## Integrantes

<table width="100%" border="0" cellspacing="0" cellpadding="0">
<tr valign="top">
<td width="48%">

### Hardware

| Foto | Nome | Perfil GitHub | Função |
| :---: | :--- | :--- | :--- |
| <img src="https://ui-avatars.com/api/?name=Luis+Guilherme&size=90" width="90" height="90" alt="Luis Guilherme"> | Luis Guilherme | Pendente | **Gerente de Hardware** <br> Eletrônica |
| <img src="https://github.com/Luc4sF3rreira.png?size=90" width="90" height="90" alt="Lucas Santana"> | Lucas Santana | [Luc4sF3rreira](https://github.com/Luc4sF3rreira) | Eletrônica |
| <img src="https://github.com/sarahteles.png?size=90" width="90" height="90" alt="Sarah Brito"> | Sarah Brito | [sarahteles](https://github.com/sarahteles) | Mecânica |
| <img src="https://github.com/luizao2945.png?size=90" width="90" height="90" alt="Luiz Octávio"> | Luiz Octávio | [luizao2945 ](https://github.com/luizao2945) | Mecânica |

</td>
<td width="0%"></td>
<td width="48%">

### Software

| Foto | Nome | Perfil GitHub | Função |
| :---: | :--- | :--- | :--- |
| <img src="https://github.com/thomas4ugust0.png?size=90" width="90" height="90" alt="Thomas Augusto"> | Thomas Augusto | [thomas4ugust0](https://github.com/thomas4ugust0) | **Gerente de Software** <br> Interface |
| <img src="https://github.com/Atila05.png?size=90" width="90" height="90" alt="Átila Sobral"> | Átila Sobral | [Atila05](https://github.com/Atila05) | Firmware |
| <img src="https://github.com/renanpr7.png?size=90" width="90" height="90" alt="Renan Reis"> | Renan Reis | [renanpr7](https://github.com/renanpr7) | Firmware |
| <img src="https://ui-avatars.com/api/?name=Lucas+Nunes&size=90" width="90" height="90" alt="Lucas Nunes"> | Lucas Nunes | Pendente | Rede |
| <img src="https://github.com/bea-debug.png?size=90" width="90" height="90" alt="Lana Beatriz"> | Lana Beatriz | [bea-debug](https://github.com/bea-debug) | Integração e <br> Documentação |

</td>
</tr>
</table>

