# Laboratório 02
## Aluno: Lucas Hervatin Trinquinato

Esse repositório contém as atividades:
1. Tarefa sobre catálogo de componentes
2. Tarefa Web Components 1
3. Tarefa Web Components 2

# Tarefa Web Components 1
```html
<dcc-trigger label="Mundo" action="message/mundo/politica" value="Notícia Mundo Política"></dcc-trigger>
<dcc-trigger label="Brasil P" action="message/brasil/politica" value="Notícia Brasil Política"></dcc-trigger>
<dcc-trigger label="Brasil E" action="message/brasil/esporte" value="Notícia Brasil Esporte"></dcc-trigger>
<dcc-trigger label="Bahia" action="message/bahia/esporte" value="Notícia Bahia Esporte"></dcc-trigger>

<dcc-lively-talk duration="0" character="doctor" speech="">
    <subscribe-dcc topic="message/+/politica"></subscribe-dcc>
</dcc-lively-talk>
<dcc-lively-talk duration="0" character="nurse" speech="">
    <subscribe-dcc topic="message/brasil/#"></subscribe-dcc>
</dcc-lively-talk>
<dcc-lively-talk duration="0" character="patient" speech="">
    <subscribe-dcc topic="message/#"></subscribe-dcc>
</dcc-lively-talk>
```

# Tarefa Web Components 2
