# Project Aegle

## Bracelete Vestível Avançado para Monitoramento Contínuo do Metabolismo e Sinais Vitais  
**Uma Investigação em Engenharia Biomédica e Instrumentação Bioelétrica Aplicada**

---

## Resumo

Este trabalho apresenta o desenvolvimento conceitual e a fundamentação técnica de um **bracelete vestível avançado**, projetado para o monitoramento contínuo do metabolismo humano e sinais vitais. O dispositivo utiliza **bioimpedância elétrica** como tecnologia central, complementada por sensores fisiológicos auxiliares, e adota um **mecanismo retrátil com carcaça cilíndrica fechada**, garantindo contato estável e repetível com o pulso humano. A abordagem combina modelagem científica do metabolismo, princípios de engenharia mecânica e ergonomia, resultando em uma **plataforma modular e robusta**, orientada à aplicação biomédica e industrial.

---

## 1. Introdução

O aumento do interesse por **dispositivos vestíveis de saúde** tem expandido o acesso a dados fisiológicos contínuos. Entretanto, a maioria dos wearables comerciais concentra-se na coleta de sinais vitais superficiais, como frequência cardíaca ou atividade física, fornecendo apenas estimativas indiretas do metabolismo humano. O metabolismo é um fenômeno sistêmico e multifatorial, cujo monitoramento exige tecnologias capazes de inferir propriedades internas do organismo de maneira confiável e repetível.

A **bioimpedância elétrica** surge como ferramenta promissora, permitindo estimativas não invasivas de composição corporal, hidratação e eficiência metabólica. Para que essas medições sejam precisas, o dispositivo deve assegurar **geometria constante de eletrodos, pressão controlada e isolamento de ruído mecânico**, aspectos intrinsecamente ligados à engenharia mecânica e ao design do bracelete. Este artigo apresenta o desenvolvimento conceitual de um bracelete vestível que integra **engenharia estrutural, biomecânica e instrumentação biomédica**, com foco no monitoramento metabólico contínuo.

---

## 2. Delimitação Conceitual: Metabolismo e Sinais Vitais

### 2.1 Metabolismo como núcleo do sistema

O metabolismo compreende processos bioquímicos responsáveis por **conversão de energia, manutenção estrutural e regulação funcional**. Variáveis metabólicas de interesse incluem:

- Estado de hidratação corporal  
- Massa magra e massa gorda (tendências)  
- Gasto energético estimado  
- Fadiga metabólica  
- Indicadores indiretos de inflamação sistêmica  
- Eficiência metabólica ao longo do dia  

Essas grandezas são **inferências indiretas** derivadas da bioimpedância elétrica, modelagem fisiológica e fusão de dados, não sendo sinais fisiológicos diretamente mensuráveis.

### 2.2 Sinais vitais como camada de suporte

Parâmetros fisiológicos diretamente mensuráveis, como:

- Frequência cardíaca e variabilidade (HRV)  
- Temperatura corporal  
- Saturação periférica de oxigênio (SpO₂)  
- Movimento e atividade física  

Atuam como **camada de contexto**, fornecendo validação, correção e interpretação para os modelos metabólicos. A distinção clara entre núcleo metabólico e suporte vital permite **modular o design e a engenharia do bracelete**, sem sobreposição funcional.

---

## 3. Bioimpedância Elétrica como Tecnologia Central

A bioimpedância elétrica aplica uma corrente alternada de baixa intensidade no corpo e mede a impedância resultante. Tecidos ricos em água oferecem baixa resistência, enquanto tecidos adiposos apresentam maior oposição.  

### 3.1 Relação com metabolismo

A impedância elétrica está relacionada a:

- Distribuição de fluidos intra e extracelulares  
- Massa magra e adiposa corporal  
- Nível de hidratação  

Essas variáveis permitem **inferir estado metabólico, eficiência energética e composição corporal ao longo do tempo**.

### 3.2 Medição multifrequência e topologia tetrapolar

A medição em múltiplas frequências diferencia compartimentos hídricos, e a topologia tetrapolar — com eletrodos separados para corrente e tensão — reduz interferências da impedância de contato da pele, aumentando precisão e repetibilidade.

### 3.3 Exigências ao dispositivo

A instrumentação impõe requisitos mecânicos e ergonômicos:

- Contato elétrico estável e uniforme  
- Pressão mecânica controlada e reprodutível  
- Geometria consistente do caminho elétrico  
- Isolamento contra ruído mecânico e elétrico  

Estes requisitos fundamentam **decisões de design do bracelete**.

---

## 4. Projeto Mecânico e Estrutural do Bracelete

### 4.1 Características físicas

- **Formato:** cilíndrico fechado, envolvendo todo o pulso  
- **Volume:** largura 6–8 cm, espessura 3–4 cm  
- **Materiais:** carcaça externa metálica (preto/grafite), reforços laterais em latão/dourado, revestimento interno macio/texturizado para conforto e isolamento  
- **Fixação:** travas mecânicas rígidas, estilo grampo industrial  
- **Detalhes funcionais:** iluminação discreta para feedback operacional  

