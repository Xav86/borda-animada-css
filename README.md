# Borda animada em css

esbarrei nesse conteudo por acaso e queria muito ver como ficaria, créditos ao tutorial do [Codign2GO](https://youtu.be/ezP4kbOvs_E?si=FF7zpP3K-7HlBp1n), em poucos minutos consegui fazer esse efeito muito legal

## imagem de como ficou
![alt text](image.png) 

mechendo na propriedade background-image, da pra fazer varias variações legais:

background-image: conic-gradient(from var(--angle),#ff4545 0 35%, transparent 35% 40%, #45ffaf 40% 70%,  transparent 70% 75%, #006aff 75% 95%, transparent 95% 100%);

ou

background-image: conic-gradient(from var(--angle), transparent 50%,#ff4545);

entre varias outras...