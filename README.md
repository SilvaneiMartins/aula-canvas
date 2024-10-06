<h1 align="center">
  Aula Canvas ChatGPT
</h1>

<h3 align="center">
  Login Screen - React Native
</h3>

## Informação do Projeto

Este projeto é uma tela de login simples desenvolvida com React Native, utilizando TypeScript. Ele inclui validação de email, verificação da força da senha, além de feedback visual e interações para uma melhor experiência do usuário.

## Funcionalidades

- Validação de email para garantir que o formato seja válido.
- Validação da força da senha, exigindo pelo menos 8 caracteres, incluindo letras maiúsculas, minúsculas e números.
- Feedback visual em tempo real para entrada inválida de email.
- Botão de login desativado até que todos os campos estejam preenchidos.
- Mensagens de erro amigáveis para guiar o usuário em caso de dados faltantes ou inválidos.

## Estrutura do Código

### Principais Componentes e Funções

- **LoginScreen**: Componente principal que renderiza a tela de login.
- **Estados**:
  - `email`, `password`, `emailError` - armazenam o valor do email, senha e mensagem de erro do email, respectivamente.
- **Funções**:
  - `handleLogin()`: Responsável por lidar com o fluxo de login, incluindo navegação para a próxima tela em caso de sucesso.
  - `validateInputs()`: Realiza a validação dos campos de email e senha, garantindo que estejam corretos antes de prosseguir.
  - `isValidEmail(email)`: Verifica se o email está no formato correto.
  - `isValidPassword(password)`: Verifica se a senha atende aos critérios de segurança estabelecidos.

### Melhorias Realizadas

- **Separação de Responsabilidades**: A função `handleLogin` foi refatorada para separar a lógica de validação (`validateInputs`) da lógica de autenticação. Isso melhora a legibilidade e a manutenção do código.
- **Sanitização do Input**: O email é sanitizado antes de ser exibido nos alertas para evitar possíveis problemas de segurança, como ataques de injeção.
- **Estilo do Botão Desativado**: Foi implementado um estilo separado para o botão de login quando ele está desativado, melhorando a consistência visual e a manutenção do código.

## Como Executar o Projeto

1. **Pré-requisitos**:
   - Node.js instalado.
   - Ambiente de desenvolvimento React Native configurado (CLI ou Expo).

2. **Instalar Dependências**:
   ```bash
   npm install
   yarn
   ```

3. **Executar o Projeto**:
   - Para usuários do Expo:
     ```bash
     expo start
     ```
   - Para usuários do React Native CLI:
     ```bash
     npx react-native run-android ou ou run-ios
     ```

## Estrutura do Arquivo

- **`LoginScreen.tsx`**: Componente principal que contém a lógica de login e a interface do usuário.
- **`styles`**: Estilização para os componentes da tela, incluindo cores e layouts.

## Melhorias Futuras

- **Integração com Backend**: Integrar com uma API para autenticar o usuário em um backend.
- **Recuperação de Senha**: Adicionar funcionalidade para recuperar a senha.
- **Tratamento de Erros**: Melhorar o tratamento de erros para lidar com falhas na comunicação com o servidor.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorar o projeto.

## Licença

Este projeto é licenciado sob [CC0 1.0 Universal]. Consulte o arquivo [LICENSE](https://github.com/SilvaneiMartins/aula-canvas/blob/master/LICENSE) para obter detalhes.

## Informações do desenvolvedor

<a href="https://github.com/SilvaneiMartins">
    <img
        style="border-radius:50%"
        src="https://github.com/SilvaneiMartins.png"
        width="100px;"
        alt="Silvanei Martins"
    />
    <br />
    <sub>
        <b>Silvanei de Almeida Martins</b>
    </sub>
</a>
     <a href="https://github.com/SilvaneiMartins" title="Silvanei martins" >
 </a>
<br />
🚀 Feito com ❤️ por Silvanei Martins
