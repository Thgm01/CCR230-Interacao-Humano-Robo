# **OmniCare:** Robô Hospitalar

Trabalho de Interação Humano-Robô (IHR) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interação Humano-Robô (IHR) (CCR230) do curso de Engenharia de Robôs, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo
- Julia Biazi Pisok - 11.124.224-4 - Eng. de Controle e Automação
- Leonardo Santos de Andrade Quirino - 11.121.422-7 - Eng. de Robôs
- Lucas Ricardo Moraes Lagoeiro - 11.120.316-2 - Eng. de Robôs
- Thiago Travagini Moura - 11.121.329-4 - Eng. de Controle e Automação

## Resumo

O protótipo OmniCare é um robô móvel omnidirecional, autônomo e modular, projetado para transportar materiais entre andares em hospitais utilizando elevadores. A proposta visa contornarlimitações de soluções que dependem da integracão como sistema interno dos elevadores. O robô conta com uma estrutura compacta e adaptável, equipada com manipulador cartesiano para acionar fisicamente os botôes, buzzer para emitir alertas, luzes LED para emissão de sinais e feedbacks visuais e uma tela que age como rosto e painel de comando.

## Introdução

Nos últimos anos, a robótica tem desempenhado um papel fundamental no desenvolvimento de soluções tecnológicas voltadas para a saúde, com o objetivo de melhorar a eficiência hospitalar e reduzir riscos para os profissionais. Aplicações como a cirurgia assistida por robôs, a reabilitação e terapia robóticas e o uso de robôs em ambientes hospitalares, como no transporte de equipamentos, têm sido amplamente adotadas. Essas tecnologias têm permitido intervenções mais precisas, maior agilidade no atendimento e uma significativa redução no tempo de recuperação dos pacientes. 
E no cenário pós-pandêmico, a automação hospitalar tem ganhado destaque como uma ferramenta de apoio à rotina clínica e operacional. Contudo, um desafio técnico recorrente é a limitação dos robôs móveis em realizarem tarefas logísticas entre diferentes andares, já que a maioria das soluções atuais depende da integração com o sistema interno dos elevadores, algo muitas vezes inviável.

Omnicare é um robô móvel omnidirecional, autônomo e modular, com capacidade de interagir fisicamente com elevadores comuns por meio de um manipulador que aciona os botões necessários para a navegação entre andares.

Navegar em diferentes andares de um hospital para auxilar a equipe do local.

O robô deve proporcinar uma experiência segura e confiavél.

## Publico Alvo

Equipe que trabalha no hospital.
  

### Personas

- Descreva as personas que irão interagir com o robô. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o robô deve saber antes de iniciar a tarefa?

**1ª Persona: Dra. Mariana Alves – Coordenadora de Enfermagem**

Identidade
  - Nome: Mariana Alves;
  - Idade: 38 anos;
  - Estado civil: Casada, três filhos;
  - Formação: Enfermagem com especialização em Gestão Hospitalar;
  - Local de trabalho: Hospital geral de médio porte;
  - Personalidade: Prática, responsável, comprometida com a segurança e o bem-estar da equipe e dos pacientes;

Status
  - Persona Primária

Objetivos
  - Garantir eficiência no transporte de materiais entre setores e andares;
  - Reduzir a sobrecarga da equipe de enfermagem em tarefas logísticas;
  - Melhorar a agilidade e segurança nos processos internos do hospital;
  - Aumentar o tempo disponível da equipe para atendimento direto aos pacientes.

Habilidades
  - Graduação em enfermagem com mestrado em órteses;
  - Experiência em gestão de equipes multidisciplinares;
  - Conhecimento em protocolos de biossegurança hospitalar;
  - Capacidade de organizar fluxos de trabalho em ambientes de alta demanda;
  - Boa adaptação a novas tecnologias, desde que tragam benefícios claros à equipe.
  
Tarefas
  - Supervisionar e organizar turnos e funções da equipe de enfermagem;
  - Garantir que materiais e equipamentos cheguem no tempo certo aos setores;
  - Solucionar problemas logísticos do dia a dia (falta de insumos, atrasos em entregas internas);
  - Avaliar se novas soluções tecnológicas são viáveis na rotina da equipe.

Relacionamentos
  - Equipe de enfermagem: principal elo, responsável por executar muitas das tarefas operacionais;
  - Gestores hospitalares: reporta indicadores e sugere melhorias, influencia em decisões de adoção de tecnologias;
  - Equipe de apoio logístico: trabalha em conjunto para transporte de insumos;
  - Médicos: depende da rapidez logística para atender às demandas clínicas;
  - Pacientes: impacto indireto — melhor logística significa mais tempo e qualidade no atendimento;
  - Principal responsável por coordenar a equipe de enfermagem e garantir o bom fluxo de materiais e equipamentos dentro do hospital;
  - Atua como decisora de rotina operacional, mas não necessariamente na compra de tecnologias (pode influenciar gestores).

