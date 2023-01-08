# Dell Latitude 5400 - Hackintosh EFI

---
**NOTA: Encontrei aqui no GitHub e melhorei a EFI de um outro repositório já existente**
**MELHORIAS:**
- Opencore 0.8.8
- Menu Visual
- Instalação em Inglês (a original estava em Húngaro, rsrsrsr :p)
---

**AVISO: EFI para macOS 13 Ventura.**

## Especificações

| | |
|-|-|
|**CPU**|Intel i5-8265U CPU @ 1.60GHz (Whiskey Lake)|
|**RAM**|16GB DDR4 2400MHz|
|**IGPU**|Intel UHD 620|
|**SSD**|Western Digital Black NVMe 500GB|
|**ETH**|Intel I217-LM|
|**WLAN+BT**|Intel 9560NGW ou podendo usar a BCM94360NG|
|**WWAN**|Dell DW5809e (EM7305, 4G)|
|**Audio**|Realtek ALC236|
|**Ports**|USB-C (PD+DP-AltMode), 3xUSB3.0, HDMI, microSD, Multi-Jack, DC|

## Não funciona

- Teclas de função para ajuste de Brilho da Tela (use Fn+S/Fn+B)
- HDMI coldplug (hotplug tá OK, basta reconectar o cab0)
- *Hibernação (nenhum Hackintosh faz mesmo rsrsrs...)*

## Funcionando

- **Basicamente tudo que não está listado na seção acima**
- Intel WLAN [kexts presentes]
- Ethernet
- HDMI, DisplayPort Alt Mode (Som funcionando, porém, sem ajuste de volume)
- USB-C
- WWAN
- USB ports mapped, working after sleep
- TrackPad with gestos
- Audio, falantes e microfones
- QE/CI
- Repouso
- Leitor MicroSD
- TouchPad buttons
- TrackStick
- Multi-Jack (both cold- and hotplug)

- **Para quem possui uma BCM94360NG:**
- BCM94360NG Bluetooth (4.0, LE, Handoff) [out-of-the-box, no kext needed]
- BCM94360NG WLAN [sem kext] (recomendado)

## Conheça um pouco mais do meu trabalho:

https://beacons.page/rafaelwms
