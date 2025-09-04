# **OmniCare:** Robô Hospitalar

Trabalho de Interação Humano-Robô (IHR) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Interação Humano-Robô (IHR) (CCR230) do curso de Engenharia de Robôs, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo
- Julia Biazi Pisok - 11.124.224-4 - Eng. de Controle e Automação
- Leonardo Santos de Andrade Quirino - 11.121.422-7 - Eng. de Robôs
- Lucas Ricardo Moraes Lagoeiro - 11.120.316-2 - Eng. de Robôs
- Thiago Travagini Moura - 11.121.329-4 - Eng. de Controle e Automação

## Resumo

O protótipo OmniCare é um robô móvel omnidirecional, autônomo e modular, projetado para transportar materiais entre andares em hospitais utilizando elevadores. A proposta visa contornarlimitações de soluções que dependem da integracão como sistema interno dos elevadores. O robô conta com uma estrutura compacta e adaptável, equipada com manipulador cartesiano para acionar fisicamente os botôes.

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

  Persona: Dra. Mariana Alves – Coordenadora de Enfermagem
Identidade
  •	Nome: Mariana Alves;
  •	Idade: 38 anos;
  •	Estado civil: Casada, três filhos;
  •	Formação: Enfermagem com especialização em Gestão Hospitalar;
  •	Local de trabalho: Hospital geral de médio porte;
  •	Personalidade: Prática, responsável, comprometida com a segurança e o bem-estar da equipe e dos pacientes;

Status
  •	Persona Primária

Objetivos
  •	Garantir eficiência no transporte de materiais entre setores e andares;
  •	Reduzir a sobrecarga da equipe de enfermagem em tarefas logísticas;
  •	Melhorar a agilidade e segurança nos processos internos do hospital;
  •	Aumentar o tempo disponível da equipe para atendimento direto aos pacientes.

Habilidades
  •	Graduação em enfermagem com mestrado em órteses;
  •	Experiência em gestão de equipes multidisciplinares;
  •	Conhecimento em protocolos de biossegurança hospitalar;
  •	Capacidade de organizar fluxos de trabalho em ambientes de alta demanda;
  •	Boa adaptação a novas tecnologias, desde que tragam benefícios claros à equipe.
  
Tarefas
  •	Supervisionar e organizar turnos e funções da equipe de enfermagem;
  •	Garantir que materiais e equipamentos cheguem no tempo certo aos setores;
  •	Solucionar problemas logísticos do dia a dia (falta de insumos, atrasos em entregas internas);
  •	Avaliar se novas soluções tecnológicas são viáveis na rotina da equipe.

Relacionamentos
  •	Equipe de enfermagem: principal elo, responsável por executar muitas das tarefas operacionais;
  •	Gestores hospitalares: reporta indicadores e sugere melhorias, influencia em decisões de adoção de tecnologias;
  •	Equipe de apoio logístico: trabalha em conjunto para transporte de insumos;
  •	Médicos: depende da rapidez logística para atender às demandas clínicas;
  •	Pacientes: impacto indireto — melhor logística significa mais tempo e qualidade no atendimento;
  •	Principal responsável por coordenar a equipe de enfermagem e garantir o bom fluxo de materiais e equipamentos dentro do hospital;
  •	Atua como decisora de rotina operacional, mas não necessariamente na compra de tecnologias (pode influenciar gestores).


### Mapa de empatia

<img width="1052" height="728" alt="image" src="https://github.com/user-attachments/assets/f6f80076-ac20-46f0-958c-7f4effb212d5" />


## Contexto de uso

- Descreva o ambiente em que o robô interage com os usuários
- Qual/quais o(s) contexto(s) sociais, econômicos e culturais existentes neste ambiente?
- Quais informações sobre o ambiente o robô deve saber antes de iniciar a tarefa?

## Jornada do usuário

- Criar uma narrativa para o o seu robô e o usuário.
- Determine o passo a passo que o usuário realiza desde o primeiro até o último encontro com robô na realização da tarefa.
- O que está acontecendo com o ambiente quando o robô está interagindo com o usuário?
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa evolui? Como a tarefa termina?
- Enfatize todos os momentos em que acontece uma interação verbal, não-verbal e espacial.

