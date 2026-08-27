# Gerador de Assinatura de E-mail — COMURG

Página web simples para gerar assinaturas de e-mail padronizadas da COMURG. A pessoa preenche seus dados, vê uma pré-visualização em tempo real e copia o código pronto para colar no editor de assinatura do cliente de e-mail (Umbler, Gmail, Outlook, etc).

🔗 **Acesse:** https://josesilva422.github.io/geracao_assinatura_email_comurg/

## Funcionalidades

- Formulário com Nome, Cargo | Função, Local de Trabalho e Telefone
- Máscara automática no campo de telefone, no padrão `(xx) x xxxx-xxxx`
- Pré-visualização da assinatura atualizada em tempo real
- Botão **Copiar código HTML** — copia o código-fonte da assinatura, para colar no editor `<>` do Umbler
- Botão **Copiar assinatura** — copia a assinatura já formatada (HTML rico), para colar direto em campos de assinatura que aceitam texto formatado
- Visual baseado nas cores institucionais da COMURG

## Como usar (Umbler)

1. Preencha seus dados na página e clique em **"Copiar código HTML"**.
2. No Umbler, clique na **engrenagem** de configuração.
3. Vá em **Assinaturas** → **Nova Assinatura**.
4. Clique no **"+"** e depois no ícone **"<>"**.
5. Cole o código HTML copiado (Ctrl+V).
6. Clique novamente em **"<>"** para ver como ficou.
7. Clique em **Salvar** e depois em **Salvar** novamente, na parte superior.

Pronto — assinatura configurada.

## Desenvolvimento

O projeto é uma única página estática (`index.html`), sem dependências ou build. Para testar localmente, basta abrir o arquivo no navegador ou servir a pasta com qualquer servidor HTTP simples:

```bash
python3 -m http.server 8000
```

Publicado via GitHub Pages a partir da branch `main`.

## Licença

Distribuído sob a licença MIT — veja [LICENSE](LICENSE).
