# Автоматизация части задач  отдела продаж. 

 *Начать решили с написания простого инструмента анализа статистики продаж.*
 
 **Первая версия такого сервиса:**

```java 
public class SalesManager {
    protected int[] sales;

    public SalesManager(int[] sales) {
        this.sales = sales;
    }

    public int max() {
        int max = -1;
        for (int sale : sales) {
            if (sale > max) {
                max = sale;
            }
        }
        return max;
    }
}
```
### Следите за обновлениями!

___До скорой встречи!___
