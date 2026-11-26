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
