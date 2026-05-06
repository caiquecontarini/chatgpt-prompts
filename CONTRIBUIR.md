# 🤝 Contribuindo para ChatGPT Prompts

Obrigado por querer melhorar esta biblioteca! Aqui estão as diretrizes.

---

## Como Contribuir

### 1. Adicionar um Novo Prompt

#### Template Padrão

```markdown
# [Nome do Prompt]

## 📝 Descrição
Uma linha: o que esse prompt faz?

## 🎯 Objetivo
Qual problema resolve? Para quem é?

## 📋 Prompt Completo

[Cole aqui TODO o texto do prompt]

## ✨ Exemplo de Uso

**Input:**
```
[Pergunta/contexto do usuário]
```

**Output:**
[Resposta do ChatGPT]
```

## 🔧 Como Customizar

- `[variável1]` → descrição
- `[variável2]` → descrição

## 💡 Dicas de Uso

- Melhor em novo chat
- Combine com [outro_prompt]
- Refine com feedback

## 📚 Inspiração & Referências

Links para artigos, documentação, etc.

## ✅ Tags

`#tag1` `#tag2` `#tag3`
```

---

### 2. Melhorar Existente

- Corrija typos/português
- Melhore clareza
- Adicione exemplos
- Normalize formatação

### 3. Relatar Problema

Se encontrou um prompt:
- ❌ Que não funciona
- ❌ Com erros de formatação
- ❌ Desatualizado

Abra uma **Issue** com:
- Qual prompt
- O que está errado
- Como deveria ser
- Screenshot se possível

---

## Padrões

### Nomes de Arquivo

```
01-personas/
  - dr-alex-black.txt
  - dr-data-pro.txt

02-educacao/planejamento/
  - eduPlanner.txt
  - eduPlanner-plus.txt

04-tecnologia/desenvolvimento/
  - codeXpert.txt
```

### Estrutura de Pastas

```
nova-categoria/
├── README.md (índice)
├── prompt-1.txt
├── prompt-2.txt
└── examples/
    ├── exemplo-1.md
    └── exemplo-2.txt
```

### Nomenclatura

- Use kebab-case: `meu-prompt.txt`
- Seja descritivo: `analise-whatsapp.txt` ✓
- Evite genérico: `prompt-novo.txt` ✗

---

## Processo de Submissão

### Via GitHub

1. **Fork** o repositório
2. Crie branch: `git checkout -b add/novo-prompt`
3. Adicione seu arquivo
4. Atualize o README se necessário
5. Commit: `git commit -m "Add: novo prompt de X"`
6. Push: `git push origin add/novo-prompt`
7. Abra **Pull Request** com descrição clara

### Via Issue

Não sabe usar Git? Abra uma issue com:
- Nome do prompt
- Categoria
- Conteúdo completo
- Por que vai ser útil

---

## Checklist para Submissão

Antes de enviar:

- [ ] Prompt foi testado no ChatGPT
- [ ] Formatação está clara
- [ ] Sem erros de português
- [ ] Tem exemplos de uso
- [ ] Tem instruções de customização
- [ ] Categoria está correta
- [ ] README foi atualizado

---

## Qualidade & Boas Práticas

### ✅ Faça

- Teste no ChatGPT antes
- Seja específico e prático
- Inclua exemplos reais
- Refatore para legibilidade
- Documenta bem
- Cite inspirações/referências

### ❌ Evite

- Prompts genéricos demais
- Sem exemplo de funcionamento
- Português ruim
- Cópia descarada sem créditos
- Prompts muito longos (use modular)

---

## Tipos de Contribuição

| Tipo | Exemplo | Prioridade |
|------|---------|-----------|
| **Novo Prompt Premium** | Persona nova | 🔴 Alta |
| **Melhoria Existente** | Typo, clareza | 🟡 Média |
| **Documentação** | Exemplos, guias | 🟢 Baixa |
| **Bug Report** | Prompt não funciona | 🔴 Alta |

---

## Após Aprovação

Seu prompt será:
- ✅ Revisado e testado
- ✅ Formatado conforme padrão
- ✅ Adicionado ao README
- ✅ Crédito seu no arquivo
- ✅ Publicado para comunidade

---

## Licença

Ao contribuir, você concorda:
- Seu código é MIT License
- Pode ser usado comercialmente
- Dará crédito original

---

## Dúvidas?

- 📧 Abra uma **Issue**
- 💬 Comentário no PR
- 🔗 Veja [README.md](./README.md)

---

<div align="center">

**Obrigado por contribuir!** 🙏

Toda contribuição, por menor que seja, ajuda a comunidade!

</div>