Mapa de empatia

<img width="1052" height="728" alt="image" src="https://github.com/user-attachments/assets/f6f80076-ac20-46f0-958c-7f4effb212d5" />

Jornada do usuário

<img width="1920" height="1080" alt="dra mariana" src="https://github.com/user-attachments/assets/9aa292b3-ed77-4f7b-96b5-2d575773747b" />






**2ª Persona: Carlos Mendes – Gerente Administrativo Hospitalar**

Identidade
  - Nome: Carlos Mendes;
  - Idade: 45 anos;
  - Estado civil: Solteiro, dois filhos;
  - Formação: Administração com MBA em Gestão Hospitalar;
  - Local de trabalho: Hospital privado de grande porte;
  - Personalidade: Analítico, orientado a resultados, focado em custo-benefício e eficiência operacional;

Status
  - Persona Primária.  

Objetivos
  - Reduzir custos operacionais ligados à logística interna;
  - Garantir eficiência no transporte de insumos, sem precisar contratar mais pessoal;
  - Minimizar riscos trabalhistas relacionados ao esforço físico de transporte manual;
  - Tornar o hospital referência em inovação tecnológica e automação hospitalar.

Habilidades
  - Graduação em enfermagem com mestrado em órteses;
  - Gestão financeira e análise de retorno sobre investimento (ROI);
  - Planejamento estratégico de processos hospitalares;
  - Capacidade de negociação com fornecedores e parceiros tecnológicos;
  - Visão sistêmica para equilibrar inovação, custo e aplicabilidade real.
  
Tarefas
  - Avaliar propostas de novas tecnologias para o hospital;
  - Monitorar indicadores de eficiência operacional (tempo de entrega de materiais, custos de pessoal);
  - Coordenar melhorias de infraestrutura hospitalar;
  - Aprovar investimentos em automação e soluções inovadoras.

Relacionamentos
  - Diretoria hospitalar: reporta resultados financeiros e propõe inovações;
  - Equipe de enfermagem e médica: depende de feedback deles sobre eficiência logística;
  - Equipe de TI e manutenção: garante integração, suporte e funcionamento das novas soluções.;
  - Fornecedores de tecnologia: negocia aquisição, contratos de manutenção e suporte;
  - Pacientes (indiretamente): busca melhorar a experiência por meio de processos mais ágeis e eficientes.


Mapa de empatia

<img width="1048" height="730" alt="image" src="https://github.com/user-attachments/assets/61f24f18-db7c-4be7-ba84-f010701a20fb" />

Jornada do usuário

<img width="1920" height="1080" alt="carlos mendes" src="https://github.com/user-attachments/assets/4733558f-98c5-4483-aed9-b482527b3fe0" />



**3ª Persona: Enzo Ferreira – Estagiário de Enfermagem**

Identidade
  - Nome: Enzo Ferreira;
  - Idade: 26 anos;
  - Estado civil: Solteiro;
  - Formação: Graduando em Enfermagem;
  - Local de trabalho: Hospital universitário de médio porte;
  - Personalidade: Curioso, esforçado, adaptável, mas ainda inseguro em algumas situações práticas;

Status
  - Persona Secundária  

Objetivos
  - Aprender na prática e ganhar experiência no ambiente hospitalar;
  - Ajudar a equipe sem comprometer o cuidado com os pacientes;
  - Ser reconhecido como alguém dedicado e colaborativo;
  - Reduzir erros e evitar situações que exponham sua falta de experiência;
  - Mostrar interesse por novas tecnologias para se destacar.

Habilidades
  - Boa disposição física para deslocamentos e atividades práticas;
  - Rápida adaptação a mudanças e novos processos;
  - Familiaridade com tecnologias digitais (apps, sistemas, automação);
  - Capacidade de aprender observando e executando sob supervisão.
  
Tarefas
  - Apoiar a equipe de enfermagem em tarefas logísticas e administrativas;
  - Acompanhar transporte de medicamentos, materiais e exames;
  - Auxiliar em rotinas básicas de cuidado direto com pacientes;
  - Aprender protocolos de biossegurança e fluxo hospitalar;
  - Observar o funcionamento de tecnologias e sistemas do hospital.

