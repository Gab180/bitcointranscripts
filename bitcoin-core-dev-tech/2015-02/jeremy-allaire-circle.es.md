---
title: Charla de los fundadores de Circle
transcript_by: Bryan Bishop
translation_by: Blue Moon
categories: ['core-dev-tech']
speakers: ['Jeremy Allaire', 'Sean Neville']
---

Estamos encantados de estar aquí y de patrocinar este evento. Nuestra experiencia en herramientas para desarrolladores se remonta a los primeros días de algo.

¿Cómo maduramos el desarrollo del propio Bitcoin Core? Una de las cosas útiles es identificar los componentes clave. En un estándar tienes una especificación, podría ser un libro blanco, y luego tienes una implementación de referencia, y luego un conjunto de pruebas que hace cumplir la interoperabilidad. El conjunto de pruebas es lo que hace cumplir la norma. No es el texto del libro blanco el que dice cuál es el estándar... Si hay alguien que puede satisfacer cuántos cientos de miles de pruebas, si puede escribir software que pueda satisfacer estas pruebas ha escrito una implementación interoperable. El código C++ existente, está el libro blanco de Satoshi, pero realmente el código fuente en sí mismo es la especificación. La RI es importante. Están explícitamente vinculadas. No estoy hablando de pruebas de certificación o de marca o de licencias... si alguien estuviera lo suficientemente loco como para reimplementar este libro mayor y el conjunto de protocolos, que sea realmente interoperable con lo que se ha construido en Bitcoin Core, no hay un conjunto de pruebas para eso hoy en día... ¿Cómo maduramos el proceso? Si yo fuera un desarrollador, ¿cuál sería el primer pull request que podría enviar? Empezaría por el área de pruebas. Y entonces lo haría con el pensamiento de que en última instancia lo que tiene que suceder es que debe haber algún tipo de conjunto de pruebas que garantice que cuando se introducen nuevas variaciones que hay acuerdo en que lo que el interop parece. Y entonces eso permite que otras personas se conecten al proceso, no hay un gran comité que se reúna, no hay empresas de software gigantes que tengan voz, es más una meritocracia que creo que está bien hasta hoy, pero a veces cuando los proyectos maduran se hace difícil para las personas que no necesariamente encajan dentro de esa cultura de comunicación en esta lista de correo electrónico dev particular o en el IRC, las personas que no tienen nada que añadir realmente no encajan en el desarrollo de software. Así que se trata más bien de cómo atraer a la gente a este sistema, cómo hacer que las empresas de software entren en él. ¿Cuál es el formato adecuado sin complicarnos demasiado? ¿Cómo permitimos que la gente se conecte a este sistema? ¿Cómo facilitamos que la gente escriba código e innove en lo que estamos construyendo colectivamente?

