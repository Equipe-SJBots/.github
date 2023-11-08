# Equipe SJBots

Esta organização visa concentrar os códigos da Equipe SJBots que surgiu como um projeto do [LabIFMaker São João da barra][LinkLabMaker].

## Participantes

| Integrante                                           | Cargo                                   | Bolsa                                      | Vigência          |
| ---------------------------------------------------- | --------------------------------------- | ------------------------------------------ | ----------------- |
| [Allysson Rodrigues Teixeira Tavares][Link_Allysson] | Coordenador                             | Orientador                                 | 2023/01 ~ ...     |
| [Jean Carlos Barreto Henriques Filho][Link_Jean]     | Modelagem 3D; Manutenção do laboratório | Laboratório - Superior                     | 2023/01 ~ ...     |
| [Karine Silva Rangel][Link_Karine]                   | Organização; Gestão; Marketing          | Laboratório - Superior                     | 2023/01 ~ ...     |
| [Herick Alexandre Neves Gonçalves][Link_Herick]      | Programação                             | Iniciação Tecnológica - Superior           | 2023/01 ~ ...     |
| [João Vítor Fernandes Dias][Link_João]               | Líder; Piloto; Elétrica                 | Iniciação Tecnológica - Superior           | 2023/01 ~ ...     |
| [Maria Rebeca Corrêa de Sá][Link_Maria]              | Engenharia; Modelagem 3D                | Iniciação Tecnológica - Superior           | 2023/01 ~ 2023/10 |
| [Murilo Menezes Rangel][Link_Murilo]                 | Elétrica                                | Iniciação Científica Júnior - Ensino Médio | 2023/03 ~ 2023/10 |
| [Allan Arruda Rocha Dias][Link_Allan]                | Voluntário                              | Voluntário - Ensino Médio                  | 2023/03 ~ ...     |
| [Krishna Loterio Gamboa][Link_Krishna]               | Voluntário                              | Voluntário - Ensino Médio                  | 2023/03 ~ ...     |
| [Murilo Menezes Rangel][Link_Murilo]                 | Voluntário                              | Voluntário - Ensino Médio                  | 2023/10 ~ ...     |
| [Julia Pessanha Machado da Silva][Link_Murilo]       | Voluntário                              | Voluntário - Ensino Médio                  | 2023/10 ~ ...     |
| [Marcelo Ecard Souza dos Anjos][Link_Marcelo]        | Elétrica                                | Jovens Talentos - Ensino Médio             | 2023/10 ~ ...     |

## Grupos de WhatsApp

- [Areninha][LinkAreninha]
- [Guerra de Robôs][LinkGuerraDeRobos]
- [Seguidor de Linha Brasil][LinkSeguidorDeLinha]
- [Sumô de Robôs Brasil][LinkSumô]
- [ArtBot Brasil][Artbot]
- [Combate Rio][Combate Rio]
- Guerra de Robôs (sério)
- Robótica Rio

[LinkAreninha]: https://chat.whatsapp.com/G75cAFL1zIU3ST5fdk17M5
[LinkGuerraDeRobos]: https://chat.whatsapp.com/B8sLR2Al0UkEI26f12fLha
[LinkSeguidorDeLinha]: https://chat.whatsapp.com/DR6eKw7h3QsCIDOppnp4ab
[LinkSumô]: https://chat.whatsapp.com/D8Z5p4fXTLCGTwzOUwecf3
[Artbot]: https://chat.whatsapp.com/BXMSQ6iBZ9b792aG2I1yYy
[Combate Rio]: https://chat.whatsapp.com/FadAHLT8pOoLmbCUI0WQ8o

## Progressões

### [Amalinha][LinkAmalinha]

```mermaid

---
title: PROGRESSÃO AMALINHA
---
flowchart LR

  s0[[Início]]
  s1[[Semana 1]]
  s2[[Semana 2]]
  s3[[Semana 3]]

  p1[Código de teste]
  p2[Carcaça temporária]
  p3[Soldas mal feitas]

  s0 --> p1 & p2 & p3 --> s1

  i1[Reconhecer linha preta com sensor IR #1]:::marcelo
  i2[Checar o funcionamento dos motores #2]:::julia
  i3[Cortar a base do Amalinha adequadamente #3]:::jean
  cbt1[Soldar elétrica #4]:::krishna

  click i1 "https://github.com/Equipe-SJBots/amalinha/issues/1"
  click i2 "https://github.com/Equipe-SJBots/amalinha/issues/2"
  click i3 "https://github.com/Equipe-SJBots/amalinha/issues/3"
  click cbt1 "https://github.com/Equipe-SJBots/combots/issues/4"

  s1 --> i1 & i2 & i3 & cbt1 --> s2

  i5[Implementar código PID no Amalinha #4]:::julia
  i4[Implementar código para sensor de início #5]:::marcelo

  s2 --> i4 & i5 --> s3

  s3 --> a[Ajustes Finais] --> c1

  c1[[Summit]]


  pessoas((participantes))
  pessoa1[Marcelo]:::marcelo
  pessoa2[Julia]:::julia
  pessoa3[Jean]:::jean
  pessoa4[Krishna]:::krishna

  pessoas --> pessoa1 & pessoa2 & pessoa3 & pessoa4

  classDef marcelo stroke:#FF0000
  classDef jean stroke:#00FF00
  classDef julia stroke:#0000FF
  classDef krishna stroke:#FFFF00
```

[LinkMisc]: https://github.com/Equipe-SJBots/misc
[LinkCombots]: https://github.com/Equipe-SJBots/combots
[LinkAmalinha]: https://github.com/Equipe-SJBots/amalinha
[LinkTermitinho]: https://github.com/Equipe-SJBots/termitinho

<!-- Links -->
[LinkLabMaker]: https://www.instagram.com/labmakersjb/
[Link_Allysson]: https://www.linkedin.com/in/allysson-tavares-92291632/
[Link_Jean]: https://github.com/
[Link_Karine]: https://www.instagram.com/arquirine/
[Link_Herick]: https://github.com/JohtoGamesOf
[Link_João]: https://github.com/jvfd3
[Link_Maria]: https://github.com/
[Link_Murilo]: https://github.com/
[Link_Allan]: https://github.com/
[Link_Krishna]: https://github.com/JulhoGamboa
[Link_Marcelo]: https://github.com/
