# LS 13 320 com ULM e Tornado: de onde veio cada informação (v0.5)

Fonte principal: *LS 13 320 Laser Diffraction Particle Size Analyzer, Instructions for Use* (B05577AA), na pasta `materiais`. Fotos de uma unidade em uso: frente, laterais e traseira do Tornado, o banco com o compartimento aberto e, desde a v0.5, o ULM (frente, laterais, etiqueta *Universal Liquids Module 2*, montagem 383665) com a sonda e a unidade de controle de sonicação. Um relatório de corrida serviu só para conferir nomes de campos (Average Vacuum, Residual, Optical model); produto, lote e resultados não aparecem no material.

| Informação | Onde está no manual |
|---|---|
| Laser de diodo de 5 mW, 750 ou 780 nm; filtro espacial de fibra óptica; lâmpada de tungstênio-halogênio com filtros de 450, 600 e 900 nm e polarizadores | Introdução, *Light Source* |
| Fonte, filtro espacial, lente de projeção, célula, óptica de Fourier, três conjuntos de detectores (ângulo baixo, médio e alto) | Introdução, *Optical Bench Overview* e fig. 4 |
| Encaixe automático: botões OPEN e EJECT MODULE, pinos da bandeja, inclinação de 30°, autoteste | §6, *Docking the Tornado DPS*; Introdução, fig. 5 |
| Tornado: 0,4 a 2000 µm, 5 a 30 cm³, mínimo de 10 s de medição, controle de obscuração de 4 a 8% com média a ±2% do alvo, dispersa pós coesos sem moer frágeis, sistema sob vácuo com filtro | §6, *Tornado Dry Powder System* e *Tornado Description* |
| LEDs Error, Load Sample, Vacuum e Power | §6, fig. 6.33 |
| Menu Control (Run Cleaner, Feed Sample, Sample Lift, Spinner, Lamp, Vacuum, Vacuum Settings) | §6, *Control Menu* |
| SOM (passo 4: obscuração de 4 a 8%; ISO 13320 sugere 5%), SOP = SOM + preferências; segurança alta só o administrador salva | §6, *SOM* e *SOP* |
| Limpeza: amostra de limpeza de 15 a 25 cm³; janelas (suporte, quatro travas, papel de lente com limpador); tampa com duas travas; placa de impacto com quatro parafusos; tubos de sucção e de bainha; filtro de bainha | §6, *Cleaning the Tornado DPS* e figs. 6.34 a 6.40 |
| Problemas de vácuo, LEDs e background | §6, *Tornado DPS Troubleshooting* |
| Fonte de vácuo: 420 L/min a 740–750 torr (5 a 10" de água abaixo da atmosfera), interruptor remoto | Cap. 2, *Vacuum for Tornado*; §6, especificações |
| Faixas: 0,017–2000 µm (ALM, ULM) e 0,4–2000 µm (MLM, Tornado); 92 e 116 canais; repetibilidade de 1%; medição de 1 a 999 s, típica de 30 a 90 s | Apêndice A |
| Aquecimento de 20 min (15 min em *Warming up*); fontes de erro; variação de 2 °C/h exige alinhamento e offsets pelo menos a cada hora | Segurança, *Other Precautions*; Cap. 2, *Getting Started*; Apêndice A |
| Offsets, alinhamento a 1–2 µm do centro, background, carga; obscuração de 4 a 7% basta no Tornado | Cap. 2, *Making Measurements* |
| Amostras-controle (G35 e GB 500 para o Tornado), verificação diária, sem calibração | Cap. 2, *Instrument Verification* e tab. 2.3 |
| Background duas vezes acima do normal: corrigir antes de medir; ver View › Intensity | Apêndice D |
| Fraunhofer × Mie: quase iguais acima de 100 µm, diferença pequena de 10 a 100 µm, modelo correto bem mais preciso com fração abaixo de 10 µm; Mie supõe esferas homogêneas | Apêndice C; Cap. 1, *Fraunhofer Theory* |
| Lentes de Fourier superior e inferior e lente de projeção: limpeza em espiral, papel uma vez só, nunca papel de óculos com silicone, offsets, alinhamento e background depois | Apêndice E, figs. E.1 e E.2 |
| PIDS: diferença entre polarizações vertical e horizontal em três comprimentos de onda | Cap. 1, *PIDS* |

| Proveta de plástico transparente e graduada no porta-amostra preto; bico de sucção chanfrado; parte traseira preta que entra no banco com a célula; quatro travas em T; janela redonda com três parafusos de um lado e janela retangular alta do outro; porta de vácuo na frente da base | Fotos de referência |

## ULM (v0.5)

| Informação | Onde está no manual |
|---|---|
| ULM: 0,017 a 2000 µm, mede toda a amostra recirculando, volume total de 125 mL, aquoso e orgânico, alvo de obscuração fixado ou automático, bomba interna com sensor de nível, enchimento e enxágue automáticos, rejeito em recipiente | §6, *Universal Liquid Module* e *ULM Description* |
| Encaixe: OPEN, EJECT MODULE, pinos, inclinação de 30°, uma mão no topo e outra na base | §6, *Loading the ULM* |
| Menu Control: Fill, Rinse (abrir dreno, fechar dreno, encher, bomba; N vezes), De-bubble, Pump Speed, Pump On/Off, Sonicate (tempo e potência), Open/Close Inlet, Open/Close Drain | §6, *ULM Software* |
| SOM passo 4: 60 s sem PIDS (mínimo 10 s), pelo menos 90 s com PIDS; bomba a ~30% com surfactante; 100% e depois ~50%, duas ou três vezes, para bolhas; bomba alta para partículas grandes e densas | §6, *Creating SOMs* |
| Líquidos: materiais molhados (Teflon, inox 316, vidro, Kalrez), ponto de fulgor > 10 °C, densidade ≥ 0,6, requisitos (transparente de 450 a 900 nm, limpo, sem bolhas etc.), lista de líquidos aceitos, miscibilidade antes de trocar | §6, *Suspension Fluids* e fig. 6.41 |
| Limpeza: Rinse, Open Drain, solução de limpeza pela entrada, Fill, 15 min a 1 h, Rinse; tampa com parafusos borboleta e haste do kit; superfícies ópticas a cada três meses | §6, *Cleaning the ULM* |
| Troca da janela de difração (anel, dois parafusos de náilon, o-ring, lado revestido para fora, teste do lápis, ferramenta de assentamento, teste de vazamento) | §6, *Replacing the Diffraction Cell Window* |
| Problemas: sem comunicação, não enche, não drena, bomba parada, vazamento | §6, *ULM Troubleshooting* |
| Dimensões (49,5 × 21 × 11,4 cm visíveis), 8,85 kg, < 50 W do banco | §6, *ULM Specifications* |
| Obscuração: 8 a 12% sem PIDS; PIDS de 40 a 60%; com distribuição larga, aumentar a de difração mesmo com a PIDS acima do máximo | Cap. 2, *Measure Loading* |
| Include PIDS para partículas abaixo de 0,4 µm (ULM e ALM); controles Latron 300LS, G15 e GB 500 | Cap. 2, *Running a Control* e tab. 2.3 |
| PIDS: lâmpada de tungstênio-halogênio, 450, 600 e 900 nm, duas polarizações, seis detectores perto de 90° e um de obscuração, informação principal de 0,017 a 0,4 µm e melhora até 0,8 µm, mesma matriz de deconvolução | Cap. 1, *PIDS Sizing* |
| 116 canais com ULM; 1 mg a 10 g de amostra | Apêndice A |
| Preparo: escolha do diluente (solubilidade, reatividade, suspensão, uso final; niacina como exemplo de pó farmacêutico que pede meio não aquoso), receita prática (molhar, espatular, diluir, microscópio, energia, estabilidade), surfactantes, pH a 2 unidades do ponto isoelétrico, riscos do ultrassom, emulsões e lipossomas, diluente com índice ou cor parecidos | Apêndice B |
| Corpo de inox com frente arredondada, topo branco com abertura e tampa articulada, conexões DRAIN e FILL na base, armação preta traseira com a célula (janela redonda com dois parafusos) e suporte branco, parafuso borboleta no alto da armação, sonda inclinada com etiqueta de não prender abaixo da linha, unidade *Sonication Control Unit* (LEDs SONICATING e POWER) sobre o banco | Fotos de referência |

**Interpretações minhas sobre o ULM:**
- A posição interna da bomba, do vaso e do caminho do líquido no 3D. O manual não traz desenho.
- Que a tampa com parafusos borboleta fica no alto da célula e cobre as janelas PIDS. No ALM o manual mostra isso; no ULM ele só diz "tampa".
- Que é preciso ejetar o módulo para alcançar a tampa da célula. O manual não diz, mas a célula fica dentro do banco.
- A sonda de ultrassom e a unidade de sonicação: o guia só descreve o comando Sonicate; o resto vem das fotos.

**Laboratório do ULM (`src/ls/simulador_ulm.js`, 14 testes em `test/ls-ulm.test.mjs`).** Vêm do manual as faixas e recomendações da tabela acima. São escolhas do simulador: as cinco amostras fictícias; quanto o ultrassom desfaz aglomerados e a partir de quando quebra; o limiar de 45% para bolhas com surfactante; a velocidade em que os grossos assentam; a relação entre a obscuração de difração e a PIDS; o borrão abaixo de 0,4 µm sem PIDS; e o tamanho de cada desvio. As condições de referência seguem o manual, não um método validado.

**Interpretações minhas (Tornado e banco):**
- Que o PIDS não entra nas medições com o Tornado. Concluí isso da faixa de especificação (0,4 µm, a mesma do MLM), da frase do manual que atribui a faixa até 0,017 µm ao PIDS e da opção Include PIDS, que o manual restringe a ULM e ALM.
- A função da placa de impacto (ajudar a desfazer aglomerados) e do fluxo de bainha (afastar o pó das janelas). O manual só cita as duas peças na limpeza e na solução de problemas.
- A definição do campo *Residual* do relatório. O manual do LS não o descreve nem dá limite.
- A geometria interna do 3D: posição das lentes e dos detectores, a tubulação interna e o lado em que ficam as fontes. A janela redonda virada para as fontes e a retangular para os detectores é dedução minha a partir das fotos. O manual não traz desenho cotado. A aparência externa e a posição da célula na parte traseira seguem as fotos.
- As formas das curvas na animação do modelo óptico. As faixas de tamanho (100 e 10 µm) são do manual; o formato da diferença é ilustrativo.

## Laboratório simulado (v0.3)

O simulador (`src/ls/simulador.js`) é fenomenológico: reproduz a direção dos efeitos, não faz a inversão óptica. Os testes em `test/ls-simulador.test.mjs` conferem a direção de cada parâmetro.

Vêm do manual: alvo de obscuração de 4 a 8% e média a ±2% do alvo; 5 a 30 cm³ de amostra; mínimo de 10 s de medição; faixa de 0,4 a 2000 µm em 92 canais; Fraunhofer quase igual a Mie acima de 100 µm, diferença pequena de 10 a 100 µm e Mie bem mais preciso com fração abaixo de 10 µm; background ruim exige correção; causas de vácuo alto e baixo; Mie supõe esferas homogêneas.

São escolhas do simulador, sem base no manual:
- a eficiência de dispersão de cada amostra no Tornado;
- o consumo de amostra (0,1 cm³/s a 5% de obscuração);
- que vácuo baixo deixa os grossos chegarem menos à célula e que vácuo alto reduz a obscuração;
- a forma e o tamanho de cada desvio na curva, e o valor do resíduo.

As condições de referência (alvo de 5%, 15 cm³, 60 s, Mie com o índice certo) seguem o manual e a ISO 13320, não um método validado.

**A confirmar no equipamento ou no software:**
- Se o "vácuo alvo" registrado em relatórios de corrida é um parâmetro do método ou só um registro.
- O que o campo *Obscuration* do relatório mostra (média, valor final ou pico).

## v0.10 — PIDS: como funciona

Novo passo na jornada do ULM, antes de "PIDS: quando incluir". Fonte: cap. 1 do manual (*Theory › PIDS* e *PIDS Sizing*, fig. 1.2): dipolo induzido, Iv − Ih como sinal PIDS, três comprimentos de onda (450, 600 e 900 nm), seis detectores perto de 90°, 36 leituras reduzidas a 18, sétimo detector para a obscuração PIDS, mesma matriz de deconvolução da difração.

**Cálculo:** o gráfico do passo novo e as barras do PIDS no passo seguinte usam a teoria de Mie (`scripts/pids_mie.py`, biblioteca miepython), com látex de poliestireno (n 1,59) em água (n 1,33), de 60 a 120°. A grandeza mostrada é (Iv − Ih)/(Iv + Ih). Antes, as barras eram uma curva inventada. As barras agora mostram quanto o padrão de cada cor já se afastou do padrão de partícula mínima (média do afastamento absoluto, escala do simulador).

**Escolhas minhas:** as posições angulares dos seis detectores (o manual só diz "centrados em cerca de 90°"); a amostra de látex; a vista de cima com o lóbulo de dipolo ideal no painel esquerdo.

**Incoerências do manual:** a teoria fala em limite "até 40 nm", a especificação em 0,017 µm; a descrição dos 36 → 18 fala em "cinco ângulos", mas 18 = 3 cores × 6 ângulos. O texto do Atlas cita os dois limites e usa seis ângulos.

**Vácuo do Tornado (v0.11):** métodos de uso definem o vácuo como condição, com valor alvo e limites inferior e superior em polegadas de água (exemplo usado no Atlas: alvo de 19", limites de 18 e 20"). O manual B05577AA só descreve os limites de erro (Control › Vacuum Settings, Administrator ou Supervisor), a regra do LED e a especificação da fonte (420 L/min a 5–10" abaixo da atmosfera); não mostra onde se define o alvo. A leitura de 19" acima da especificação da fonte é coerente: com o fluxo restrito pelo caminho do pó, o vácuo no módulo sobe.

No laboratório: vácuo alvo, limites e "caminho do pó" (livre, vazamento, entupido) substituem a antiga escolha do LED. Vêm do manual: limites, cores do LED, causas de vácuo baixo e alto, pó não aspirado com limites mal ajustados. São escolhas do simulador: a leitura igual ao alvo com o caminho livre; ±3,5" para vazamento e entupimento; a referência de 19" das amostras virtuais; o efeito do nível de vácuo na dispersão (aglomerados residuais proporcionais a (19/leitura)², limitados); o ruído mostrado quando a aspiração é bloqueada.

**v0.12:** faixa do vácuo alvo de 8 a 20" (limites de 6 a 22"), conforme o usuário lembra do software, sem documento; saiu a hipótese de quebra das agulhas por vácuo alto, que dependia de valores acima dessa faixa. No ULM, "Sonicar durante o carregamento" e "Sonicar antes da análise" passam a ser opções separadas, como nos métodos de uso; o tempo informado vale para a de antes da análise. O manual só descreve a sonicação antes da análise (tempo e potência). Os 30 s que a sonicação durante o carregamento soma são escolha do simulador. A potência não entrou no laboratório.

## v0.13 — Ajuda nos parâmetros do laboratório
- Cada campo do laboratório (ULM e Tornado) ganhou um "i" com um resumo de como o parâmetro afeta a curva.
- Os textos seguem as regras já documentadas acima: faixas de obscuração (difração 8–12%, PIDS 40–60%, Tornado 4–8%), duração mínima de 10 s e 90 s com PIDS, 5 a 30 cm³ no Tornado, LED de vácuo fora dos limites. Os pontos que são escolha do simulador estão marcados no texto: os 30 s de ultrassom durante o carregamento e o efeito do vácuo sobre os aglomerados (hipótese, sem fonte).
