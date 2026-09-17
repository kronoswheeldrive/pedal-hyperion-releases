# Pedal Hyperion V3 — downloads

Aqui ficam o **configurador** (o programa do Windows) e o **firmware** (o
programa que roda dentro da placa do pedal). É daqui que o próprio
configurador busca as atualizações.

## Baixar

Abra **[Releases](../../releases)** e pegue sempre a versão mais recente:

| Arquivo | O que é |
|---|---|
| `PedalHyperion-Setup-<versão>.exe` | Instalador do configurador para Windows 10 e 11 |
| `PedalHyperion-Firmware-<versão>.hex` | Firmware da placa |

## Instalar o configurador

1. Baixe o `PedalHyperion-Setup-....exe` e execute.
2. Na primeira vez, o Windows mostra **"O Windows protegeu o computador"**.
   Clique em **Mais informações › Executar assim mesmo**. O aviso aparece
   porque o instalador ainda não tem certificado de assinatura.
3. O programa não pede senha de administrador e cria o atalho no Menu Iniciar.

Seus perfis e a calibração **não se perdem** ao instalar uma versão nova.

## Como a numeração funciona

* **Configurador:** versões `app-v1.0.0`, `app-v1.1.0`…
* **Firmware:** versões `firmware-v3.5`, `firmware-v3.6`…

As duas andam separadas: dá para atualizar só o programa do computador, ou só
o da placa.

## Suporte

Com o pedal ligado, abra o configurador, ligue o **Modo avançado**, vá em
**Diagnóstico › Emitir diagnóstico** e envie o arquivo que ele salva na pasta
**Downloads**. Ele traz tudo o que é preciso para achar o problema à
distância.

---

O código-fonte é fechado. Este repositório guarda apenas os arquivos para
download.
