 Calculadora de Produtividade Logística

Este projeto é uma ferramenta web simples, criada em um único arquivo HTML, que simula o impacto de penalidades de processo (como "Escada" e "Bin Box") na produtividade logística. Ela foi convertida de um script original em Python (Streamlit).

🚀 Funcionalidades

Entrada de Parâmetros: Permite ao usuário inserir a meta de produtividade desejada e os tempos de penalidade.

Cálculo em Tempo Real: Todos os cálculos são refeitos instantaneamente a cada alteração nos inputs.

Visualização de Métricas: Exibe cartões de métricas (KPIs) com os resultados, incluindo:

Tempo Ideal por Peça

Tempo Real (com penalidades)

Produtividade Real Obtida

Potencial de Ganho (em %)

Gráfico Comparativo: Um gráfico de barras simples compara a produtividade "Meta (Ideal)" com a "Real (Com Penalidades)".

Detalhes dos Tempos: Um resumo detalhado dos tempos calculados.

🛠️ Tecnologias Utilizadas

HTML5: Estrutura semântica do aplicativo.

Tailwind CSS: Para estilização rápida e responsiva, recriando o tema laranja (similar ao Shopee) e o layout.

JavaScript (ES6+): Para toda a lógica de cálculo e manipulação dinâmica do DOM (atualização dos valores e do gráfico).

💻 Como Usar

Basta abrir o arquivo calculadora_logistica.html em qualquer navegador web moderno.

Acesse o painel "⚙️ Parâmetros de Entrada" à esquerda.

Insira a Meta de Produtividade (em peças por hora).

Insira a Penalidade Escada (em segundos).

Insira a Penalidade Bin Box (em segundos).

Os resultados e o gráfico no painel principal serão atualizados automaticamente.
