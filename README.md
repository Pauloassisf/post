tentei fazer a atividade mas me encontrei com problemas quanto a execução tendo em vista que o computador da minha casa estava dando erro com o visual code a partir do momento em que tentei usar o npm init e ja nos computadores da UNIFOR não consigo usar o postman pois não é permitido baixar o aplicativo e a extenção foi descontinuada, até tentei fazer pelo celular mas também está dando erro 

var express = require('express');
var app = express();
var bodyParser = require('body-parser');
app.use(bodyParser.json());

app.get('/', function(req, res) {
  res.send('Oi, mundo :-)');
});

var port = 3001;

// iniciando o processo do servidor
app.listen(port, function() {
  console.log(`App de Exemplo escutando na porta http://localhost:${port}/`);
});

app.post('/soma', function (req, res) {
    res.send('Response da requisição POST');
    var body = req.body;
    console.log(body);
    res.send('via post');
  });

  function soma(a, b) {
    return a + b;
  }

  function subtracao(a, b) {
    return a - b;
  }

  function multiplicacao(a, b) {
    return a * b;
  }

  function divisão(a, b) {
    return a / b;
  }

esse é o corpo do codigo que fiz 

![Screenshot_20231107-170239_Opera GX](https://github.com/Pauloassisf/post/assets/106407121/7334fe5d-d72c-4444-95ed-f037fd723b09)
![Screenshot_20231107-170230_Opera GX](https://github.com/Pauloassisf/post/assets/106407121/e9a49e06-f729-4e92-802d-bb7bc753b261)

acima foi minha tentativa de usar o postman no celular embora tenha sido em vão

