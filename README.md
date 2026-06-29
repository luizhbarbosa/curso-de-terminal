#  Curso de Terminal — Módulo 1: Fundamentos

Material de apoio do curso de terminal para iniciantes, com foco no ambiente **Windows (PowerShell)**.

---

##  Conteúdo do Módulo

| Capítulo | Tema | Comandos |
|----------|------|----------|
| 1 | O que é o Terminal? | — |
| 2 | Navegação Básica | `pwd` `ls` `cd` |
| 3 | Criando Coisas | `mkdir` `New-Item` |
| 4 | Gerenciando Arquivos | `cp` `mv` `rm` |
| 5 | Lendo Arquivos | `cat` `Get-Content` |

---

##  Como usar

Não é necessário instalar nada. Basta abrir o **PowerShell** no Windows:

```
Win + R → powershell → Enter
```

---

##  Referência Rápida

```powershell
# Navegação
pwd                         # Onde estou?
ls                          # Ver arquivos e pastas
cd nome_da_pasta            # Entrar em uma pasta
cd ..                       # Voltar uma pasta
cd ~                        # Ir para a pasta do usuário

# Criando
mkdir nome_da_pasta         # Criar pasta
New-Item arquivo.txt        # Criar arquivo

# Gerenciando
cp origem destino           # Copiar arquivo
mv origem destino           # Mover ou renomear
rm arquivo.txt              # Remover arquivo
rm -r nome_da_pasta         # Remover pasta (cuidado!)

# Lendo
cat arquivo.txt             # Ver conteúdo completo
Get-Content arq.txt -Head 10  # Ver primeiras 10 linhas
Get-Content arq.txt -Tail 10  # Ver últimas 10 linhas
```

---

##  Arquivos do Repositório

```
 curso-terminal
 ┣  README.md
 ┗  curso.html   ← guia completo com exemplos e exercícios
```

---

##  Aviso importante

> Arquivos removidos com `rm` no terminal **não vão para a Lixeira** — são excluídos permanentemente. Use com cuidado!

---

##  Ambiente

- **Sistema:** Windows 10 / 11
- **Shell:** PowerShell
- **Nível:** Iniciante
