# Conversor de UID NFC

Converta o UID hexadecimal lido por um dispositivo NFC para decimal, invertendo a ordem dos bytes antes da conversão.

**[Abrir o conversor](https://mrwohnrath.github.io/conversor-nfc/)**

## Como usar

1. Digite ou cole o código lido pelo dispositivo.
2. Confira a ordem dos bytes invertida.
3. Copie o resultado decimal, se desejar.

O código pode ter bytes separados por `:`, espaços ou hífens. Também é possível informar os dígitos hexadecimais sem separadores.

### Exemplo

| Etapa | Valor |
|---|---|
| UID lido | `6D:B0:0F:D4` |
| Bytes invertidos | `D4:0F:B0:6D` |
| Resultado decimal | `3557797997` |

## Recursos

- Conversão de hexadecimal para decimal com inversão dos bytes.
- Validação de caracteres e bytes incompletos.
- Cópia do resultado para a área de transferência.
- Interface adaptada para celular e computador.

## Privacidade

A conversão é feita no próprio navegador. Os códigos digitados não são enviados para um servidor.

## Tecnologias

Aplicação estática em HTML, CSS e JavaScript, hospedada gratuitamente no GitHub Pages.
