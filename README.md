# 👋 Olá, eu sou Eduardo Cavagnoli

## 🧪 Analista de Quality Assurance (QA) | QA Júnior

Estou iniciando minha trajetória na área de **Quality Assurance**, com foco em **testes manuais e validação de funcionalidades**. Gosto de entender como o sistema deve se comportar, identificar possíveis falhas e garantir que tudo funcione de forma clara e correta para o usuário.

Tenho buscado evoluir por meio de **projetos práticos**, nos quais exercito atividades comuns do dia a dia de um QA Júnior, como criação de casos de teste, escrita de cenários BDD e organização de documentações simples e objetivas.

---

## 🎯 Objetivo Profissional

Atuar como **Analista de QA Júnior**, contribuindo com a validação de funcionalidades, criação de testes bem estruturados e colaboração com times de desenvolvimento e produto, ajudando a reduzir falhas em produção e melhorar a experiência do usuário.

---

## 🛠️ Habilidades

* Testes Manuais (funcionais e exploratórios)
* Criação e execução de casos de teste
* Escrita de cenários BDD (Gherkin)
* Análise, registro e acompanhamento de bugs
* Testes de API (nível introdutório)
* Validação de regras de negócio
* Leitura e entendimento de requisitos e critérios de aceite
* Noções do ciclo de vida de desenvolvimento de software (SDLC)
* Noções iniciais de automação de testes

---

## 🧰 Ferramentas

* Git & GitHub
* Postman
* Jira (ou ferramentas similares)
* Swagger
* VS Code
* Markdown
* JSON

---

# 📌 Projeto de QA – Atualização de Perfil do Usuário

## 🧪 Projeto prático para portfólio de **QA Júnior**

Este projeto simula a atuação de um **Analista de QA Júnior** validando a funcionalidade de **Atualização de Perfil do Usuário**, muito comum em sistemas web e aplicações corporativas.

O foco do projeto é demonstrar a capacidade de analisar requisitos, criar casos de teste positivos e negativos, escrever cenários BDD e documentar resultados de forma clara e organizada.

---

## 🎯 Objetivo do Projeto

Garantir que a funcionalidade de **Atualização de Perfil** permita a alteração correta dos dados do usuário, respeitando regras de negócio, validações de campos e proporcionando uma boa experiência de uso.

---

## 📄 Escopo Testado

* Atualização de nome do usuário
* Atualização de telefone
* Upload de foto de perfil
* Validação de campos obrigatórios
* Validação de formatos inválidos
* Persistência dos dados após atualização

---

## 🛠️ Atividades de QA Realizadas

* Análise dos requisitos da funcionalidade
* Criação de casos de teste manuais (cenários positivos e negativos)
* Escrita de cenários BDD utilizando Gherkin
* Execução dos testes funcionais
* Validação de mensagens de erro e sucesso
* Documentação dos testes e resultados

---

## 🧪 Exemplos de Cenários BDD

### Cenário Positivo – Atualizar perfil com dados válidos

```gherkin
Cenário: Atualizar o perfil com dados válidos
  Dado que o usuário esteja autenticado no sistema
  E esteja na tela de atualização de perfil
  Quando informar um nome válido
  E informar um telefone em formato válido
  E selecionar uma imagem válida como foto de perfil
  E clicar no botão salvar
  Então o sistema deve atualizar os dados do perfil com sucesso
  E deve exibir uma mensagem de confirmação
```

### Cenário Negativo – Atualizar perfil com dados inválidos

```gherkin
Cenário: Tentativa de atualizar o perfil com dados inválidos
  Dado que o usuário esteja autenticado no sistema
  E esteja na tela de atualização de perfil
  Quando deixar o campo nome em branco
  E informar um telefone em formato inválido
  E selecionar um arquivo não permitido como foto de perfil
  E clicar no botão salvar
  Então o sistema não deve permitir a atualização do perfil
  E deve exibir mensagens de validação
```

---

## 📂 Estrutura do Projeto

```bash
qa-profile-update-project/
│
├── README.md
├── casos-de-teste/
│   └── casos_de_teste_atualizacao_perfil.md
├── bdd/
│   └── atualizacao_perfil.feature
├── bugs/
│   └── bug_validacao_perfil.md
└── evidencias/
    └── README.md
```

---

## 📄 Caso de Teste – Atualização de Perfil do Usuário

Arquivo localizado em: `casos-de-teste/casos_de_teste_atualizacao_perfil.md`

```markdown
# Casos de Teste – Atualização de Perfil do Usuário

## CT-01 – Atualizar perfil com dados válidos

**Pré-condição:**
- Usuário autenticado no sistema
- Tela de atualização de perfil disponível

**Dados de teste:**
- Nome: Eduardo Cavagnoli
- Telefone: (11) 91234-5678
- Foto de perfil: imagem válida (.jpg ou .png)

**Passos:**
1. Acessar a tela de atualização de perfil
2. Informar um nome válido
3. Informar um telefone em formato válido
4. Selecionar uma imagem válida como foto de perfil
5. Clicar no botão "Salvar"

**Resultado esperado:**
- Sistema salva as alterações com sucesso
- Mensagem de confirmação é exibida
- Dados permanecem atualizados após recarregar a página

---

## CT-02 – Atualizar perfil com dados inválidos

**Pré-condição:**
- Usuário autenticado no sistema

**Dados de teste:**
- Nome: (em branco)
- Telefone: 123ABC456
- Foto de perfil: arquivo inválido (.pdf)

**Passos:**
1. Acessar a tela de atualização de perfil
2. Deixar o campo nome em branco
3. Informar um telefone em formato inválido
4. Selecionar um arquivo não permitido como foto de perfil
5. Clicar no botão "Salvar"

**Resultado esperado:**
- Sistema não permite salvar as alterações
- Mensagens de validação são exibidas
- Nenhuma informação é alterada
```

---

## 📚 Considerações Finais

Este projeto foi desenvolvido com foco em prática, organização e aprendizado contínuo, simulando atividades reais do dia a dia de um **QA Júnior** e reforçando conceitos essenciais de qualidade de software.

---

## 🔗 Contato

* 💼 LinkedIn: [https://www.linkedin.com/in/eduardo-cavagnoli-a4053215b/](https://www.linkedin.com/in/eduardo-cavagnoli-a4053215b/)
* 📧 Email: [eduardo_castelano@hotmail.com](eduardo_castelano@hotmail.com)

---

⭐ Este repositório faz parte do meu portfólio profissional e da minha evolução na área de Quality Assurance.
