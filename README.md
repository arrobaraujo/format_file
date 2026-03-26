# format_file

<!-- badges: start -->
<!-- badges: end -->

O `format_file` é um aplicativo interativo (Shiny) projetado para facilitar a renomeação de arquivos em lote, permitindo adicionar prefixos e sufixos de forma rápida e segura com pré-visualização em tempo real.

## 🚀 Funcionalidades

- **Seleção de Diretório**: Navegue e escolha a pasta que contém os arquivos.
- **Seleção Flexível**: Selecione arquivos individuais, use "Selecionar todos" ou "Limpar seleção".
- **Prefixos e Sufixos**: Adicione textos personalizados no início ou no fim dos nomes dos arquivos.
- **Pré-visualização**: Veja como os nomes ficarão antes de aplicar as mudanças.
- **Segurança**: O app verifica se o novo nome já existe para evitar a sobrescrita acidental de arquivos.

## 🛠️ Pré-requisitos

Para rodar este projeto, você precisará do R instalado e dos seguintes pacotes:

```R
install.packages(c("shiny", "shinyFiles", "dplyr", "tibble"))
```

## 💻 Como Usar

Para iniciar o aplicativo, execute o seguinte comando no seu console do R:

```R
shiny::runApp("codigos/app.R")
```

Ou, se preferir, abra o arquivo `codigos/app.R` no RStudio e clique no botão **"Run App"**.

## 📁 Estrutura do Projeto

- `codigos/app.R`: Script principal contendo a interface do usuário (UI) e a lógica do servidor.
- `README.md`: Documentação do projeto.
- `format_file.Rproj`: Arquivo de projeto do RStudio.
