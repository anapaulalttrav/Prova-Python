#  Auditor de Diretórios Python — Manutenção de Código Legado

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![Nível](https://img.shields.io/badge/Nível-Intermediário-yellow?style=for-the-badge)

---

##  Sobre o Projeto

Sistema de auditoria de arquivos desenvolvido em **Python**, responsável por percorrer recursivamente a estrutura de diretórios de um projeto, contabilizar arquivos, calcular o tamanho total, identificar o maior arquivo e gerar relatórios e logs de execução.

### 🎯 Contexto da Atividade

Este projeto foi entregue como **código legado com bugs intencionais**, simulando um cenário real do mercado de trabalho: um sistema que "funciona" (não quebra), mas entrega **resultados incorretos**. O objetivo foi realizar a **investigação, diagnóstico e correção cirúrgica** dos problemas, **sem reescrever o sistema do zero** — uma prática essencial no dia a dia de qualquer desenvolvedor.

> *"A execução do programa sem apresentar uma exceção não significa necessariamente que os resultados estejam corretos."*
> — Enunciado da atividade

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função |
|------------|--------|
| **Python 3.x** | Linguagem principal |
| **`os`** | Manipulação de caminhos, diretórios e arquivos |
| **`logging`** | Registro de eventos, etapas e erros da execução |
| **`os.walk()`** | Percorrer recursivamente a árvore de diretórios |
| **`os.path.getsize()`** | Obtenção do tamanho de arquivos em bytes |
| **`os.makedirs()`** | Criação segura de diretórios |
| **VS Code** | IDE com debugger integrado |

---

## 🚀 Como Executar

### Pré-requisitos
- Python 3.x instalado
- VS Code (ou outra IDE de sua preferência)

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone <url-do-seu-repositorio>
   cd Prova-Python
