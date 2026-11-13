# Satellites using CubeSat Space Protocol

<img src="logo.png" alt="CSP satellites list logo" width="160">

A source-backed list of satellites with documented or possible use of [CubeSat Space Protocol (CSP)](https://github.com/libcsp/libcsp).

**Last reviewed: 13 November 2026.** The list contains 86 unique spacecraft: 3 with explicit CSP documentation and 83 candidates requiring further confirmation. It includes historical missions and does not track operational status.

## Reading the list

- **Direct:** mission documentation explicitly identifies CSP.
- **Indirect — radio:** a satellite record lists an AX100-family radio mode. This suggests a CSP connection but does not establish the installed transceiver or onboard network.
- **Indirect — supplier:** a source identifies a GomSpace platform or component. A supplier relationship alone does not establish CSP use.
- **Unverified:** the reviewed sources do not substantiate the original CSP claim.

Satellite names link to mission documentation or a catalog record. Evidence links support the specific statement in that row. “Not established” means the reviewed sources do not establish the information, rather than that the satellite does not use CSP.

## Documented CSP use

| Satellite | Evidence | Transceiver |
|---|---|---|
| [PIXL-1][pixl] | [DLR reports successful commanding over CSP][pixlcsp]. | Not established |
| [GOMX-1][gomx] | [Mission design paper, p. 4][gomx], describes CSP across the subsystems and space-to-ground link. | Not established |
| [GreenCube (IO-117)][green] | [Mission-team decoding guide][greencsp] identifies CSP packets and the radio. | GomSpace AX100 |

## Candidates: radio evidence

GomSpace's [AX100 documentation][ax100] identifies CSP support. The records below list **AX.100 Mode 5** framing; that is indirect evidence, not a confirmed hardware inventory or an explicit mission CSP statement. Listings may be inferred or unconfirmed; consult each record's transmitter citations.

| Satellite / catalog record | Radio evidence | CSP assessment |
|---|---|---|
| [GALASSIA-2](https://db.satnogs.org/satellite/BYRQ-8084-9850-7997-7193/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/BYRQ-8084-9850-7997-7193/#transmitters) | Indirect |
| [BRO-13](https://db.satnogs.org/satellite/KSFC-2018-1319-4536-1314/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/KSFC-2018-1319-4536-1314/#transmitters) | Indirect |
| [KSM1-A](https://db.satnogs.org/satellite/HUNW-6973-2030-4958-5201/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/HUNW-6973-2030-4958-5201/#transmitters) | Indirect |
| [ERMIS-3](https://db.satnogs.org/satellite/ZRPV-6317-0836-0013-3209/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ZRPV-6317-0836-0013-3209/#transmitters) | Indirect |
| [ION SCV Daring Diego](https://db.satnogs.org/satellite/BZWJ-9712-5590-5046-8513/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/BZWJ-9712-5590-5046-8513/#transmitters) | Indirect |
| [BRO-22](https://db.satnogs.org/satellite/98304/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/98304/#transmitters) | Indirect |
| [KINEIS-1A](https://db.satnogs.org/satellite/HPAR-8709-5177-4142-4273/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/HPAR-8709-5177-4142-4273/#transmitters) | Indirect |
| [ION SCV-004](https://db.satnogs.org/satellite/EAHI-9090-2555-3685-8378/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EAHI-9090-2555-3685-8378/#transmitters) | Indirect; listing cites earlier missions |
| [NUSHSat1](https://db.satnogs.org/satellite/AGMX-2508-1337-4945-9939/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/AGMX-2508-1337-4945-9939/#transmitters) | Indirect |
| [ION SCV Marvelous Mathias](https://db.satnogs.org/satellite/EZAU-8235-2008-4656-9477/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EZAU-8235-2008-4656-9477/#transmitters) | Indirect |
| [NuLink-2](https://db.satnogs.org/satellite/REYA-7757-1619-4009-9971/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/REYA-7757-1619-4009-9971/#transmitters) | Indirect |
| [ION SCV Astounding Alexandra](https://db.satnogs.org/satellite/IVCW-8630-3606-0296-9103/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/IVCW-8630-3606-0296-9103/#transmitters) | Indirect |
| [BRO-21](https://db.satnogs.org/satellite/EPSO-2740-8746-3078-9656/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EPSO-2740-8746-3078-9656/#transmitters) | Indirect |
| [AISTECHSAT-2](https://db.satnogs.org/satellite/MSIH-7029-5546-1995-2723/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/MSIH-7029-5546-1995-2723/#transmitters) | Indirect |
| [BRO-6](https://db.satnogs.org/satellite/FIRA-5450-5372-6155-3095/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/FIRA-5450-5372-6155-3095/#transmitters) | Indirect |
| [BRO-18](https://db.satnogs.org/satellite/ENLC-4952-6681-1812-8294/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ENLC-4952-6681-1812-8294/#transmitters) | Indirect |
| [BRO-19](https://db.satnogs.org/satellite/ZLVU-1189-2777-4843-4951/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ZLVU-1189-2777-4843-4951/#transmitters) | Indirect |
| [ALAINSAT-1](https://db.satnogs.org/satellite/JRPK-1739-9766-4189-3079/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/JRPK-1739-9766-4189-3079/#transmitters) | Indirect |
| [LUR-1](https://db.satnogs.org/satellite/HMLT-0173-5504-1396-8170/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/HMLT-0173-5504-1396-8170/#transmitters) | Indirect |
| [ION SCV Passionate Paula](https://db.satnogs.org/satellite/JLJE-0670-3801-0857-8118/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/JLJE-0670-3801-0857-8118/#transmitters) | Indirect |
| [VELOX-AM](https://db.satnogs.org/satellite/BVGM-7941-1194-7387-5450/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/BVGM-7941-1194-7387-5450/#transmitters) | Indirect |
| [BRO-5](https://db.satnogs.org/satellite/EAPL-5646-6568-7428-1685/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EAPL-5646-6568-7428-1685/#transmitters) | Indirect |
| [BRO-11](https://db.satnogs.org/satellite/BKIY-3032-2869-4485-1697/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/BKIY-3032-2869-4485-1697/#transmitters) | Indirect |
| [SATURNIN-1](https://db.satnogs.org/satellite/ZRUJ-5863-3206-3578-5209/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ZRUJ-5863-3206-3578-5209/#transmitters) | Indirect |
| [BEE-1000](https://db.satnogs.org/satellite/FUNJ-2834-4382-2735-5337/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/FUNJ-2834-4382-2735-5337/#transmitters) | Indirect |
| [ION SCV-014](https://db.satnogs.org/satellite/JVIJ-4226-9631-1978-7970/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/JVIJ-4226-9631-1978-7970/#transmitters) | Indirect |
| [DUTHSat-2](https://db.satnogs.org/satellite/HWSK-3928-3901-7383-3031/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/HWSK-3928-3901-7383-3031/#transmitters) | Indirect |
| [BRO-14](https://db.satnogs.org/satellite/ZTUR-8052-1950-5911-7314/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ZTUR-8052-1950-5911-7314/#transmitters) | Indirect |
| [ION SCV-016](https://db.satnogs.org/satellite/TNCA-2269-1089-8167-2586/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/TNCA-2269-1089-8167-2586/#transmitters) | Indirect |
| [SNIPE B](https://db.satnogs.org/satellite/KZDM-2447-6592-4881-9320/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/KZDM-2447-6592-4881-9320/#transmitters) | Indirect |
| [BRO-16](https://db.satnogs.org/satellite/HMRN-7466-8969-6530-1296/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/HMRN-7466-8969-6530-1296/#transmitters) | Indirect |
| [BRO-8](https://db.satnogs.org/satellite/RJCF-5779-9216-5641-4111/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/RJCF-5779-9216-5641-4111/#transmitters) | Indirect |
| [ION SCV Charismatic Carlus](https://db.satnogs.org/satellite/MJWC-6105-7146-5103-2066/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/MJWC-6105-7146-5103-2066/#transmitters) | Indirect |
| [SNIPE C](https://db.satnogs.org/satellite/ZNAY-2858-6600-3535-8759/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ZNAY-2858-6600-3535-8759/#transmitters) | Indirect |
| [K-HERO](https://db.satnogs.org/satellite/VFAW-1957-0148-9612-7991/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/VFAW-1957-0148-9612-7991/#transmitters) | Indirect |
| [THEA](https://db.satnogs.org/satellite/OSTA-3937-9747-5420-7898/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/OSTA-3937-9747-5420-7898/#transmitters) | Indirect |
| [SNIPE D](https://db.satnogs.org/satellite/EOVQ-9559-0511-0103-2591/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EOVQ-9559-0511-0103-2591/#transmitters) | Indirect |
| [SNIPE A](https://db.satnogs.org/satellite/AYLO-6910-6407-3496-4588/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/AYLO-6910-6407-3496-4588/#transmitters) | Indirect |
| [FrontierSat](https://db.satnogs.org/satellite/GGCH-4346-1583-9419-5634/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/GGCH-4346-1583-9419-5634/#transmitters) | Indirect |
| [BRO-12](https://db.satnogs.org/satellite/IQOY-7969-6018-3429-4654/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/IQOY-7969-6018-3429-4654/#transmitters) | Indirect |
| [BRO-15](https://db.satnogs.org/satellite/PUFM-6212-8243-7442-9645/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/PUFM-6212-8243-7442-9645/#transmitters) | Indirect |
| [TY-41](https://db.satnogs.org/satellite/FOYC-0465-3890-7368-7165/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/FOYC-0465-3890-7368-7165/#transmitters) | Indirect |
| [UND ROADS 2](https://db.satnogs.org/satellite/BZMH-1691-0385-6822-7921/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/BZMH-1691-0385-6822-7921/#transmitters) | Indirect |
| [ION SCV-007](https://db.satnogs.org/satellite/VPUU-7194-1121-2414-5647/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/VPUU-7194-1121-2414-5647/#transmitters) | Indirect |
| [CatSat](https://db.satnogs.org/satellite/EIOW-0233-5270-5407-2865/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EIOW-0233-5270-5407-2865/#transmitters) | Indirect |
| [UND ROADS 1](https://db.satnogs.org/satellite/CGQM-1404-3051-5125-7571/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/CGQM-1404-3051-5125-7571/#transmitters) | Indirect |
| [KSM1-C](https://db.satnogs.org/satellite/ZQAV-4893-1919-8347-2035/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/ZQAV-4893-1919-8347-2035/#transmitters) | Indirect |
| [ION SCV Joyful Julia](https://db.satnogs.org/satellite/QGYT-6411-9788-7098-8379/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/QGYT-6411-9788-7098-8379/#transmitters) | Indirect |
| [BRO-10](https://db.satnogs.org/satellite/BISO-5259-3723-1730-8460/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/BISO-5259-3723-1730-8460/#transmitters) | Indirect |
| [ERNST](https://db.satnogs.org/satellite/OZFM-4525-5507-9609-6820/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/OZFM-4525-5507-9609-6820/#transmitters) | Indirect |
| [CoRAL](https://db.satnogs.org/satellite/PBKS-8836-3208-9942-5973/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/PBKS-8836-3208-9942-5973/#transmitters) | Indirect |
| [UM5Sat-Ribat](https://db.satnogs.org/satellite/QRWE-3933-7174-7805-6481/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/QRWE-3933-7174-7805-6481/#transmitters) | Indirect |
| [ION SCV-006](https://db.satnogs.org/satellite/TQIP-5428-9682-2220-6430/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/TQIP-5428-9682-2220-6430/#transmitters) | Indirect |
| [ION SCV-012](https://db.satnogs.org/satellite/LWDE-7403-4643-6587-2546/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/LWDE-7403-4643-6587-2546/#transmitters) | Indirect |
| [ERMIS-2](https://db.satnogs.org/satellite/EALZ-0780-6325-0069-2307/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/EALZ-0780-6325-0069-2307/#transmitters) | Indirect |
| [BRO-31](https://db.satnogs.org/satellite/98286/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/98286/#transmitters) | Indirect; radio listing unconfirmed |
| [KINEIS-1E](https://db.satnogs.org/satellite/LCDF-7727-1999-3080-1795/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/LCDF-7727-1999-3080-1795/#transmitters) | Indirect |
| [NuLink-1](https://db.satnogs.org/satellite/YEEE-7340-7726-4018-8919/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/YEEE-7340-7726-4018-8919/#transmitters) | Indirect |
| [KSM1-B](https://db.satnogs.org/satellite/MWRL-6562-0983-3996-2101/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/MWRL-6562-0983-3996-2101/#transmitters) | Indirect |
| [MIMAN](https://db.satnogs.org/satellite/AOTT-8678-9365-5674-2308/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/AOTT-8678-9365-5674-2308/#transmitters) | Indirect |
| [BRO-17](https://db.satnogs.org/satellite/JBBF-3425-4524-4262-2493/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/JBBF-3425-4524-4262-2493/#transmitters) | Indirect |
| [Suomi 100](https://db.satnogs.org/satellite/MUVJ-0454-0662-1172-2559/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/MUVJ-0454-0662-1172-2559/#transmitters) | Indirect |
| [ION-MK02-SCV013](https://db.satnogs.org/satellite/YODX-5832-7103-0922-4071/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/YODX-5832-7103-0922-4071/#transmitters) | Indirect |
| [KSM1-D](https://db.satnogs.org/satellite/LQIA-1498-8400-4918-0119/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/LQIA-1498-8400-4918-0119/#transmitters) | Indirect |
| [BRO-20](https://db.satnogs.org/satellite/QTIE-7003-0773-7118-5213/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/QTIE-7003-0773-7118-5213/#transmitters) | Indirect |
| [GXIBA-1](https://db.satnogs.org/satellite/CAOL-2416-3135-3240-8425/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/CAOL-2416-3135-3240-8425/#transmitters) | Indirect |
| [ERMIS-1](https://db.satnogs.org/satellite/DJQS-0588-0767-3427-2831/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/DJQS-0588-0767-3427-2831/#transmitters) | Indirect |
| [ION SCV-011](https://db.satnogs.org/satellite/TWEF-8525-8046-9814-5948/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/TWEF-8525-8046-9814-5948/#transmitters) | Indirect; listing cites earlier missions |
| [INNOCUBE](https://db.satnogs.org/satellite/IMIN-5614-5566-5816-9152/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/IMIN-5614-5566-5816-9152/#transmitters) | Indirect |
| [ION SCV-010](https://db.satnogs.org/satellite/DIVJ-8110-8669-4923-0530/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/DIVJ-8110-8669-4923-0530/#transmitters) | Indirect |
| [BRO-9](https://db.satnogs.org/satellite/XFVV-4114-4685-9543-2674/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/XFVV-4114-4685-9543-2674/#transmitters) | Indirect |
| [ION SCV-008](https://db.satnogs.org/satellite/NJEX-6170-8600-1975-0468/) | [AX.100 Mode 5 listing](https://db.satnogs.org/satellite/NJEX-6170-8600-1975-0468/#transmitters) | Indirect; listing requests a citation |

## Candidates: supplier evidence

These sources establish a platform or component relationship, without explicitly documenting CSP for the named spacecraft. See also Astrocast's [constellation documentation][astro]. The Astrocast supplier release concerns the constellation's first ten operational satellites collectively; it does not identify each satellite's installed hardware.

| Satellite / mission documentation | Evidence | CSP assessment |
|---|---|---|
| [BRO-1][bro] | [GomSpace reports delivering the satellite bus][bro]. | Indirect — supplier |
| [Astrocast 3 (Astrocast-0101)](https://db.satnogs.org/satellite/BDLJ-2616-4411-1398-7647/) | [GomSpace propulsion contract for the first ten constellation satellites][astroprop]. | Indirect — constellation-level supplier evidence |
| [Astrocast 5 (Astrocast-0103)](https://db.satnogs.org/satellite/QJNL-5424-7348-8857-3059/) | [GomSpace propulsion contract for the first ten constellation satellites][astroprop]. | Indirect — constellation-level supplier evidence |
| [Astrocast 7 (Astrocast-0105)](https://en.sonik.space/satellites/EBBN-0730-8295-6255-3355/) | [GomSpace propulsion contract for the first ten constellation satellites][astroprop]. | Indirect — constellation-level supplier evidence |
| [Astrocast 8 (ASTROCAST-0201)](https://db.satnogs.org/satellite/YSAD-0391-3129-9092-9760/) | [GomSpace propulsion contract for the first ten constellation satellites][astroprop]. | Indirect — constellation-level supplier evidence |
| [Astrocast 10 (ASTROCAST-0203)](https://www.nanosats.eu/sat/astrocast) | [GomSpace propulsion contract for the first ten constellation satellites][astroprop]. | Indirect — constellation-level supplier evidence |
| [Astrocast 12 (ASTROCAST-0205)](https://db.satnogs.org/satellite/YHCV-5439-4218-0901-5637/) | [GomSpace propulsion contract for the first ten constellation satellites][astroprop]. | Indirect — constellation-level supplier evidence |
| [ARCSAT (ARCSAT-1, FFI CubeSat)][arc] | [Launch integrator identifies GomSpace as the manufacturer][arc]. | Indirect — supplier |
| [IOD-1 (Startical 1)][iod] | [SESAR identifies GomSpace as the manufacturer][iod]. | Indirect — supplier |

## Entries awaiting evidence

These entries are retained from the original list for follow-up and are not counted as documented CSP users.

| Satellite / catalog record | What the reviewed source establishes | Still needed |
|---|---|---|
| [CAKRA-1][cakra] | [SatNOGS lists an unconfirmed S-band FM downlink][cakra], without an explicit CSP identification. | Mission or subsystem documentation identifying CSP. |
| [BUZZER-1][buzzer] | [Government launch catalog, entry 177][buzzer], identifies an Unseenlabs spacecraft; it does not identify a manufacturer or CSP. | A spacecraft-specific source supporting the original GomSpace/CSP association. |

## Research notes

- The 88 original rows represent 86 unique spacecraft. Duplicate NUSHSat1 and ALAINSAT-1 entries were consolidated.
- IOD-2 is a separate Startical demonstrator, and ECHOES is the project containing both demonstrators; neither is retained as an alias of IOD-1. See the [SESAR mission announcement][iod].
- Satellite names follow the linked records, including ERNST, CoRAL, MIMAN and ION SCV Charismatic Carlus.
- Numeric prefixes were removed from names because some were temporary SatNOGS identifiers rather than established NORAD catalog numbers. The linked records preserve identification details.
- Broken local PDF references were replaced with [GomSpace's published AX100 documentation][ax100]. Hardware support for CSP is kept separate from evidence that a particular mission uses it.

## Contributing

Additions and corrections are welcome through an issue or pull request. Include the satellite name, a mission documentation link, and a source that supports CSP use. State whether the evidence is direct, a radio listing, or a supplier relationship.

[pixl]: https://www.dlr.de/en/latest/news/2021/01/20210124_pioneering-launch-compact-satellite-with-smallest-laser-terminal
[pixlcsp]: https://www.dlr.de/en/blog/archive/2024/german-space-operations-center-commands-small-satellite-with-next-generation-software-via-cubesat-space-protocol
[gomx]: https://vbn.aau.dk/ws/files/70858093/GomX_1_A_Nano_satellite_Mission_to_Demonstrate_Improved_Situatio.pdf
[green]: https://www.s5lab.space/index.php/greencube-home/
[greencsp]: https://www.s5lab.space/index.php/decoding-ledsat-2/
[ax100]: https://gomspace.com/UserFiles/Subsystems/flyer/gomspace_nanocom_ax100_flyer.pdf
[bro]: https://news.cision.com/gomspace-a-s/r/gomspace-and-unseenlabs-commission-bro-1-in-record-time,c2891775
[astro]: https://www.astrocast.com/news/astrocast-constellation-keeps-growing/
[astroprop]: https://mb.cision.com/Main/14387/2574484/877674.pdf
[arc]: https://exolaunch.com/news_74
[iod]: https://www.sesarju.eu/news/european-satellite-launched-test-space-based-air-traffic-communications
[cakra]: https://db.satnogs.org/satellite/98861/
[buzzer]: https://www.crms.go.kr/download.do?uuid=5ca3539e-bab9-4f7b-ad3e-36c7f076397b
