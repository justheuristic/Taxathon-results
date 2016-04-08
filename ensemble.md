#Ensemble performance

![](https://raw.githubusercontent.com/justheuristic/Taxathon-results/master/roc_curves.png?raw=true)

| Dataset | AUC | Accuracy | Precision@5k|
| :--- | :--- | :--- | :--- | :--- |
| Training | 0.79784 | 0.75571 | 0.83960 |
| Test | 0.65398 | 0.74465 | 0.73080 |


#Feature ranking:

![](https://github.com/justheuristic/Taxathon-results/blob/master/importances.png?raw=true)

| №    | Team  | Feature | Importance |
| ---: | :---: |  :---:  | :--- |
| 1 | Dima_Borzih (Arshak Minasyan, filatovartm, outbreakfury)-1006229 | A-1643024-No-compiler-OK.csv | 0.060071 |
| 2 | FTW (Vessemer, minibaev.e.m, abuca9268)-1006164 | A-1643018-No-compiler-OK.csv | 0.051875 |
| 3 | FTW (Vessemer, minibaev.e.m, abuca9268)-1006164 | A-1643045-No-compiler-OK.csv | 0.048733 |
| 4 | Huston (liubov.yaronskaya, medanya.nounors, sofiapotapova95)-1006251 | A-1643096-No-compiler-OK.csv | 0.041805 |
| 5 | Kolyan_416 (MironLevkov, kuzmichev_dima, ryad0m)-1006153 | A-1642965-No-compiler-OK.csv | 0.039998 |
| 6 | Kolyan_416 (MironLevkov, kuzmichev_dima, ryad0m)-1006153 | A-1643019-No-compiler-OK.csv | 0.035198 |
| 7 | MIPT (alexander@plav.in, Игорь Иноземцев, yaroslav.averyanov)-1006371 | A-1643069-No-compiler-OK.csv | 0.032317 |
| 8 | Meh (gleb.posobin, martynov.oleg.mipt, hse.yurboss)-1006037 | A-1642874-No-compiler-OK.csv | 0.031989 |
| 9 | Meh (gleb.posobin, martynov.oleg.mipt, hse.yurboss)-1006037 | A-1642981-No-compiler-OK.csv | 0.031973 |
| 10 | Meh (gleb.posobin, martynov.oleg.mipt, hse.yurboss)-1006037 | A-1643091-No-compiler-OK.csv | 0.030676 |
| 11 | RainMonkeys (GushchinaVarya, qashqay.sol, tarkhoff.andrei)-1006265 | A-1643020-No-compiler-OK.csv | 0.030480 |
| 12 | RainMonkeys (GushchinaVarya, qashqay.sol, tarkhoff.andrei)-1006265 | A-1643042-No-compiler-OK.csv | 0.029096 |
| 13 | Valentin-1006052 | A-1642890-No-compiler-OK.csv | 0.027774 |
| 14 | Weak Learners (kings-quest, domaso, Hoderu)-1006154 | A-1643011-No-compiler-OK.csv | 0.027266 |
| 15 | bibik.platon-1005986 | A-1643059-No-compiler-OK.csv | 0.026618 |
| 16 | blank_teamname (belyaeva.dr, SKorolS, mike0sv2)-1006106 | A-1643006-No-compiler-OK.csv | 0.025964 |
| 17 | dream_world (reqnv, mealsoul)-1006196 | A-1643012-No-compiler-OK.csv | 0.025556 |
| 18 | dream_world (reqnv, mealsoul)-1006196 | A-1643057-No-compiler-OK.csv | 0.023577 |
| 19 | from xgboost import * (norpadon, lev-prol, VisualPaul)-1006230 | A-1643022-No-compiler-OK.csv | 0.023462 |
| 20 | from xgboost import * (norpadon, lev-prol, VisualPaul)-1006230 | A-1643047-No-compiler-OK.csv | 0.023437 |
| 21 | teorMehTeam (Mihail-Maryfich, andrei.tsypilnikov)-1006239 | A-1643041-No-compiler-OK.csv | 0.023395 |
| 22 | tuple(noob,noob,noob) (emilkayumov, y.kemaev, Артём Попов)-1005970 | A-1643001-No-compiler-OK.csv | 0.022646 |
| 23 | tuple(noob,noob,noob) (emilkayumov, y.kemaev, Артём Попов)-1005970 | A-1643055-No-compiler-OK.csv | 0.021089 |
| 24 | wild beasts (nikolaypopov95, kiz.roman, stephan.zimin@msuteam.ru)-1006209 | A-1643089-No-compiler-OK.csv | 0.020998 |
| 25 | Антон Смердов-1005980 | A-1643052-No-compiler-OK.csv | 0.020735 |
| 26 | ВВВ (Вильям Саакян, tilgasergey, Vaness)-1006120 | A-1642990-No-compiler-OK.csv | 0.019530 |
| 27 | ВВВ (Вильям Саакян, tilgasergey, Vaness)-1006120 | A-1642999-No-compiler-OK.csv | 0.018788 |
| 28 | ВВВ (Вильям Саакян, tilgasergey, Vaness)-1006120 | A-1643017-No-compiler-OK.csv | 0.018651 |
| 29 | ВВВ (Вильям Саакян, tilgasergey, Vaness)-1006120 | A-1643036-No-compiler-OK.csv | 0.018394 |
| 30 | ВВВ (Вильям Саакян, tilgasergey, Vaness)-1006120 | A-1643049-No-compiler-OK.csv | 0.018308 |
| 31 | КокосВалидация (marat.akhmatnurov, gizdatullindanil, k.n.kuznetsov)-1006256 | A-1643000-No-compiler-OK.csv | 0.018108 |
| 32 | КокосВалидация (marat.akhmatnurov, gizdatullindanil, k.n.kuznetsov)-1006256 | A-1643007-No-compiler-OK.csv | 0.017886 |
| 33 | Сенежская (ramly, astiunov, aibek.alanov)-1006195 | A-1643010-No-compiler-OK.csv | 0.017391 |
| 34 | Yandex.Taxi | dist | 0.016968 |
| 35 | Yandex.Taxi | lat | 0.016343 |
| 36 | Yandex.Taxi | lon | 0.016135 |
| 37 | Yandex.Taxi | time_of_day_rel | 0.016061 |
| 38 | Yandex.Taxi | day_of_week=fri | 0.001303 |
| 39 | Yandex.Taxi | day_of_week=mon | 0.001054 |
| 40 | Yandex.Taxi | day_of_week=sat | 0.001008 |
| 41 | Yandex.Taxi | day_of_week=sun | 0.000992 |
| 42 | Yandex.Taxi | day_of_week=thu | 0.000991 |
| 43 | Yandex.Taxi | day_of_week=tue | 0.000912 |
| 44 | Yandex.Taxi | day_of_week=wed | 0.000899 |
| 45 | Yandex.Taxi | f_class | 0.000863 |
| 46 | Yandex.Taxi | f_class=business | 0.000676 |
| 47 | Yandex.Taxi | f_class=econom | 0.000598 |
| 48 | Yandex.Taxi | f_class=vip | 0.000597 |
| 49 | Yandex.Taxi | s_class | 0.000445 |
| 50 | Yandex.Taxi | s_class=business | 0.000239 |
| 51 | Yandex.Taxi | s_class=econom | 0.000066 |
| 52 | Yandex.Taxi | s_class=vip | 0.000063 |
| 53 | Yandex.Taxi | t_class | 0.000001 |
| 54 | Yandex.Taxi | t_class=business | 0.000000 |
| 55 | Yandex.Taxi | t_class=econom | 0.000000 |
| 56 | Yandex.Taxi | t_class=vip | 0.000000 |
