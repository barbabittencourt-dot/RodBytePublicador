---
carrossel: auditoria-skills-claude-code
data: 2026-08-30
handle: "@rodbyte"
---

# Legenda Instagram

Você instalou um monte de skill no Claude Code. Aposto que usa metade.

A oferta boa existe de sobra, entre repositórios oficiais e comunidade. O problema é outro: ninguém audita o que já está instalado. Skill que nunca dispara ocupa espaço no diretório e não muda uma linha do que o Claude entrega.

Cada skill custa cerca de 100 tokens de contexto até o Claude decidir que precisa dela. Isso é ótimo, dá pra ter cinquenta instaladas sem pesar. Também é o motivo de uma skill mal escrita nunca aparecer nos seus alertas: ela não trava, não dá erro, só fica ali ignorada porque a description não bate com o jeito que você pede as coisas.

A auditoria tem quatro passos:

1. Liste tudo que está instalado, pessoal e do projeto. A maioria nunca fez essa lista completa.
2. Teste cada uma com um pedido real que bata com a description. Se o resultado não muda, ela não está funcionando.
3. Para as que não dispararam, peça "evaluate my [nome da skill] skill with skill-creator". O diagnóstico sai em cima de dado, não de achismo.
4. Decida. Description vaga se reescreve com as palavras que você usaria de verdade. Se nem assim disparar, deleta.

Depois que sobrar só o que funciona, separe o que é seu do que é do time. Skill pessoal mora em ~/.claude/skills. Skill do time vai pra .claude/skills dentro do repositório, versionada junto com o código, e quem clona o projeto já herda tudo.

Salva esse post pra fazer sua auditoria no fim de semana.

Segue @rodbyte pra mais leituras e tutoriais sobre Claude Code e IA aplicada no dia a dia de quem programa. Toda semana tem post novo.

#claudecode #ia #inteligenciaartificial #devbrasil #produtividade #programacao #anthropic #vibecoding

## Notas

- Sem em-dash e sem itálico, mesma regra dos slides.
- A legenda repete o gancho da capa na primeira linha, porque o feed corta o resto.
- Os quatro passos aparecem numerados aqui para quem lê só a legenda, sem abrir o carrossel.
- Nenhum dado novo foi introduzido: os números (100 tokens, 25 skills) vêm do roteiro original.
