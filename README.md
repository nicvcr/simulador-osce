# 🩺 Simulador de Avaliação OSCE — 2º Período de Fisioterapia

Simulador interativo desenvolvido para treino e preparação de estudantes do 2º período de Fisioterapia para avaliações no formato **OSCE** (*Objective Structured Clinical Examination*), sob metodologias ativas (PBL/TBL).

---

## 🏛️ Estrutura das Estações (Salas) & Guias Teóricos

O projeto é organizado em duas frentes complementares: **Guias Teóricos de Alto Rendimento** (para consolidação dos conteúdos antes da prova) e **Simuladores Cronometrados** (5 minutos cada com gongo sonoro):

### 📚 Guias Teóricos Aprofundados (Estudo Prévio):
1. 📖 **[Guia Teórico Sala 1: Locomotor, Bioquímica & Histologia](resumo_sala1_locomotor_bioquimica_histologia.html):** Anatomia detalhada de Membros Inferiores (quadril, coxa e perna/pé), bioquímica de aminoácidos, proteínas e turnover, ciclo excitação-contração com Ca²⁺ e ATP, necrose muscular, rabdomiólise e CK, inflamação e estresse oxidativo (ERO/ERN vs antioxidantes), histologia sarcomérica e regeneração por células satélite. Inclui **5 Flashcards de Respostas Orais** e um **Simulado Interativo com 10 Questões de Prova** com gabarito comentado e pontuação em tempo real.
2. 📖 **[Guia Teórico Sala 2: Microbiologia & Imunologia](resumo_sala2_imunologia_microbiologia.html):** Propriedades biológicas e estrutura viral, ação físico-química do álcool 70%, principais viroses (Chikungunya, Hepatite B e C, HIV, Raiva), Complexo MHC/HLA no cromossomo 6, Linfócitos T CD4/CD8 e B, classes de anticorpos (IgM, IgG, IgA, IgE) e quadro comparativo definitivo de Vacinas vs Soros. Inclui **5 Flashcards de Respostas Orais** e um **Simulado Interativo com 10 Questões de Prova** com gabarito comentado e pontuação em tempo real.

---

### 📍 [Sala 1: Aparelho Locomotor, Bioquímica e Histologia (Simulador)](sala1_locomotor_bioquimica_histologia.html)
Integração pura das ciências biológicas básicas do 2º período, sem prescrição de condutas clínicas:
1. **Biossegurança e Acolhimento (1.0 pt):** Apresentação profissional e higienização alcoólica das mãos a 70%.
2. **Anatomia de Membro Inferior (3.0 pts):** Identificação de grupos musculares, origens ósseas, inserções, ações articulares e inervação motora correspondente.
3. **Bioquímica da Contração e do Dano Celular (3.0 pts):** Fisiologia do acoplamento excitação-contração (íons cálcio, troponina C, tropomiosina, actina/miosina e ATP) vs. mecanismo molecular da ruptura do sarcolema, influxo patológico de íons cálcio, ativação de calpaínas, estresse oxidativo por radicais livres e extravasamento sérico de **Creatina Quinase (CK)** e Mioglobina.
4. **Histologia: Envoltórios e Sarcômero (1.5 pts):** Tecidos conjuntivos organizadores (**Epimísio**, **Perimísio** e **Endomísio**) e ultraestrutura sarcomérica (linhas Z, bandas A e I).
5. **Histologia: Regeneração Tecidual e Células Satélite (1.5 pts):** Fagocitose por macrófagos, ativação das células satélite na lâmina basal, diferenciação em mioblastos, fusão em miotubos e prevenção biológica da fibrose cicatricial por excesso de colágeno secretado por fibroblastos.

#### 🎯 Cenários de Treino da Sala 1:
- **Cenário 1:** Estiramento de Isquiotibiais (Face Posterior da Coxa em frenagem excêntrica).
- **Cenário 2:** Síndrome da "Pedrada" no Tríceps Sural (Gastrocnêmios e Sóleo na transição miotendínea).
- **Cenário 3:** Estiramento do Reto Femoral / Quadríceps (Chute em falso na face anterior da coxa).
- **Cenário 4:** Sobrecarga Muscular Severa pós-Agachamentos com Urina Escura (Rabdomiólise e Mioglobinúria).

---

### 📍 [Sala 2: Microbiologia e Imunologia](sala2_imunologia_microbiologia.html)
Enfoque rigoroso em biossegurança, virologia, resposta imune celular/humoral e imunobiológicos:
1. **Biossegurança e Proteção Pessoal (1.0 pt):** Higienização alcoólica e paramentação de EPIs.
2. **Microbiologia Geral (3.0 pts):** Estrutura dos vírus (capsídeo, genoma DNA/RNA e envelope lipoproteico), vias de transmissão e desinfecção química (álcool 70%).
3. **Imunologia Inata e Adaptativa (3.0 pts):** Linfócitos B (plasmócitos e anticorpos IgM/IgG), Linfócitos T auxiliares (CD4) e citotóxicos (CD8), cascatas de citocinas inflamatórias e memória imunológica.
4. **Imunobiológicos e Prevenção em Saúde Pública (3.0 pts):** Diferença biológica entre imunização ativa (vacinas/toxoides) e imunização passiva (soros e imunoglobulinas), interpretação sorológica e controle vetorial do *Aedes aegypti*.

#### 🎯 Cenários de Treino da Sala 2:
- **Cenário 1:** Infecção Respiratória Viral e Biossegurança em Ambulatório.
- **Cenário 2:** Acidente Perfurocortante com Agulha Contaminada e Hepatite B (HBsAg vs. Anti-HBs).
- **Cenário 3:** Artralgia Crônica pós-Chikungunya e Persistência de Antígenos Virais Sinoviais.
- **Cenário 4:** Ferimento Contaminado com Risco de Tétano (Soro Antitetânico vs. Vacina dT).

---

## 🚀 Como Executar

O projeto é 100% estático (HTML5, CSS3 e JavaScript Vanilla moderno), não dependendo de servidores externos, bancos de dados ou instalações complexas.

Para abrir no navegador:
```bash
# Clone ou baixe o repositório e abra no seu navegador
open index.html
```
Ou dê dois cliques no arquivo `index.html`.

---

## 🛠️ Tecnologias Utilizadas
- **HTML5 Semântico**
- **CSS3 Moderno:** Variáveis CSS, Glassmorphism, Design Responsivo e Dark Theme nativo.
- **JavaScript Vanilla:** Motor de contagem regressiva, cálculo em tempo real de notas da prova, síntese de frequências acústicas (Web Audio API) e alternância dinâmica de cenários clínicos.
- **Tipografia:** Google Fonts (*Outfit*, *Plus Jakarta Sans*, *JetBrains Mono*).

---

Feito com dedicação para a formação de excelência em Fisioterapia! 🩺✨
