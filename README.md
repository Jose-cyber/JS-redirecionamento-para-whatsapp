# JS-redirecionamento-para-whatsapp

Projeto usando javascript na qual indentifica o tamanho do display para á partir do tamanho do dispay redirecionar a pessoa usando o link correto do whatsapp, já que existe diferença no link quando o direcionamento é feito para o whatsapp web ou para o app do whatsapp do celular:


**https://api.whatsapp.com/send?phone=5512991708065&text=Olá** --> link do whatsapp para celular 


**https://web.whatsapp.com/send?phone=5512991708065&text=Olá** --> link do whatsapp web


Na função **link()** do javascript é determinado dentro do parametro **screen.width<1024** que se a largura do display for menor que 1024 para redirecionar para o app do whatsapp no celular, já se a largula do display for maior que 1024 provavelmente o usuario esta acessando de um computador, portanto ele direciona para o whatsapp web. 


### Funcionamento:

Para executar apenas clique no botão do Icone do Whatsapp:

<img src="https://i.ibb.co/Yd04Qw5/Whatsapp-redirect.png" alt="juninho tecnologia">


