# databases
datas for personal use

- idh_census.xlsx

- dados_efetividade.xlsx

- Ranking da Transparência MPF

From: [Ranking da Transparência - Governo Municipal](https://sig.mpf.mp.br/sig/servlet/mstrWeb?evt=3140&src=mstrWeb.3140&documentID=CD5BD3BA11E621B2E4D90080EFC54015&server=MSTRIS.PGR.MPF.MP.BR&Project=Ranking%20da%20Transparencia&port=0&share=1)

To import to R:

transp <- rio::import("https://github.com/ronycoelho/databases/raw/master/D01_Ranking_da_Transpar%C3%AAncia_2016.xlsx", skip=2) %>% 
  janitor::clean_names()

# Bases do IBGE
repositório IBGE - ftp://ftp.ibge.gov.br/
