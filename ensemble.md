#Ensemble performance

![](https://raw.githubusercontent.com/justheuristic/Taxathon-results/master/roc_curves.png?raw=true)

| Dataset | AUC | Accuracy | Precision@5k|
| :--- | :--- | :--- | :--- | :--- |
| Training | 0.73916 | 0.74929 | 0.79300 |
| Test | 0.64498 | 0.74238 | 0.69360 |


#Feature ranking:

![](https://github.com/justheuristic/Taxathon-results/blob/master/importances.png?raw=true)

| №    | Team  | Feature | Importance |
| ---: | :---: |  :---:  | :--- |
| 1 | Chmel_Tolstiy-1001180 | A-1639114-No-compiler-OK.csv | 0.283449 |
| 2 | justHeuristic-989496 | A-1639435-No-compiler-OK.csv | 0.149513 |
| 3 | justHeuristic-989496 | A-1640016-No-compiler-OK.csv | 0.122354 |
| 4 | Yandex.Taxi | dist | 0.122046 |
| 5 | Yandex.Taxi | lat | 0.101074 |
| 6 | Yandex.Taxi | lon | 0.091753 |
| 7 | Yandex.Taxi | time_of_day_rel | 0.081506 |
| 8 | Yandex.Taxi | day_of_week=fri | 0.004620 |
| 9 | Yandex.Taxi | day_of_week=mon | 0.004430 |
| 10 | Yandex.Taxi | day_of_week=sat | 0.004382 |
| 11 | Yandex.Taxi | day_of_week=sun | 0.004232 |
| 12 | Yandex.Taxi | day_of_week=thu | 0.004056 |
| 13 | Yandex.Taxi | day_of_week=tue | 0.003999 |
| 14 | Yandex.Taxi | day_of_week=wed | 0.003905 |
| 15 | Yandex.Taxi | f_class | 0.003798 |
| 16 | Yandex.Taxi | f_class=business | 0.003757 |
| 17 | Yandex.Taxi | f_class=econom | 0.003158 |
| 18 | Yandex.Taxi | f_class=vip | 0.003005 |
| 19 | Yandex.Taxi | s_class | 0.002401 |
| 20 | Yandex.Taxi | s_class=business | 0.001207 |
| 21 | Yandex.Taxi | s_class=econom | 0.000670 |
| 22 | Yandex.Taxi | s_class=vip | 0.000661 |
| 23 | Yandex.Taxi | t_class | 0.000022 |
| 24 | Yandex.Taxi | t_class=business | 0.000001 |
| 25 | Yandex.Taxi | t_class=econom | 0.000000 |
| 26 | Yandex.Taxi | t_class=vip | 0.000000 |
