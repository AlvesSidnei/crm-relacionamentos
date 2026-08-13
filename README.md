# 📊 CRM de Relacionamentos

CRM pessoal para rastrear leads por indicação e relacionamentos.

## 📁 Estrutura

- **pessoas/** - Contatos individuais (ex: Clóvis Faé)
- **empresas/** - Empresas e parceiros (ex: Raimonde, Globo Sul)
- **indicacoes/** - Oportunidades/leads ativos
- **templates/** - Modelos para copiar

## 🚀 Como usar

### Ao receber uma indicação:

1. Crie a nota da **pessoa** em `pessoas/nome-pessoa.md`
2. Crie/atualize a nota da **empresa** em `empresas/nome-empresa.md`
3. Crie a nota da **indicação** em `indicacoes/data-nome.md`
4. Use **links** `[[Nome]]` para conectar tudo

### Exemplo:
Raimondi indicou Clóvis → Crie:

pessoas/clovis-fae.md

empresas/raimonde-artefatos.md

indicacoes/2026-08-11-clóvis-raimonde.md

## 📝 Templates

Copie e use os templates:

- [Template de Pessoa](pessoas/template-pessoa.md)
- [Template de Empresa](empresas/template-empresa.md)
- [Template de Indicação](indicacoes/template-indicacao.md)

## 🔍 Como buscar

- Para ver todas as indicações de uma empresa: busque por `[[Nome da Empresa]]`
- Para ver todos os leads: busque por `status: lead`

---

*Última atualização: 2026-08-13*
