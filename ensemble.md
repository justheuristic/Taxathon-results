#Ensemble performance

![](roc_curves.png?raw=true)

| Dataset | AUC | Accuracy | Precision@5k|
| :--- | :--- | :--- | :--- | :--- |
| Training | 0.73424 | 0.74886 | 0.78800 |
| Test | 0.64552 | 0.74239 | 0.69620 |


#Feature ranking:

![](importances.png?raw=true)

1. Chmel_Tolstiy-1001180|A-1639114-No-compiler-OK.csv (0.301619)

2. justHeuristic-989496|A-1639435-No-compiler-OK.csv (0.176040)

3. Yandex.Taxi | dist (0.167684)

4. Yandex.Taxi | lat (0.111530)

5. Yandex.Taxi | lon (0.102907)

6. Yandex.Taxi | time_of_day_rel (0.088708)

7. Yandex.Taxi | day_of_week=fri (0.004865)

8. Yandex.Taxi | day_of_week=mon (0.004816)

9. Yandex.Taxi | day_of_week=sat (0.004745)

10. Yandex.Taxi | day_of_week=sun (0.004718)

11. Yandex.Taxi | day_of_week=thu (0.004367)

12. Yandex.Taxi | day_of_week=tue (0.004177)

13. Yandex.Taxi | day_of_week=wed (0.004112)

14. Yandex.Taxi | f_class (0.004005)

15. Yandex.Taxi | f_class=business (0.003828)

16. Yandex.Taxi | f_class=econom (0.003354)

17. Yandex.Taxi | f_class=vip (0.003041)

18. Yandex.Taxi | s_class (0.002522)

19. Yandex.Taxi | s_class=business (0.001401)

20. Yandex.Taxi | s_class=econom (0.000797)

21. Yandex.Taxi | s_class=vip (0.000731)

22. Yandex.Taxi | t_class (0.000032)

23. Yandex.Taxi | t_class=business (0.000000)

24. Yandex.Taxi | t_class=econom (0.000000)

25. Yandex.Taxi | t_class=vip (0.000000)

