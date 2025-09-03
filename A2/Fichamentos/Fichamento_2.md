# Can ChatGPT Repair Non-Order-Dependent Tests?  

Zhang, J., et al. *“Can ChatGPT Repair Non-Order-Dependent Tests?,”* in **Proceedings of the 46th International Conference on Software Engineering (ICSE ’24) – Companion Proceedings**, ACM, 2024. doi: [10.1145/3643656.3643900](https://dl.acm.org/doi/pdf/10.1145/3643656.3643900)  

## 1. Fichamento de Conteúdo  

O artigo investiga se o ChatGPT, como modelo de linguagem de grande escala, é capaz de reparar testes de software que falham devido a problemas não relacionados à ordem de execução (*non-order-dependent tests*). O contexto do estudo está inserido no crescente interesse em aplicar IA generativa para apoiar o processo de garantia de qualidade de software. O problema central analisado é a dificuldade em manter testes confiáveis, já que falhas recorrentes podem comprometer a evolução do código. A metodologia empregada envolve a seleção de um conjunto de testes problemáticos em sistemas reais, a formulação de *prompts* para o ChatGPT sugerir reparos e a avaliação dos resultados em termos de correção e viabilidade de integração. Os autores mostram que, embora o ChatGPT consiga propor reparos funcionais em parte dos casos, existem limitações ligadas à precisão semântica e à falta de contexto sobre o sistema em questão. Os resultados apontam que a ferramenta pode ser útil como apoio inicial no processo de depuração de testes, mas requer supervisão e ajustes humanos para alcançar soluções robustas.  

## 2. Fichamento Bibliográfico  

- Testes não dependentes de ordem (*non-order-dependent tests*) são aqueles que falham independentemente da sequência de execução, dificultando o diagnóstico (p. 2).  
- O ChatGPT foi usado como gerador de reparos, recebendo como entrada os códigos de teste e as mensagens de falha (p. 3).  
- A avaliação foi feita em sistemas reais, comparando sugestões da IA com reparos manuais realizados por desenvolvedores (p. 4).  
- Resultados mostraram que o modelo acerta reparos parciais em uma fração significativa, mas falha em casos que exigem raciocínio contextual mais profundo (p. 5).  
- Conclui-se que a IA pode acelerar a correção de testes, mas não elimina a necessidade de revisão crítica (p. 6).  

## 3. Fichamento de Citações  

- *“Non-order-dependent test failures remain a persistent challenge in maintaining reliable test suites.”* (p. 1)  
- *“We explore whether ChatGPT, as a large language model, can generate effective repairs for such failures.”* (p. 2)  
- *“Our study shows that ChatGPT can repair some test failures, but its success is limited by the lack of contextual understanding of the target system.”* (p. 5)  
- *“Developers must carefully validate and refine AI-generated repairs before adoption.”* (p. 6)  
- *“Generative AI has the potential to support, but not fully automate, the maintenance of software test suites.”* (p. 6)  
