# Desafio-2-Bootcamp-Santander-Ciberseguranca-2025
Criando malwares com python. Ransomware e Keylogger com python e simulando os scripts em ambiente virtual
Objetivos de estudos e aprendizagem, para saber como o ataque funciona e se precaver.

# Entenda o que é um ransomware
Primeiro vamos entender como um ransoware funciona, o ator malicioso cria um código malicioso que vai executar na rede
do seu alvo criptografando todos os arquivos, imagems, documentos e diretórios dessa rede, ou seja, o ransomware vai bloquear
acesso aos dados dessa rede criptografando os arquivos e só com uma chave de descriptografia conseguimos restaurar os arquivos.

O objetivo desse tipo de ataque é exigir que se ualvo pague um certo valor em criptomoedas por ser mais difícil de rastrear
e quando receber o pagamento o atacante vai enviar a chave de descriptografia para o alvo. Mas em muitos casos o atacante
nunca vai enviar essa chave e tende a solicitar mais dinheiro em criptomoedas.

# CRIANDO UM RANSOMWARE COM PYTHON
# Código em Python que simula um ransomware
<img width="702" height="879" alt="image" src="https://github.com/user-attachments/assets/811f270a-5991-47fd-81ca-11a901521f7f" />


# Executando o código em um arquivo de senhas.txt
Arquivo original:

<img width="392" height="130" alt="image" src="https://github.com/user-attachments/assets/67b94ef2-ca2b-4b44-8825-d5b487c0eec8" />


Executando o código malicioso para criptografar o arquivo senhas.txt e exibir a mensagem do atacante:

<img width="559" height="163" alt="image" src="https://github.com/user-attachments/assets/33deef8b-b320-4e85-a91e-1231dfc74bcf" />


Agora vamos ver como ficou o conteúdo dentro do arquivo senhas.txt

<img width="1148" height="147" alt="image" src="https://github.com/user-attachments/assets/a5ca1315-1ac6-4391-a271-65b1e75ab4da" />


Agora vou executar o segundo código em python que faz justamente o oposto, ele vai inserir a chave de descriptografia para descriptografar
os arquivos que foram afetados:

<img width="344" height="196" alt="image" src="https://github.com/user-attachments/assets/0902648b-a804-4463-a212-df4e0035047e" />


# COMO SE PROTEGER?

1. Educar o usuário sobre as práticas de engenharia social.
2. Se atentar com phishing.
3. Nunca fazer download de arquivos suspeitos.
4. Ter antivirús instalados nos computadores da rede.
5. Ter EDR instalado nos computadores da rede.
6. Ter monitoramento e time de resposta a incidente.

Com isso concluímos nosso laborátorio de estudos sobre o desafio de ransomware
vamos agora para o segundo laboratório.

# Entenda o que é um keylogger
Vamos entender como funciona um keylogger, basicamente esse tipo de código malicioso funciona em background com o objetivo
de coletar logs de tudo que o usuários daquele computador digitar em seu teclado e enviar esses logs para o atacante seja via email
ou via ssh através de um backdoor.

O principal objetivo desse tipo de ataque é coletar informações, logins, senhas, dados financeiros e até mensagens que possam
ser úteis de alguma forma.

# CRIANDO UM KEYLOGGER COM PYTHON
# Código em Python que simula um keylogger:

<img width="489" height="667" alt="image" src="https://github.com/user-attachments/assets/653fde77-31ed-4c3d-8603-d9ef9083847b" />


# Executando o código do keylogger:

<img width="393" height="78" alt="image" src="https://github.com/user-attachments/assets/f244930e-4b92-499c-ad47-40f22db0acc0" />


# Abri um editor de texto e digitei algumas informações:

<img width="668" height="530" alt="image" src="https://github.com/user-attachments/assets/73706a12-b9fc-400f-acd1-dd393cd90f52" />


# Agora podemos ver nosso arquivo de log.txt que o código keylogger.py gera:

<img width="390" height="126" alt="image" src="https://github.com/user-attachments/assets/c1c349ff-7f14-44a6-9c1e-71890bb39f55" />


Podemos também enviar essa saída de tudo o que é digitado pelo alvo para um e-mail falso em que podemos estar recebendo de tempos em tempos
tudo o que foi digitado.


# COMO SE PROTEGER?

1. Educar o usuário sobre as práticas de engenharia social.
2. Se atentar com phishing.
3. Nunca fazer download de arquivos suspeitos.
4. Ter antivirús instalados nos computadores da rede.
5. Ter EDR instalado nos computadores da rede.
6. Ter monitoramento e time de resposta a incidente.
