
# ClinicApp

O ClinicApp é um aplicativo móvel desenvolvido para a gestão de clínicas, pacientes e médicos. Com ele, é possível realizar o cadastro e controle de informações importantes, como dados de pacientes, informações de clínicas e detalhes de médicos.

## Funcionalidades

  * **Gestão de Pacientes:**
      * Cadastro, edição e exclusão de pacientes.
      * Armazenamento de informações como nome, telefone, endereço, cidade, UF, convênio e status.
  * **Gestão de Clínicas:**
      * Cadastro, edição e exclusão de clínicas.
      * Armazenamento de informações como nome, endereço, cidade e UF.
  * **Gestão de Médicos:**
      * Cadastro, edição e exclusão de médicos.
      * Armazenamento de informações como nome, CRM, telefone, especialidades e status.
  * **Autenticação de Usuários:**
      * Sistema de login e cadastro de usuários.
      * Recuperação de senha por e-mail.

## Tecnologias Utilizadas

  * **Ionic:** Framework para desenvolvimento de aplicativos móveis híbridos.
  * **Angular:** Plataforma para a criação de aplicativos web.
  * **Firebase:** Plataforma da Google para o desenvolvimento de aplicativos, utilizada para:
      * **Realtime Database:** Armazenamento e sincronização de dados em tempo real.
      * **Authentication:** Autenticação de usuários.
  * **Cordova:** Plataforma para a criação de aplicativos móveis nativos utilizando tecnologias web.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

  * `src/app/`: Contém os arquivos principais da aplicação, como o módulo principal (`app.module.ts`), o componente principal (`app.component.ts`) e as configurações globais.
  * `src/pages/`: Contém as páginas da aplicação, cada uma com seu respectivo arquivo de template (`.html`), estilização (`.scss`) e lógica (`.ts`).
  * `src/providers/`: Contém os serviços responsáveis pela comunicação com o Firebase e outras APIs.
  * `src/models/`: Contém os modelos de dados da aplicação (Paciente, Clínica e Médico).

## Como Executar o Projeto

1. **Instale as dependências:**
    ```bash
    npm install
    ```
3.  **Execute o projeto em um navegador:**
    ```bash
    ionic serve
    ```
4.  **Para executar em um dispositivo móvel (Android):**
    ```bash
    ionic cordova platform add android
    ionic cordova run android
    ```

## Autores

  * Alice Facundo
