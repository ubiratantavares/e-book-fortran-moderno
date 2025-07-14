# 1.3 Filosofia do Livro

Este livro adota uma abordagem moderna, prática e orientada à produção de código limpo, robusto e portável. O foco está nas versões **Fortran 90/95**, estendendo-se às melhorias introduzidas no **Fortran 2003** e **2008**, com ênfase no estilo de programação que acompanha os padrões atuais da computação científica.

Embora o Fortran mantenha compatibilidade com versões antigas, muitos recursos do passado são considerados **obsoletos**, **redundantes** ou **removidos** nas normas mais recentes. O uso desses elementos em novos projetos é fortemente desencorajado neste livro.

A estratégia proposta enfatiza:

- O uso de `IMPLICIT NONE` para evitar erros silenciosos na declaração de variáveis.
- A substituição de blocos `COMMON` por **módulos** com controle explícito de visibilidade (`PUBLIC`, `PRIVATE`).
- A utilização de `DO ... END DO` em vez de `DO ... CONTINUE` para laços.
- A preferência por **procedimentos internos** ou modulares, no lugar de funções de declaração (`statement functions`).
- A prática da **tipagem explícita**, modularização e documentação do código.

O objetivo é promover um estilo de programação que seja não apenas funcional, mas também **sustentável**, **manutenível** e compatível com práticas modernas de desenvolvimento científico.

Ao centrar-se no “núcleo moderno” da linguagem, busca-se tornar o aprendizado mais claro, relevante e alinhado com os desafios computacionais contemporâneos.
