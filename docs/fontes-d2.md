# D2 PHASER: fontes e decisões (v0.1)

## Fontes
- *D2 PHASER User Manual*, DOC-M88-EXX141 V5 (01.2015), Bruker AXS. Cópia do ManualsLib. Fonte principal do Equipamento, da Jornada e dos valores do simulador.
- *DIFFRAC.EVA User Manual*, DOC-M88-EXX200 V8 (04.2021). Fundo (Enhanced desmarcado para a busca), Kα2 stripping dispensável, busca sobre o difratograma inteiro, correção de deslocamento pelo raio do goniômetro, X offset, cristalinidade.
- Folheto *D2 PHASER 2nd Generation* (2015): dimensões (61 × 60 × 70 cm), 95 kg, faixa angular, detectores, trocador de 6 posições Ø 32 mm.
- Procedimento de uso da WSU (OPPXRD-1, Rev. 3-2022), **de terceiros**, usado só onde o manual não diz:
  - abertura do LYNXEYE de cerca de metade do ângulo inicial abaixo de 10°;
  - discriminador inferior de 0,110 para 0,190 em amostras com Fe, Co ou Ni;
  - fendas de 0,1/0,2/0,6/1,0 mm;
  - 0,5 s como tempo padrão.
- Configuração da unidade, informada pelo usuário: trocador de 6 posições, porta-amostra de aço com anéis concêntricos (a amostra vai no lado dos anéis), tubo de Cu. Exemplo de método: 30 kV, 10 mA, 2–40° (às vezes 50°), passo 0,02°, 0,5 s.

## Do manual
| Conteúdo | Onde |
|---|---|
| Raio do goniômetro 141,4 mm; θ/θ Bragg-Brentano; amostra horizontal | Basics; Goniometer |
| Tubo KFL Cu 2K, foco 12 × 0,4 mm, 30 kV/10 mA, janela de Be, termomódulo (62/68/86 °C) | X-ray tube; Troubleshooting |
| Fendas, Soller 1,5/2,5/4° iguais nos dois lados, filtro de Ni, absorvedor, anteparo 1/3 mm e 0,5/2 mm no trocador | Slit systems e seguintes |
| LYNXEYE: 192 tiras, 100 a 150× mais rápido que cintilador, 0,1–1 s por passo | Detectors; Start measurement with commander |
| Porta trava com HV ligada; LEDs ready/alarm/busy; barra de raios X; ar soprado ao abrir a porta | Front door; Warning and status lamps; Sample holder |
| Corindo: 13 posições de pico; ±0,02° de 25° a 145°; condição da verificação | Measurement with the D2 PHASER; Zero definition |
| Trocador: carregamento n, n+1, n+2 e rotação de 180° | Configuration and settings of sample section |
| Refrigeração: nível semanal, pH ≥ 8, completar até 10 mm da borda, filtros semanais | Maintenance |
| Kα1 0,154060 nm; Kα2/Kα1 = 51,2%; Kβ1+Kβ3 ≈ 18% | Tables and constants |

## Escolhas e hipóteses
- **3D:**
  - O gabinete, o goniômetro e o trocador são esquemáticos: não há fotos da unidade.
  - A escala é 1 unidade = 100 mm; o raio do goniômetro está em escala.
  - A forma e a cor do gabinete são aproximadas.
- **Fenda e abertura do feixe:** a abertura foi tomada como proporcional à largura da fenda. O manual só dá o ponto 1,0 mm = 0,6°.
- **Cavidade:** o diâmetro de cerca de 25 mm é estimado pela foto (anel de 32 mm). Falta a medida real.
- **Simulador:**
  - As amostras são fictícias, com intensidades relativas observadas.
  - As intensidades do corindo são aproximadas; as posições vêm do manual.
  - São escolhas do simulador:
    - largura dos picos;
    - escala de contagens;
    - transmissão do filtro (Kα 0,6, Kβ 0,01);
    - espalhamento do ar;
    - fluorescência do aço;
    - estatística de grãos;
    - orientação preferencial;
    - corte do feixe pela borda baixa do anteparo, uma estimativa geométrica.
- **Física padrão usada:**
  - Bragg;
  - Δ2θ = 2·s·cosθ/R;
  - comprimento iluminado R·α/senθ;
  - ruído de Poisson.

## Pendências
- Fotos da unidade, para o 3D.
- Diâmetro e profundidade da cavidade do porta-amostra.
- Fenda, anteparo e abertura do LYNXEYE usados no método.