### 4.2 Conceito funcional

- **Plataforma modular**, com carcaça como chassi estrutural  
- **Dispositivo homem–máquina**, capaz de estender capacidades sensoriais e computacionais  
- Orientado a **ambientes táticos ou industriais**, não casual  

### 4.3 Estrutura e integração

- Carcaça segmentada para **manutenção, dissipação térmica e absorção de impacto**  
- Reforços laterais para proteção de componentes sensíveis  
- Módulo central superior abrigando **processamento, energia e núcleo de sensores**  
- Interior acolchoado para **distribuição de pressão, isolamento de vibração e conforto prolongado**

---

## 5. Modos de Operação

O sistema opera em múltiplos estados funcionais:

- **Passivo:** monitoramento, coleta de dados, standby energético  
- **Ativo:** processamento em tempo real, resposta tátil/visual  
- **Bloqueio:** travas rígidas ativadas, proteção máxima  
- **Manutenção:** abertura parcial do chassi para acesso técnico  

A transição entre modos é automática, baseada em sensores de pressão, toque e movimento, configurando uma **máquina de estados fisiológicos e mecânicos**.

---

## 6. Integração de Camadas Funcionais

O bracelete é estruturado em camadas:

1. **Estrutura e mecanismo retrátil** – garante contato estável  
2. **Núcleo de bioimpedância** – coleta dados metabólicos  
3. **Sensores de sinais vitais** – contextualizam medições  
4. **Processamento embarcado** – modelagem e fusão de dados  
5. **Comunicação externa** – visualização e análise  

Cada camada tem funções claramente definidas, assegurando modularidade e possibilidade de evolução tecnológica.

---

## 7. Limitações e Considerações

- Depende de calibração individual e anatomia do usuário  
- Peso elevado (300–600 g) pode limitar algumas aplicações  
- Exposição a impactos extremos ou variação térmica intensa requer avaliação adicional  

Essas limitações são **aceitáveis dentro de aplicações biomédicas ou industriais especializadas**.

---

## 8. Conclusão
<p align="center">
  <img src=""/>
</p>
Este trabalho apresenta o **desenvolvimento conceitual de um bracelete vestível avançado**, integrando bioimpedância elétrica, engenharia mecânica e ergonomia. A estrutura cilíndrica fechada com mecanismo retrátil garante **contato estável e repetível**, essencial para monitoramento metabólico contínuo. O dispositivo se distingue de wearables convencionais por seu foco em **metabolismo como núcleo**, modularidade e robustez industrial, estabelecendo base sólida para futuras implementações, prototipagem e validação experimental em ambientes biomédicos ou técnicos.



## 9. Inspiração 

<p align="center">
  <img src=""/>
</p>

<p align="center">
  <img src=""/>
</p>

<p align="center">
  <img src=""/>
</p>

<p align="center">
  <img src=""/>
</p>

---

## Referências

[1] *Real-world assessment of Multi-Frequency Bioelectrical Impedance Analysis (MFBIA) for measuring body composition in healthy physically active populations.*  
European Journal of Clinical Nutrition, 2025;79:1235–1244.  
doi:10.1038/s41430-025-01664-4.  
Este estudo recente valida o uso de BIA multifrequência em populações ativas e reforça a aplicabilidade da bioimpedância em monitoramento corporal contínuo. :contentReference[oaicite:1]{index=1}

[2] *Smartwatch-based bioimpedance analysis for body composition estimation: precision and agreement with a 4-compartment model.*  
PubMed (2024).  
Avalia a precisão de dispositivos com BIA integrados em smartwatches comparados a modelos de referência, demonstrando potencial e limitações para estimativa de composição corporal. :contentReference[oaicite:2]{index=2}

[3] Branco, M. G. et al. *Bioelectrical Impedance Analysis (BIA) for the Assessment of Body Composition in Oncology: A Scoping Review.*  
Nutrients, 2023;15(22):4792.  
Impacto da bioimpedância na avaliação de composição corporal em contextos clínicos, com análise de múltiplos estudos. :contentReference[oaicite:3]{index=3}

[4] Groenendaal, W., Lee, S., & van Hoof, C. *Wearable Bioimpedance Monitoring: Viewpoint for Application in Chronic Conditions.*  
JMIR Biomedical Engineering, 2021;6(2):e22911.  
Discussão teórica sobre a aplicação da bioimpedância em dispositivos vestíveis para monitoramento de saúde em condições crônicas. :contentReference[oaicite:4]{index=4}

[5] *A review of bio-impedance devices.*  
(2023). International Federation for Medical and Biological Engineering.  
Revisão concisa sobre fundamentos de bioimpedância e técnicas de medição em dispositivos portáteis, com foco em instrumentação e calibração. :contentReference[oaicite:5]{index=5}

[6] Alemu, T., et al. *Multi-sensor Data Fusion for Wearable Health Monitoring (Revisão).*  
ArXiv (2024).  
Revisão recente de métodos de fusão de dados multisensor em monitoramento de saúde vestível, incluindo técnicas de combinação de bioimpedância e sinais vitais. :contentReference[oaicite:6]{index=6}