"Confianza"... ¿qué implica eso? ¿Existe una diferencia generacional en la forma de pensar sobre esta tecnología? ¿En qué deben confiar las partes interesadas institucionales tradicionales para integrar las industrias establecidas con esta tecnología? ¿Cómo concebimos la rendición de cuentas, que forma parte de la confianza, con el tipo de partes interesadas que participan en las capas de infraestructura de Bitcoin y la cadena de bloques? Nuestro mercado objetivo confía intrínsecamente en la tecnología de Internet. Que puede hacer cualquier cosa. Las generaciones mayores no tienen esa confianza. Desconfían de esas facetas. Realmente da mucho juego. El público más joven asume la conectividad instantánea. Lo consideran un bien público. La gente que ha estado dirigiendo intermediarios tiene la reacción contraria. Interactuamos con banqueros, auditores, contables, abogados, reguladores, ¿quién más es grande y da miedo? Esos son los grandes tipos que dan miedo. Sólo la idea de utilizar matemáticas y algoritmos frente a utilizar personas es realmente difícil para estas instituciones. Si damos un paso atrás, están estas industrias fiduciarias que se construyeron sobre el control de los derechos para hacer entradas en los libros de contabilidad, intermediando el acceso y reclamando la procedencia y autenticidad de esos registros. Son los bancos, los bufetes de abogados, las empresas de contabilidad, las auditoras, las compañías de seguros, las hipotecarias, etc. En el futuro, creemos que muchas de las cosas que la gente hace con estos procesos manuales sobre libros de contabilidad y mantenimiento de registros podrían automatizarse de maneras interesantes.Esto asusta a esas personas. Es una cuestión clave. Es esclarecedor para mí que cuando estábamos en DC, no nos grilled pero nos dieron un montón de preguntas de la gente en entornos reguladores que tipo de se da cuenta de la cuestión clave es que el uso de la criptografía es mucho más extraño para ellos que confiar en algún individuo para hacer las cosas. Ni siquiera se trata de una cuestión técnica, sino de una gran desconexión. Mientras hablamos de diversos temas, se puede ver a la gente asintiendo con la cabeza: son las personas que estarían de acuerdo con el uso de ordenadores, mientras que otros piensan que eso llevaría a la aparición de Terminator y que él se encargaría de nuestros pagos o algo así. Ahora estamos regulados, estamos regulados como una especie de institución financiera y por ley estamos obligados a mantener reservas completas de los fondos de nuestros clientes, ya sean dólares o bitcoin. En el pasado, si una empresa como nosotros tenía que ser auditada, el auditor pediría extractos bancarios, o podríamos tener acceso a un informe que sus finanzas de Oracle producido, y vamos a confiar en que nadie manipuló las finanzas de Oracle, o confiamos en que nadie está haciendo diferentes entradas de diario en la empresa ... Cuando les decimos que usted puede controlar las direcciones, no pueden understandtna dthat. (Bueno duh, eso es porque es una afirmación falsa). Son mucho más comfortbale con una hoja de cálculo Excel (entonces usted debe integrar vbscript / rpc comandos, suspiro). La persona que tiene el trabajo de administrar los números están aterrorizados de esto. Hay confianza de la gente en el sistema, la cuestión de la confianza es complicada, hemos quitado la necesidad de confiar en la gente... mucha gente ni siquiera lee las notas de la versión cuando actualizan sus nodos, no leen los pull requests, por lo que confían en que el proceso de desarrollo de código abierto dará lugar a un software en el que pueden confiar, cuando alguien firma una versión están confiando en toda la cadena... están confiando en la gente para ser incentivados por los incentivos implícitos en el protocolo... Obviamente, el protocolo está configurado para que la gente esté incentivada a hacer lo correcto, y estamos confiando en que la gente esté incentivada por los incentivos financieros. Hay gente a la que no le importa el beneficio económico y que estaría dispuesta a destruir la red. Estamos confiando en los mineros hasta cierto punto (??). No tener que tomar decisiones sobre el intercambio transaccional es enorme.

"El problema de fondo de la moneda convencional es toda la confianza que se requiere para que funcione. Hay que confiar en que el banco central no devaluará la moneda, pero la historia de las monedas fiduciarias está llena de violaciones de esa confianza. Hay que confiar en los bancos para que guarden nuestro dinero y lo transfieran electrónicamente, pero ellos lo prestan en oleadas de burbujas de crédito con apenas una fracción en reserva. Tenemos que confiarles nuestra privacidad, confiar en que no dejarán que los ladrones de identidad vacíen nuestras cuentas. Sus enormes gastos generales hacen imposibles los micropagos".

"La identidad es un concepto clave"... (bla, no, gracias). Reputación, identidad federada, enfoques reglamentarios para conocer a su cliente, lucha contra el blanqueo de dinero, fraude, riesgo y cosas por el estilo en las transacciones y que se superponen en la protección de la privacidad del consumidor y evitar el anonimato criminal para ciertos tipos de cosas. Es un tema importante. Hace 12 años que me apasiona el tema de la identidad, incluida la identidad federada. Existe una relación fundamental entre la identidad gubernamental y la identidad financiera. Están estrechamente vinculadas. Si hablas con los gobiernos y las grandes instituciones financieras, estos son los problemas a los que se enfrentan. Quieren identidad. Quieren la identidad de sus ciudadanos. Sean y yo hemos hablado de estos temas. Creo que la cadena de bloques ha abierto de par en par el tema de la reputación y la identidad: ..... El concepto de ataques sibilinos, la criptografía de clave pública y el hecho de que la gente ((no)) necesite la identidad es un concepto realmente poderoso. Es muy importante. Hay dos lados cuando hablamos de los beneficios de Bitcoin como medio de transacción. Uno es que, hey, tenemos esta Internet existente que se ha construido sobre.... ((No importa, realmente no puedo tolerar esto. Parece que no entienden los ataques Sybil)).

