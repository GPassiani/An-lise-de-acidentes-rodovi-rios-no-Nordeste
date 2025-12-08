# Análise da Relação entre Fatores Ambientais e a Gravidade de Acidentes no Nordeste

**Esse projeto foi criado em conjunto.**

## 👥 Autores
* **Flavio Henrique Santos**
* **Gustavo Henrique Passiani Florêncio**
* *Centro Universitário SENAI São Paulo*

## 📄 Resumo do Projeto
Este estudo de Análise de Dados investigou a correlação estatística entre fatores ambientais (clima e fase do dia/iluminação) e a gravidade dos acidentes de trânsito na Região Nordeste do Brasil.

Utilizando dados abertos da Polícia Rodoviária Federal (PRF), a pesquisa comprovou, via Teste de Qui-quadrado (χ²), que a visibilidade reduzida é um fator que aumenta significativamente a chance de acidentes serem classificados como Gravíssimos ou Fatais.

**Palavras-Chave:** Segurança Viária · Análise de Acidentes · Condições Climáticas · Iluminação · Qui-quadrado

## 🎯 Objetivo
O objetivo central foi validar a hipótese de que o ambiente (clima e iluminação) possui uma influência direta e mensurável na severidade final de uma colisão, e não apenas na sua ocorrência.

## ⚙️ Metodologia e Pipeline de Dados
O projeto seguiu um rigoroso pipeline de Data Science, implementado majoritariamente em Python, utilizando o Jupyter Notebook (`Script_analises_Nordeste.ipynb`).

### Fonte de Dados
* **Origem:** Dados Abertos Oficiais da Polícia Rodoviária Federal (PRF).
* **Período:** Dados de acidentes de 2024 (filtrados para a Região Nordeste).
* **Variáveis Chave:** `gravidade`, `condicao_metereologica`, `fase_do_dia`.
* **Link Base de dados:** [Google Drive](https://drive.google.com/drive/folders/185CW-zfaanF000Gh5sH2hcYK_b3De5qv)

### Ferramentas (Python)
* **Pandas:** Limpeza, manipulação e categorização dos dados.
* **Matplotlib / Seaborn:** Geração de gráficos de frequência e proporção de risco.
* **SciPy.stats:** Validação estatística (função `chi2_contingency`).

### Passos da Análise
1. **Importação e Filtragem:** Carregamento do dataset e seleção de acidentes na Região Nordeste.
2. **Limpeza/Categorização:** Normalização e padronização das colunas (Ex: Gravidade: Sem Vítimas, Feridos Leves, Feridos Graves, Fatais).
3. **Análise Descritiva:** Geração de gráficos para visualizar a distribuição da gravidade em função do clima e da fase do dia.
4. **Validação Estatística:** Aplicação do Teste de Qui-quadrado para testar a independência.

## 📊 Conclusão Estatística
O teste de Qui-quadrado resultou em um **p-valor < 0,05** para as variáveis analisadas, permitindo rejeitar a hipótese nula de independência.

### Resultado
A correlação entre as condições ambientais e a gravidade dos acidentes é estatisticamente relevante. Os dois principais achados do estudo, validados estatisticamente, são:

* **Fator Climático:** As condições de Chuva e Neblina não apenas causam acidentes, mas aumentam a chance de o resultado ser Gravíssimo ou Fatal.
* **Fator Iluminação:** A maior proporção de acidentes de alta gravidade ocorre na Plena Noite (escuridão), indicando a insuficiência de visibilidade como um risco primordial.

## 🏆 Publicação e Aceitação
O artigo completo, resultado desta análise, foi aceito e apresentado no **II CONGRESSO INTERNACIONAL DE INOVAÇÃO E PESQUISA**.
* [Link do congresso na Even3](https://www.even3.com.br/ii-congresso-internacional-de-inovacao-e-pesquisa-603868/)

## 📞 Contato
Sinta-se à vontade para entrar em contato para dúvidas, sugestões ou colaborações:
* [Flavio Henrique Santos](https://www.linkedin.com/in/flaviosantos-dev-eng/)
* [Gustavo Henrique Passiani Florêncio](https://www.linkedin.com/in/gustavo-h-passiani-a87b1a215/)