Relacionamentos
  - Enfermeiros supervisores: principais responsáveis por sua formação prática;
  - Médicos residentes: contato frequente durante rotinas de enfermagem;
  - Pacientes: vínculo indireto, ajudando em tarefas simples;
  - Colegas estagiários: troca de experiências e aprendizado conjunto.

Mapa de empatia

<img width="1048" height="731" alt="image" src="https://github.com/user-attachments/assets/16b535d2-b4a9-41a6-8732-b83af0c0cd7f" />

Jornada do usuário

<img width="1920" height="1080" alt="enzo ferreira" src="https://github.com/user-attachments/assets/de898096-3f75-4e37-8b92-2aec33176c43" />



## Contexto de uso
O OmniCare foi projetado para interagir em ambientes hospitalares, como hospitais, clínicas e centros de saúde, onde há grande fluxo de pessoas e rotinas sensíveis ao tempo. Nesse espaço, o robô precisa lidar com corredores movimentados, elevadores, diferentes andares e áreas de acesso restrito, sempre respeitando as regras de higiene, segurança e silêncio que caracterizam o ambiente hospitalar. A sua presença deve ser discreta e eficiente, auxiliando a equipe de saúde em tarefas logísticas como entrega de medicamentos e materiais, sem atrapalhar o trabalho humano.

No aspecto social, o robô se insere em um ambiente onde há pacientes em situações de vulnerabilidade, profissionais que trabalham sob pressão e familiares que muitas vezes estão preocupados. Por isso, a interação deve transmitir confiabilidade, empatia e neutralidade, de modo que seja visto como um aliado e não como um intruso. Já no aspecto econômico, a implementação do OmniCare está ligada à busca dos hospitais por otimização de recursos, redução de custos e aumento da eficiência. A automação de tarefas repetitivas libera tempo dos profissionais de saúde para atividades que exigem atenção humana, contribuindo para um melhor uso da equipe disponível. Culturalmente, o ambiente hospitalar exige respeito à privacidade, dignidade e protocolos estabelecidos, além de adaptação às diferentes formas de comunicação, considerando a diversidade linguística e cultural dos pacientes e colaboradores.

Para atuar de forma eficaz, o OmniCare deve conhecer previamente informações sobre o hospital em que está inserido. É essencial que tenha acesso ao mapeamento do espaço, incluindo plantas dos andares, localização de corredores, salas e elevadores, além de distinguir áreas públicas das restritas. Também deve compreender a infraestrutura de mobilidade, como dimensões de portas e regras de circulação, e estar atento às condições dinâmicas do ambiente, como a movimentação constante de pessoas, macas e cadeiras de rodas. Além disso, precisa ter informações operacionais, como horários de entrega de medicamentos, prioridades de cada tarefa e protocolos de segurança no transporte de itens sensíveis. Por fim, é fundamental que reconheça quem são os usuários autorizados a interagir com ele, quais idiomas deve utilizar e quais são os diferentes níveis de acesso, garantindo que sua atuação seja eficiente, segura e adequada ao contexto hospitalar.


## Análise de concorrência

**TUG / T3 - Aethon**

<img width="3840" height="2159" alt="image" src="https://github.com/user-attachments/assets/169a24b5-e013-40b5-af6e-26391e4cd82c" />


TUG / T3 é uma linha consolidada de AMRs hospitalares que auxiliam em transporte de medicamentos, roupas, refeições, amostras etc. Ele é capaz de trabalhar com elevadores por meio de um sistema de integração por meio de interface com as controladoras do prédio

- Forças: implantado em muitos hospitais, modelos voltados para cargas grandes, suporte comercial, técnico e de experiência de integração com TI hospitalar.
- Fraquezas: depende de integração com a infraestrutura do hospital, e tambám há relatos públicos sobre a vulnerabilidades de segurança dos sistemas de robôs AMRs

Quando comparado ao Omnicare, é notavél a sua superioridade no quesito de maior suporte para carregamento de cargas, porém ele perde ao precisar ser integrado ao sistema do hospital para se locomover entre andares.

**Athena 2.0 - Slamtec**

<img width="640" height="765" alt="image" src="https://github.com/user-attachments/assets/dfa74134-b66f-43d1-a010-b27b47aa3973" />


A Athena 2.0 é plataforma robótica móvel de uso geral, comunmente usada em logística, hotéis, hospitais e fábricas. Além de ser capaz de suportar transporte de cargas de até 60 kg, esse robô conta com o Smart Elevator Control 4.0, um sistema que se integra digitalmente aos elevadores, permitindo chamadas, monitoramento e deslocamento entre andares.

