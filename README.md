![image](https://github.com/deniskriukov/predictions-of-the-recovery-coefficient-of-gold-from-ore/assets/113203842/109d586c-fecb-4bf1-9db1-ac75027dd5a1)# predictions-of-the-recovery-coefficient-of-gold-from-ore

Технологический процесс:

Когда добытая руда проходит первичную обработку, получается дроблёная смесь. Её отправляют на флотацию (обогащение) и двухэтапную очистку.

![image](https://github.com/deniskriukov/predictions-of-the-recovery-coefficient-of-gold-from-ore/assets/113203842/d9d07103-3784-4da3-bd60-e86a5dffbc15)

Стадии:
1. Флотация. Во флотационную установку подаётся смесь золотосодержащей руды. После обогащения получается черновой концентрат и «отвальные хвосты», то есть остатки продукта с низкой концентрацией ценных металлов. На стабильность этого процесса влияет непостоянное и неоптимальное физико-химическое состояние флотационной пульпы (смеси твёрдых частиц и жидкости).
2. Очистка. Черновой концентрат проходит две очистки. На выходе получается финальный концентрат и новые отвальные хвосты.

Эффективность обогащения рассчитывается по формуле:

![image](https://github.com/deniskriukov/predictions-of-the-recovery-coefficient-of-gold-from-ore/assets/113203842/c310a7e5-616d-4b68-9bd7-1cd4e213fb52)

где:
- C — доля золота в концентрате после флотации/очистки;
- F — доля золота в сырье/концентрате до флотации/очистки;
- T — доля золота в отвальных хвостах после флотации/очистки.

Метрика качества - sMAPE (Symmetric Mean Absolute Percentage Error, «симметричное среднее абсолютное процентное отклонение»):

![image](https://github.com/deniskriukov/predictions-of-the-recovery-coefficient-of-gold-from-ore/assets/113203842/2a3e8123-d273-4258-9b55-4e659a40bd2c)

Необходимо посчитать эффективность обогащения чернового концентрата и финального концентрата. Итоговая метрика складывается из двух величин:

![image](https://github.com/deniskriukov/predictions-of-the-recovery-coefficient-of-gold-from-ore/assets/113203842/e660f21a-1a48-4bf4-b292-e371ab7ad3a6)
