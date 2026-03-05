# Proposta de Projeto - Cluster IA (SENAI)

Este repositório contém a documentação técnica e propostas de parceria para o projeto de **Cluster de IA**, desenvolvidos utilizando o sistema de tipografia LaTeX.

## Pré-requisitos

Antes de iniciar, você precisará instalar as seguintes ferramentas em seu ambiente:

| Ferramenta | Descrição | Link de Download |
|------------|-----------|-----------------|
| **Git** | Controle de versão | [git-scm.com](https://git-scm.com) |
| **Perl** | Necessário para scripts de automação do LaTeX | [strawberryperl.com](https://strawberryperl.com) |
| **MiKTeX** | Distribuição LaTeX (compilador e pacotes) | [miktex.org](https://miktex.org) |

## Configuração das Variáveis de Ambiente (PATH)

Para que o compilador funcione corretamente via terminal ou VS Code, adicione os seguintes caminhos à variável `PATH` do seu usuário (substituindo `<DIR_INSTALACAO>` pelo local onde você instalou cada programa):

- `<DIR_INSTALACAO>\git\bin`
- `<DIR_INSTALACAO>\miktex\bin\x64`
- `<DIR_INSTALACAO>\perl\bin`

## Como Gerar o PDF

Siga os passos abaixo para clonar o projeto e compilar os documentos:

### 1. Clonar o Repositório

Abra o seu terminal e execute:

```bash
git clone git@github.com:batistabjs/senai-proj-cluster-ia.git
```

### 2. Configurar o VS Code

1. Abra a pasta clonada no VS Code.
2. Instale a extensão oficial **LaTeX Workshop**.
3. Certifique-se de que o MiKTeX está devidamente reconhecido.

### 3. Compilação

Abra um dos arquivos principais abaixo e utilize o comando de **Build** da extensão (geralmente `Ctrl+Alt+B` ou pelo ícone de "Play" no menu lateral do LaTeX):

- `senai-proposta-parceria-cluster-ia.tex`
- `senai-proposta-projeto-cluster-ia.tex`

## Customização de Dados

Para manter a padronização e facilitar a manutenção, as informações de autoria e nomes de instituições foram centralizadas.

> [!IMPORTANT]
> Caso precise alterar o autor, instituições ou datas nos PDFs gerados, modifique apenas as variáveis contidas no arquivo: `vars.tex`

## Estrutura do Projeto

```
.
├── vars.tex                              # Definições de variáveis globais
├── senai-proposta-parceria-...tex        # Documento focado em parcerias
└── senai-proposta-projeto-...tex         # Documento técnico do projeto
```
