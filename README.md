# App Web MVC
* Autocontida
* Todas as responsabilidades (persistência, apresentação, segurança, regras de negócio, etc.)

### Respostas
* HTML
* Layout específico
* Foco: navegador/usuário final

### Requisições
* Rotas AspNet MVC
* GET/POST {controlador}/{action}/{id?}

### Segurança baseada em Cookies
* Acoplamento por Sessão
* Identidade e direitos(claims) separados na requisição + servidor

# Web Api
* Solução é dividida em serviços com responsabilidades distintas
* Integração é objetivo
* Estilo arquitetural REST

### Respostas
* JSON, XML, etc (conteúdo negociado)
* Status Code adequados à operação
* Foco: aplicações/desenvolvedor

### Requisições
* Verbos HTTP + URI (Recursos)
* Verbo {controlador}/{id?}

### Segurança baseada em Tokens
* Identidade e direitos(claims) no token enviado a cada requisição
* JWT