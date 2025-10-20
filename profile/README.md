# Verifica.AI — Organização criada durante a matéria Projeto Integrador II no CEUB para o desenvolvimento de uma Ferramenta de Detecção de Fake News no contexto político brasileiro.

## Problema

A desinformação digital é um dos maiores desafios da atualidade.  
Com o avanço das redes sociais e das inteligências artificiais generativas, notícias falsas são produzidas e disseminadas em grande escala, influenciando decisões políticas e sociais.
Durante as eleições e crises sanitárias, como a pandemia de COVID-19, observou-se um crescimento alarmante na circulação de **fake news**.  
No Brasil, cerca de **80% dos usuários afirmam querer ferramentas que ajudem a verificar a veracidade de informações** (Avaaz, 2020).

---

## Objetivos

### Objetivo Geral
Desenvolver uma **aplicação web baseada em inteligência artificial** capaz de **detectar e classificar notícias falsas** relacionadas à política brasileira,  
proporcionando aos usuários uma ferramenta confiável para combate à desinformação e fortalecimento da credibilidade das informações online.

### Objetivos Específicos
- Implementar uma **análise automatizada de textos** para verificação de veracidade;  
- Aplicar técnicas de **machine learning** e **processamento de linguagem natural (NLP)** para detectar padrões de desinformação;  
- Desenvolver uma interface web responsiva e acessível que permita o envio e análise de notícias;  
- Fornecer **relatórios explicativos** sobre os resultados das análises, incluindo fontes de verificação;  
- Armazenar o histórico de análises de forma segura, permitindo rastreabilidade;  
- Garantir a **transparência** e a **usabilidade** da ferramenta para usuários sem conhecimento técnico.

---

## Escopo

O **Verifica.Al** permite que o usuário envie uma notícia (texto ou arquivo) para análise.  
O sistema processa o conteúdo por meio de um modelo de IA, retornando:

- Grau de confiabilidade do texto;  
- Referências externas de fontes confiáveis;  
- Relatório sobre a veracidade;  

### Limitações Iniciais
- Apenas entrada de texto;  
- Limite de caracteres e de análises diárias.

---

## Solução Proposta

A ferramenta utiliza um **Modelo de Linguagem de Grande Escala (LLM)** ajustado especificamente para o domínio político.  

### Arquitetura do Sistema
- **Backend:** Django + Django REST Framework  
- **Frontend:** React  
- **Banco de Dados:** MongoDB Atlas  
- **Hospedagem:** Nuvem (AWS / Google Cloud / Azure)  
- **Autenticação:** JSON Web Token (JWT)

O modelo de IA é responsável por analisar textos, identificar padrões de desinformação e classificar conteúdos com base em critérios estatísticos e semânticos.

---

## Equipe

| Nome | Função | Contato |
|------|--------|------------|
| **Victor Albuquerque Cordeiro** | Desenvolvimento Backend e Integração de IA | [LinkedIN](https://www.linkedin.com/in/victoralbucorde/) |
| **Gabriel Paiva** | Desenvolvimento Frontend e Modelagem do Sistema | [LinkedIN](https://www.linkedin.com/in/gabriel-navarro-paiva-901662299/) |

**Orientação:** Profª Kadidja Valéria  
**Curso:** Ciência da Computação — CEUB  
**Disciplina:** Projeto Integrador II  

---

## Público-Alvo

A aplicação é voltada para todos que necessitam validar informações de forma prática e confiável:

- Cidadãos interessados em checar notícias;  
- Jornalistas e comunicadores;  
- Estudantes e pesquisadores;
  
Esses usuários compartilham o mesmo objetivo: **verificar rapidamente a autenticidade de conteúdos digitais** e reduzir a disseminação de desinformação.

---

## Licença

Este projeto é desenvolvido para fins acadêmicos e de pesquisa no âmbito do **Projeto Integrador II — CEUB**,  
com propósito educacional e de impacto social.

---

## Referências

AVAAZ. O Brasil está sofrendo uma infodemia de Covid-19. 4 de maio de 2020. Disponível em: https://avaazimages.avaaz.org/brasil_infodemia_coronavirus.pdf. Acesso em: 23 set. 2025.
