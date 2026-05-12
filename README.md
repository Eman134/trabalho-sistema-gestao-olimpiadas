# 🏅 SGO – Sistema de Gestão das Olimpíadas

> Curso: Engenharia de Software – PUC Minas  
> Professor: João Paulo Carneiro Aramuni  

---

## 📋 Descrição do Sistema

Com a chegada das Olimpíadas, um novo sistema de gestão é necessário para coordenar os diferentes aspectos do evento. O SGO permite o gerenciamento de competições, inscrições de atletas, alocação de locais para as provas e controle de resultados.

---

## 📁 Estrutura do Repositório

```
sistema-gestao-olimpiadas/
├── README.md
├── docs/
│   ├── diagrama-de-caso-de-uso.png
│   ├── diagrama-de-classes-e-pacotes.png
│   ├── diagrama-de-componentes.png
│   └── diagrama-de-implantacao.png
└── puml/
    ├── diagrama-de-caso-de-uso.puml
    ├── diagrama-de-classes-e-pacotes.puml
    ├── diagrama-de-componentes.puml
    └── diagrama-de-implantacao.puml
```

---

## 👤 Histórias de Usuário

### Gestão de Competições

**US01 – Cadastrar Competição**  
*Como* administrador do sistema,  
*quero* cadastrar uma competição informando modalidade, data, horário, local e atletas inscritos,  
*para que* o evento seja registrado e gerenciado corretamente no sistema.

**US02 – Editar Competição**  
*Como* administrador do sistema,  
*quero* editar as informações de uma competição já cadastrada,  
*para que* correções ou atualizações possam ser realizadas antes do evento.

**US03 – Listar Competições**  
*Como* administrador, atleta ou público,  
*quero* visualizar todas as competições cadastradas,  
*para que* eu possa acompanhar a programação das Olimpíadas.

---

### Inscrição de Atletas

**US04 – Inscrever Atleta em Competição**  
*Como* atleta,  
*quero* me inscrever em uma competição específica representando meu país,  
*para que* eu possa participar oficialmente da modalidade desejada.

**US05 – Cancelar Inscrição**  
*Como* atleta,  
*quero* cancelar minha inscrição em uma competição,  
*para que* minha vaga seja liberada para outro atleta.

**US06 – Validar País por Modalidade**  
*Como* sistema,  
*quero* validar que um atleta representa apenas um país por modalidade,  
*para que* a regra de elegibilidade olímpica seja respeitada.

---

### Alocação de Locais

**US07 – Cadastrar Local**  
*Como* administrador ou gestor de locais,  
*quero* cadastrar um local informando nome, capacidade e recursos disponíveis,  
*para que* ele possa ser alocado para competições.

**US08 – Alocar Local para Competição**  
*Como* administrador ou gestor de locais,  
*quero* alocar um local a uma competição em determinado horário,  
*para que* cada competição tenha um espaço físico definido.

**US09 – Verificar Conflito de Horário**  
*Como* sistema,  
*quero* verificar se um local já está ocupado em determinado horário,  
*para que* não ocorram dois eventos simultâneos no mesmo espaço.

---

### Controle de Resultados

**US10 – Registrar Resultado**  
*Como* árbitro ou oficial,  
*quero* registrar o resultado de uma competição indicando os classificados em 1º, 2º e 3º lugares,  
*para que* os dados sejam computados para o quadro de medalhas.

**US11 – Homologar Resultado**  
*Como* administrador,  
*quero* homologar o resultado registrado por um árbitro,  
*para que* ele seja oficialmente válido e gere a distribuição de medalhas.

**US12 – Consultar Resultado**  
*Como* árbitro, atleta ou público,  
*quero* consultar os resultados de uma competição,  
*para que* eu possa acompanhar o desempenho dos participantes.

---

### Relatórios e Medalhas

**US13 – Gerar Relatório de Medalhas**  
*Como* administrador,  
*quero* gerar um relatório com o total de medalhas de ouro, prata e bronze por país,  
*para que* o desempenho das delegações possa ser avaliado.

**US14 – Exibir Quadro de Medalhas**  
*Como* público ou delegação,  
*quero* visualizar o quadro de medalhas atualizado,  
*para que* eu possa acompanhar o desempenho dos países nas Olimpíadas.

**US15 – Exportar Relatório**  
*Como* administrador,  
*quero* exportar o relatório de medalhas em PDF ou CSV,  
*para que* o documento possa ser distribuído ou arquivado.

---

## 📊 Diagramas UML

### 1. Diagrama de Caso de Uso

<img width="800px" src="https://github.com/eman134/trabalho-sistema-gestao-olimpiadas/blob/main/docs/diagrama-de-casos-de-uso.png"/>

---

### 2. Diagrama de Classes e Pacotes

<img width="800px" src="https://github.com/eman134/trabalho-sistema-gestao-olimpiadas/blob/main/docs/diagrama-de-classes-e-pacotes.png"/>

---

### 3. Diagrama de Componentes

<img width="800px" src="https://github.com/eman134/trabalho-sistema-gestao-olimpiadas/blob/main/docs/diagrama-de-componentes.png"/>

---

### 4. Diagrama de Implantação

<img width="800px" src="https://github.com/eman134/trabalho-sistema-gestao-olimpiadas/blob/main/docs/diagrama-de-implantacao.png"/>

---

## 🛠️ Ferramentas Utilizadas

- [PlantUML](https://plantuml.com/) – geração dos diagramas UML
- [PlantUML Guide](https://plantuml.com/guide) – referência da linguagem

---

## 👥 Autores

Kayke Emanoel de Souza Santos<br>
Ana Luiza de Freitas Rodrigues
