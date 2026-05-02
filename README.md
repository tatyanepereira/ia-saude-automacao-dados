# 🩺 IA e Automação na Saúde: Suporte à Decisão com NotebookLM

<p align="center">
  <img src="https://img.shields.io/badge/Bootcamp-Afya%20|%20DIO-orange?style=for-the-badge" alt="Bootcamp Afya">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge" alt="Status Concluído">
  <img src="https://img.shields.io/badge/Tecnologia-NotebookLM-blue?style=for-the-badge" alt="NotebookLM">
</p>

---

## 📋 Contexto e Objetivos

Este projeto foi desenvolvido como parte do bootcamp **Afya - Automação de Dados com IA (DIO)**. O objetivo é utilizar o **NotebookLM** como uma ferramenta de "segundo cérebro" para organizar e extrair insights de grandes volumes de dados e documentos técnicos da área da saúde e educação médica.

> [!IMPORTANT]
> **Perfil da Autora:** Como profissional da área de **Tecnologia** e amante do universo da educação, utilizei este projeto para demonstrar como a curadoria pedagógica aliada à engenharia de dados pode acelerar a tomada de decisão em ambientes complexos.

---

## 📚 Curadoria de Fontes

Para alimentar a inteligência do meu caderno temático, selecionei várias fontes, listando abaixo as 5 principais para o contexto desta pesquisa:

### 🔗 Detalhamento das Fontes Selecionadas

