# 📋 GUIA: Como Gerar o PDF com Evidências

## 🖼️ Passo 1: Capturar Screenshots (Prints)

### Windows 10/11 - Ferramenta Nativa (Recomendado)

**Opção 1: Print Screen Completo**
1. Pressione `Print Screen` ou `PrtScn`
2. Abra Paint (`Windows + R` → digitue `mspaint` → Enter)
3. Cole (`Ctrl + V`)
4. Salve com nome descritivo

**Opção 2: Print Screen Selecionado (Melhor)**
1. Pressione `Windows + Shift + S`
2. Arraste para selecionar a área desejada
3. Clique em "Salvar" na notificação
4. Escolha pasta para salvar

**Opção 3: Ferramenta "Recorte"**
1. Abra: `Windows + Shift + U` ou procure "Ferramenta de Captura"
2. Clique em "Novo"
3. Selecione a área
4. Salve como imagem

### Mac
- **Cmd + Shift + 4** = seleção livre
- **Cmd + Shift + 5** = menu com opções

### Linux
- Print Screen ou utilize Gnome Screenshot

---

## 📸 Prints que Você Deve Capturar

### Essenciais:

1. **Terminal com `git init`**
   - Execute: `git init`
   - Capture o resultado

2. **Listagem de Arquivos**
   - Execute: `ls -la` (Linux/Mac) ou `dir` (Windows)
   - Capture a estrutura de pastas

3. **Primeiro Commit**
   - Execute: `git log --oneline`
   - Capture o histórico

4. **Status do Repositório**
   - Execute: `git status`
   - Capture o resultado

5. **Conteúdo de um Arquivo**
   - Abra: CHECKLIST.md ou README.md
   - Capture a tela mostrando o conteúdo

---

## 📝 Opções para Converter para PDF

### Opção 1️⃣: Microsoft Word (Mais Fácil)

**Passo a passo:**
1. Abra Microsoft Word
2. Crie um documento novo
3. Copie o conteúdo de `RELATORIO_PDF.md` para o Word
4. Insira as imagens (prints) nos locais marcados `[INSERIR SCREENSHOT AQUI]`
5. Formate conforme necessário
6. Clique em **Arquivo → Exportar → Criar PDF → Publicar**

---

### Opção 2️⃣: Google Docs (Gratuito)

**Passo a passo:**
1. Acesse https://docs.google.com
2. Crie um novo documento
3. Copie o conteúdo de `RELATORIO_PDF.md`
4. Insira imagens via **Inserir → Imagem → Fazer Upload**
5. Clique em **Arquivo → Baixar → PDF Document**

---

### Opção 3️⃣: LibreOffice (Gratuito)

**Passo a passo:**
1. Baixe LibreOffice em: https://www.libreoffice.org
2. Abra LibreOffice Writer
3. Copie o conteúdo de `RELATORIO_PDF.md`
4. Insira imagens e formate
5. Clique em **Arquivo → Exportar como PDF**

---

### Opção 4️⃣: Pandoc (Profissional)

**Para Windows:**
```powershell
# 1. Instale Pandoc
# Baixe em: https://pandoc.org/installing.html

# 2. Instale LaTeX
# Baixe MiKTeX em: https://miktex.org

# 3. Converta para PDF
pandoc RELATORIO_PDF.md -o relatorio.pdf
```

---

### Opção 5️⃣: Markdown to PDF Online (Instantâneo)

1. Acesse: https://md2pdf.netlify.app/
2. Cole o conteúdo de `RELATORIO_PDF.md`
3. Clique em "Download PDF"

---

## 📋 Checklist de Conteúdo do PDF Final

Antes de enviar, verifique se tem:

- [x] **Capa** com título e dados básicos
- [x] **Folha de Rosto** com disciplina, aluno, matrícula
- [x] **Objetivos** da atividade
- [x] **Respostas das 2 Questões:**
  - Questão 1: Confiabilidade
  - Questão 2: Importância em ambientes reais
- [x] **Evidências (Prints) do Exercício:**
  - Terminal mostrando `git init`
  - Listagem de arquivos criados
  - Histórico de commits (`git log`)
  - Status do repositório
- [x] **Checklist de Execução** (marcado como completo)
- [x] **Estrutura do Projeto** (organização final)
- [x] **Estatísticas do Repositório**
- [x] **Referências Bibliográficas**
- [x] **Conclusão**

---

## 🎨 Dicas de Formatação para o PDF

1. **Use espaçamento** entre seções
2. **Adicione cabeçalhos** (numerados)
3. **Coloque imagens em boa qualidade** (não pixeladas)
4. **Legenda em cada screenshot**
5. **Indentação adequada** para leitura fácil
6. **Fonte legível** (tamanho 11-12)

---

## ⚡ Método RÁPIDO (5 minutos)

**Se não tiver tempo:**

1. Abra Word / Google Docs
2. Copie e cole todo o conteúdo de `RELATORIO_PDF.md`
3. Tira prints da tela do terminal mostrando os comandos git
4. Insira 3-4 prints principais
5. Exporte como PDF

**Tempo total: ~5 minutos** ⏱️

---

## 🔗 Referência Rápida de Comandos Git

```bash
# Ver histórico
git log --oneline

# Ver status
git status

# Ver diferenças
git diff

# Ver detalhes de um commit
git show <hash-do-commit>

# Ver configuração local
git config --list
```

---

## 📞 Troubleshooting

**P: O Pandoc não está funcionando**
- R: Instale também o MiKTeX para suporte a PDF

**P: As imagens não aparecem no PDF**
- R: Certifique-se de que os caminhos das imagens estão corretos

**P: O arquivo fica muito grande**
- R: Comprima as imagens antes de inserir (Paint → Arquivo → Reduzir tamanho)

**P: Como adicionar número de página?**
- R: Faça no Word (Inserir → Número de Página) antes de exportar

---

## ✅ Você está pronto!

Agora você tem:
1. ✅ Documento modelo completo (`RELATORIO_PDF.md`)
2. ✅ Instruções para capturar screenshots
3. ✅ 5 opções diferentes para converter para PDF
4. ✅ Checklist do que incluir

**Escolha a opção mais fácil para você e gere o PDF!** 📄

