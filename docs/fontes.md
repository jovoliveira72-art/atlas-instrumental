# De onde veio cada informação (v0.14)

Use esta lista para revisar. Os manuais citados estão em `materiais/`.

| Tema | Fonte |
|---|---|
| Fontes de luz: He-Ne 632,8 nm (máx. 4 mW) e LED 470 nm (máx. 10 mW); óptica de Fourier reverso; faixa de 0,01 a 3500 µm; sistemas de detecção | Guia básico PT-BR (MAN0475), Apêndice de especificações |
| Luz azul melhora a resolução abaixo de 1 µm | MAN0474, Optical unit |
| Hydro MV: tanque de 120 mL, bomba na base com agitador central, transdutor sob o tanque, tampa do tanque, entradas de dispersante (inferior aquosa com regulador; superior não aquosa, bomba externa), dreno com triângulo de aviso, indicador de status, chicanas, luz de nível, ladrão, linhas amarela e azul, ultrassom desliga após 20 min | MAN0479, §2.2–2.3 |
| Hydro SV: 7 mL (mín. 6 mL de dispersante + até 1 mL de amostra), cubeta com tampa e travas, visor e botão de agitação sincronizados, entrada da pipeta com guia curva, cabo CAN, menor que 200 µm, barra magnética de 500 a 1800 rpm, amostras não magnéticas e não abrasivas | MAN0479, §2.8–2.9 |
| Bolhas: tensoativo ou dispersante viscoso com rotação alta, vazamentos; pico secundário perto de 100 µm; degaseificar | MAN0479 §4.3; MAN0675 tab. 4.4 e §4.4.5 |
| Modos de ultrassom (Nenhum, Pré-medição, Contínuo) | MAN0675, §10.4.1.1 |
| Menor velocidade de agitação e de ultrassom que dispersa | MAN0675, §10.4.1.1 e §9.5 |
| Obscuração: úmido ideal 10–20% (5–10% utilizável); seco 0,1–10% | MAN0675, §9.4.1 |
| Sintomas: obscuração cai (dissolução, sedimentação, aglomeração) ou sobe (aderência à janela, condensação) | MAN0675, §4.4.5.4 e tab. 4.4 |
| Resíduo: alerta acima de 3% quando Dv50 > 100 nm | MAN0675, verificações de qualidade de dados |
| Fraunhofer impreciso abaixo de 50 µm ou para partículas transparentes | MAN0675, tab. 10.1 |
| Modo pó fino: limite de 600 µm; recomendado na via seca quando Dv90 < 10 µm | MAN0675, §9.10.3 |
| Aero S: funil com gap, cesto de malha com esfera, bandejas padrão, micro e macro, venturi padrão e de alta energia, inox e cerâmica, extração a vácuo | MAN0481, §2.3 |
| Pressão de 0 a 4 bar em passos de 0,1; taxa de alimentação; configuração do venturi e da bandeja | MAN0675, §10.4.1.3 |

| Tipos de partícula (não esférica, esférica, opaca/Fraunhofer), premissas de Mie e de Fraunhofer, critério de 40× λ (cerca de 25 µm) e erros perto de 30% | MAN0675, §9.2 e tab. 10.1 |
| Referências de absorção (0 / 0,001 / 0,01 / 0,1 / 1) e IR na luz azul | MAN0675, §9.3 |
| Modelos de análise (General Purpose, Narrow Purpose, Verification Latex), uma única moda, desconsiderar detectores, sensibilidade | MAN0675, §10.5.1 |
| Optical property optimizer e reanálise de registros (edit result) | MAN0675, §6.11 e §10.5.1 |
| Limites de obscuração do software (<0,2% e >35%; <13% para Dv50 de 1–10 µm; <8% abaixo de 1 µm), alerta de amostragem, alimentação seca, background (det. 1 < 200, det. 20 < 20), dados negativos | MAN0675, tab. 11.1 |
| Data Quality Guidance em tempo real é um recurso do 3000+ | MAN0675, §11.1 |
| Parâmetros de resultado (D[4,3], D[3,2], span, uniformidade, SSA, concentração) | MAN0675, §6.12 |
| Sequência de medição e limpeza (1/3/5 ciclos no Hydro; 5/10/15 s no Aero) | MAN0675, §5.2 e §5.3 |
| ISO Check (mínimo de 5 medições) e USP Check (mínimo de 6) | MAN0675, §2.3.2 |

| Célula seca: alça e botão de destravar, cobertura, obturador mecânico, entrada de amostra, entrada de ar e filtro, porta de vácuo, janelas e vedações | MAN0481, §2.4 e fig. 2.9 |
| Retirada, inspeção, limpeza e remontagem das janelas da célula seca; alinhamento após remontar | MAN0481, §4.4 e §4.5 (fig. 4.2 a 4.7) |
| Cronograma de manutenção do Aero e critérios de background ruim (detectores iniciais > 100; detector após o 20 > 20) | MAN0481, §4.2 e §4.3 |

