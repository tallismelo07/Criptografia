# Projeto de Criptografia com Cifras de César e Vigenère

Este projeto implementa duas técnicas de criptografia clássicas: a **Cifra de César** e a **Cifra de Vigenère**. O programa também permite ler mensagens de arquivos de texto e aplicar a criptografia ou descriptografia diretamente nelas.

## Funcionalidades

- **Cifra de César**:
  - Criptografar e descriptografar mensagens com um deslocamento numérico.
  
- **Cifra de Vigenère**:
  - Criptografar e descriptografar mensagens usando uma chave alfabética repetida.
  
- **Leitura de Arquivos**:
  - Lê conteúdo de arquivos `.txt` e aplica as cifras de César ou Vigenère.

## Como Utilizar

Ao iniciar o programa, o menu principal oferece as seguintes opções:

1. **Cifra de César**: Escolha esta opção para criptografar ou descriptografar uma mensagem usando a Cifra de César.
2. **Cifra de Vigenère**: Escolha esta opção para criptografar ou descriptografar uma mensagem usando a Cifra de Vigenère.
3. **Arquivo de Texto**: Permite ler uma mensagem de um arquivo `.txt` e aplicar uma das cifras.
0. **Sair**: Encerra o programa.

### Para cada cifra, o usuário será solicitado a:

- Inserir a mensagem a ser criptografada/descriptografada.
- Inserir a chave (um número no caso da Cifra de César e uma palavra no caso da Cifra de Vigenère).
- Escolher o modo (C para criptografar e D para descriptografar).

Na opção de **arquivo de texto**, o usuário deve fornecer o nome do arquivo com extensão `.txt`, e o programa processará o conteúdo aplicando a cifra escolhida.

