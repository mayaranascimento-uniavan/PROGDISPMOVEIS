## 📱 Este projeto foi desenvolvido com Apache Cordova e pode ser executado diretamente em um dispositivo Android real.

> ⚠️ **Importante:** Não utilizamos emulador. A aplicação é testada diretamente no celular via conexão USB, o que facilita a visualização do funcionamento em tempo real, incluindo o uso de funcionalidades nativas como alertas.

Após copiar os arquivos HTML para a pasta `www/` do projeto Cordova, basta executar o comando de build e rodar no dispositivo para ver o app funcionando.

🧩 Explicação:
A interface foi construída com HTML e estilizada com Bootstrap 5.

O script cordova.js é incluído para possibilitar o uso de recursos nativos no app.

O layout é centralizado com flexbox e usa uma div.container para agrupar os elementos.

Os campos de entrada permitem que o usuário insira os dados necessários: capital, taxa de juros e tempo.

Um botão aciona a função calcularJuros() e o resultado aparece abaixo do botão, dentro da tag <h3>.