## v0.2: aparência pelas fotos de modelo
O usuário enviou fotos de modelo do D2 PHASER 2nd Gen. Não são da unidade, mas são bem próximas. O 3D passou a seguir:
- **Frente em três partes:**
  - coluna esquerda com os LEDs Ready, On, Alarm e Busy, de cima para baixo;
  - porta no centro, com monitor, puxador preto e painel embaixo;
  - coluna direita com "D2 PHASER" na vertical, "2nd Gen" e a marca.
- **Faixa âmbar de raios X:** no alto da porta.
- **Cores:** laterais azul-marinho e base preta com a gaveta do teclado.
- **Compartimento:** janela logo abaixo do puxador, com moldura escura e trilhos. A porta desliza para cima para abrir.
- **Por dentro:** disco do goniômetro prateado, tubo com adesivo de aviso, LYNXEYE em carcaça clara com furos ovais, trocador embaixo no centro e um bloco escuro sobre a amostra.

Continuam esquemáticas: as posições internas e as proporções exatas.

## v0.3: porta com alavanca e travas
- **Abrir a porta:** a alavanca no centro do puxador (ou o botão **Abrir a porta**) faz a porta subir e expõe o compartimento. Fontes: o manual ("lift the knob on the lower side of the display") e as fotos de modelo.
- **Travas, do manual:**
  - com os raios X ligados, a porta só se move cerca de 4 mm e continua travada;
  - a alta tensão só liga com a porta fechada e travada.
- **LEDs, do manual:** depois que os raios X desligam, o LED Ready pisca, porque o filamento segue aquecido.
- **Escolha minha:** no 3D, o controle "Raios X e varredura" faz o papel de ligar a alta tensão.

## v0.5: critérios da USP <941>
Fonte: USP <941>, texto harmonizado Stage 4 (2021), baixado da página da USP, em `materiais\D2 PHASER`. Para identificação de fases:
- **Faixa:** de perto de 0° até pelo menos 30° 2θ.
- **Concordância:** espera-se que cada pico da amostra fique a até 0,2° 2θ do pico da referência, com a ressalva do capítulo para materiais em que se esperam variações maiores.
- **Moagem:** moer demais pode alterar a fase.

No laboratório, o "Maior desvio de pico" calcula o desvio de cada pico da referência pela altura da amostra (2·s·cosθ/R) e compara com 0,2°. O zoom mostra a faixa de ±0,2°. No simulador, só a altura desloca os picos: não há erro de zero.

Outros materiais na pasta, sem uso direto no Atlas ainda:
- Fawcett et al., 2019, revisão na revista *Powder Diffraction*;
- tutorial "How to Analyze Drugs", da ICDD;
- folhetos da IUCr nº 1 (introdução), 3 (fatores de estrutura) e 21 (empacotamento cristalino).

## v0.6: Fundamentos
Duas etapas novas no início da Jornada.
- **Lei de Bragg:** física padrão. A curva do difratograma de uma família de planos (d = 5,12 Å) usa a função de interferência de N = 30 camadas; o ângulo dos raios está desenhado em dobro.
- **Do arranjo ao difratograma:** o empacotamento é esquemático; os picos são os das formas fictícias do simulador.
- **Afirmações sobre a técnica:** vêm da USP <941>:
  - os raios X interagem com as nuvens de elétrons;
  - cada fase dá um padrão característico;
  - a posição dos picos depende da célula, e a intensidade, do conteúdo dela;
  - o método é, em geral, não destrutivo.
- **Base didática:** folhetos da IUCr nº 1 e 21.

## v0.7: amostra totalmente amorfa e correção de escala
- **Nova amostra "F: totalmente amorfa":** só halo, sem picos. O alerta explica que o DRX confirma o estado amorfo, mas não identifica a substância. Nessa amostra, sinal/ruído, pontos por pico e o critério da USP aparecem como "sem picos" ou "—".
- **Halo:** passou a ter a mesma escala dos picos, com cerca de 7% da altura do pico de 100% (escolha do simulador).
- **Correção:** a escala dos picos era normalizada pela fase mais forte da própria amostra, e a fração cristalina não aparecia na altura dos picos. Agora a escala é a da fase pura. Com isso, 25% de forma I dá picos com cerca de um quarto da altura, e os 15% de forma II da mistura ficam proporcionais.
