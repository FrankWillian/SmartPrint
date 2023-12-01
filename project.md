# Meu Projeto C++

Este é um projeto C++ que utiliza o CMake para facilitar a construção e organização.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

- **src**: Contém os arquivos de código-fonte do projeto.
- **include**: Contém os arquivos de cabeçalho do projeto.
- **tests**: Contém os arquivos de teste.

## Configuração do CMake

O arquivo `CMakeLists.txt` configura o ambiente de compilação e construção do projeto. As principais configurações incluem:

- Configuração do compilador C++ para usar o padrão C++17.
- Definição dos diretórios de origem, inclusão e teste.
- Configuração dos arquivos fonte.
- Adição do executável principal (`MeuProjetoCpp`).
- Configuração do Google Test para teste.

## Executando o Projeto

Para construir e executar o projeto, você pode seguir os passos:

1. Abra um terminal no diretório do projeto.
2. Execute os seguintes comandos:

   ```bash
   mkdir build
   cd build
   cmake ..
   make
