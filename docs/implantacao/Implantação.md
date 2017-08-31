screver software é dificil. Manter um software atualizado e em funcionamento 
sem defeitos, é ainda mais dificil.

Uma das ferramentas mais importantes para que isso ocorra, isto é, a criação 
e manutenção de um bom software, com o mínimo de defeitos (nenhum software é perfeito), é sem dúvida, os relatórios de 
defeitos, ou bug reports.

Eles podem ser criados por qualquer pessoa que use de fato o software, qualquer 
que ele seja. Alguns relatórios de bugs (chamaremos apenas de bugs, daqui por) 
diante serão escritos por desenvolvedores, que notarão comportamentos estranhos 
ainda na etapa de desenvolvimento. Outros serão escritos por testadores profissionais, 
que ganham o pão procurando a desgraça alheia. E outros bugs, serão encontrados 
apenas quando o nosso software estiver em produção - pelo usuário final.

Não importando quem escreveu, todo e qualquer bug merece um relatório e uma 
investigação formal. O quanto antes, melhor. Bugs tendem a ficar cada vez mais 
caros, conforme o tempo passa. Estima-se que um bug descoberto em produção custa 10 vezes mais o valor do que 
se ele tivesse sido encontrado antes
- durante o desenvolvimento.

A conta é simples: se o bug tivesse sido encontrado durante a etapa de desenvolvimento, o desenvolvedor gastaria 
2 horas para resolvê-lo e adicionar 
um teste de unidade, afim de garantir que o mesmo não retorne para assombrar ninguém, 
anos depois.

Se o bug é encontrado em produção, serão gastos, aproximadamente, 20 horas para 
resolvê-lo. Senão mais. Tudo em produção é mais difícil.

Certo, bugs são caros, mas e daí? Bem, se podemos resolver o bug em desenvolvimento 
e uma das principais formas de se resolver um bug é criando um bug report, 
bons relatórios de bugs facilitam a vida dos desenvolvedores, na hora de encontrar 
o danado e resolvê-lo de uma vez por todas.

Maus relatórios de bugs deixarão os desenvolvedores e usuários irritados. Bugs 
com títulos e descrições inadequadas serão muito mais difíceis de serem resolvidos, 
pois são mais difíceis de serem encontrados, terem o comportamento exato reproduzido, 
assim por diante.

Uma máxima importante é:

Um bom relatório de bug descreve o problema de forma que o desenvolvedor familiarizado com o projeto pode
entender e resolvê-lo, sem falar com a pessoa que o escreveu.
Esta é uma tradução generalizada de uma [postagem do martiancraft][martincraft-bug-report]. Realmente, 
devo concordar com o título.

Pequena estória: uma certa vez, trabalhando com um cliente - sem expertise técnica, decidiu que gostaria 
de escrever seus próprios relatórios de bugs. Ótimo, pensei, uma coisa a menos que terei de fazer. Este cliente nunca havia
utilizado ou mesmo visto um relatório de bug.
