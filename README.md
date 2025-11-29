# Estudo de Potencial Energético de Usina Solar em uma PCH

## 📌 Descrição do Projeto
Este projeto consiste na análise do **potencial energético de uma Pequena Central Hidrelétrica (PCH)** combinada com a instalação de **painéis fotovoltaicos flutuantes** na área alagada da usina. O estudo abrange:

- Análise hidrológica da PCH utilizando dados de vazão diária ajustados por áreas de drenagem.
- Determinação da **vazão ótima** (Qótima) e **potência ótima** (Pótima) da turbina.
- Cálculo da **energia anual gerada** e do **benefício econômico**.
- Avaliação do **potencial energético solar** para diferentes percentuais de cobertura da área alagada.
- Integração da energia hidro + solar para obtenção do **potencial total da usina**.

Este trabalho segue a disciplina **EHD209 – Engenharia Hídrica**, Universidade Federal de Itajubá (UNIFEI).

---

## 🗂 Estrutura do Repositório

EHD209_PCH_Solar_2025
- dados_tratados
- dados_brutos
- apresentacao
- scripts
- relatorios
   README.md

---

## ⚙️ Como Utilizar

1. **Dados Hidrológicos**  
   - Abrir os CSVs em `Dados_Hidroweb/` para análise.
   - Colunas principais: `Data`, `Q usina m³`, `Altura`, `Permanência`.

2. **Cálculos Hidroenergéticos**  
   - Abrir planilha em `Planilhas/`.  
   - Testar diferentes vazões instaladas (`Q_instalada`) para encontrar a **vazão ótima**.  
   - Energia diária, anual e potência ótima calculadas automaticamente.  

3. **Cálculos do Potencial Solar**  
   - Ajustar área alagada e percentuais de cobertura.  
   - Inserir irradiação média (kWh/m²/dia) e eficiência dos painéis.  
   - Energia anual solar calculada e somada à energia da PCH.

4. **Resultados e Gráficos**  
   - Gráficos da energia anual vs vazão instalada e percentual de cobertura solar estão na pasta `Figuras/`.  
   - Tabelas de energia hidro, solar e total estão nas planilhas.

---

## 📊 Principais Resultados

- **Vazão ótima (Qótima):** X m³/s  
- **Potência ótima (Pótima):** Y kW  
- **Energia anual PCH:** Z MWh  
- **Energia anual solar (para 50% de cobertura):** W MWh  
- **Energia total PCH + Solar:** V MWh  

*(Valores podem ser ajustados conforme os dados finais da PCH selecionada)*

---

## 📚 Referências

1. Dissertação: [Nome da Dissertação, 2019, UNIFEI](https://repositorio.unifei.edu.br/jspui/bitstream/123456789/2059/1/disserta%c3%a7%c3%a3o_2019151.pdf)  
2. Hidroweb: [http://www.snirh.gov.br/hidroweb](http://www.snirh.gov.br/hidroweb)  
3. Atlas Brasileiro de Energia Solar – ANEEL/CRESESB: [https://www.cresesb.cepel.br/atlas/](https://www.cresesb.cepel.br/atlas/)  

---

## 👥 Equipe

- Raphael  
- Pablo  
- João Pedro  

---

## 📝 Licença

Projeto desenvolvido exclusivamente para fins acadêmicos (Disciplina EHD209 – UNIFEI, 2025).  
Uso e compartilhamento permitidos apenas com fins educativos, citando a fonte.

---

## 💡 Observações

- Para atualizar os cálculos de energia, basta alterar a série de vazões ou os percentuais de cobertura na planilha Excel.  
- O projeto pode ser expandido para incluir **simulação diária de energia solar real** usando dados meteorológicos detalhados.  
