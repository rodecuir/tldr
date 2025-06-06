# lsblk

> Lista informações sobre dispositivos.
> Mais informações: <https://manned.org/lsblk>.

- Lista todos dispositivos de armazenamento no formato de árvore:

`lsblk`

- Também lista dispositivos vazios:

`lsblk {{[-a|--all]}}`

- Mostra a coluna de tamanhos em bytes, em vez de um formato legível por humanos:

`lsblk {{[-b|--bytes]}}`

- Mostra na saída padrão informações sobre os filesystems dos dispositivos:

`lsblk {{[-f|--fs]}}`

- Utiliza caracteres ASCII para o formato de árvore:

`lsblk {{[-i|--ascii]}}`

- Mostra na saída padrão informações sobre block-device topology:

`lsblk {{[-t|--topology]}}`

- Excluír da saída padrão os dispositivos específicados por seus repectivos números separados por vírgulas:

`lsblk {{[-e|--exclude]}} {{1,7,...}}`

- Mostra um resumo de forma customizada passando as colunas separadas por vírgulas:

`lsblk {{[-o|--output]}} {{NAME,SERIAL,MODEL,TRAN,TYPE,SIZE,FSTYPE,MOUNTPOINT,...}}`
