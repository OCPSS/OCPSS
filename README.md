# OCPSS — Organização Colaborativa de Projetos de Sistemas de Software

A **OCPSS** é uma organização colaborativa criada para centralizar, organizar e compartilhar os projetos desenvolvidos na disciplina de **Projetos de Sistemas de Software (PSS)** da **UFES**. O objetivo é promover a colaboração, o versionamento adequado e as boas práticas de desenvolvimento em equipe.

---

## Sumário

1. [Objetivos](#objetivos)
2. [Repositórios](#repositórios)
3. [Tecnologias](#tecnologias)
4. [Como contribuir](#como-contribuir)
5. [Boas práticas](#boas-práticas)
6. [Modelo de README para projetos](#modelo-de-readme-para-projetos)
7. [Observações](#observações)

---

## Objetivos

- 🗂️ Centralizar os projetos da disciplina em um único ambiente
- 🤝 Estimular o trabalho colaborativo com Git e GitHub
- 🌿 Aplicar boas práticas de versionamento e organização de código
- 📈 Facilitar o acompanhamento e a avaliação dos projetos
- 🎓 Criar um portfólio acadêmico dos trabalhos desenvolvidos

---

## Repositórios

| Repositório | Descrição |
|---|---|
| [pss-guia-estudos](https://github.com/OCPSS/pss-guia-estudos) | Guia de estudos da disciplina: Java, OO, UML, SOLID, padrões de projeto (GoF), Maven, Git e persistência |
| [OCPSS](https://github.com/OCPSS/OCPSS) | Este repositório: apresentação e regras de colaboração da organização |

> 📚 Está começando agora? Comece pelo **[guia de estudos](https://github.com/OCPSS/pss-guia-estudos)**.

---

## Tecnologias

Tecnologias usadas nos projetos da disciplina:

| Categoria | Tecnologias |
|---|---|
| Linguagem | Java (JDK 17 ou 21) |
| Interface gráfica | Java Swing |
| Build e dependências | Maven |
| Banco de dados | SQLite, H2, MySQL (JDBC) |
| Modelagem | UML (Astah Community) |
| Versionamento | Git e GitHub |

---

## Como contribuir

Todos os integrantes devem contribuir com commits. Fluxo recomendado:

1. **Clone** o repositório do projeto:

   ```bash
   git clone https://github.com/OCPSS/<nome-do-repositorio>.git
   ```

2. **Crie uma branch** para a sua tarefa a partir da `main`:

   ```bash
   git checkout -b feature/nome-da-tarefa
   ```

3. **Faça commits** pequenos, com mensagens claras e objetivas:

   ```bash
   git commit -m "Adiciona cadastro de produtos"
   ```

4. **Envie a branch** para o GitHub:

   ```bash
   git push -u origin feature/nome-da-tarefa
   ```

5. **Abra um Pull Request** para a `main` e peça revisão de outro integrante antes do merge.

> 💡 Use Pull Requests sempre que possível, em vez de enviar direto para a `main`.

---

## Boas práticas

### Código

- Código organizado e comentado quando necessário
- Padrão de nomenclatura consistente em pastas, arquivos e classes
- Aplicação dos princípios e padrões estudados na disciplina (SOLID, GoF, DAO/Repository)

### Versionamento

- Uso correto de branches (uma branch por funcionalidade ou correção)
- Mensagens de commit claras, que descrevem **o que** foi feito
- Nada de arquivos gerados no repositório (ex.: `target/`, `.class`, arquivos da IDE) — use um `.gitignore`
- Nunca envie senhas ou credenciais; use variáveis de ambiente (`.env`) e coloque o `.env` no `.gitignore`

### Documentação

- **Todo projeto deve ter um README**, seguindo o modelo abaixo

---

## Modelo de README para projetos

Copie e adapte este modelo para o README de cada projeto:

```markdown
# Nome do Projeto

Breve descrição do que o sistema faz.

## Integrantes

- Nome 1 (@usuario-github)
- Nome 2 (@usuario-github)

## Tecnologias

- Java 21
- Maven
- Banco de dados: SQLite / H2 / MySQL

## Como executar

1. Pré-requisitos: JDK e Maven instalados
2. Clone o repositório
3. Configure o arquivo `.env` (se houver)
4. Execute: `mvn clean install` e depois rode a classe principal

## Arquitetura e padrões utilizados

Descreva a estrutura do projeto e os padrões de projeto aplicados.

## Diagramas

Inclua ou referencie os diagramas UML (classes, sequência, estados).
```

---

## Observações

- Esta organização tem **fins acadêmicos** e serve como registro das atividades práticas da disciplina.
