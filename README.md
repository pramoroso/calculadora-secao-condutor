
# ⚡ Calculadora de Seção de Condutor

Este é um aplicativo web simples, prático e responsivo desenvolvido por **Paulo Amoroso** para ajudar engenheiros, eletricistas e projetistas a **dimensionar a seção de condutores elétricos** de forma rápida, com base em critérios técnicos de corrente e queda de tensão.

## 🚀 Funcionalidades

- Cálculo automático da corrente elétrica com base na potência e tensão
- Cálculo da seção mínima com base na queda de tensão permitida
- Escolha entre **material do condutor** (Cobre ou Alumínio)
- Suporte a circuitos **monofásicos e trifásicos**
- Cálculo com **queda de tensão em volts ou percentual (%)**
- Validação da bitola com base em tabelas de corrente padrão
- Alerta especial para **sistemas de baixa tensão (12V ou 24V)**
- Contador de acessos local (via `localStorage`)

## 🧮 Fórmulas utilizadas

- **Corrente (I)**:
  - Monofásico: `I = P / V`
  - Trifásico: `I = P / (√3 × V)`

- **Seção (S)**:
  - Monofásico: `S = (2 × L × I) / (γ × ΔV)`
  - Trifásico: `S = (√3 × L × I) / (γ × ΔV)`

Onde:
- `L` = comprimento do circuito (m)
- `γ` = condutividade do material (Cobre = 56, Alumínio = 35)
- `ΔV` = queda de tensão admissível (em V)

## 💻 Tecnologias

- HTML5
- CSS3
- JavaScript puro (sem frameworks)

## 📂 Acesse

- 🔗 Projeto online: [https://pramoroso.github.io/calculadora-secao-condutor/](https://pramoroso.github.io/calculadora-secao-condutor/)
- 📁 Código-fonte: [https://github.com/pramoroso/calculadora-secao-condutor](https://github.com/pramoroso/calculadora-secao-condutor)

## 👨‍💼 Autor

**Paulo Amoroso**  
Engenheiro Eletricista | Gerente de Projetos  
🔗 [LinkedIn](https://www.linkedin.com/in/paulo-amoroso-04782a29/)

---

> Esta ferramenta é de uso educativo e técnico, e não substitui normas ou responsabilidades profissionais. Utilize com critério.
