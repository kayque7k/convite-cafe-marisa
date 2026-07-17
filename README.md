# Convite ☕ — o convite de café irrecusável

Um convite de café reutilizável (e ligeiramente irrecusável): o botão **"Não" foge** quando ela tenta tocar nele. Depois de 8 tentativas frustradas, ele se rende e vira um segundo "Sim". 😄

**No ar:** https://kayque7k.github.io/convite/

## Como usar

Monte o link com o nome dela (use `-` no lugar de espaço):

```
https://kayque7k.github.io/convite/?nome=Ana-Clara
```

Opcionalmente, adicione local e hora — revelados **só depois** do "Sim", como surpresa na "ata oficial" e na mensagem do WhatsApp:

```
https://kayque7k.github.io/convite/?nome=Ana-Clara&quando=sabado-as-15h-no-Cafe-Central
```

Preguiça de montar o link na mão? Abra a URL **sem parâmetros** e a **Central de Convites** monta o link para você, com botão de copiar e de testar:

```
https://kayque7k.github.io/convite/
```

## Características

- Página única, HTML/CSS/JS puros, zero dependências
- Mobile-first: o botão foge no toque (`touchstart`), nunca sai da área visível da tela
- Confete em canvas ao aceitar + confirmação direto no WhatsApp
- Nome e detalhes inseridos com segurança (sem injeção via URL)

— feito com ☕ pelo Kayque
