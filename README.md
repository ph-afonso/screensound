# Screen Sound 🎸

O **Screen Sound** é um programa desenvolvido em C# utilizando .NET 8 que permite o registro e avaliação de bandas musicais. Com ele, é possível adicionar bandas ao sistema, registrar notas para essas bandas e calcular a média das notas atribuídas a cada uma.

## Funcionalidades
1. **Registrar bandas**: Adicione novas bandas ao sistema.
2. **Registrar notas**: Insira notas para cada banda registrada.
3. **Calcular média de notas**: Retorne a média das notas de uma banda específica.

## Pré-requisitos

- [**.NET SDK 8**](https://dotnet.microsoft.com/download/dotnet/8.0) (ou superior) instalado em sua máquina.

---

## Como Baixar o Repositório

1. Abra o terminal ou prompt de comando.
2. Navegue até o diretório onde deseja baixar o repositório.
3. Execute o comando para clonar o repositório:
   ```bash
   git clone https://github.com/usuario/ScreenSound.git
   ```
   Substitua `https://github.com/usuario/ScreenSound.git` pela URL correta do repositório.

---

## Como Extrair o Projeto

1. Após clonar, entre na pasta do projeto:
   ```bash
   cd ScreenSound
   ```

---

## Como Executar o Programa

1. Certifique-se de estar no diretório raiz do projeto.
2. Compile o programa com o comando:
   ```bash
   dotnet build
   ```
   Isso irá compilar os arquivos necessários para a execução do programa.

3. Execute o programa com:
   ```bash
   dotnet run
   ```

---

## Como Usar o Programa

1. **Registrar Banda**: Ao iniciar, o programa oferece a opção de registrar o nome de uma nova banda.
2. **Adicionar Notas**: Após registrar uma banda, é possível inserir notas de 0 a 10 para cada uma.
3. **Calcular Média**: Escolha uma banda para visualizar a média das notas atribuídas.

---

## Exemplo de Uso

```plaintext
Bem-vindo ao Screen Sound!
Escolha uma opção:
1. Registrar Banda
2. Adicionar Nota para Banda
3. Calcular Média de Notas de uma Banda
4. Sair

Opção: 1
Digite o nome da banda: Queen
Banda "Queen" registrada com sucesso!

Opção: 2
Digite o nome da banda para adicionar uma nota: Queen
Digite a nota (0-10): 10
Nota adicionada com sucesso!

Opção: 3
Digite o nome da banda para calcular a média de notas: Queen
Média das notas da banda "Queen": 10.0
```

---

## Estrutura do Projeto

- **`Program.cs`**: Arquivo principal com a lógica de controle do programa.
- **`Band.cs`**: Classe que representa as bandas e armazena suas notas.

---

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir *issues* com sugestões ou enviar *pull requests* com melhorias e novas funcionalidades.

---

## Licença

Este projeto está sob a licença MIT.
