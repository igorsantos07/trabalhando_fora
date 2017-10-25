# Descomplicando o trabalhar para fora

Praticamente toda semana eu e o [Caffo] recebemos emails com dúvidas de pessoas que estão planejando ou começando a trabalhar com empresas no exterior. Normalmente eu tento responder rapidamente porém com a correria do trabalho e da vida pessoal nem sempre isso é possível.

Normalmente as perguntas são bem parecidas, mas mesmo fazendo um "copy and paste" acabo demorando para responder. Sei que isso é bem ruim para quem manda o email, mas até então era o melhor que eu podia fazer. Outro dia o [Caffo] me deu a ideia de escrever um FAQ/post sobre isso e resolvi que esse seria o meu presente de Natal para a comunidade de desenvolvedores.

Como esse artigo é de um desenvolvedor para outros desenvolvedores acho que não existe lugar melhor para publicar do que no [GitHub](http://github.com/tapajos/trabalhando_fora). Para fazer essa [página bonitinha](http://tapajos.me/trabalhando_fora) estamos usando o [DocumentUp](http://documentup.com/). Se quiser contribuir sugiro dar uma lida nas dicas de formatação.

Tentei responder as perguntas mais frequentes mas provavelmente muitas dúvidas foram esquecidas. Você pode me enviar suas [dúvidas](https://github.com/tapajos/trabalhando_fora/issues) e vou tentar responder o mais rápido possível.

## Disclaimer

Esse artigo foi escrito baseado na minha experiência trabalhando com exportação de software desde 2008 e de [outros colaboradores](https://github.com/tapajos/trabalhando_fora/graphs/contributors). As coisas mudam com uma certa frequência e não estou assumindo nenhum compromisso de manter esse artigo atualizado.

Eu não sou contador, não sou advogado tributarista e nem especialista em comércio exterior. Não tenho nenhuma responsabilidade por qualquer problema que você venha a ter. Minha recomendação é que você procure profissionais competentes e de sua confiança para te orientar.

## Contratação

Só existe uma regra: TENHA UM CONTRATO entre você e a empresa/pessoa de fora. Esse contrato é a forma de você comprovar a origem e a legalidade do dinheiro que você está recebendo.

## Impostos

O que você vai pagar de imposto vai depender da forma como você foi contratado, isto é, se foi via pessoa física ou jurídica. Não vou entrar na discussão da legalidade de você usar uma pessoa jurídica, sugiro que pesquise, consulte um bom advogado tributarista antes de tomar uma decisão. Não se esqueça de considerar os custos de contabilidade se você optar por abrir uma empresa.

### Pessoa Física
Vai pagar apenas o Imposto de Renda normal, de acordo com a tabela vigente. Nesse caso, você recebe o dinheiro da forma que for mais conveniente e deve declarar mensalmente no programa do Carnê Leão (que você encontra no Google / site da Receita Federal). Ele vai gerar um boleto para que você pague o IR convencional, todo mês, e no começo do ano, você poderá importar o relatório dele no programa de Declaração e Ajuste do IRPF.

Na prática, funciona da mesma forma que uma empresa CLT faria por você - exceto que eles fazem o pagamento à receita e descontam na sua folha de pagamento, mas o valor do imposto é o mesmo. Vale citar que, ao contrário do que muita gente pensa, calcular 27.5% em cima do que vai ser recebido é **errado**, pois o imposto é crescente de acordo com os níveis - mas não muda de acordo com o quanto você recebe; faça a previsão correta no [Simulador de alíquota do IRPF oficial](http://www.receita.fazenda.gov.br/aplicacoes/atrjo/simulador/simulador.asp?tipoSimulador=M).

### Pessoa Jurídica
Nesse caso os impostos podem variar bastante de acordo com o tipo da sua empresa e a sua localização. Se a sua empresa for cadastrada no Simples você irá pagar os impostos como se tivesse prestando serviço no Brasil. Caso sua empresa seja de Lucro Presumido você pode usufruir da isenção de PIS e Cofins existente para serviços de exportação de software conforme [IN-SRF 247 Art. 46 de 21/11/2002](http://www.receita.fazenda.gov.br/PessoaJuridica/PisPasepCofins/IncidImunIsencoes.htm#Isenções).

Dependendo do seu município você ainda pode contar com isenção de ISS. Porém, para ter essa isenção, é necessário que exista no seu contrato uma cláusula de não verificação em território nacional.

## Siscoserv

Recentemente o Governo Federal criou um [Sistema Integrado de Comércio Exterior de Serviços, Intangíveis e Outras Operações que Produzam Variações no Patrimônio (Siscoserv)](http://www.desenvolvimento.gov.br/sitio/interna/interna.php?area=4&menu=2234) que introduziu mais uma obrigação a ser cumprida por Pessoas Físicas e Jurídicas que exportam serviços para o exterior.

Esse obrigação não se trata de mais um imposto, é apenas uma conjunto de informações que devem ser enviadas a cada remessa recebida do exterior.

**Atenção**, as multas pelo não cumprimento e/ou atraso dessa obrigação são altas e você não perde nem 10 minutos por mês fazendo essa declaração. Vale ressaltar que será necessária a utilização de um [e-CPF](http://www.receita.fazenda.gov.br/atendvirtual/orientacoes/conceitobasico.htm#Certificado Digital e-CPF ou e-CNPJ) para acesso ao sistema.

**Atenção**, não existe mais a obrigação de enviar essas informações em alguns casos, conforme a [Portaria Conjunta RFB/SCS Nº 1908/2012](http://normas.receita.fazenda.gov.br/sijut2consulta/link.action?visao=anotado&idAto=38371)

> Art. 2º Ficam dispensadas do registro de que trata o caput do art. 1º, nas operações que não tenham utilizado mecanismos de apoio ao comércio exterior de serviços, de intangíveis e demais operações de que trata o art. 26 da Lei nº 12.546, de 14 de dezembro de 2011:

> I - as pessoas jurídicas optantes pelo Regime Especial Unificado de Arrecadação de Tributos e Contribuições devidos pelas Microempresas e Empresas de Pequeno Porte (Simples Nacional) e os Microempreendedores Individuais (MEI) de que trata o § 1º do art. 18-A da Lei Complementar nº 123, de 14 de dezembro de 2006; e

> II - as pessoas físicas residentes no País que, em nome individual, não explorem, habitual e profissionalmente, qualquer atividade econômica de natureza civil ou comercial, com o fim especulativo de lucro, desde que não realizem operações em valor superior a US$ 30.000,00 (trinta mil dólares dos Estados Unidos da América), ou o equivalente em outra moeda, no mês. (Redação dada pelo(a) Portaria Conjunta RFB SCS nº 1268, de 06 de setembro de 2013)

## PayPal

Muita gente me pergunta sobre receber via PayPal e a minha recomendação é para que você **não** faça isso. O PayPal não é banco e possui suas próprias regras e estas não são muito claras. Resista a tentação da simplicidade deles, você pode ter várias dores de cabeça.

Conheço duas pessoas que tiveram as contas canceladas (suspeita de atividades ilegais) e que nunca conseguiram recuperar o dinheiro que estava lá. Uma delas tinha 15 mil dólares na conta, já enviou fax com contrato, uma infinidade de documentos e até hoje não teve nenhuma resposta deles.

## Escolha do banco

Essa é uma pergunta bastante recorrente e a resposta é que não existe um banco que seja maravilhoso e no início você vai ter bastante trabalho. Na prática são três coisas que fazem a escolha do banco ser importante: cotação do dólar, tarifa de operação e o processo.

### Experiência antiga com o Real / Santander
Quando comecei a trabalhar prestando serviços para empresas de fora do Brasil eu tinha conta no Banco Real e a maior dificuldade que eu tive foi com o meu gerente que não fazia a menor idéia de como funcionava o setor de câmbio. Na época a tarifa era fixa e a cotação não era das piores. O processo era todo feito por telefone e o dinheiro demorava em torno de 24h para ser creditado na conta. A parte mais chata era a necessidade de enviar o contrato de câmbio assinado pelo correio dentro de um prazo de 30 dias.

### Experiência com o Itaú
Depois de operar com o Real por alguns anos resolvi mudar para o Itaú já que o Santander havia comprado o Real e estava tudo ficando muito confuso. No Itaú o processo foi muito mais tranquilo, minha gerente entendia tudo de câmbio e em pouco mais de uma semana eu já estava com o cadastro feito e podendo receber. A tarifa do Itaú também é fixa porém a cotação nunca foi boa. A grande vantagem é no processo de "fechamento" de câmbio, que acontece todo pela internet.

Através do Internet Bank é possível consultar uma cotação e iniciar a contratação. Uma vez preenchido tudo você recebe um email solicitando a documentação e poucos minutos após o envio chega o contrato e o pagamento acontece em algumas horas. É necessário entregar uma cópia assinada do contrato em uma agência em até 15 dias. Recentemente passou a ser possível assinar o contrato digitalmente com um e-cpf e com isso o processo se tornou 100% digital.

### Mudança pro Banco Rendimento / Cotação
Eu estava bem satisfeito com o Itaú até que eles fizeram umas mudanças no setor de câmbio e tive alguns pequenos problemas. Não foi nada grave mas como o [Peleteiro](http://twitter.com/peleteiro) vivia falando do [Banco Rendimento](http://www.rendimento.com.br/) eu resolvi testar. O processo de abertura de conta de câmbio foi bem simples, em 24h eu já tinha um cadastro básico e já podia receber até 36 mil reais. O cadastro completo foi liberado após o envio de alguns documentos assinados pelo correio.

O [Banco Rendimento](http://www.rendimento.com.br/) também trabalha com uma taxa fixa por operação e possui uma cotação bem competitiva. O processo é bem rápido, basta ligar no setor de câmbio e solicitar o fechamento. Na hora o operador te envia por email o boleto de câmbio. Atualmente você só precisa assinar digitalmente ([eu faço isso usando o Preview do Mac](http://www.techtudo.com.br/dicas-e-tutoriais/noticia/2012/09/como-assinar-pdfs-no-mac-os-x-com-o-aplicativo-preview.html)) para ordens acima de 10k USD. Independente do valor você deverá enviar enviar a invoice por e-mail para o operador. Feito isso eles verificam e fazem o pagamento em poucas horas. Para agilizar eu solicito sempre que o operador aguarde na linha enquanto assino e retorno tudo. Com isso ele verifica tudo e já libera o pagamento na hora.

Recentemente o Banco Rendimento separou os clientes grandes dos clientes pequenos e transferiu esses pequenos para a [Cotação](https://cotacao.com.br/), uma outra empresa do grupo. Continua a mesma coisa mas com outro nome.

### Experiência com bancos digitais
O [igorsantos07] abriu conta no Banco do Brasil, por ter a menor taxa mensal de contas PJ nos bancos tradicionais. Minhas wire transfers seriam recebida por uma casa de câmbio, então eu não precisaria lidar com o setor cambial de banco algum - e correr o risco de enfrentar gerentes que desconhecessem processos, ou taxas absurdas.

Neste ano de 2017 foram surgindo alguns bancos digitais com contas PJ. Nomeadamente, a Agiplan lançou o Agipag, que até o presente momento funciona somente via aplicativo e não permite o pagamento de impostos, o que dificulta um pouco o seu uso - pois não é muito interessante que você misture sua PF com a PJ pagando impostos fora da conta jurídica. Em resumo, cheguei a usá-lo para reduzir o custo de TED na minha conta do BB, mas não me senti contente ali.

Pouco depois o Inter lançou a Conta Digital Pro (AKA conta PJ), e ela funciona muito bem. É possível fazer TEDs ilimitados, pagar boletos, impostos, e tem até cartão de crédito. Eles também fazem operações de câmbio, mas como eu (Igor) faço minhas operações via casa de câmbio, não sei detalhes sobre esta parte.

### Resumo
Como vocês podem ver, cada banco tem um procedimento totalmente diferente e você deve analisar qual que te atende melhor. No meu caso o mais importante é não precisar sair de casa, se eu puder fazer tudo de casa eu até aceito uma cotação ruim e/ou uma tarifa mais alta.

**Atenção**, não adianta pedir à sua empresa para fazer a Wire transfer em reais, a operação de câmbio será necessária para a liberação da quantia transferida.

### Casas de Câmbio
_Disclaimer: esta é uma adição de contribuinte, que não reflete a opinião e experiência do autor original._

Outra forma de fazer a operação cambial, que possivelmente terá cotações e taxas mais atraentes do que as oferecidas pelos bancos comuns do mercado, é abrir uma conta em uma casa de câmbio.

Na Toptal a casa de câmbio preferida dos brasileiros é a B&T. Após a abertura da conta eles te darão os dados necessários para que você repasse ao seu cliente para o envio da wire transfer. A partir daí, em um dia útil ou dois a casa de câmbio receberá a quantia e te avisa, por Skype, do recebimento da mesma. Você pode aguardar o melhor dia/momento para fechar a operação, dado que o câmbio que te oferecem vai flutuar no decorrer do dia. A taxa que a B&T tem cobrado é um valor fixo em dólares + um pequeno spread. A partir do fechamento da operação, se este for feito até o meio-dia (horário em que o mercado de câmbio faz uma pausa, até as 13h30), o valor é creditado na conta-corrente da sua PJ no mesmo dia. Caso o câmbio seja feito durante a tarde (até as 15h30), o crédito ocorre no próximo dia útil.

Eu ([igorsantos07]) tentei migrar para a MultiMoney, que me foi indicada por outro toptaler como sendo mais em conta. No entanto, a economia saiu pela culatra. Eles cobram uma taxa fixa levemente maior que a da B&T, mas o spread é ainda mais reduzido (menos de 1%), mas o atendimento é bem... complicado. O recebimento das wires levava pelo menos dois dias, e tanto lidando com o pessoal da agência de Blumenau quanto com a sede a comunicação era falha. Por fim, tive problemas em ambas as agências para pedir a [isenção de ISS](#impostos), sendo que na sede eles se recusaram e passaram por cima de mim, efetuando o câmbio mesmo sem a isenção. A lição de moral é clássica: às vezes, o barato sai caro.

## O fluxo de recebimento

1. Envio da invoice (ver detalhes abaixo)
2. Recebimento da Wire
3. Contratação do câmbio (fechamento de câmbio)
4. Emissão da nota fiscal (no caso de PJ)
5. Envio das informações do Siscoserv
6. Envio da nota fiscal e do boleto de câmbio para o contador (no caso de PJ)

## Nota Fiscal (no caso de PJ)

O processo de emissão da nota fiscal é bem parecido com o da prestação de serviços para o Brasil. O único detalhe é que ela deve ser emitida no dia do fechamento de contrato de câmbio e com o valor creditado em reais na conta corrente da empresa. Você deve consultar o seu contador para saber os detalhes da emissão da nota.

A nota fiscal não tem nenhum valor para a empresa de fora, não há necessidade de enviá-la.

## Invoice

A [invoice](http://en.wikipedia.org/wiki/Invoice) é um tipo de fatura. Não existe nenhum mistério em gerar invoices, o único detalhe é que a numeração deverá ser única.

Você pode usar até o Word para gerar esse documento. Eu utilizo e recomendo o [Blinksale](http://www.blinksale.com/).

## Mais informações

Eu e o Caffo gravamos uma série no Grok Podcast falando sobre como é trabalhar remotamente para empresas no exterior, para quem se interessar: ["Trabalho Remoto – Parte 1 de 5"](http://www.grokpodcast.com/2013/04/02/episodio-86-trabalho-remoto-parte-1-de-4/)


[caffo]: http://twitter.com/caffo
[igorsantos07]: http://igorsantos.com.br
