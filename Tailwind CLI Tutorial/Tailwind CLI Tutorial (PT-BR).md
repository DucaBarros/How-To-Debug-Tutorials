## TAILWIND CLI

### "COMO PREPARAR O AMBIENTE PARA TRABALHAR COM TAILWIND SEM FRAMEWORKS"

1) Primeiro, crie uma pasta chamada _src_ com os arquivos _index.html_, _input.css_ e _output.css_ dentro da pasta _src_ do seu projeto conforme imagem abaixo.

![Imagem 01](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/406786e87a16e32acdd413c6d47ffa611d06e235/Tailwind%20CLI%20Tutorial/img01.jpg)

2) Em seguida, abra seu projeto no terminal integrado **CMD** ou **BASH** (não funciona no **PowerShell**).

![Imagem 02](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/406786e87a16e32acdd413c6d47ffa611d06e235/Tailwind%20CLI%20Tutorial/img02.jpg)

3) Execute o comando _npm init_ e pressione _Enter_ até que o arquivo _package.json_ seja criado.

![Imagem 03](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/406786e87a16e32acdd413c6d47ffa611d06e235/Tailwind%20CLI%20Tutorial/img03.jpg)

4) Agora execute o comando abaixo no **Terminal**:

>npm install tailwindcss @tailwindcss/cli

5) Aguarde até que a pasta _node_modules_ e o arquivo _package-lock.json_ sejam criados.

6) Abra o arquivo _input.css_, escreva _@import "tailwindcss";_ salve e feche o arquivo.

![Imagem 04](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/406786e87a16e32acdd413c6d47ffa611d06e235/Tailwind%20CLI%20Tutorial/img04.jpg)

7) Por último rode esse comando no **Terminal**:

>npx ./node_modules/@tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

![Imagem 05](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/406786e87a16e32acdd413c6d47ffa611d06e235/Tailwind%20CLI%20Tutorial/img05.jpg)

8) Agora é só abir seu arquivo _index.html_, referenciar o arquivo _output.css_ no atributo _href_ da tag _link_ (conforme imagem), salvar o arquivo _index.html_
  
9) Seu ambiente está pronto para receber código **Tailwind**.

![Imagem 06](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/cd2e8c1507071f22ced1579ce21003b48434b6d5/Tailwind%20CLI%20Tutorial/img06.jpg)

### **Recomendação**

- Instale a extenão **Tailwind CSS IntelliSense** para ajudar na produtividade ao usar o Tailwind.

![Imagem 07](https://github.com/DucaBarros/How-To-Debug-Tutorials/blob/cd2e8c1507071f22ced1579ce21003b48434b6d5/Tailwind%20CLI%20Tutorial/img07.jpg)
