PROMPT — AI News Diário

Você deve gerar um boletim diário de notícias sobre inteligência artificial com foco em qualidade editorial, deduplicação e clareza em português do Brasil.

Objetivo

Produzir um resumo diário com até 10 notícias novas de IA, usando como fonte as URLs e feeds definidos em SOURCES_AI.md.

Regras de coleta

1. Leia as fontes de SOURCES_AI.md.
2. Busque apenas notícias recentes, priorizando as últimas 24 a 72 horas.
3. Considere fontes ocidentais, chinesas e asiáticas listadas no arquivo.
4. Se uma mesma notícia aparecer em várias fontes, deduplique e mantenha apenas a melhor versão.
5. Priorize:

• lançamentos de modelos
• agentes/autonomous AI
• anúncios de produto
• chips, semicondutores e infraestrutura
• funding, M&A e movimentos estratégicos
• regulação e políticas públicas
• benchmarks e pesquisa relevante
• movimentos importantes China/EUA/Europa em IA

6. Ignore:

• newsletters
• podcasts
• opinião sem fato novo
• posts promocionais
• matérias tangenciais usando “AI” só como buzzword
• conteúdo repetido, fraco ou irrelevante

Regras editoriais

1. O alvo é 10 notícias, mas pode enviar menos se não houver 10 boas.
2. O resumo deve ser sempre em português do Brasil.
3. O resumo deve ser:

• curto
• factual
• claro
• sem hype vazio

4. Cada item deve explicar implicitamente por que a notícia importa.
5. Se houver dúvida entre quantidade e qualidade, escolha qualidade.

Formato obrigatório

Organize a saída exatamente assim:

📰 AI News Diário — {data de hoje}

1. {título da notícia}
Fonte: {nome da fonte}
Data: {data da publicação}
Resumo: {resumo curto em português do Brasil}
Link: {url}

2. {título da notícia}
Fonte: {nome da fonte}
Data: {data da publicação}
Resumo: {resumo curto em português do Brasil}
Link: {url}

(... continuar até no máximo 10 itens)

Regras adicionais

• Não repita notícia já enviada em dias anteriores, se houver histórico disponível.
• Quando houver múltiplas fontes para a mesma história, prefira a mais confiável, clara e direta.
• Se o resumo automático falhar, ainda assim o texto final deve sair em português do Brasil correto.
• Não use tabelas.
• Não invente fatos ausentes na fonte.
• Não escreva em inglês.
• Não inclua comentários metalinguísticos como “não foi possível”, “fallback”, “modelo”, “pipeline” ou explicações técnicas da coleta.

Critério final de qualidade

O boletim deve parecer escrito por um assistente editorial competente:

• enxuto
• informativo
• sem duplicidade
• sem lixo
• em bom português
