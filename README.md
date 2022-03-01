# Projeto 1 de Camada Física da Computação

Implementação de um protocolo de envio "Copy-paste" de uma imagem, via UART de um Arduino Uno fazendo artifício de suas portas RX e TX.



Para utilização,após escolher uma imagem (preferencialmente de tipo PNG), abra um terminal dentro da pasta e execute:

```console
borg@borg:~$ sudo
python aplicacao.py
```

Dessa forma, será gerado uma imagem cópia dentro do diretório após o envio da imagem (convertida em bytes) por meio do arduino e salva uma exata cópia na mesma raiz.