1. **[IA e Automação na Transformação de Dados em Conhecimento Médico](https://www.lftechnology.com/blogs/how-ai-turns-healthcare-data-into-real-time-clinical-decision-support#content)**
   *   **Foco:** Fonte técnica central da pesquisa.
   *   **Pipelines de Dados:** Explica a construção de fluxos que capturam dados estruturados (FHIR/HL7) e não estruturados (PDFs, imagens).
   *   **Normalização Semântica:** Aborda o desafio crítico de alinhar terminologias divergentes (como ICD-10 e SNOMED-CT) para criar um "Registro de Ouro" do paciente.
   *   **Sistemas Multiagentes:** Mostra como IAs podem orquestrar fluxos operacionais com precisão superior à humana.

2. **[Real-World Evidence: contribuições metodológicas e estudos de caso](https://www.bdtd.uerj.br:8443/handle/1/25395)**
   *   **Foco:** Essencial para entender como extrair padrões de grandes volumes de informação técnica "do mundo real".
   *   **Processamento de Linguagem Natural (NLP):** Demonstra o uso de NLP para extrair dados valiosos (como valores laboratoriais) de exames não estruturados.
   *   **Real-World Data (RWD):** Fornece a base metodológica para utilizar dados assistenciais e administrativos em larga escala para prever recorrência de pacientes e analisar custos.

3. **[Suporte à Decisão baseado em Lean Healthcare e Análise de Dados](https://dspace.sti.ufcg.edu.br/handle/riufcg/43987)**
   *   **Foco:** Gestão hospitalar, unindo a engenharia de produção à ciência de dados.
   *   **Otimização de Processos:** Detalha como usar a análise de dados para aplicar a filosofia Lean (redução de desperdícios) em ambientes hospitalares.
   *   **Sistemas de Suporte à Decisão:** Fornece o arcabouço para criar ferramentas que auxiliem gestores na tomada de decisão operacional.

4. **[Transformação da educação médica: ABP e mudanças no ensino](https://www.scielo.br/j/rbem/a/vY3BY5VrN3KYxk5QmyPTWNg/?lang=pt)**
   *   **Foco:** Indispensável para o pilar de gestão de faculdades de medicina.
   *   **Aprendizagem Baseada em Problemas (ABP):** Explica o método que centra o aprendizado no aluno e como ele gera dados sobre o desenvolvimento de competências críticas e reflexivas.
   *   **Integração Ensino-Serviço:** Discute a articulação entre o currículo acadêmico e a prática real no sistema de saúde, ponto onde o assistente pode monitorar o desempenho discente.

5. **Hospital.IA: Inteligência Artificial nos Hospitais, e agora? (Arquivo PDF)**
   *   **Gestão de Recursos:** Aborda o uso da IA para prever demanda, otimizar a alocação de leitos e reduzir tempos de espera.
   *   **Educação e Simulação:** Menciona o uso de hospitais virtuais (como o "Agent Hospital" na China) e simuladores para formação médica.
   *   **Matriz de Riscos:** Lista desvantagens críticas como a falta de transparência ("caixas pretas"), infraestruturas inadequadas e vieses nos dados de treino.

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

O processo de refinamento foi fundamental para extrair respostas de alto nível técnico:

### 🔴 Prompt Inicial (Tentativa e Erro)
> *"Resuma o que os documentos dizem sobre tecnologia."*
> *   **Dificuldade encontrada:** A resposta foi muito genérica e não trouxe insights práticos para a área de dados.

### 🟢 Prompts Refinados (Sucesso)

> **Cenário A:** *"Aja como um Engenheiro de Dados: Identifique nas fontes quais são os 3 principais gargalos na automação de dados de saúde."*

> **Cenário B:** *"Aja como uma Engenheira de Dados sênior. Com base nas fontes fornecidas, estruture um plano de automação para a ingestão de dados clínicos que garanta a integridade e a conformidade com a LGPD."*

*   **Resultado:** A IA entregou uma estrutura de pipeline técnica, citando os pontos de segurança presentes nos documentos e garantindo maturidade no fluxo sugerido.

---

## 📖 Miniguia de Estudo: IA e Automação de Dados

### 1. Resumos Estruturados
*   **A Revolução dos Dados na Saúde:** A transição do registro manual para o digital permitiu a aplicação de modelos de IA para identificar padrões em larga escala, reduzindo erros de diagnóstico e otimizando a gestão hospitalar.
*   **Papel da IA Generativa:** Ferramentas como o NotebookLM não apenas resumem informações, mas atuam como motores de busca semântica, permitindo que profissionais técnicos encontrem respostas precisas dentro de fontes confiáveis (sem as famosas "alucinações").
*   **Segurança e Governança:** A automação de dados deve, obrigatoriamente, passar por camadas de anonimização e conformidade com a LGPD, garantindo que a inovação não comprometa a privacidade do paciente.

### 2. Glossário de Conceitos-Chave
Para facilitar futuras consultas, estruturei os termos técnicos essenciais em um documento complementar:
👉 **[Acessar Glossário.pdf](https://github.com/user-attachments/files/27307667/Glossario.pdf)**

### 3. Conjunto de Prompts Reutilizáveis

> [!TIP]
> **Para Análise Técnica:**
> ```markdown
> "Aja como uma Engenheira de Dados. Analise o documento [NOME DO ARQUIVO] e identifique os principais desafios de infraestrutura mencionados para a implementação de automação."
> ```

> [!TIP]
> **Para Resumo Executivo:**
> ```markdown
> "Sintetize em 5 tópicos os impactos financeiros da implementação de IA na gestão de dados de saúde, utilizando apenas as fontes fornecidas."
> ```


> [!TIP]
> **Para  verificação de Conformidade:**
> ```markdown
> "Com base nos arquivos de curadoria, quais são os 3 requisitos fundamentais de segurança que devem ser seguidos para tratar dados sensíveis conforme a LGPD?"
> ```
---

## 🛠️ Tecnologias Utilizadas
*   **NotebookLM** (Google)
*   **GitHub** (Versionamento e Portfólio)
*   **Markdown** (Documentação Profissional)

---

## ✍️ Autora
**Tatiane Pereira**
*Tecnologia | Educação | Dados*
[[LinkedIn](https://www.linkedin.com/in/pereira-tatiane/]
