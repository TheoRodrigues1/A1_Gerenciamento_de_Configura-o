# RELATÓRIO DE ATIVIDADE PRÁTICA
## Gestão de Configuração de Software

---

# CAPA

## ANHANGUERA EDUCACIONAL

### Análise e Desenvolvimento de Sistemas

---

#### **GESTÃO DE CONFIGURAÇÃO DE SOFTWARE**
#### Evidência de Prática

Aluno: **Theo Fernandes Rodrigues**  
Matrícula: **2025473623**

Fevereiro de 2026

---

# FOLHA DE ROSTO

**INSTITUIÇÃO:** Anhanguera Educacional

**DISCIPLINA:** Análise e Desenvolvimento de Sistemas

**ALUNO:** Theo Fernandes Rodrigues

**MATRÍCULA:** 2025473623

**ATIVIDADE:** Gestão de Configuração e Versionamento de Artefatos

**DATA DE EXECUÇÃO:** 22 de fevereiro de 2026

**SEMESTRE:** (Consulte seu portal)

**TURMA:** (Consulte seu portal)

---

# INTRODUÇÃO

Esta atividade prática demonstra a aplicação de competências em gestão de configuração de software, utilizando Git como ferramenta de versionamento. O exercício abrange desde a iniciação de um repositório local até a criação, documentação e rastreamento de artefatos de um projeto de software.

---

# OBJETIVOS

1. Demonstrar competência na implementação de gestão de configuração
2. Explicar como gestão de configuração contribui para confiabilidade
3. Justificar a importância de ferramentas de gestão em ambientes profissionais
4. Criar e versionaracrifatos de um projeto
5. Registrar histórico completo de alterações

---

# COMPETÊNCIAS DESENVOLVIDAS

## 1. Confiabilidade através da Gestão de Configuração

### Rastreabilidade Completa
- Cada alteração é registrada com autor, data e motivação
- Possibilita auditoria completa do projeto
- Facilita identificação de quando e por quem foi feita cada mudança

### Integridade dos Artefatos
- Todos os membros trabalham com versões consistentes
- Controle automático de conflitos
- Garante sincronização entre equipe

### Recuperação de Falhas
- Possibilidade de reverter para versões anteriores
- Minimiza impacto de erros
- Oferece "ponto de repouso" em cada commit

### Documentação Automática
- Commits servem como registro de mudanças
- Histórico do projeto fica documentado automaticamente
- Facilita onboarding de novos membros

### Colaboração Eficiente
- Múltiplos desenvolvedores sem sobrescrita de trabalho
- Branches permitem trabalho paralelo
- Merge automático quando possível

### Confiança na Entrega
- Tags para versões específicas
- Rastreabilidade de cada release
- Reproduzibilidade garantida

### Redução de Riscos
- Backup automático em repositório remoto
- Minimiza risco de perda de código
- Detecção rápida de problemas

## 2. Importância de Ferramentas em Ambientes Reais

### Escalabilidade
- Suporta equipes grandes (10-1000+ pessoas)
- Coordena trabalho sem caos
- Estrutura para crescimento

### Conformidade Regulatória
- Satisfaz requisitos legais (LGPD, HIPAA, SOX)
- Auditoria completa para verificadores
- Evidência de conformidade comprovável

### Qualidade de Software
- Integração contínua (CI) automatizada
- Testes automáticos em cada commit
- Feedback rápido de problemas

### Gestão de Releases
- Mantém múltiplas versões em produção
- Hotfixes sem afetar desenvolvimento
- Rollback rápido se necessário

### Conhecimento Distribuído
- Reduz dependência de uma pessoa
- Código documentado no histórico
- Onboarding mais rápido

### Automação
- CI/CD pipelines
- Deploys automáticos
- Testes contínuos

### Backup e Redundância
- Repositórios remotos como backup
- Recuperação em desastres
- Replicação geográfica possível

### Segurança
- Controle de acesso granular
- Rastreamento de quem fez o quê
- Proteção contra alterações não autorizadas

---

# EVIDÊNCIA PRÁTICA

## Passo 1: Inicialização do Repositório Git

### Comando Executado:
```
git init
```

### Resultado:
```
Initialized empty Git repository in C:/Users/THEO/Desktop/Gerenciamento de proje
tos (trabalho)/.git/
```

**[INSERIR SCREENSHOT AQUI]**

---

## Passo 2: Configuração de Identidade

### Comandos Executados:
```
git config user.name "Desenvolvedor Projeto"
git config user.email "dev@projeto.local"
```

**[INSERIR SCREENSHOT AQUI]**

---

## Passo 3: Criação de Artefatos

### Arquivos Criados:
- README.md - Documentação geral
- DOCUMENTACAO.md - Documentação detalhada
- RESUMO_EXECUTIVO.md - Resumo executivo
- CHECKLIST.md - Checklist de atividades
- artefatos/requisitos.txt - Requisitos funcionais
- artefatos/arquitetura.txt - Arquitetura do sistema
- artefatos/plano_teste.txt - Plano de testes
- .gitignore - Configurações de exclusão

**[INSERIR SCREENSHOT AQUI - Listagem de arquivos]**

