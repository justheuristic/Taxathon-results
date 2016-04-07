#Ensemble performance

![](roc_curves.png?raw=true)

| Dataset | AUC | Accuracy | Precision@5k|
| :--- | :--- | :--- | :--- | :--- |
| Training | 0.73906 | 0.74930 | 0.79360 |
| Test | 0.64478 | 0.74224 | 0.69380 |


#Feature ranking:

![](importances.png?raw=true)

1. Chmel_Tolstiy-1001180|A-1639114-No-compiler-OK.csv (0.285894)

2. justHeuristic-989496|A-1639435-No-compiler-OK.csv (0.144170)

3. justHeuristic-989496|A-1640016-No-compiler-OK.csv (0.125087)

4. Yandex.Taxi | dist (0.121856)

5. Yandex.Taxi | lat (0.101833)

6. Yandex.Taxi | lon (0.091095)

7. Yandex.Taxi | time_of_day_rel (0.081665)

8. Yandex.Taxi | day_of_week=fri (0.004647)

9. Yandex.Taxi | day_of_week=mon (0.004432)

10. Yandex.Taxi | day_of_week=sat (0.004412)

11. Yandex.Taxi | day_of_week=sun (0.004243)

12. Yandex.Taxi | day_of_week=thu (0.004078)

13. Yandex.Taxi | day_of_week=tue (0.003892)

14. Yandex.Taxi | day_of_week=wed (0.003859)

15. Yandex.Taxi | f_class (0.003801)

16. Yandex.Taxi | f_class=business (0.003737)

17. Yandex.Taxi | f_class=econom (0.003213)

18. Yandex.Taxi | f_class=vip (0.003047)

19. Yandex.Taxi | s_class (0.002435)

20. Yandex.Taxi | s_class=business (0.001229)

21. Yandex.Taxi | s_class=econom (0.000678)

22. Yandex.Taxi | s_class=vip (0.000671)

23. Yandex.Taxi | t_class (0.000025)

24. Yandex.Taxi | t_class=business (0.000001)

25. Yandex.Taxi | t_class=econom (0.000000)

26. Yandex.Taxi | t_class=vip (0.000000)