- Forças: boa capacidade de carga para porte médio, navegação SLAM avançada com LiDAR, detecção de obstáculos, mapeamento de múltiplos andares, autonomia de até 19 horas, e disponibilidade comercial.
- Fraquezas: depende de integração eletrônica com elevadores, risco de falhas de compatibilidade ou de comunicação entre sistemas.

Omnicare apresente uma superioridade à Athena 2.0 por não precisar de um sistema integrado para utilizar elevadores, porém ele perde quando olhamos para a autonomia de 19 horas da Athena 2.0.


**Moxi - Diligent Robotics**

<img width="768" height="854" alt="image" src="https://github.com/user-attachments/assets/f6b97897-e661-49e6-8d68-093685c068fe" />


Moxi é robô assistente social desenvolvido para hospitais com foco em aliviar a carga de trabalho de enfermagem e corpo clínico. Faz isso por meio de entregas internas de suprimentos, medicamentos, kits e materiais leves. Apesar de um design mais "humano", ele não pode utilizar elevadores por meio de contato físico, no lugar conta com um sistema de integração.

- Forças: design humanizado e social, experiência comprovada em ambientes hospitalares, foco em tarefas que liberam tempo da equipe de enfermagem.
- Fraquezas: capacidade de carga limitada,ddependência de integração com elevadores, menor versatilidade em relação a tarefas industriais ou de transporte pesado.

O Moxi tem uma grande vantagem em relação ao Omnicare no quesito de aceitação social e o foco na experiência de usuários humanos, enquanto o OmniCare aposta em versatilidade técnica. Isso dá ao OmniCare vantagem em hospitais com infraestrutura mais antiga e a vantagem de suportar mais carga.


## Design
<!-- ![Partes do robô](partes_do_robo.png) -->
<!-- ![Robô](robo.png) -->
URDF do Omnicare:

<img width="440" height="701" alt="image" src="https://github.com/user-attachments/assets/207e3279-b311-450c-affa-77d40f177ee5" />



## Interações do robô

### Espacial

- Uso de elevadores:
  - Com seu manipulador, Omnicare irá chamar o elevador e se posicionar dentro próximo ao painel, onde irá selecionar o andar de entrega.
  - Pré-requisitos: manipulador funcional, visão computacional para identificação dos andares e sensores para detectar obstáculos.
  - Resposta emocional do usúario: alívio e tranquilidade.
 
- Entrega de itens:
  - Omnicare irá se posicinar, de maneira alinhada, no ponto de coleta dos itens. Feito isso se deslocará até o local de entrega de forma autonoma.
  - Pré-requisitos: reconhecimento do ponto de entrega (checkpoint na navegação), sensores para indentificar possiveis obstaculos, área de armazenamento.
  - Resposta emocional do usúario: segurança com itens e praticidade do serviço.

- Distância entre pessoas ao se locomover:
  - Omnicare deve manter uma distância segura de, pelo menos, meio metro dos funcionários e pacientes do hospital enquanto se desloca.
  - Pré-requisitos: sensores para indentificar obstáculos e pessoas, rotas mapeadas, programa que ajusta a velocidade dos motores.
  - Resposta emocional do usúario: segurança e confiança.


### Verbal

- Confirmação de entrega:
  - Ao chegar no local de entrega dos itens, o Omnicare irá emitir uma mensagem de voz avisando que os itens estão prontos para retirada.
  - Pré-requisitos: sistema de voz, alto falantes.
  - Resposta emocional do usúario: clareza e confiança.

- Aviso de falha:
  - Em caso de algum erro ocorrer durante a entrega de algum item, o Omnicare irá emitir um alerta avisando que uma falha no sistema ou um impecilio na rota foi identificado.
  - Pré-requisitos: sistema de voz, alto falantes, sensores para indentificar obstáculos.
  - Resposta emocional do usúario: transparência em relação a identificação do erro e preocupação com o que pode ter ocorrido.

### Não-verbal

- Sinalização com LEDs:
  - O Omnicare utilizará LEDs para identificar seu status ao se locomover, como: luz verde para tudo ok, luz amarela para alertar que está em movimento e luz vermelha para sinalizar erros.
  - Pré-requisitos: hardware que se cominuque com os LEDs, integração de status.
  - Resposta emocional do usúario: clareza e tranquilidade.
 
  - Movimentação suave:
  - Ao se locomover é importante que o Omnicare seja capaz de controlar sua velocidade, de forma suave e gradual, em momentos de curvas ou que passar perto de pessoas.
  - Pré-requisitos: controle dos motores, sensores para identificar a presença de pessoas.
  - Resposta emocional do usúario: Conforto e calma.
 
 
 ## Interações culturais

