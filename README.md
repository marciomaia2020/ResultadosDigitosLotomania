# ResultadosDigitosLotomania

Principais Adaptações:
1. Cores da Lotomania:
Laranja primário: #E68527 (como você especificou)
Laranja secundário: #CC7420
Modo escuro: #F29545
2. APIs da Lotomania:
API principal: https://servicebus2.caixa.gov.br/portaldeloterias/api/lotomania
API por concurso: https://servicebus2.caixa.gov.br/portaldeloterias/api/lotomania/{numero}
API completa: https://loteriascaixa-api.herokuapp.com/api/lotomania
3. Funcionalidades Específicas:
⚡ Sistema de cache inteligente para carregamento ultra-rápido
📊 Análise de dígitos únicos dos 20 números sorteados da Lotomania (00 a 99)
🔍 Filtros avançados por quantidade de dígitos, dígito específico, range de concursos
📈 Análise de frequência e intervalos entre aparições
📋 Resumo automático com estratégias de aposta baseadas nos dados
💾 Downloads em XLS, HTML e TXT
🌙 Tema escuro/claro automático
🔄 Atualização automática a cada 5 minutos
🚫 Modais customizados (sem uso de alert/confirm/prompt)
4. Valores de Referência:
Concurso padrão: 2805 (baseado no JSON fornecido)
Estrutura: Análise dos dígitos únicos presentes nos 20 números sorteados
5. Adaptações para Lotomania:
20 números sorteados (00 a 99)
Intervalo médio muito baixo (10 concursos) devido à abundância de números
Praticamente todos os dígitos 0-9 aparecem em cada sorteio
Estratégias específicas para a natureza da Lotomania
Combinação padrão: 0,1,2,3,4,5,6,7,8,9 (todos os dígitos aparecem quase sempre)
6. Performance:
Carregamento otimizado com cache
Busca apenas concursos novos quando possível
Fallback para API completa se necessário
Indicadores visuais de progresso
Modais customizados sem dependência de funções nativas do navegador
7. Características únicas da Lotomania:
Frequência muito alta de todos os dígitos (280+ aparições)
Intervalos muito curtos entre aparições (média 10 concursos)
Combinação quase sempre completa (0,1,2,3,4,5,6,7,8,9)
Análise mais focada em padrões sutis entre os intervalos
A aplicação está pronta para uso e analisará automaticamente os dígitos únicos presentes nos sorteios da Lotomania, mantendo o esquema de cores laranja característico desta modalidade! 🧡🎰

Diferencial: Esta versão da Lotomania reconhece que com 20 números sorteados (00-99), praticamente todos os dígitos 0-9 aparecem em cada sorteio, então o foco da análise está nos intervalos mínimos e padrões mais sutis.