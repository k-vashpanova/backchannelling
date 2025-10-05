# backchannelling
Проект по анализу обратной связи в диалоге (на материале русского языка).

Ниже приводятся теоретические предпосылки исследования и выводы. Подробное описание сбора данных и разметки, а также визуализация собранных данных и их статичстических анализ находятся в файле Backchannelling_analysis (<https://github.com/k-vashpanova/backchannelling/blob/main/Backchannelling_analysis.Rmd> {код на R}, <https://github.com/k-vashpanova/backchannelling/blob/main/Backchannelling_analysis.html> {html версия})

## Теоретические предпосылки

Обратная связь (в англоязычной литературе также называемая backchanneling, feedback и listener responses, далее ОС) – это сигналы от слушающего к говорящему, которые не приводят к смене ролей
коммуникантов и происходят параллельно с речью говорящего. Она показывает, понимает ли слушающий говорящего и как именно, а также как слушающий реагирует на сообщаемое.

В данном проекте будет исследована зависимость появления сигналов ОС от границ ЭДЕ и пауз в речи говорящего, а также от направления взгляда коммуникантов. Проверяемая гипотеза:

-   H0: Появление ОС не зависит от напревления взгляда испытуемых и их собеседников, от пауз в речи собеседника и от границ ЭДЕ в речи собеседника;

-   Н1: Появление ОС зависит от исследуемых переменных (или части из них).

Обоснованность исследования этой гипотезы подкрепляется следующими исследованиями:

В [Truong et al. 2011] было показано, что ОС часто происходит возле конца речевого сегмента. Вокальная обратная связь с вероятностью выше случайной происходит в паузах, в то время как визуальная не склонна к
этому. В [Morency 2010] как один из триггеров указывается долгая пауза. В заполненных же паузах ОС не происходит вовсе ([Koiso et al. 1998]).

Также в [Truong et al. 2011] показано, что зрительный контакт является сильным триггером ОС, причём как для вокальной, так и для визуальной, хотя для вокальной зависимость несколько слабее. Это объясняется тем,
что при зрительном контакте слушающий уверен, что его визуальная ОС будет замечена говорящим. При этом важно отметить (для дальнейшего анализа), что во время и сразу после ОС количество зрительного контакта
снижается. Синхронизация движений слушающего и говорящего (также иногда считающаяся ОС) в исследовании [Koutsombogera, Papageorgiou 2010] также происходила только во время зрительного контакта между коммуникантами.

## Выводы

В этом анализе было показано, что появление сигналов ОС значимо повышается при направления взгляда говорящего на слушающего и возле конца ЭДЕ и значимо понижается вблизи начала ЭДЕ. Взаимодействие
направления взгляда и конца ЭДЕ меняет эффект направления взгляда на противоположный. Влияние остальных факторов (заполненных и абсолютных пауз, направления взгляда испытуемого на партнёра и зрительного
контакта, а также контекста внутри эде) не оказалось статистически значимым.

Таким образом, мы может отвергнть нулевую гипотезу о независимости сигналов ОС от направления взгляда и сегментов речи, но не о независимости от пауз.

## Литература

1.  *Вашпанова К. В.* Сравнение жестикуляции в разных социальных группах: смены позы у людей разного возраста. Экспериментальное исследование //Курсовая работа, рукопись – 2021.

2.  *Вашпанова К. В.* Отражение глобальной структуры дискурса в сменах позы коммуникантов //Курсовая работа, рукопись – 2022.

3.  *Кибрик А. А., Подлесская В. И.* Проблема сегментации устного дискурса и когнитивная система говорящего //Когнитивные исследования. – 2006. – С. 138-158.

4.  *Федорова О. В.* О коммуникативной функции взгляда //Труды института русского языка им. ВВ Виноградова. – 2019. – Т. 21. – С. 222-241.

5.  *Bavelas J. B., Coates L., Johnson T.* Listeners as co-narrators //Journal of personality and social psychology. – 2000. – Т. 79. – №. 6. – С. 941.

6.  *Kidwell M., Reynolds E.* Gaze and the Organization of Participation in Collective Visual Conduct [Электронный ресурс] //Social Interaction. Video-Based Studies of Human Sociality. – 2022. – Т. 5.
    – №. 2. – URL: <https://doi.org/10.7146/si.v5i2.119332> (дата обращения 10.05.2023)

7.  *Koiso H. et al.* An analysis of turn-taking and backchannels based on prosodic and syntactic features in Japanese map task dialogs //Language and speech. – 1998. – Т. 41. – №. 3-4. – С. 295-321.

8.  *Koutsombogera M., Papageorgiou H.* Linguistic and non-verbal cues for the induction of silent feedback //Proceedings of the Second international conference on Development of Multimodal Interfaces:
    active Listening and Synchrony. – 2009. – С. 327-336.

9.  *Leinonen I.* Multimodal Try-marking for Securing Recipient Understanding of Codeswitched Lexical Items in Everyday ELF Conversations [Электронный ресурс] //Social Interaction. Video-Based
    Studies of Human Sociality. – 2022. – Т. 5. – №. 2. – URL: <https://doi.org/10.7146/si.v5i2.124481> (дата обращения 10.05.2023)

10. *Morency L. P.* Modeling human communication dynamics [social sciences] //IEEE Signal Processing Magazine. – 2010. – Т. 27. – №. 5. – С. 112-116.

11. *O’Keeffe A., Adolphs S.* Response tokens in British and Irish discourse //Variational pragmatics. – 2008. – С. 69-98.

12. *Truong K. P. et al.* A Multimodal Analysis of Vocal and Visual Backchannels in Spontaneous Dialogs //INTERSPEECH. – 2011. – С. 2973-2976.

13. *Ward N., Tsukahara W.* Prosodic features which cue back-channel responses in English and Japanese //Journal of pragmatics. – 2000. – Т. 32. – №. 8. – С. 1177-1207.

14. *White S.* Backchannels across cultures: A study of Americans and Japanese //Language in society. – 1989. – Т. 18. – №. 1. – С. 59-76.


