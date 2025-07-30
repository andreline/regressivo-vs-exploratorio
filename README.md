📘 Testes Regressivos x Exploratórios: Guia Estratégico para QA

Este repositório é um compilado prático e estratégico sobre dois pilares essenciais da qualidade de software: **Testes Regressivos** e **Testes Exploratórios**. Aqui você vai entender a diferença entre eles, quando aplicar cada tipo e como estruturar esses testes de forma eficiente no seu time.

---

🧠 O que são Testes Regressivos?

Testes regressivos têm o objetivo de garantir que funcionalidades já existentes continuam funcionando após alterações no sistema, como novas features, correções de bugs ou atualizações técnicas.

Com testes regressivos bem aplicados, você:

✅ Garante que funcionalidades antigas não quebraram após mudanças  
✅ Aumenta a confiança em releases e hotfixes  
✅ Evita que bugs antigos retornem ao sistema  
✅ Ganha previsibilidade e estabilidade nas entregas  

💡 É ideal para manter a **confiabilidade do sistema ao longo do tempo**.

---

🧠 O que são Testes Exploratórios?

Testes exploratórios são testes **não roteirizados**, guiados pela experiência, intuição e curiosidade da pessoa testadora. Eles são ideais para descobrir falhas inesperadas e validar comportamentos sob diferentes contextos de uso.

Com testes exploratórios bem executados, você:

🔍 Encontra cenários que não foram previstos nos roteiros tradicionais  
🔍 Gera insights valiosos para melhoria do produto  
🔍 Valida a experiência real do usuário final  
🔍 Testa fluxos novos, edge cases e combinações fora do padrão  

💡 É ideal para **levantar hipóteses de erro, testar comportamentos e prevenir falhas antes mesmo que elas virem bugs**.

---

✍️ Comparativo Estratégico

| Característica               | Teste Regressivo                  | Teste Exploratórios                      |
|-----------------------------|-----------------------------------|------------------------------------------|
| Objetivo principal          | Garantir que o que já funcionava, continua funcionando | Explorar comportamentos e identificar falhas ocultas |
| Roteirização                | Baseado em cenários definidos     | Sem roteiro fixo, com base em intuição   |
| Ferramentas comuns          | XRay, TestRail, Zephyr, Jenkins   | OBS, Notion, Test Charters               |
| Quando usar                 | Pós-deploy, pré-release, hotfix   | Funcionalidade nova ou complexa          |
| Quem executa                | QA, Dev, times cross              | QA com conhecimento funcional e técnico  |
| Ideal para                  | Automação, rastreabilidade        | Descoberta, usabilidade, edge cases      |

---

🧪 Como aplicar Testes Regressivos na prática

- Documente os fluxos mais críticos do sistema
- Agrupe os testes por app, sprint, versão ou release
- Automatize o que for repetitivo e de alta cobertura
- Execute os testes sempre que houver alteração relevante no sistema
- Utilize ferramentas como: **XRay, Jenkins, Cypress, Puppeteer, SQL**

---

🧭 Como aplicar Testes Exploratórios no dia a dia

- Defina um objetivo exploratório (ex: “tentar quebrar o formulário com dados inválidos”)
- Crie um “charter” leve com foco do teste e tempo estimado
- Use gravação de tela, logs e anotações para documentar
- Analise comportamento, mensagens, bordas, atalhos, responsividade e integrações
- Integre as descobertas em reuniões de Bug Review ou SACARs
- Utilize ferramentas como: **Notion, Instana, Datadog, OBS, Kibana**

---

🚦 Quando usar cada um?

Use os dois em conjunto! Enquanto o **teste regressivo** garante estabilidade, o **exploratório** amplia a visão e previne problemas ainda não mapeados.

📌 Estratégia recomendada:
- Planeje regressivos a cada sprint ou release
- Realize exploratórios em funcionalidades novas, críticas ou pouco testadas
- Documente ambos para aprendizado e rastreabilidade

---

💡 Dicas Estratégicas

- Registre descobertas dos testes exploratórios em reuniões de Bug Review
- Use evidências sempre: prints, GIFs, vídeos e logs
- Automatize os regressivos mais críticos e que consomem tempo
- Revise os testes regressivos periodicamente: sistema muda, os testes também devem evoluir
- Teste com contexto: pense como o usuário final e também como o sistema

---

🌍 Artigos complementares

🔗 [Guia Prático de X-Ray para QA](https://github.com/andreline/xray-qualidade/tree/main)  
Como uso o X-Ray no dia a dia para organizar regressivos, bugbashs e documentar casos de teste.

🔗 [Bug Review: como estruturar uma cultura de observabilidade no time](https://github.com/andreline/bug-review/tree/main)  
Artigo sobre reuniões semanais de análise de bugs, logs, métricas e insights técnicos.

🔗 [BugBash Guide: testes colaborativos com o time todo](https://github.com/andreline/bugbash-guide/tree/main)  
Tudo que você precisa saber para organizar um BugBash com o time e melhorar a entrega da sua feature.

🔗 [Estratégia de Testes: entendendo e aplicando a Pirâmide de Testes](https://github.com/andreline/estrategia-teste/tree/main)  
Artigo explicando como estruturar sua estratégia de testes baseada em pirâmide e aplicar isso com o time.

---

🧑‍💻 Sobre a autora

Me chamo **Andreline Lira**, sou QA com foco em qualidade de ponta a ponta: estratégia, processos, prevenção e melhoria contínua.  
Faço testes com propósito, crio cultura de qualidade e não descanso enquanto tiver bug no caminho.  

📍 Recife – Brasil  
🔗 [LinkedIn](https://www.linkedin.com/in/andrelinelira/)  