La complejidad es un problema clave en términos de adopción de Bitcoin. Esta idea de un espectro de control... tener control absoluto de las claves privadas, y simplicidad... Cuanto más simple lo haces, más control tienes que ceder no es cierto. Es intelectualmente perezoso pensar en esto como un espectro. Creo que ambas cosas podrían lograrse al mismo tiempo. No se trata de quitar el control, sino de la naturaleza esencial de lo que la gente debería ser capaz de lograr con la cadena de bloques y luego iterar sobre ello. La complejidad y la adopción generalizada significan algo diferente para la gente de Bitcoin que para los consumidores habituales... hablamos de reducir la complejidad, hablamos de flujos de trabajo para multisig o de asegurar tus claves en hardware. A los consumidores no les importa nada de eso. Tiene que ser mucho más simple. Tiene que ser como Steve Jobs. Si tiene un lápiz óptico, has perdido. Tiene que haber otro nivel de simplicidad que no quiera unirse al movimiento Bitcoin pero que aún así pueda beneficiarse de Bitcoin. Quizá no necesiten saber que están usando Bitcoin, quizá obtengan las comisiones casi nulas y la liquidación casi instantánea. Tiene que haber un tipo diferente de pensamiento para abordar la complejidad para los consumidores reales de la corriente principal. Si no, podemos hacer Bitcoin más simple. En realidad, lo que estamos haciendo es encontrar a los primeros en adoptarlo en lugar de pasar al siguiente grupo, que es la mayoría, y subirlos a bordo.

¿Serán 2015 o 2016 los años en los que podamos convertirnos en la corriente dominante? Mi familia, mis amigos, la gente, etc., me preguntan constantemente cuál es la aplicación asesina. La killer app significa introducir nuevas capas de... surge cuando la tecnología desaparece, cuando la búsqueda web hace que HTTP deje de ser un problema. Cuando puedes registrarte y usar una cuenta de correo web en lugar de configurar SMTP. Se trata de hacer desaparecer la tecnología. ¿Cuál es el anillo de tokens adecuado para que esto sea sencillo? Si estás pensando en anillos de tokens, entonces ya has perdido. Hay que crear las abstracciones adecuadas. Estamos justo en la cúspide de los beneficios, como la liquidación casi instantánea, la interoperabilidad global, la mejor seguridad, la mejor privacidad, estas son enormes ventajas sobre los sistemas de pago existentes. Para el ciudadano de a pie sigue siendo un compromiso excesivo. Eso realmente desanima a muchos usuarios. Una de las otras cosas en el lado de la complejidad, si fuera sólo un problema de creación de software, las cosas serían más fáciles para nosotros, a diferencia de otros negocios que han implicado una infraestructura significativa y herramientas para otros usuarios, este es el primer negocio en el que necesito permiso para escribir software o lanzar un producto, necesito permiso del gobierno para hacerlo. Así que hay otro tipo de complejidad con Bitcoin en sí, que es que realmente para ofrecer experiencias realmente grandes y para que funcione para los usuarios requiere una especie de interoperabilidad con los sistemas de pago existentes y las formas existentes en que la gente mueve el valor para que sea útil a la gente hoy en día y para que sea útil hoy podemos innovar en Bitcoin de una manera sin permiso que es increíble, pero no podemos innovar en la parte superior de ACH o las redes de tarjetas sin una gran cantidad de supervisión y que hace que sea complejo para conseguir la aceptación masiva porque tenemos que invertir más y se podría discutir si esto es bueno o malo y si perjudica nuestra capacidad de crecimiento y que vale la pena debatir. Creo que esa es la base de las limitaciones de la adopción de blockchain. Muchas startups han sentido el impacto de eso, como tasas inesperadas o cosas así, lo que creo que lo hace muy diferente de otras tecnologías que se hicieron más simples.

