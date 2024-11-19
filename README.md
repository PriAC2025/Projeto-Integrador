# Projeto-Integrador - Gestão de Dados da Universidade

## Objetivo
Este projeto visa desenvolver um sistema de gestão de dados de diferentes pessoas que interagem com uma grande universidade, pois sabemos que dados precisos e atualizados são essenciais para tomadas de decisões que visam atingir objetivos com mais eficiência e rapidez. Sendo assim, o sistema foi modelado em UML e prototipado para garantir que a experiência do usuário seja prática e intuitiva.

## Requisitos tecnológicos
- Java, HTML, CSS, MIRO
- IDE 

## Casos de Uso
### Cadastro de Pessoa Física
Campos do Formulário:
- Campo para inserir foto
- Nome Completo
- CPF
- Data de Nascimento
- Endereço Completo
- Contatos
- Atividade Profissional
- Formação Acadêmica
- Campo de texto para informações adicionais
- Botão para Salvar
- Botão para Cancelar
- Botão para retornar ao menu principal

### Cadastro de Alunos
Campos do Formulário:
- Campo para inserir foto
- Nome Completo do Aluno
- Número de matricula
- CPF
- Data de Nascimento
- Endereço Completo
- Contatos
- Botão de seleção do Curso
- Botão de seleção da Disciplina
-(se menor de idade) Nome Completo do Responsável Legal 
- CPF do Responsável Legal
- Botão para Salvar
- Botão para Cancelar
- Botão para retornar ao menu principal

### Cadastro de Pessoa Jurídica
Campos do Formulário:
- Razão Social
- CNPJ
- Endereço Completo
- Contatos
- Botão clicável para ramos de atividades
- Composição Societária
- Botões para Upload de documentos
- Espaço digitável para assinaturas digital ou eletrônica
- Botão para Salvar
- Botão para Cancelar
- Botão para retornar ao menu principal
- 
### Cadastro de Professores
- Campo para inserir foto
- Nome Completo
- Número de matrícula
- CPF
- Data de nascimento
- Endereço Completo
- Contatos
- Formação Acadêmica
- Botões para Upload de documentos
- Campo de texto para informações adicionais
- Botão para Salvar
- Botão para Cancelar
- Botão para retornar ao menu principal
- 
### Cadastro de Fornecedores
- Razão Social
- CNPJ
- Endereço Completo
- Contatos
- Botões clicáveis para ramos de atividades
- Nome completo do representante legal
- CPF do Representante Legal
- Botões para Upload de documentos
- Espaço digitável para assinaturas digital ou eletrônica
- Botão para Salvar
- Botão para Cancelar
- Botão para retornar ao menu principal
- 
## Protótipos
![Cadastro de Pessoa Física](https://miro.com/app/board/uXjVLDNtiZw=/) 
![Cadastro de Pessoa Jurídica](https://miro.com/app/board/uXjVLDNtiZw=)
![Cadastro de Professores](https://miro.com/app/board/uXjVLDNtiZw=/)
![Cadastro de Fornecedores](https://miro.com/app/board/uXjVLDNtiZw=/)
![Cadastro de Alunos](]https://miro.com/app/board/uXjVLDNtiZw=/)
![ADS - PI-Protótipo_Sistema_Gestão_Universidade](https://github.com/user-attachments/assets/ccec48a3-6329-48b5-8a59-69fff7efb739)

## Diagrama UML
[Links para diagramas]





# Sistema de Gestão de Dados da Universidade

## Descrição
Este projeto é um sistema de gestão de dados desenvolvido para uma grande universidade. Ele permite o cadastro e gerenciamento de diferentes tipos de pessoas que interagem com o sistema, como alunos, professores, fornecedores, entre outros.

## Funcionalidades
- Cadastro de Pessoa Física
- Cadastro de Pessoa Jurídica
- Cadastro de Professores
- Cadastro de Fornecedores
- Cadastro de Alunos

## Diagrama de Caso de Uso
![Diagrama de Caso de Uso](url_para_diagrama_de_caso_de_uso.png)

## Descrição dos Casos de Uso
### Cadastro de Pessoa Física
**Ator Principal:** Usuário

**Pré-condição:** Usuário autenticado no sistema

**Cenário Principal:**
1. Usuário seleciona a opção "Cadastro de Pessoa Física"
2. Sistema exibe formulário de cadastro
3. Usuário preenche os dados
4. Usuário confirma o cadastro
5. Sistema salva os dados e exibe confirmação

**Cenário Alternativo 1:** Dados Incompletos
- Usuário não preenche todos os campos obrigatórios
- Sistema exibe mensagem de erro

**Cenário Alternativo 2:** Dados Inválidos
- Usuário preenche campos com dados inválidos
- Sistema exibe mensagem de erro

... (repetir estrutura para os demais casos de uso)

## Diagrama de Classe
![Diagrama de Classe](url_para_diagrama_de_classe.png)

## Protótipo da Interface
Os protótipos das interfaces foram desenvolvidos usando [Figma](https://www.figma.com/). Abaixo estão as jornadas de usuário:

- [Cadastro de Pessoa Física](url_para_prototipo_pessoa_fisica)
- [Cadastro de Pessoa Jurídica](url_para_prototipo_pessoa_juridica)
- [Cadastro de Professores](url_para_prototipo_professores)
- [Cadastro de Fornecedores](url_para_prototipo_fornecedores)
- [Cadastro de Alunos](url_para_prototipo_alunos)

## Como Contribuir
1. Crie uma conta no GitHub
2. Faça um fork do projeto
3. Crie uma branch para sua feature (`git checkout -b feature/fooBar`)
4. Commit suas mudanças (`git commit -am 'Add some fooBar'`)
5. Push para a branch (`git push origin feature/fooBar`)
6. Crie um novo Pull Request

## Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