Para analizar o comportamento que o Omnicare deve apresentar quando estiver em um local com uma cultura diferente do nosso país, foi pensado em possíveis interações nos 3 seguintes países: Alemanha, Japão e Suécia

### Alemanha 
- Precisão no posicinamento de coleta/entrega:
  - É muito importante para os alemães que a ordem, a presibilidade e a eficiência sejam preservadas. Caso opere em hospitais na Alemanha, o Omnicare deverá sempre se posicionar no mesmo ponto designado com marca no chão.
  - Pré-requisitos: mapeamento, marcações visuais/físicas, precisão na navegação.
  - Resposta emocional do usúario: eficiência e disciplina.
 
- Tom objetivo:
  - Os alemães são um povo que tendem a se comunicar de maneira clara e concisa com base em dados. Caso opere em hospitais na Alemanha, o Omnicare deverá comunicar todo o status da entrega de forma direta como: “Entrega dos remédios foi concluída. O tempo total foi de 3 minutos. A entrega foi recebida pelo enfeimeiro responsável”.
  - Pré-requisitos: módulo de voz e personalização de frases.
  - Resposta emocional do usúario: eficiência e profissionalismo.

- Exibição de dados:
  - Como já mencionado, a clareza e transparência nos dados é muito importante para os alemães. Caso opere em hospitais na Alemanha, é importante que o corpo do Omnicare receba uma atualização para contar com um display que mostre o tempo estimado de entrega e status exato.
  - Pré-requisitos: painel LCD integrado ao corpo do Omnicare e sincronização de dados.
  - Resposta emocional do usúario: organização e confiança.
 
### Japão
- Posicinamento ao parar:
  - Os japoneses prezam muito pela harmonia coletiva, para eles é um ato de educação parar de uma forma que não bloqueie o fluxo de passagem. O Omnicare deve ficar enconstado à parede para mostrar discrição e respeito ao espaço compartilhado.
  - Pré-requisitos: mapeamento, sensores precisos, boa leitura do espaço.
  - Resposta emocional do usúario: respeito e harmonia.
 
- Tom mais polido:
  - A cultura japonesa valoriza a cortesia e o respeito hierárquico. É importante que o Omnicare possa dizer ao menos um simples “Muito obrigado pelo seu trabalho” para reforça boas práticas sociais e criar empatia, mesmo sendo um robô.
  - Pré-requisitos: módulo de voz e personalização de frases.
  - Resposta emocional do usúario: respeito e cortesia.

- Exibição de dados:
  - A cultura do respeito é muito forte no Japão, o gesto de inclinar-se é culturalmente reconhecido como sinal de respeito. Omnicare pode realizar um pequeno movimento simbolico de inclinação pela tela que servirá como sua tela, assim ele se conecta à etiqueta local, tornando-o mais aceito socialmente.
  - Pré-requisitos: tela funcional para ser seu rosto e efeito visual.
  - Resposta emocional do usúario: respeito e empatia.
 
### Suécia
- Respeito do espaço interpessoal:
  - Os suecos são um povo que valorizam muito o respeito a sua privacidade e distanciamento físico em áreas públicas. Ao operar na Suécia, OmniCare deve manter uma zona de segurança maior para evitar a sensação de invasão e gerar desconforto.
  - Pré-requisitos: sensores melhorados para atender a zona de segurança maior e configuração reginal.
  - Resposta emocional do usúario: conforto e privacidade.
 
- Comunicação reduzida:
  - A comunicação do povo sueco é contida e funcional. Ao Omniciare emitir mensagens simples e diretas como somente “Entrega concluída” evitam sobrecarga informativa e transmitem naturalidade e sobriedade, alinhadas ao estilo local.
  - Pré-requisitos: filtro de mensagens, módulo de voz e modo silencioso.
  - Resposta emocional do usúario: naturalidade e discrição.

- Neutralidade visual:
  - O design escandinavo é conhecido pela simplicidade, clareza e ausência de excessos. Para transmitir tranquilidade em um hospital da Suécia, o OmniCare deve usar cores discretas, evitar animações chamativas e adaptar a intensidade de seus LEDs ao trocar de ambiente.
  - Pré-requisitos: sitema de iluminação regulavél, estrutura adaptada, algoritimo de comportamento.
  - Resposta emocional do usúario: conforto e tranquilidade.
 
 

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>


## Molic Apresentação da OmniCare

<img width="1148" height="729" alt="image" src="https://github.com/user-attachments/assets/247be3ac-320e-4403-997c-e3ee4492a837" />


## Molic Navegação da OmniCare

<img width="920" height="729" alt="image" src="https://github.com/user-attachments/assets/f8842f1f-fc73-48b9-8bcd-4fba41cbdc2d" />