| Célula úmida: alça e botão de destravar, cobertura com etiqueta azul (FKM) ou vermelha "R" (FFKM), braço do obturador, conexões amarela (para a célula, embaixo) e azul (da célula, em cima), camisa d'água (máx. 0,5 bar), bandeja de gotas | MAN0479, §2.2, §2.10 e figs. 2.2, 2.23 e 2.24 |
| Retirada da placa de cobertura, vedação central e janelas; inspeção, limpeza, lubrificação das vedações, ferramenta de aplicação, alinhamento após remontar | MAN0479, §4.4 a §4.6 e figs. 4.3 a 4.7 |
| Cronograma de manutenção do Hydro MV, deixar a célula cheia de dispersante por até 24 h | MAN0479, §4.1 a §4.3 |
| Torre do Aero S (a tampa da área da amostra e a mangueira de ar saíram do 3D na v0.7): indicador de status (azul contínuo/pulsando), conexões traseiras (ar de 5,5 a 8 bar, nominal 6; CAN; auxiliar; aterramento), trava da bandeja, funil com controle de fluxo, posição da unidade conforme o venturi, retirada do venturi (1/6 de volta) | MAN0481, §2.2, §2.3 e figs. 2.2 a 2.8 |
| Troca do filtro de ar da tampa, limpeza do cesto, da bandeja e das tampas | MAN0481, §4.6 |

| Vistas "Por dentro" e "Desmontar" (v0.14): textos do caminho da luz e da amostra reaproveitam as fichas das peças e as fontes acima (MAN0474 unidade óptica; MAN0479 §2.2–2.3 e §2.8–2.9; MAN0481 §2.3). "Partículas grandes espalham em ângulos pequenos" é o princípio da difração laser (MAN0675, §9.2) | ver linhas acima |

| Luz vermelha e azul: na via úmida, background e amostra medidos primeiro com a vermelha e depois com a azul; na via seca, só a vermelha | MAN0675, §5 (sequência de medição) |
| Duração da luz azul é ajuste exclusivo das unidades úmidas; azul mais significativa abaixo de 1 µm, com peso decrescente acima; pigmentos vermelhos e amarelos absorvem a azul; "Don't perform blue light measurement" | MAN0675, §10.3.2.1 e §10.3.2.2 |
| "Remove Blue Light from Analysis" | MAN0675, §10.5 (Red-Light Only) |
| Absorção por cor (pigmento vermelho absorve a azul), IR azul igual ao vermelho quando não informado, "Different Blue-light optical properties" | MAN0675, §9.3 e §6.11 |
| A luz azul melhora a resolução abaixo de 1 µm; LED de 470 nm, 10 mW | MAN0474, visão geral da unidade óptica; MAN0475, especificação da luz azul |
| A obscuração vem do detector central (Ob = 1 − Ls/Lb) | MAN0474, cap. 5 |

| Venturi padrão (ligação reta, boa dispersão para ampla variedade, inclusive frágeis, unidade paralela ao banco) e de alta energia (ângulo reto, partículas robustas e fortemente aglomeradas, unidade de costas para o banco); inox e cerâmica com anéis para abrasivos | MAN0481, §2.1.1 e §2.3.2.5 |
| Troca dos tubos do venturi pelo menos a cada três meses; acúmulo no cone, no bocal e no tubo; esferas de vidro grossas ou escova; limpeza avançada | MAN0481, §4 (cronograma) e §4.6.4 |
| Pressões baixas para finos ou frágeis, altas para aglomerados ou metálicos | MAN0675, §5.3.3.3 |
| Software registra o "disperser type"; venturi e bandeja escolhidos nos menus da unidade seca | MAN0481, §2.3.2.5; MAN0675, §10.4 |
| Três mecanismos de dispersão (cisalhamento, choque partícula-parede, choque partícula-partícula); venturi padrão sem impacto direto contra a parede e de alta energia com superfície de impacto | Material enviado pelo setor: figura de mecanismos de dispersão e apresentação da ATA Scientific (distribuidor Malvern), slide "Aero S: modular venturi for flexibility". Não é manual; as imagens não foram reproduzidas, a animação é desenho próprio |

**Interpretação minha, não está no manual:** no laboratório, a amostra fictícia E (aglomerada e robusta) e os limiares em que o venturi padrão deixa aglomerados e o de alta energia quebra partículas são escolhas do simulador; que, com o venturi de alta energia, a mesma pressão entrega mais energia ao pó (consequência da superfície de impacto) e que a titulação deve ser refeita ao trocar de venturi; a animação "Luz vermelha e luz azul" usa a aproximação de Rayleigh-Gans (o software usa Mie completo); os rótulos "diferencia bem/pouco" vêm de um critério ilustrativo meu (diferença média entre as duas curvas). A atribuição de detectores específicos à luz azul foi retirada por não estar nos manuais da pasta. no simulador, o modo esférico aplicado a partículas irregulares gera ondulações e resíduo maior, e o modo não esférico alarga um pouco a distribuição de esferas perfeitas. As tendências são plausíveis, mas a forma exata do efeito é ilustrativa.

**Ainda NÃO verificado nos manuais:** a geometria interna exata (o 3D é esquemático; as direções de separação na vista Desmontar são didáticas, não a ordem de desmontagem do manual, que está só nos procedimentos guiados) e as demais diferenças do 3000+ além da Data Quality Guidance.
