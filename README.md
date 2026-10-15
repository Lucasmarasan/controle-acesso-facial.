[README.md](https://github.com/user-attachments/files/33507614/README.md)
# controle-acesso-facial.# Controle de Acesso Facial

Protótipo educacional em HTML, CSS e JavaScript para demonstrar cadastro e comparação facial usando `face-api.js`.

## Funcionalidades

- Cadastro de uma pessoa com nome e três capturas: frente, lado direito e lado esquerdo.
- Exige os três ângulos antes de salvar um cadastro.
- Compara um rosto diante da câmera com os descritores dos cadastros locais.
- Exibe **Acesso Confirmado** quando encontra correspondência suficiente ou **Pá! Acesso Negado** quando não encontra.
- Permite visualizar e excluir cadastros.

## Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta no Visual Studio Code.
3. Execute `index.html` com uma extensão de servidor local, como Live Server.
4. Permita o acesso à câmera no navegador.
5. Mantenha uma conexão com a internet para carregar `face-api.js` e os modelos usados pelo projeto.

## Observações importantes

- Este projeto é um protótipo para aprendizado, não um sistema de segurança pronto para produção.
- Os descritores faciais ficam no `localStorage` do navegador e não são criptografados.
- Os dados ficam no navegador/dispositivo onde o cadastro foi feito; não são sincronizados automaticamente entre dispositivos.
- O limite de comparação é ilustrativo e pode produzir falsos positivos ou falsos negativos.
- Use apenas com consentimento informado. Dados biométricos exigem proteção especial; avalie a LGPD antes de qualquer uso real.
- Não use este protótipo como único mecanismo para controlar portas, contas ou áreas restritas.

## Tecnologias

- HTML
- CSS
- JavaScript
- [face-api.js](https://github.com/justadudewhohacks/face-api.js/)

## Licença

Defina uma licença antes de permitir reutilização pública do código.
