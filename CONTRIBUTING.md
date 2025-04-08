# Contribuyendo a rust-analyzer

¡Gracias por tu interés en contribuir a rust-analyzer! Hay muchas maneras de contribuir
y las apreciamos todas y cada una.

*Si deseas contribuir una nueva característica a rust-analyzer, visita el [repositorio oficial](https://github.com/rust-lang/rust-analyzer).*
Este repositorio son únicamente traducciones al idioma español sobre las características
que provienen de rust-analyzer.

Para obtener una vista por encima sobre la estructura y los crates en este repositorio hecha un vistazo a
la sección del manual [Contributing (inglés)](https://rust-analyzer.github.io/book/contributing).

Si tienes cualquier pregunta relacionada con rust-analyzer, por favor, pregunta en [rust-analyzer Zulip stream](
https://rust-lang.zulipchat.com/#narrow/stream/185405-t-compiler.2Frust-analyzer) en caso de no
estar seguro sobre donde empezar cuando estés trabajando en una issue concreta, escribe un
comentario con la issue relacionada para mentoría (las discusiones generales es recomendado que
pasen en Zulip).


## Arreglando un bug o mejorando una característica

Generalmente, está bien si simplemente trabajas en este tipo de cosas y abres una pull-request para
ello. Si hay alguna issue acompañando tu solución, asegúrate de adjuntarla en la descripción de la
pull-request para que sea cerrada posteriormente o simplemente adjuntada para contexto

Si quieres buscar algo que arreglar o algo en lo que trabajar, busca las etiquetas `C-bug` y
`C-enchancement` en el [repositorio oficial](https://github.com/rust-lang/rust-analyzer).



## Implementando una nueva característica

Es recomendado que primero abras una issue, para cualquier tipo de nueva característica, de este
modo el equipo puede decirte de primeras si la característica es deseada o no, antes de que
cualquier trabajo de implementación suceda. Queremos minimizar la posibilidad de que alguien ponga
mucho trabajo en una característica muy grande, y que luego la designemos como que no se alinea
con el repositorio (generalmente porque la característica no tiene nada que ver con rust-analyzer o
porque no tenemos los recursos para mantener esta). Si ya hay una issue abierta describiendo lo que
deseas implementar, ¡Escribe un comentario allí y pregunta!