---

## Passo 4: Primeiro Commit

### Comando Executado:
```
git add .
git commit -m "Commit inicial: Documentação e artefatos do projeto de gestão de configuração"
```

### Resultado:
```
[master 326b1b7] Commit inicial: Documentação e artefatos do projeto de gestão de configuração
```

**[INSERIR SCREENSHOT AQUI]**

---

## Passo 5: Adição de .gitignore

### Arquivo Criado: `.gitignore`

### Commit:
```
git commit -m "Adicionar arquivo .gitignore com padrões de exclusão"
[master de36663] Adicionar arquivo .gitignore com padrões de exclusão
```

**[INSERIR SCREENSHOT AQUI]**

---

## Passo 6: Checklist de Conclusão

### Arquivo Criado: `CHECKLIST.md`

### Commit:
```
git commit -m "Adicionar CHECKLIST com status completo da atividade"
[master ab42055] Adicionar CHECKLIST com status completo da atividade
```

**[INSERIR SCREENSHOT AQUI]**

---

## Passo 7: Resumo Executivo

### Arquivo Criado: `RESUMO_EXECUTIVO.md`

### Commit:
```
git commit -m "Adicionar resumo executivo do projeto com todas as competências demonstradas"
[master 63a233b] Adicionar resumo executivo do projeto com todas as competências
```

**[INSERIR SCREENSHOT AQUI]**

---

## Passo 8: Histórico de Commits

### Comando Executado:
```
git log --oneline
```

### Resultado:
```
63a233b (HEAD -> master) Adicionar resumo executivo do projeto com todas as competências demonstradas
ab42055 Adicionar CHECKLIST com status completo da atividade
de36663 Adicionar arquivo .gitignore com padrões de exclusão
326b1b7 Commit inicial: Documentação e artefatos do projeto de gestão de configuração
```

**[INSERIR SCREENSHOT AQUI - Histórico completo]**

---

## Passo 9: Status do Repositório

### Comando Executado:
```
git status
```

### Resultado:
```
On branch master
nothing to commit, working tree clean
```

**[INSERIR SCREENSHOT AQUI]**

---

# CHECKLIST DE EXECUÇÃO

- [x] Projeto criado no ambiente local com sucesso
- [x] Repositório Git inicializado
- [x] Identidade do desenvolvedor configurada
- [x] Artefatos criados (7 arquivos + .gitignore)
- [x] Commits realizados com mensagens descritivas (4 commits)
- [x] Documentação completa fornecida
- [x] Questões teóricas respondidas (2 questões)
- [x] Boas práticas implementadas (.gitignore)
- [x] Histórico de mudanças rastreável
- [x] Projeto pronto para entrega

---

# ESTRUTURA FINAL DO PROJETO

```
Gerenciamento de projetos (trabalho)/
├── README.md
├── DOCUMENTACAO.md
├── CHECKLIST.md
├── RESUMO_EXECUTIVO.md
├── .gitignore
├── artefatos/
│   ├── requisitos.txt
│   ├── arquitetura.txt
│   └── plano_teste.txt
└── .git/ (repositório local)
```

---

# ESTATÍSTICAS

| Métrica | Valor |
|---------|-------|
| Total de Commits | 4 |
| Arquivos Rastreados | 8 |
| Branches | 1 (master) |
| Data de Criação | 22/02/2026 |
| Tamanho Repositório | ~10 KB |

---

# REFERÊNCIAS BIBLIOGRÁFICAS

1. **GIT DOCUMENTATION.** Git Official Documentation. Disponível em: <https://git-scm.com/doc>. Acesso em: 22 fev. 2026.

2. **CHACON, S.; STRAUB, B.** Pro Git. 2. ed. Apress, 2014. Disponível em: <https://git-scm.com/book/en/v2>. Acesso em: 22 fev. 2026.

3. **ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS (ABNT).** NBR ISO/IEC/IEEE 42010:2011 - Sistemas e software de engenharia - Representação e descrição da arquitetura. Rio de Janeiro: ABNT, 2011.

4. **SOMMERVILLE, I.** Engenharia de Software. 10. ed. São Paulo: Pearson, 2018.

5. **PRESSMAN, R. S.** Software Engineering: A Practitioner's Approach. 9. ed. New York: McGraw-Hill, 2019.

6. **BECK, K.** Extreme Programming Explained: Embrace Change. 2. ed. Boston: Addison-Wesley, 2004.

7. **FOWLER, M.** Continuous Integration. Disponível em: <https://martinfowler.com/articles/continuousIntegration.html>. Acesso em: 22 fev. 2026.

---

# CONCLUSÃO

Esta atividade prática demonstrou com sucesso a implementação de gestão de configuração utilizando Git. Foram criados 4 commits com mensagens descritivas, 8 arquivos foram versionados e documentados, e todo o histórico de alterações foi rastreado conforme os requisitos da disciplina.

A prática reforçou a importância de ferramentas de gestão de configuração em ambientes reais e como elas contribuem para a confiabilidade, qualidade e organização de projetos de software.

---

**Data de Conclusão:** 22 de fevereiro de 2026

**Assinatura do Aluno:** ________________________