Pensamientos finales. Sí. Más o menos. Creo que, a alto nivel, creo, Bitcoin va a tener un profundo impacto en más de 10 o 20 años. Creo que el impacto va a ser mucho mayor de lo que anticipamos. Hay una especie de perogrullada. Las nuevas tecnologías en la web en los años 90 tardan mucho más de lo que los defensores piensan, pero el impacto a largo plazo es a menudo mayor de lo que los defensores más fuertes piensan. Teníamos ideas gigantescas de que la web estaría disponible en todas partes. La expansión tardará más de lo que pensamos, pero creo que el impacto a largo plazo será mayor de lo que pensamos. Aplicaciones fiduciarias... este tipo de aplicaciones afectan a todas las instituciones del planeta, todo el mundo necesita estas intersecciones de contabilidad y pagos, se abren camino a través de todas las instituciones del planeta. La gente que se da cuenta de eso y contribuye a Bitcoin Core y se da cuenta de lo que se puede construir sobre él es realmente emocionante. Trabaja en algo.

Estamos transmitiendo en vivo.

Steven de Rivetz (¿tal vez?). Esto está trayendo una nueva capacidad a Internet y es la capacidad de enviar una instrucción segura. No es la autenticación y luego abrimos una tubería y metemos algunos datos. Lo que blockchain está permitiendo es una micropublicación de una transacción financiera, pero si das un paso atrás y ves, son instrucciones seguras en una red sin núcleo.... El dispositivo desempeña un papel importante en este ecosistema. No hablamos del dispositivo. No es la abstracción de la identidad personal en un dispositivo desconocido el problema de ciberseguridad, la identidad del dispositivo es una parte importante... la blockchain como autoridad de registro de dispositivos... ((¿Qué? Sospecho que la gente no está familiarizada con la criptografía, así que de ahí viene esto, aunque tenga poco que ver con la blockchain). Nos ocupamos de eso porque tenemos defraudadores que intentan robar dinero todo el tiempo. Como referencia a otras bases de datos, la blockchain debería aprovecharse para ese tipo de cosas.

P: Soy comercial. ¿Cuál es su plan para darlo a conocer y conseguir que los primeros en adoptarlo sean la mayoría? La mayoría de la gente ni siquiera entiende el concepto de Bitcoin y criptomoneda. Cualquier idea al respecto sería de gran ayuda.

R: Podría hablar desde una perspectiva específica de un cìrculo. Hemos intentado facilitar las cosas y eliminar muchas fricciones para que la gente obtenga Bitcoin y eliminar algunas de las barreras temporales, no tienes que esperar una semana para conseguir tu primer BTC. Nos hemos centrado en facilitar las cosas y reducir la fricción. Todavía son los primeros en adoptar el producto los que se sienten atraídos por él. Son personas que lo quieren y están entusiasmadas con ello. Creo que existe la metáfora de cruzar el abismo para llegar a la mayoría temprana... Sean suele decir que a menudo los productos que creas para los early adopters, los productos que quiere la mayoría temprana es un producto diferente. Hablando desde la perspectiva de Circle, es sólo un paso de bebé, es sólo un primer paso en esta cosa gigante que queremos hacer. La curva de adopción siempre se presenta como.. las pequeñas líneas deben ser realmente enormes, abismos gigantes. Así que cualquier característica que hayamos introducido para la gente que está interesada en usar Bitcoin y quiere Bitcoin, puede no tener ninguna relación con el siguiente grupo de gente. Usamos multisig para asegurar nuestro BTC, y tenemos seguro de robo del 100% de tus depósitos, así que si no quieres tomar el control de tus claves privadas... así que para los consumidores mayoritarios, no saben realmente que quieren un seguro de robo.. incluso la palabra clave es aterradora. Hay muchas cosas así. Puede que ni siquiera se den cuenta de que tienen un seguro antirrobo para sus depósitos en dólares en sus bancos actuales. Así que tenemos que hacer desaparecer estos problemas. Nos interesan los pagos de persona a persona mucho más que los comerciantes que aceptan Bitcoin. Los pagos de persona a persona son todavía nuevos, los universitarios usan Venmo y cosas así, sólo hay unos pocos millones de personas que los usan en comparación con el correo electrónico o la mensajería o Skype o lo que sea, que tienen cientos de millones de usuarios. Los pagos de persona a persona no tienen eso todavía, ese es un espacio problemático que estamos interesados en resolver. Creemos que el mercado internacional de remesas es un subconjunto del mercado de pagos de persona a persona. El coste de los pagos se reducirá a cero, es sólo el coste de mover los datos a menos que Gavin realmente meta la pata y tengamos que pagar enormes tasas. Así que eso sucede y eso significa enviar mensajes que cambian las entradas de los libros de contabilidad en cualquier parte del planeta .. remesas es sólo una característica. No pensamos... antes de Internet, pensábamos que el envío de correo internacional requería un montón de franqueo, hay este centro y el radio de enrutamiento, así es como funcionaba, y así es como funciona el dinero hoy en día y es muy similar. Creo que eso desaparece y es un servicio gratuito, lo cual es bueno. Eso probablemente no te satisface totalmente. Para muchos de los adoptantes de la corriente principal, que no van a vivir sus vidas en Bitcoin, que tipo de implica que necesitamos puerta de acceso a los sistemas fiat y así sucesivamente, por lo que es lógico que necesitaríamos ot ... usted tiene todos estos servidores jardín amurallado, usted tiene AOL y Compuserve, y luego se podía conectar y luego las universidades subieron a bordo, y luego la configuración de las empresas que solía ser interno sólo correo electrónico. Así que básicamente estos sistemas de almacenamiento y reenvío de archivos por lotes para actualizar los libros de contabilidad en diferentes países, sólo tenemos que conectarlos a Bitcoin y es algo así como conectar los viejos jardines amurallados a Internet. Están intentando conectar los antiguos sistemas heredados de store and forward para actualizar el libro mayor a Bitcoin y conseguir un sistema de libro mayor más moderno e interesante. Esto debería beneficiar a todos. Como estamos empezando a resolver problemas, otras personas y otras empresas pueden resolver problemas en este espacio. Así que lo vemos colectivamente como un ecosistema que avanza. Lo último que querríamos es crear otra red cerrada que llegue a unos pocos países, no creo que eso logre lo que queremos en nuestro propio negocio.

P: ¿Qué pensáis sobre la interacción con los intereses corporativos como Circle y Bitcoin Foundation? Se trata del núcleo de Bitcoin, y tú estás dando la segunda charla. ¿Cómo gestionamos estas dinámicas de poder? ¿Cómo nos aseguramos de no ver la propiedad corporativa con los navegadores web al principio? ¿Cómo impulsamos Bitcoin de una manera que sea buena para todos?

R: Todas las organizaciones sin ánimo de lucro que existen en torno a esto, hay organizaciones de defensa como Coincenter, hay organizaciones autorreguladoras emergentes, ahora que la Fundación está centrada en Bitcoin Core, hay un tremendo... queremos apoyarlas, pero tiene que haber muchas empresas que contribuyan y ayuden. Esa es la forma de lidiar con eso, creo. Puedes imaginar, como dijo Patrick, el IETF. ¿Es esto una cosa IETF para Bitcoin? Esa es una organización altamente política con las partes interesadas de la industria. Se necesita músculo político para hacer las cosas allí. Y Microsoft y Google y otros están jugando cosas allí. Creo que es una pena. Creo que las meritocracias son buenas. Esto se ve en otros proyectos de código abierto que han tomado escala y se han afianzado en Internet. Esperemos que esté sujeto a la meritocracia... Lo que realmente importa es el trabajo que se realiza. Sea cual sea el proceso, lo dirija la Fundación o lo que sea, que el proceso permita que entre el código correcto, independientemente de cuál sea la fuente, independientemente de que se grite. En última instancia, el código triunfará.

Genial, gracias a todos.