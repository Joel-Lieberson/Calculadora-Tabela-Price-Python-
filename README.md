Calculadora — Tabela Price (Python)

Gere a tabela de amortização no sistema Price (prestação constante) a partir do valor financiado, taxa mensal e número de parcelas.

✨ O que faz

Calcula a prestação (PMT) fixa

Gera a tabela parcela a parcela com: saldo inicial, juros, amortização, prestação e saldo final

Exporta para CSV (opcional, via CLI)

🧮 Fórmula

Prestação (PMT):

PMT
=
𝑃
⋅
𝑖
1
−
(
1
+
𝑖
)
−
𝑛
PMT=P⋅
1−(1+i)
−n
i
	​


Onde:

𝑃
P = principal (valor financiado)

𝑖
i = taxa mensal (ex: 1,5% → 0,015)

𝑛
n = número de parcelas
