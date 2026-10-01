# Extensão Rotacional das Equações de Campo de Fluxo Inverso

Registro da extensão rotacional do **axioma de campo de fluxo inverso**,
formulada em **01 de outubro de 2026**, posterior ao registro do axioma de
campo e das formas derivadas.

Ecossistema **O Atemporal** — Antônio Marcos. Licença CC BY 4.0.

---

## Axioma de Campo (forma base)

$$
R_c = \lambda \left( \frac{k}{\Phi + \varepsilon} \right)^{1/n}
$$

Registrado em 01 de outubro de 2026. A rotação não estava incorporada na
forma original.

| Termo | Papel | Escopo |
| --- | --- | --- |
| R_c | Escala crítica resultante | Universal |
| λ | Chave seletora de escala | Do domínio observado |
| k | Identidade do sistema | Do sistema em análise |
| Φ | Fluxo de energia (Φ = Mc² em astrofísica) | Universal |
| ε | Energia do domínio observado | Do domínio observado |
| n | Expoente geométrico | Do regime |

---

## Opção A — Rotação como Energia

$$
R_c = \lambda \left( \frac{k}{(\Phi + \varepsilon)(1 + \Omega^2)} \right)^{1/n}
$$

**Papel da rotação.** Energia adicional do domínio, no mesmo lugar ocupado
por ε. A rotação redistribui o fluxo disponível: parte da energia deixa de
sustentar a estrutura e se converte em movimento angular. O termo (1 + Ω²)
mede essa redistribuição, atuando diretamente sobre a fonte.

**Domínio.** Φ + ε > 0, n > 0, λ > 0, k ≠ 0, Ω ≥ 0.

**Limite canônico.** Com Ω = 0, retorna à forma base e, com λ = 1,
ε → 0 e n = 1, à 5ª Forma:

$$
R_c = \frac{k}{\Phi}
$$

**Relação com a 10ª Forma.** É a generalização direta dela — o mesmo termo
(1 + Ω²) no denominador:

$$
R_{rot} = \lambda \frac{k}{\Phi (1 + \Omega^2)}
$$

**Aplicações.** Discos de acreção em torno de buracos negros, estrelas em
rotação rápida, curvas de rotação galácticas, sistemas com velocidade angular
mensurável, fluidos e rotores em engenharia.

**Cuidado dimensional.** Ω em s⁻¹ somado a 1 exige unidades naturais ou
normalização — o mesmo cuidado que a 10ª Forma já tem.

---

## Opção B — Rotação como Geometria

$$
R_c = \lambda \left( \frac{k}{\Phi + \varepsilon} \right)^{1/(n + \Omega/\Omega_0)}
$$

**Papel da rotação.** Assinatura de regime, o mesmo papel que n ocupa. Um
sistema em rotação tem geometria efetiva diferente, e o expoente desloca-se:

$$
\frac{1}{n} \longrightarrow \frac{1}{n + \Omega/\Omega_0}
$$

| Termo | Papel | Escopo |
| --- | --- | --- |
| Ω | Velocidade angular | Do sistema em análise |
| Ω₀ | Escala angular de referência | Do domínio |

**Domínio.** Φ + ε > 0, n > 0, λ > 0, k ≠ 0, Ω ≥ 0, Ω₀ > 0.

**Limite canônico.** Com Ω = 0, retorna exatamente à forma base, sem resíduo.

**Normalização.** A escala angular Ω₀ cumpre o mesmo papel que L₀ na
normalização do seletor quântico. Sem ela, a soma do expoente não fecha
dimensionalmente em unidades do Sistema Internacional.

---

## Comparação das Opções

| Critério | Opção A | Opção B |
| --- | --- | --- |
| Onde a rotação entra | No denominador, como energia | No expoente, como geometria |
| Papel físico | Redistribuição de fluxo | Assinatura de regime |
| Recupera a forma base com Ω = 0 | Sim | Sim, sem resíduo |
| Ambiguidade de leitura | A rotação comparece em dois lugares | Um único lugar |
| Normalização exigida | Não | Sim, por Ω₀ |
| Forma de origem | 10ª Forma | Papel de n |

---

## Correspondência com o Regime de Kerr

No limite relativístico, a velocidade angular clássica torna-se o spin
adimensional:

| Grandeza | Regime clássico | Regime relativístico |
| --- | --- | --- |
| Rotação | Ω | χ |
| Fator de contração | 1 + Ω² (A) · Ω/Ω₀ (B) | F_χ = 2 / (1 + √(1 − χ²)) |
| Forma de origem | 10ª Forma | 20ª Forma |

O fator de spin da 20ª Forma é a razão entre o raio de Schwarzschild e o
horizonte externo de Kerr — a expressão, no limite relativístico, da mesma
contração que a rotação descreve nas duas opções.

---

## Propriedades

- **Recuperação da forma original** — nas duas opções, Ω = 0 devolve o
  axioma de campo registrado.
- **Continuidade** — na Opção B, o expoente efetivo é contínuo em Ω; não
  há salto entre regimes.
- **Direção do efeito** — em ambas, a rotação contrai a escala, coerente
  com o comportamento de sistemas rotantes.
- **Sentido de rotação** — as formas distinguem sentido apenas se Ω for
  tomado com sinal. Prógrado ou retrógrado é informação separada, do mesmo
  modo que o sinal do spin na 20ª Forma.

---

## Status do Registro

Este documento registra as duas formulações da extensão rotacional do
axioma de campo. Não apresenta calibração numérica e não deve ser lido
como validação.

**Em aberto.** A escolha entre as Opções A e B permanece como decisão de
formulação. A determinação da escala angular Ω₀ e do par (k, λ) em domínios
rotacionais permanece como trabalho de calibração.

---

## Repositórios relacionados

- Equações de Campo de Fluxo Inverso — axioma de campo e formas derivadas:
  [github.com](https://github.com/o-atemporal/inverse-flow-field-equations)
- Telemetria para Inclinação Orbital e Redshift — Métricas de Kerr:
  [github.com](https://github.com/o-atemporal/telemetria-orbital-redshift-metrica-kerr)

---

## Precedência

| Formulação | Primeira aparição pública |
| --- | --- |
| Axioma fundamental Φ · Va = k/R | 10/04/2026 (Cap. 18) · Biblioteca Nacional 06/04 |
| 20 formas | 11/09/2026 (1ª edição) |
| Axioma de campo e formas derivadas | 01/10/2026 |
| **Extensão rotacional (Opções A e B)** | **01/10/2026 (este registro)** |

---

Princípio da Proporcionalidade Inversa © 2026 [Antônio Marcos] — CC BY 4.0
