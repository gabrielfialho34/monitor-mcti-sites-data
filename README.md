# monitor-mcti-sites-data
Pacotes criptografados para atualizacao automatica do painel privado MCTI

Este repositorio publico contem somente envelopes AES-256-GCM autenticados.
Os dados em claro e a chave de descriptografia permanecem fora do repositorio;
a chave e mantida no Windows DPAPI e como secret do OpenAI Sites.

O arquivo `painel_mcti_sites.enc.json` e atualizado pela automacao local depois
de cada ciclo concluido do monitor. Ele nao deve ser descriptografado nem
transformado em artefato legivel neste repositorio.
