# Site — Lorrana O. Veloso, Advogada

## Como atualizar o site

### Alterar textos principais (nome, OAB, WhatsApp, email)
Abra o arquivo `_config.yml` e edite os valores na seção `advogada:`.

```yaml
advogada:
  nome: "Lorrana O. Veloso"
  whatsapp: "5573999502281"   # somente números, com DDI 55
  email: "lorrana.juridico95@gmail.com"
  frase: "Seu direito, defendido com ética e dedicação."
```

### Alterar textos do site (Sobre, Áreas, etc.)
Abra o arquivo `index.html` e edite os textos diretamente.

### Como publicar alterações
1. Acesse o repositório no GitHub
2. Clique no arquivo que quer editar
3. Clique no ícone de lápis (Edit)
4. Faça a alteração
5. Clique em **Commit changes**
6. O site atualiza automaticamente em 1-2 minutos

---

## Configuração inicial (feita uma vez pelo desenvolvedor)

1. Criar repositório no GitHub com nome: `lorranaveloso.github.io` (ou qualquer nome)
2. Fazer upload de todos esses arquivos
3. Em Settings > Pages > Source: selecionar `main` branch
4. O arquivo `CNAME` já aponta para `lorranaveloso.com.br`

### Apontar o domínio (no painel do registrador)
Adicionar os seguintes registros DNS:

**Tipo A — aponta para GitHub Pages:**
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**Tipo CNAME:**
```
www  →  seu-usuario.github.io
```

Aguardar propagação DNS (até 24h).