## Análise de concorrência

- Pesquise robôs existentes atualmente que possam fazer a tarefa deste projeto.
- Selecione pelo menos 3 robôs diferentes que podem fazer essa tarefa.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Quais plataformas sua equipe acha mais interessantes? Qual a justificativa?

## Design

- Pense nas características de Affordances do seu robô. Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto de um robô. Qual a importância e pontos a serem considerados se você quiser vender esse robô  seu robô?
- O seu robô tem um padrão com mais ou menos características antropomórficas? Qual padrão é mais aceito pela sociedade dentro do projeto que você está desenvolvendo?
- Quais o design mais apropriado para o robô deste projeto? Modele o seu robô com desenhos de formas primitivas (caixas, cilindros, esferas)

<!-- ![Partes do robô](partes_do_robo.png) -->
<!-- ![Robô](robo.png) -->
<img alt="Partes do robô" src="partes_do_robo.png" height="200"/>
<img alt="Robô" src="robo.png" height="200"/>

## Ações do robô

- Para cada ação:
  - Descreva a ação.
  - Determine os pré-requisitos para que a ação aconteça
  - Determine o que se espera que seja modificado no ambiente quando a ação é finalizada

## Interações do robô

### Espacial

- Para cada interação:
  - Descreva a interação.
  - Determine os pré-requisitos para que a interação aconteça
  - Determine espera de resposta emocional do usúario quando a interação é finalizada

### Verbal

- Para cada interação:
  - Descreva a interação.
  - Determine os pré-requisitos para que a interação aconteça
  - Determine espera de resposta emocional do usúario quando a interação é finalizada

### Não-verbal

- Para cada interação:
  - Descreva a interação.
  - Determine os pré-requisitos para que a interação aconteça
  - Determine espera de resposta emocional do usúario quando a interação é finalizada

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>


# Aula 4
## Tarefa 1

- Qual é a situação de uso para a IHR do seu robô?
  Transporte de itens e assitente de informação 
  - Contexto:
    O contexto principal analisado foi em um ambiente hospitalar.
  
  - Usuário(s):
    Os principais usuários são os funcionarios do hospital (Setor logistico, medicos, enfermeiros e etc.), os pacientes e também prestadores de serviços no hospital. Levando em conta principlamente as pessoas com qualquer tipo de dificuldade fisica, mental ou psicologica.
  
  - Objetivos:
    Auxiliar no transporte de cargas dentro do hospital de forma segura para os pacientes, prestadores de serviços e funcionários e também fornecer informações sobre o hospital.
  
  - Interação:
    Comunicação entre os funcionários para definir o que deve ser feito, interação social com todas as pessoas que frequentam o ambiente hospitalar e comunicação com os pacientes e prestadores de serviço do hospital para fornecer informações.

  - Interface e Sistema:
    Fiquei com duvida nesse topico

- Como inserir o seu robô em um contexto cotidiano para aprimorar a solução de um problema?
  É possível inserir o nosso robô dentro dos hospitais para servir de transportadores de cargas, realizando interações verbais e não verbais com todas as pessoas desse ambiente, podendo fornecer informações e repcionar os pacientes

- Onde seus usuários interagem com seu Robô?
  Robô utilizado para transporte de materiais que precisam de um maior cuidado (material infeccioso, alimentos, documentos ou remédios). Nesse caso o robô terá um uso mais interno do hospital onde suas principais interações serão com funcionários e prestadores de serviços com uma movimentação menor de pacientes. Esse uso fica com maior enfase em interagir com os responsaveis pela carga a ser transportada e com os destinatários dessas cargas (Farmácia, centros de exames, centros de coleta, lixeira e etc.). Também tem a interação com os pacientes onde o robo pode se comunicar com eles e fornecer informações e solicitar algumas tarefas como chamar o medico, guiar pelo hospital e etc.

