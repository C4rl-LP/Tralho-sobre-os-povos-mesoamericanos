# Revisão acadêmica e pendências de rastreabilidade

Esta nota registra problemas detectados durante a interconexão do cofre. Não altera nem corrige o texto original `Ensaio/maias.tex`.

## Citação sem entrada na bibliografia

- **Monteferrante (2012)** é citada no trecho sobre ponto, barra, concha-zero e o ajuste calendárico do *tun* em [[Ensaio/maias#Códice de Dresden: cálculo, imagem e transmissão|maias.tex / versão Markdown]], mas não aparece na lista final de referências do ensaio.
- A identificação existente em [[Ensaio/07_Referencias_e_Auditoria#Referências bibliográficas utilizadas|auditoria]] e [[Referências/Monteferrante (2012)|nota da obra]] fornece título, periódico/série, DOI e URL, mas requer conferência dos metadados antes de completar a lista ABNT.
- A versão `maias.md` preserva a lista bibliográfica que está no original e marca a pendência, sem acrescentar silenciosamente uma referência que falta no `.tex`.

## Questões de paginação a conferir no PDF

- A citação “inert or passive” aparece no PDF de Houston e Taube na página impressa 263 (PDF, página 4), mas o ensaio a atribui à p. 265. A referência de página no original precisa ser corrigida em revisão futura; não alterei o `.tex` por instrução. A nota conceitual e a nota de contribuição também devem manter a paginação impressa, não a posição da página no arquivo.
- Nas notas de Aveni, algumas citações usam a página impressa do periódico e outras seleções apontam a contagem do PDF. A [[Ensaio/07_Referencias_e_Auditoria#Auditoria de rastreabilidade|auditoria]] afirma que o ensaio segue a paginação impressa; manter essa distinção ao citar.

## Alinhamento entre plano e ensaio

- A proposta pede explicitar a cronologia dos três casos: Chichén Itzá no Clássico Terminal/Pós-Clássico Inicial, Dresden pós-clássico e Bonampak no Clássico Tardio. O ensaio explicita o período de Chichén Itzá, mas não situa com a mesma clareza Dresden e Bonampak na introdução/corpo. O leitor pode perder a assimetria cronológica.
- O critério metodológico de separar observação material, interpretação e hipótese é explicitado na introdução e aplicado ao Castillo e a Bonampak. A natureza da comparação entre os três casos poderia ser nomeada diretamente como método de síntese histórico-crítica, como recomenda [[Ensaio/05_Plano_Argumentativo#Introdução|o plano]].
- A interpretação de Milbrath sobre alinhamentos e iconografia é apresentada como hipótese, em diálogo com a reavaliação de Šprajc e Sánchez Nava. Não tratar como consenso.

## Limites documentais que devem permanecer visíveis

- Não há estudo especializado local dedicado exclusivamente ao Códice de Dresden, à epigrafia de Bonampak ou às técnicas materiais dos murais; ver [[Ensaio/03_Mapa_Bibliografico#Lacunas documentais|lacunas do mapa bibliográfico]].
- Houston e Taube oferecem uma lente comparativa pan-mesoamericana para percepção e escrita, não evidência de astronomia no Dresden. A nota crítica assinala viés de fontes de elite e irrecuperabilidade das experiências individuais: [[houston2000/4_Análise_crítica|análise crítica]].
- A hipótese Vênus–guerra/Bonampak vem mediada pela discussão de Milbrath; a própria seção do ensaio a qualifica e recusa tratá-la como prova de calendário mural.
- A descrição do fenômeno equinocial e sua intenção devem seguir o grau de confiança estabelecido pela matriz; ver [[Ensaio/04_Matriz_de_Evidencias|matriz]].

## Nota de conversão

`Ensaio/maias.md` foi gerado a partir do conteúdo completo de `Ensaio/maias.tex`, preservando texto, seções, citações, equação e referências; apenas comandos estruturais LaTeX foram convertidos e links internos foram adicionados. A referência incompleta é marcada no próprio Markdown. A checagem de parágrafos e compilação consta no relatório de execução do agente.
