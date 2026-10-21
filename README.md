# TTT Expansion — DLC Rebuild 2.0 (ULUS10537)

Pacote com projeto completo de plugin PRX PSP/PPSSPP, assets de menu, missões de treinamento, mapa de índices e ferramentas de PACKFILE/EBOOT. **Não inclui ISO, nem os 11 CHRs externos que ainda não foram enviados como arquivos.**

**IMPORTANTE:** Fonte C e projeto GitHub Actions para compilar PRX. Compilação PSPSDK e validação PPSSPP ainda não foram executadas neste ambiente. Não afirme que todos os recursos estão prontos para uma versão final sem teste no emulador.

Leia **LEIA_PRIMEIRO_REBUILD_V2.md** para instruções. A ISO modificada pelo usuário com contagem 0x3734 e 12 CHRs já é suficiente para os primeiros testes; NÃO reaplique o expansor em uma ISO já expandida.

Componentes que devem funcionar se os endereços ULUS10537 e seus arquivos originais coincidirem: Goku (Início), Goku (Meio), Goku (Meio) — Super Saiyajin; 4 Colors cada; plano separado 1P–4P; menu texturizado ABGR4444 com fallback; 6 desafios DLC com seleção e progresso manual em arquivo.

Limitados/desabilitados: novos mapas carregáveis e modo História interno do jogo (não há hook validado); SFX próprios; personagens com movesets internos exclusivos (IDs 00/01/02 compartilham forma interna 0x47).

## Build V2.0.1

Veja `LEIA_CORRECAO_BUILD_V2001.md` para correção do erro 127 no GitHub Actions.
