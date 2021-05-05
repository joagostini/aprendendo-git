<DEV65> Inicia hoje o processo de formação de um desenvolvedor front-end aos 65 anos de idade, inaugurando uma nova etapa.

A chance de sucesso é minima, tanto porque posso morrer amanhã, nesta idade o corpo já não se sente tão confortável. Além disso, posso nunca conseguir um trabalho. É difícil quando se é jovem, imagina aos 65 sem experiência. Dai que tentarei criar algumas coisas e ser free. Em suma, 'oh vida, oh azar' - os velhos entenderam -, posso não sair do lugar, mas, mesmo assim, é melhor tentar andar do que ficar parado olhando o horizonte. Andando, pelo menos, poderei ver coisas novas e dar uma nova chance para que a paixão pelo mundo volte e tome conta do meu espírito.

Agora estou me concentrando em conhecer o Git, pois todos os youtubers, de cursos de empresas, como independentes, aconcelham o conhecimento deste instrumento, pois ele é amplamente usado nas empresas.

Hoje há muito trabalho em equipe e o Git é uma das ferramenteas disponíveis para realizar essa tarefa.

Introduzi esta alteração em master com o intuíto de observar o comando diff que nos mostra as alterações realizadas no documento antes de fazer commit.

Esta frase só será visivil no ramo teste1 e não aparecerá no master.

Erro, a frase que começa com Introduzi..., feita no ramo master aparece no ramo teste1 porque o documento README.md não foi salvo quando da mudança. Ele foi comitado em master, mas o texto foi salvo em teste1. Assim, em teste1
com o comando git diff, Introduzi..., Esta frase..., Erro... aparecem para ser commitados em teste1.

Zerando os erros nos ramos principal e teste1. Esta linha aparece nos dois (mais ou menos igual).
Esta linha é exclusiva do ramo teste1.
