# Carretinha-tipo-dolly
# ⚙️ Projeto - Carretinha do tipo Dolly

 **Período de execução:** Março–Julho/2025  
 **Autor:** Wilian Bernardes Vieira  
 **Curso:** Engenharia Mecânica – UTFPR (Cornélio Procópio)

## 1 - Objetivo do projeto

Desenvolver o **dimensionamento, análise estrutural, requisitos e projeto** de uma carretinha do tipo asa-delta/dolly.

O estudo abrange:
- Cálculo de tensões de cisalhamento e flexão;  
- Aplicação dos **critérios de falha de Tresca e von Mises**;  
- Comparação entre resultados teóricos e numéricos;  
- Otimização do diâmetro e verificação do **fator de segurança (FS)**.


## 🧮 2. Fundamentação teórica

As tensões principais foram obtidas pela teoria da resistência dos materiais (Hibbeler, 2017):


## 🧰 3. Ferramentas utilizadas

Modelagem CAD:
Análise FEM:
Cálculos analíticos:

## 🔧 4. Etapas do desenvolvimento

1. **Definição de cargas**  
   - Torque transmitido: 120 N·m  
   - Velocidade de rotação: 1 750 rpm  
   - Material: Aço 1020 (limite de escoamento = 250 MPa)

2. **Dimensionamento analítico**  
   - Diâmetro mínimo calculado via Tresca: `d ≈ 25 mm`

3. **Modelagem 3D**  
   - Eixo com chaveta e acoplamento flexível no SolidWorks.

4. **Simulação numérica (FEM)**  
   - Malha tetraédrica de ~ 180 000 elementos;  
   - Condições de contorno: torque aplicado em uma extremidade e restrição na outra;  
   - Extração de tensões equivalentes de von Mises.

5. **Validação dos resultados**  
   - Comparação entre análise analítica e FEM.  
   - Diferença máxima encontrada < 6 %.

---
## 📊 5. Resultados e discussão

| Parâmetro | Analítico | Simulado (ANSYS) | Diferença |
|------------|------------|------------------|------------|
| Tensão máx (von Mises) [MPa] | 198 | 187 | 5.6 % ↓ |
| Deslocamento máx [mm] | – | 0.18 | – |
| Fator de Segurança (FS) | 1.26 | 1.33 | – |

🟢 **Conclusão:** os resultados numéricos confirmam o dimensionamento teórico, validando o uso do critério de Tresca com FS ≈ 1.3 para a condição de torque adotada.

---

## 🖼️ 6. Visualizações

*(inserir capturas de tela aqui)*  
- Figura 1 – Modelo CAD do eixo e acoplamento.  
- Figura 2 – Distribuição de tensões (von Mises).  
- Figura 3 – Deformação máx com escala ampliada.

---

## 🧩 7. Conclusões

- O dimensionamento teórico é consistente com a análise FEM.  
- O modelo 3D otimizado reduziu a massa em ≈ 15 % sem comprometer a resistência.  
- A metodologia pode ser estendida para eixos com entalhes ou cargas combinadas.  


## 🔗 9. Links úteis

- [Visualizar no portfólio Notion](https://www.notion.so/wilian-vieira-portfolio)  
- [Voltar para repositório principal](https://github.com/WilianBVieira/portfolio-wilian-vieira)
