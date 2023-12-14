# BebaAgua2
Calcular ingestão diaria, idade e ml. 
Aluno(a): Erica Jaislane Campos Fernandes
Turma: Android
 Documentação do Aplicativo Lembrete de Beber Água.

Visão Geral
O aplicativo Lembrete de Beber Água é um aplicativo Android desenvolvido no Android Studio versão 4.7 usando a linguagem de programação Kotlin. Ele foi projetado para ajudar os usuários a manterem-se hidratados, lembrando-os de beber água em intervalos regulares.

Requisitos
- Android Studio 4.7
- SDK do Android versão 30
- Kotlin versão 1.5.0

Funcionalidades
1. **Lembretes**: O aplicativo envia notificações para lembrar o usuário de beber água em intervalos definidos pelo usuário.
2. **Monitoramento**: O aplicativo permite que os usuários monitorem a quantidade de água que consomem durante o dia.
3. **Personalização**: Os usuários podem personalizar o volume de cada copo de água e o intervalo entre os lembretes.

## Configuração do Projeto
1. Abra o Android Studio e selecione 'Open an existing Android Studio project'.
2. Navegue até o diretório onde o projeto foi clonado ou descompactado.
3. Selecione a pasta do projeto e clique em 'OK'.
4. Aguarde o Android Studio baixar todas as dependências necessárias.
5. Uma vez que todas as dependências tenham sido resolvidas, você pode executar o aplicativo em um emulador ou dispositivo Android.

 Estrutura do Código
O código é organizado em pacotes de acordo com a funcionalidade. Aqui estão os principais pacotes:
Seu código parece ser um layout de uma tela de registro em um aplicativo Android. Aqui está a estrutura básica:

View: Um contêiner no topo da tela com altura de 200dp.
ImageView: Uma imagem (provavelmente um logotipo) que está centralizada dentro do contêiner superior.
TextInputLayout (Email): Um campo de entrada de texto para o e-mail do usuário. Este campo está logo abaixo do contêiner superior.
TextInputLayout (Senha): Um campo de entrada de texto para a senha do usuário. Este campo está logo abaixo do campo de e-mail.
AppCompatButton: Um botão que provavelmente é usado para enviar as informações inseridas pelo usuário. Este botão está logo abaixo do campo de senha.
AppCompatButton: Um botão com o id “btEntrar”. Este botão provavelmente é usado para enviar as informações inseridas pelo usuário. Este botão está logo abaixo do campo de senha.
 Testes
Os testes unitários estão localizados no diretório `src/test/KOTLIN` e os testes de instrumentação estão no diretório `src/androidTest/KOTLIN`.
